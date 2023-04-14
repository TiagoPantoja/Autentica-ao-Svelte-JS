<script>
	import DiCode from 'svelte-icons/di/DiCode.svelte';
</script>

<div class="flex flex-col items-center h-full w-full pt-12">
	<div class="h-24 w-24 text-primary">
		<DiCode />
	</div>
	<h2 class="mt-2 text-center text-3xl font-bold tracking-tight text-base-content">
		Entrar com sua conta
	</h2>
	<p class="text-center mt-1">
		Ou <a href="/login" class="text-primary font-medium hover:cursor-pointer">criar conta</a> se você não tem uma
	</p>
	<div class="bg-white py-6 shadow-md rounded-lg w-full max-w-sm mt-6">
		<form method="POST" action="?/login" class="flex flex-col items-center space-y-2 w-full">
			<div class="form-control w-full max-w-xs">
				<label for="email" class="label font-medium pb-1">
					<span class="label-text">E-mail</span>
				</label>
				<input type="email" name="email" class="input input-bordered w-full max-w-xs" />
			</div>
			<div class="form-control w-full max-w-xs">
				<label for="password" class="label font-medium pb-1">
					<span class="label-text">Senha</span>
				</label>
				<input type="password" name="password" class="input input-bordered w-full max-w-xs" />
			</div>
			<div class="w-full max-w-xs pt-3">
				<button class="btn btn-primary w-full max-w-xs">Entrar</button>
			</div>
		</form>
	</div>
</div>