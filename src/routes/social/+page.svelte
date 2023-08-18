<script>
    import SocialCard from "../../components/SocialCard.svelte";
    import DiscordIcon from "../../components/icons/DiscordIcon.svelte";
    import GithubIcon from "../../components/icons/GithubIcon.svelte";
    import GitlabIcon from "../../components/icons/GitlabIcon .svelte";
    import MatrixIcon from "../../components/icons/MatrixIcon.svelte";
    import TwitterIcon from "../../components/icons/TwitterIcon.svelte";
    import UnsplashIcon from "../../components/icons/UnsplashIcon.svelte";
</script>

<div class="mx-auto max-w-screen-xl px-8  py-20">
    <section>
        <h2
            class="text-slate-600 dark:text-slate-400 text-2xl sm:text-3xl md:text-5xl font-bold"
        >
            Social Media Links
        </h2>
        <div
            class="grid grid-cols-1 sm:grid-cols-1 md:grid-cols-2 lg:grid-cols-3 grid-flow-row gap-4 pt-4 sm:pt-8"
        >
            <SocialCard
                title={"Suhas Dissanayake"}
                subtitle={"SuhasDissa"}
                link={"https://github.com/SuhasDissa/"}
            >
                <GithubIcon />
            </SocialCard>

            <SocialCard
                title={"Suhas Dissanayake"}
                subtitle={"@suhas_d"}
                link={"https://matrix.to/#/@suhas_d:matrix.org"}
            >
                <MatrixIcon />
            </SocialCard>

            <SocialCard
                title={"Suhas Dissanayake"}
                subtitle={"SuhasDissa"}
                link={"https://github.com/SuhasDissa/"}
            >
                <TwitterIcon />
            </SocialCard>

            <SocialCard
                title={"Suhas Dissanayake"}
                subtitle={"suhasdissa"}
                link={"https://discordapp.com/users/924165265258844180"}
            >
                <DiscordIcon />
            </SocialCard>

            <SocialCard
                title={"Suhas Dissanayake"}
                subtitle={"@suhasdissa"}
                link={"https://unsplash.com/@suhasdissa"}
            >
                <UnsplashIcon />
            </SocialCard>

            <SocialCard
                title={"Suhas Dissanayake"}
                subtitle={"SuhasDissa"}
                link={"https://gitlab.com/SuhasDissa"}
            >
                <GitlabIcon />
            </SocialCard>
        </div>
    </section>
</div>
