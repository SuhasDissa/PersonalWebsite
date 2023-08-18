<script lang="ts">
    export let id:string;
</script>

<a href="https://unsplash.com/photos/{id}" class="block rounded-lg drop-shadow hover:-translate-y-2 hover:drop-shadow-xl duration-100">
    <img
        class="h-auto max-w-full rounded-lg"
        src="https://source.unsplash.com/{id}"
        alt=""
    />
</a>
