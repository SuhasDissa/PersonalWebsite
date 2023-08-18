<script>
    import { onMount } from "svelte";
    import GithubCard from "../../components/GithubCard.svelte";

    let repos = [];
    onMount(async () => {
        const res = await fetch("https://api.github.com/users/SuhasDissa/repos");
        const repositories = await res.json();
        repos = repositories
            .filter((repo) => !repo.fork)
            .sort((a, b) => b.stargazers_count - a.stargazers_count);
    });
</script>

<div class="mx-auto max-w-screen-xl px-8 py-20">
    <section class="pt-20">
        <h2
            class="text-slate-600 dark:text-slate-400 text-2xl sm:text-3xl md:text-5xl font-bold"
        >
            My GitHub Projects
        </h2>
        <div
            class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 grid-flow-row gap-4 pt-4 sm:pt-8"
        >
            {#each repos as repo}
                <GithubCard
                    repoName={repo.name}
                    description={repo.description ?? ""}
                    stars={repo.stargazers_count}
                    forks={repo.forks_count}
                />
            {/each}
        </div>
    </section>
</div>
