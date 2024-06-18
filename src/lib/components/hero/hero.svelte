<script>
	import * as Card from '$lib/components/ui/card';
	import logo100 from '$lib/images/100.svg';
	import bg2 from '$lib/images/bg_2.svg';
	import card1 from '$lib/images/card_1.svg';
	import card2 from '$lib/images/card_2.svg';
	import card3 from '$lib/images/card_3.svg';
	import coffeCup from '$lib/images/coffe_cup.svg';
	import heroImage from '$lib/images/coffee_image.jpg';
	import colombia from '$lib/images/colombia.svg';
	import cup from '$lib/images/cup.svg';
	import logo from '$lib/images/logo.svg';
	import goldLogo from '$lib/images/logo_dorado.svg';
	import social1 from '$lib/images/social_1.svg';
	import social3 from '$lib/images/social_3.svg';
	import splashLeft from '$lib/images/splash_l.svg';
	import splashRight from '$lib/images/splash_r.svg';
	import location from '$lib/images/ubi.svg';
	const SHEET_SIDES = ['Inicio', 'Sobre Nosotros', 'Proposito', 'Contacto'];

	function contactHandler() {
	
		window.open('https://wa.me/573232314602?text=I%27m%20interested%20in%20Cafe%20Plus', '_blank');}
</script>

