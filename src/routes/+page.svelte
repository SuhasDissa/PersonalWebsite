<script>
    import Quote from "../components/Quote.svelte";
</script>

<div class="mx-auto max-w-screen-xl px-8 py-20">
    <section>
        <h3
            class="text-slate-700 dark:text-slate-300 text-3xl sm:text-4xl md:text-5xl font-bold"
        >
            Hi, I'm
        </h3>
        <h1
            class="text-slate-700 dark:text-slate-300 text-4xl sm:text-5xl md:text-7xl font-bold pt-4 sm:pt-8"
        >
            Suhas Dissanayake
        </h1>
        <h2
            class="text-slate-400 text-xl sm:text-2xl md:text-4xl font-bold max-w-prose pt-4 sm:pt-8"
        >
            I am a 20-year-old Android app developer from Sri Lanka. I am also
            passionate about graphics design, and I have been using Arch Linux
            for many years.
        </h2>
    </section>
    <section class="pt-40">
        <h2
            class="text-slate-600 dark:text-slate-400 text-2xl sm:text-3xl md:text-5xl font-bold"
        >
            My Favourite Quotes
        </h2>
        <div class="flex flex-col items-center">
            <Quote>
                If you can't explain it simply, you don't understand it well enough.
            </Quote>
            <Quote>
                The first time you do anything, it will be bad. But the only way to get better is to start.
            </Quote>
        </div>
    </section>
</div>
