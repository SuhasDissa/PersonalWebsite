<script lang="ts">
    export let title;
    export let subtitle;
    export let link;
</script>

<a
    href={link}
    class="flex items-center max-w-sm p-6 bg-slate-50 rounded-lg drop-shadow hover:-translate-y-2 hover:drop-shadow-xl duration-100 dark:bg-slate-800 dark:hover:bg-slate-700"
>
    <slot />
    <div>
        <h5
            class="mb-2 text-2xl font-bold tracking-tight text-slate-700 dark:text-slate-300"
        >
            {title}
        </h5>
        <p class="font-normal text-slate-500 dark:text-slate-400">
            {subtitle}
        </p>
    </div>
</a>
