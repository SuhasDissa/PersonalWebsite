<script>
    import UnsplashCard from "../../components/UnsplashCard.svelte";
</script>

<div class="mx-auto max-w-screen-xl px-8 py-20">
    <section>
        <h2
            class="text-slate-600 dark:text-slate-400 text-2xl sm:text-3xl md:text-5xl font-bold"
        >
            My Unsplash Photo Collection
        </h2>
        <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-8 pt-4 sm:pt-8">
            <UnsplashCard id={"nf3qozawzRw"} />
            <UnsplashCard id={"3_uM7uiRf9g"} />
            <UnsplashCard id={"BfNoP-iIs18"} />
            <UnsplashCard id={"asxPa1Ftufs"} />
            <UnsplashCard id={"su22rgZRGNI"} />
            <UnsplashCard id={"LtAR-k4biCg"} />
        </div>
    </section>
</div>
