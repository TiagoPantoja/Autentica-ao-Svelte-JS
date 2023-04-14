<script>
	export let data;
</script>

<h1 class="text-3xl font-bold">
	Bem vindo ao projeto Svelte, {data?.profile?.name || ''}!
</h1>