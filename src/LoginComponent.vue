<template>
	<div class="h-dvh flex flex-col content-center items-center">
		<div class="bg-white text-black w-full flex flex-col justify-center items-center">
			<h1 class="text-5xl text-slate-800">Bienvenido a PelisPlus</h1>
			<img class="p-5 w-6/12" src="/src/assets/images/imgLoggin.avif" alt="firstImage" />
			<div class="bg-slate-300 flex flex-col gap-5 p-5 rounded-lg w-4/12">
				<div class="flex flex-col gap-2">
					<label class="text-lg">Ingrese su correo electrónico</label>
					<input
						type="text"
						class="rounded-md p-3 outline-none border-none bg-slate-200 focus:outline-1 focus:outline-slate-400"
						autocomplete="off"
					/>
				</div>
				<div class="flex flex-col gap-2">
					<label class="text-lg">Ingrese su correo contraseña</label>
					<input
						type="password"
						class="rounded-md p-3 outline-none border-none bg-slate-200 focus:outline-1 focus:outline-slate-400"
						autocomplete="off"
					/>
				</div>
			</div>
		</div>
	</div>
</template>
