<script>
    export let id;
</script>
<section {id} class="min-h-screen flex flex-c px-4">
    <div class="flex flex-col flex-a max-w-[1400px] mx-auto w-full">
        <slot />
    </div>
</section>