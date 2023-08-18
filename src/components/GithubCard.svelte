<script lang="ts">
    export let repoName;
    export let stars = 0;
    export let forks = 0;
    export let description = "";
</script>

<a
    href="https://github.com/SuhasDissa/{repoName}"
    class="flex flex-col justify-between max-w-sm p-6 bg-slate-50 rounded-lg drop-shadow hover:-translate-y-2 hover:drop-shadow-xl duration-100 dark:bg-slate-800 dark:hover:bg-slate-700"
>
    <h5
        class="mb-2 text-2xl font-bold tracking-tight text-slate-700 dark:text-slate-300"
    >
        {repoName}
    </h5>
    <p class="font-normal text-slate-500 dark:text-slate-400">
        {description}
    </p>
    <div class="flex flex-row w-full justify-evenly pt-8">
        <div class="flex flex-row items-center">
            <span
                class="material-symbols-rounded text-slate-600 dark:text-slate-400"
            >
                star
            </span>
            <p class="font-bold text-slate-600 dark:text-slate-400 pl-4">
                {stars}
            </p>
        </div>
        <div class="flex flex-row items-center">
            <span
                class="material-symbols-rounded text-slate-600 dark:text-slate-400"
            >
                fork_right
            </span>
            <p class="font-bold text-slate-600 dark:text-slate-400 pl-4">
                {forks}
            </p>
        </div>
    </div>
</a>
