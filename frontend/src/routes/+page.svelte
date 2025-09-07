<script lang="ts">
	import Slide from '$lib/Slide.svelte';
</script>

<!-- Landing view -->
<div class="relative h-[60vh] w-[100vw] bg-[url(/src/lib/assets/landing.jpg)] bg-cover bg-center">
	<!-- Greeting -->
	<h1 class="absolute bottom-0 ml-[0rem] text-sm/12 text-[6rem] text-(--fuk-bg) lg:text-[5.5rem]">
		Herzlich Willkommen
	</h1>

	<!-- FuK Logo -->
	<img
		src="/src/lib/assets/logo.png"
		alt="Logo"
		class="absolute right-0 -bottom-48 hidden lg:inline"
	/>
</div>

<!-- Spacer -->
<div class="lg:h-[25vh]">
	<h2 class="ml-[1.5rem] text-sm/15 text-[3rem] text-(--fuk-green2)">schön dass du da bist!</h2>
</div>

<!-- About me -->
<div id="about" class="flex flex-col-reverse bg-(--fuk-green2) p-[2.5%] lg:flex-row">
	<div class="">
		<p class="row-start-1 mb-4 w-full text-[1.5rem] text-(--fuk-bg)">
			<span class="caption text-sm/15 text-[5rem] text-(--fuk-green0) md:text-[6rem]">Hi</span>, ich
			bin Janette und seit zehn Jahren biete ich wilde Ferien und Weiterbildungen als ausgebildete
			Natur- und Wildnispädagogin an.
		</p>
		<p
			class="row-start-0 float-right text-right font-[Neo_Sans_Std] text-[1rem]
      text-(--fuk-bg) italic"
		>
			„Ein Kind fragt: „Was ist das Gras?“ und pflückt mir Hände voll; was könnte ich dem
			Kinderwidern? Ich weiß es selber nicht besser als das Kind.“<br />
			- Walt Whitman
		</p>
	</div>

	<img
		src="/src/lib/assets/janette.gif"
		alt="Janette Volk"
		class="rounded-2xl object-cover lg:ml-4 lg:h-full"
	/>
</div>

<Slide />