<div class="overflow-hidden">
	<div class="relative min-h-[768px] max-h-[768px]" id="start">
		<div class="w-full absolute z-[-1]">
			<img
				class="object-cover w-full h-full object-center bg-blend-overlay brightness-75 min-h-[768px] max-h-[768px]"
				src={heroImage}
				alt="hero"
			/>
		</div>
		<header class="pt-4 z-1 md:px-8  lg:px-16">
			<div class="flex flex-col md:flex-row items-center">
				<div class=" w-16 h-11 md:w-24 md:h-16">
					<img class="object-cover object-center" src={logo} alt="cafe logo" />
				</div>

				<ul
					class="flex justify-between items-center md:ml-auto gap-x-9 text-white text-base
                font-medium cursor-pointer transition-transform duration-300 ease-in-out
				pt-5
                "
				>
					<li class="hover:scale-105 text-sm cursor-pointer">
						<a href="#start">Inicio</a>
					</li>
					<li class="hover:scale-105 text-sm cursor-pointer">
						<a href="#about_us">Sobre Nosotros</a>
					</li>
					<li class="hover:scale-105 text-sm cursor-pointer">
						<a href="#purpose">Proposito</a>
					</li>
					<li class="hover:scale-105 text-sm cursor-pointer">
						<a href="https://wa.me/573232314602?text=I'm%20interested%20in%20Cafe%20Plus" target="_blank">Contacto</a>
					</li>
				</ul>
			</div>
		</header>
		<div class=" px-10 lg:px-16">
			<div class="pt-24 max-w-[34.188rem]">
				<div class="w-[14rem] md:w-[22.875rem] h-60">
					<img class="object-cover object-center" src={goldLogo} alt="cafe logo" />
				</div>

				<div class="md:pt-24">
					<button
						on:click={contactHandler}
						class="rounded-2xl bg-[var(--Yellow,_#F9C06A)]
                    border-1
                    hover:scale-105
                    transition-all
                    ease-in-out
                    [box-shadow:0px_6px_12px_0px_rgba(249,_192,_106,_0.22)]
                    px-6 py-3 text-base font-bold
                    text-slate-800
                    ">Contacto</button
					>
					<p class="text-[19px] md:text-xl text-white leading-8 pt-8 italic">
						“Tu momento perfecto comienza con una taza de nuestro café excepcional.”
					</p>
				</div>
			</div>
		</div>
	</div>

	<div class="relative px-[3.5rem] md:px-[5.813rem] pt-[4.5rem]">
		<div class="flex">
			<h2
				class="text-left text-[2.5rem] lg:text-[3.375rem] max-w-[50.75rem] md:max-w-[79rem]
            text-[#603809] font-bold
            "
			>
				Cómo preparar un buen café
			</h2>
			<img
				class="flex-1 hidden xl:block xl:h-[8rem] xl:-w-[32.813rem] absolute top:5% right-[20%] bg-clip-content z-[-1]"
				src={coffeCup}
				alt="cafe cup"
			/>
		</div>
		<div class="flex flex-col justify-center gap-y-2 items-start 2xl:justify-center md:pt-2 md:gap-y-2">
			<div
				class="flex flex-col gap-y-4 md:gap-y-6 sm:flex-row gap-x-6 items-center justify-center pt-12 md:pt-5 text-[#707070] text-xl"
			>
				<div
					class="bg-[#F9C06A] rounded-full px-4 py-2 xl:text-base xl:px-5 xl:py-3 text-[#1E1E1E]
					font-bold shadow-md flex items-center justify-center
					text-base md:text-xs
					"
				>
					1
				</div>
				<p
					class="text-[0.9rem] md:text-base line-clamp-6 leading-8 text-left max-w-[43.063rem] lg:max-w-[79rem]"
				>
					Coloca el filtro de papel V60 en el cono, enjuágalo con agua caliente para quitarle el
					sabor a papel.
				</p>
			</div>

			<div
			class="flex flex-col gap-y-4 md:gap-y-6 sm:flex-row gap-x-6 items-center justify-center pt-12 md:pt-5 text-[#707070] text-xl"
		>
			<div
				class="bg-[#F9C06A] rounded-full px-4 py-2 xl:text-base xl:px-5 xl:py-3 text-[#1E1E1E]
				font-bold shadow-md flex items-center justify-center
				text-base md:text-xs
				"
			>
					2
				</div>
				<p
					class="text-[0.9rem]  md:text-base line-clamp-6 leading-8 text-left max-w-[43.063rem] lg:max-w-[79rem]"
				>
					Hierve el agua a una temperatura ideal de 88-92°. Pon en marcha el temporizador y vierte
					lentamente unos 50 gramos de agua encima del café molido. Asegúrate de que todo el café
					quede bien mojado, puedes usar una cuchara para mezclar.
				</p>
			</div>

			<div
				class="flex flex-col gap-y-4 md:gap-y-6 sm:flex-row gap-x-6 items-center justify-center pt-12 md:pt-5 text-[#707070] text-xl"
			>
				<div
					class="bg-[#F9C06A] rounded-full px-4 py-2 xl:text-base xl:px-5 xl:py-3 text-[#1E1E1E]
					font-bold shadow-md flex items-center justify-center
					text-base md:text-xs
					"
				>
					3
				</div>
				<p
					class="text-[0.9rem]  md:text-base line-clamp-6 leading-8 text-left max-w-[43.063rem] lg:max-w-[79rem]"
				>
					A los 30 segundos, empieza a verter el resto del agua caliente hasta llegar a 250GR con un
					movimiento constante y controlado. Asegúrate de no verter nunca directamente en los bordes
					exteriores del papel.
				</p>
			</div>

			<div
			class="flex flex-col gap-y-4 md:gap-y-6 sm:flex-row gap-x-6 items-center justify-center pt-12 md:pt-5 text-[#707070] text-xl"
		>
			<div
				class="bg-[#F9C06A] rounded-full px-4 py-2 xl:text-base xl:px-5 xl:py-3 text-[#1E1E1E]
				font-bold shadow-md flex items-center justify-center
				text-base md:text-xs
				"
			>
					4
				</div>
				<p
					class="text-[0.9rem]  md:text-base line-clamp-6 leading-8 text-left max-w-[43.063rem] lg:max-w-[79rem]"
				>
					Al final del vertido, gira delicadamente el cono un par de veces, para que ninguno de los
					granos de café se quede pegado al papel.
				</p>
			</div>
		</div>
	</div>

	<div class="relative">
		<img class="z-[1-] h-[4rem] lg:h-[11rem] lg:w-[17rem] scale-x-[-1] absolute" src={splashLeft} alt="splash_l" />
	</div>
	<div id="about_us" class=" pt-[3rem] md:pt-[7.5rem]">
		<div class="w-full flex items-center justify-center">
			<h2 class="text-[2.5rem] lg:text-[3.375rem]  text-[#603809] font-bold">Sobre nosotros</h2>
		</div>

		<div
			class="px-10 lg:px-[5.813rem] pt-[5.85rem] flex flex-wrap gap-x-4 gap-y-10 relative items-center justify-center"
		>
			<Card.Root class="bg-white w-full md:max-w-[23.75rem] min-h-[40.433rem]">
				<Card.Header>
					<div class="flex items-center justify-center -translate-y-11 hover:scale-105">
						<p class="bg-[#F9C06A] w-fit text-xs md:text-base rounded-full leading-8 px-4 py-2 cursor-pointer">
							Quienes Somos
						</p>
					</div>
					<Card.Description>
						<img class="rounded-sm" src={card1} alt="card 1" />
					</Card.Description>
				</Card.Header>
				<Card.Content class="">
					<p class="leading-8 text-slate-700 text-xs md:text-sm text-justify">
						Somos un ministerio de negocios y misión encargado de la comercialización de <span
							class="text-[#F9C06A] font-medium">café</span
						>
						tostado, molido y/o sus derivados, abasteciendo productos de
						<span class="text-[#F9C06A] font-medium">calidad al mercado regional y nacional;</span>
						utilizando el talento humano, llenos de propósito, para satisfacer las expectativas de nuestros
						consumidores y clientes. Estamos comprometidos con el crecimiento y la rentabilidad de la
						empresa y propiciamos desarrollo social a la
						<span class="text-[#F9C06A] font-medium">comunidad.</span>
					</p>
				</Card.Content>
			</Card.Root>
			<Card.Root class="bg-white max-w-[23.75rem] min-h-[40.433rem]">
				<Card.Header>
					<div class=" cursor-pointer flex items-center justify-center -translate-y-11 hover:scale-105">
						<p class="bg-[#F9C06A] w-fit text-xs md:text-base rounded-full leading-8 px-4 py-2">
							Misión
						</p>
					</div>
					<Card.Description>
						<img class="rounded-sm" src={card2} alt="card 1" />
					</Card.Description>
				</Card.Header>
				<Card.Content class="">
					<p class="leading-8 text-slate-700 text-xs md:text-sm text-justify">
						Consolidarnos como un <span class="text-[#F9C06A] font-medium">ministerio</span> líderes
						en el mercado regional, incrementar la participación en el mercado nacional e
						incursionar en el mercado internacional, asegurando la
						<span class="text-[#F9C06A] font-medium">calidad del café</span> tostado, molido y/o sus
						derivados con personal llenos de propósito, logrando la satisfacción de las necesidades de
						nuestros clientes
					</p>
				</Card.Content>
			</Card.Root>

			<Card.Root class="bg-white max-w-[23.75rem] min-h-[40.433rem]">
				<Card.Header>
					<div class=" cursor-pointer flex items-center justify-center -translate-y-11 hover:scale-105">
						<p class="bg-[#F9C06A] w-fit text-xs md:text-base rounded-full leading-8 px-4 py-2">
							Envíos
						</p>
					</div>
					<Card.Description>
						<img class="rounded-sm" src={card3} alt="card 1" />
					</Card.Description>
				</Card.Header>
				<Card.Content class="">
					<p class="leading-8 text-slate-700 text-xs md:text-sm text-justify">
						Desplegamos junto a nuestros misioneros el producto a diferentes ciudades para
						conocimiento de la comunidad dentro y fuera del país.
					</p>
				</Card.Content>
			</Card.Root>

			<img
				class="z-[1-] h-[4rem] lg:h-[11rem] lg:w-[17rem] absolute -bottom-14 right-0"
				src={splashLeft}
				alt="splash_l"
			/>
			<img
				class="z-[1-] h-[35rem] w-[35rem] absolute -top-[14rem] -right-[12.5rem]"
				src={splashRight}
				alt="splash_r"
			/>
		</div>
	</div>

	<div id="purpose" class="pt-[7.5rem] min-h-fit md:min-h-[728px]">
		<img
			class="z-[-1] absolute bg-no-repeat object-cover w-full h-[10rem] md:h-[33rem]"
			src={bg2}
			alt="background2"
		/>

		<div class="flex items-center justify-center pt-[3.313rem]">
			<h2 class="text-white text-[2.5rem] lg:text-[3.375rem] font-bold">Proposito</h2>
		</div>

		<div>
			<div
				class="px-[2.5rem]  pt-[8rem]  lg:pt-[3rem] flex flex-col lg:flex-row lg:flex-wrap gap-x-4 gap-y-10 relative items-center justify-center"
			>
				<Card.Root class="bg-white max-w-[23.75rem] min-h-[31.875rem]">
					<Card.Header>
						<div class=" cursor-pointer flex items-center justify-center -translate-y-11 hover:scale-105">
							<p class="bg-[#F9C06A] w-fit text-xs md:text-base rounded-full leading-8 px-4 py-2">
								Quienes Somos
							</p>
						</div>
						<Card.Description>
							<img class="rounded-sm" src={card1} alt="card 1" />
						</Card.Description>
					</Card.Header>
					<Card.Content class="">
						<p class="leading-8 text-slate-700 text-xs md:text-sm text-justify">
							Ser el ministerio en Colombia más reconocido por trasformar vidas en el mundo, por su
							Calidad, impacto social y sabor.
						</p>
					</Card.Content>
				</Card.Root>
				<div class="px-10">
					<img class=" w-32 md:w-32 lg:w-40 h-full lg:pt-30" src={cup} alt="coffe cup" />
				</div>
				<Card.Root class="bg-white max-w-[23.75rem] min-h-[31.875rem]">
					<Card.Header>
						<div class=" cursor-pointer flex items-center justify-center -translate-y-11 hover:scale-105">
							<p class="bg-[#F9C06A] w-fit text-xs md:text-base rounded-full leading-8 px-4 py-2">
								Variedades de Café
							</p>
						</div>
						<Card.Description>
							<img class="rounded-sm" src={card2} alt="card 1" />
						</Card.Description>
					</Card.Header>
					<Card.Content class="">
						<p class="leading-8 text-slate-700 text-xs md:text-sm text-justify">
							Java, Bourbon Pink, Geisha, Pacamara, Caturra, Tabi, Castillo, Supremo y Colombia
						</p>
					</Card.Content>
				</Card.Root>

				<img
					class="z-[1-] h-[4rem] lg:h-[11rem] lg:w-[17rem] absolute -bottom-14 right-0"
					src={splashLeft}
					alt="splash_l"
				/>
				<img
					class="z-[1-] h-[35rem] w-[35rem] absolute -top-[14rem] -right-[12.5rem]"
					src={splashRight}
					alt="splash_r"
				/>
			</div>
		</div>
	</div>

	<footer class="bg-black h-[18rem] px-5 mt-36 grid grid-cols-3 justify-center place-items-center">
		
			<div class="h-8 w-12 md:w-20 self-center">
				<img class="object-cover object-center" src={goldLogo} alt="cafe logo" />
			</div>

			<div class="flex flex-col gap-y-8 gap-x-2">
				<div class="w-full items-center justify-center pt-[4rem]">
					<div class="flex gap-x-2 items-center justify-center">
						<img class="h-12 w-12 md:w-14 md:h-14" src={logo100} alt="logo 100 percent" />
						<img class="h-12 w-12 md:w-14 md:h-14" src={colombia} alt="colombia logo" />
					</div>
				</div>
				<ul class="flex gap-x-3 items-center justify-center">
					<li>
						<a href="https://wa.me/573232314602?text=I'm%20interested%20in%20Cafe%20Plus" target="_blank" title="Cafe Plus">
							<img class="h-8 w-8 md:h-10 md:w-10" src={social1} alt="WhatsApp" />
						</a>
						
					</li>
					<li>
						<a href="https://www.instagram.com/centrointegralcafeplus?igsh=MXB3emgyeDJhZnNncQ==" target="_blank">
							<img class="h-8 w-8 md:h-10 md:w-10" src={social3} alt="instagram" />
						</a>
					</li>

				</ul>
			</div>

			<div class="flex items-center justify-center gap-x-2">
				<div class="h-3 w-8">
					<img class="object-cover object-center" src={location} alt="cafe logo" />
				</div>
				<p class="font-semibold leading-8 text-white text-xs md:text-base translate-y-2 min-w-fit">Bogotá, Colombia</p>
			</div>
		
	</footer>
</div>
