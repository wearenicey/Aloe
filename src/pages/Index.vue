<template>
	<Layout>
		<section class="position-relative padding-top-xl padding-bottom-xxl bg-quaternary" style="z-index: 1">
			<div class="container max-width-adaptive-lg">
				<div class="grid gap-lg items-center">
					<div class="col-6@md">
						<div class="text-component">
							<h1 class="text-xxl">Otkrijte posao kojim se možete ponositi</h1>
							<p class="text-md color-contrast-medium">
								Putovanje od hiljadu koraka započinje prvim. Forever je na ovom putu više od 40 godina, a mi tek počinjemo. Radite od kuće i uživajte u fleksibilnosti postavljanja sopstvenog radnog vremena.
							</p>
						</div>

						<div class="">
							<div class="flex flex-wrap inline-flex@sm items-center padding-top-md padding-bottom-lg">
								<a href="/proizvodi/" class="btn btn--primary btn--md shadow-md display@md flex-grow justify-between btn--md@lg">
									Upoznajte se sa proizvodima
									<span><g-image class="margin-left-md flex flex-center radius-bottom-left" src="~/assets/img/strelica.svg"></g-image></span>
								</a>
								<a href="/proizvodi/" class="btn btn--primary shadow-md hide@md flex-grow justify-between btn--md@lg">
									Upoznajte se sa proizvodima

									<span> <g-image class="margin-left-md flex flex-center radius-bottom-left" src="~/assets/img/strelica.svg"></g-image></span>
								</a>
							</div>
						</div>
					</div>

					<div class="col-6@md">
						<g-image class="position-absolute bottom-xxxl -translate-x-50% -translate-x-20%@md display@md translate" src="~/assets/img/znak.svg"></g-image>

						<g-image class="block width-100%" :immediate="true" src="~/assets/img/slikaaa.png" alt="Forever Living" quality="75" />
					</div>
				</div>
			</div>
		</section>

		<section class="position-relative bg-tertiary-light padding-bottom-xl padding-bottom-0@lg">
			<div class="container max-width-adaptive-sm">
				<div class="text-center padding-top-xl padding-bottom-lg">
					<div class="text-component">
						<h2>Forever Living benefiti</h2>
						<p class="color-secondary">Powerful, self-serve product and growth analytics to help you convert, engage, and retain more users. Trusted by over 4,000 startups.</p>
					</div>
				</div>
			</div>
			<div class="container max-width-adaptive-lg">
				<div class="grid items-center">
					<div class="col-6@md col-3@lg">
						<div class="grid flex-column flex-center">
							<div class="col margin-bottom-lg">
								<div class="text-center text-left@md">
									<g-image class="margin-bottom-sm" src="~/assets/img/forever-living-benefiti-icon-01.svg"></g-image>
									<div class="text-component">
										<h4>Budi sebi šef</h4>
										<p class="color-secondary">Imajte slobodu da sami napravite svoj raspored, radite gde želite i koliko želite.</p>
									</div>
								</div>
							</div>
							<div class="col">
								<div class="text-center text-left@md">
									<g-image class="margin-bottom-sm" src="~/assets/img/forever-living-benefiti-icon-02.svg"></g-image>
									<div class="text-component">
										<h4>Alati i obuke</h4>
										<p class="color-secondary">Od raznih radionica i webinara, do stotine besplatnih materijala online, imate sve što Vam je potrebno za uspeh.</p>
									</div>
								</div>
							</div>
						</div>
					</div>
					<div class="col-6@md order-lasT display@lg">
						<g-image class="block width-100% height-100%" quality="100" :immediate="true" src="~/assets/img/forever-living-benefiti.png" alt="Forever Living" />
					</div>
					<div class="col-6@md col-3@lg">
						<div class="grid flex-column flex-center">
							<div class="col margin-bottom-lg">
								<div class="text-center text-left@md">
									<g-image class="margin-bottom-sm" src="~/assets/img/forever-living-benefiti-icon-03.svg"></g-image>
									<div class="text-component">
										<h4>Putujte svetom</h4>
										<p class="color-secondary">Postanite svetski putnik uz Forever Living. Iskoristite priliku i posetite najlepše gradove na planeti.</p>
									</div>
								</div>
							</div>
							<div class="col">
								<div class="text-center text-left@md">
									<g-image class="margin-bottom-sm" src="~/assets/img/forever-living-benefiti-icon-04.svg"></g-image>
									<div class="text-component">
										<h4>Popusti na proizvode</h4>
										<p class="color-secondary">Ostvarite ekskluzivne popuste na proizvode u kojima ćete uživati sami ili prilikom prodaje drugima</p>
									</div>
								</div>
							</div>
						</div>
					</div>
				</div>
			</div>
		</section>

		<section class="position-relative padding-y-xl bg-secondary">
			<div class="container max-width-adaptive-lg">
				<div class="grid gap-lg items-center">
					<div class="col-5@md">
						<div class="text-component color-secondary-lighter white-text">
							<strong>Živite zdrav i srećan način života kakav zaslužujete.</strong> Forever Living pruža priliku da započnete posao sa stvarnim potencijalom i dokazanim rezultatima, a da pritom ne žrtvujete ravnotežu između poslovnog i
							privatnog života.
						</div>

						<div class="">
							<div class="flex flex-wrap inline-flex@sm items-center padding-top-md padding-bottom-lg">
								<a href="/proizvodi/" class="flex flex-grow btn btn--primary"> Upoznajte se sa proizvodima </a>
							</div>
						</div>
					</div>

					<div class="col-7@md">
						<g-image class="block width-100% r" :immediate="true" src="~/assets/img/contents.png" alt="Forever Living" />
					</div>
				</div>
			</div>
		</section>

		<section class="position-relative">
			<div class="container max-width-adaptive-lg">
				<div class="grid gap-lg items-center padding-top-xl padding-top-0@md">
					<div class="col-6@md">
						<div class="text-component color-accent black-text text-lg">
							<span>Premijum proizvodi</span> Forever Living predstavlja najbolje u pogledu kvaliteta i efikasnosti. Forever proizvodi su napravljeni od prirodnih sastojaka i podržani su dugogodišnjim ispitivanjem.
						</div>
					</div>
					<div class="col-6@md">
						<g-image class="block width-100% r" :immediate="true" src="~/assets/img/premium-proizvodi.png" alt="flp klijenti" />
					</div>
				</div>
			</div>
		</section>

		<section class="position-relative">
			<div class="container max-width-adaptive-lg">
				<div class="grid gap-lg items-center">
					<div class="col-6@md order-last">
						<g-image class="block width-100% r" :immediate="true" src="~/assets/img/zdravo-okruzenje.png" alt="flp klijenti" />
					</div>
					<div class="col-6@md">
						<div class="text-component color-secondary-light black-text text-lg">
							<span>Zdravo okruženje</span> Forever Living je kompanija sa savešću, gde je na prvom mestu briga o planeti, ljudima i generacijama koje dolaze. Nastojimo da pozitivno utičemo na svet oko nas
						</div>
					</div>
				</div>
			</div>
		</section>

		<section class="position-relative">
			<div class="container max-width-adaptive-lg">
				<div class="grid gap-lg items-center">
					<div class="col-6@md">
						<div class="text-component color-primary-dark black-text text-lg">
							<span>Briga o drugima</span> nudi priliku za posao u kome možete zaraditi koliko god želite, a da istovremeno budete u mogućnosti da postignete savršenu ravnotežu između poslovnog i privatnog života kojoj svi teže!
						</div>
					</div>
					<div class="col-6@md">
						<g-image class="block width-100%" :immediate="true" src="~/assets/img/briga-o-drugima.png" alt="flp klijenti" />
					</div>
				</div>
			</div>
		</section>

		<section class="products-gallery-v2 padding-bottom-xl padding-top-xxl bg-secondary">
			<div class="container max-width-adaptive-sm">
				<div class="gap-lg flex-row@md">
					<div class="margin-bottom-md">
						<div class="text-component text-center color-primary">
							<h2 class="white-text-one color-tertiary-light font-secondary text-xl"><strong>Forever Living proizvodi</strong> počnite danas da živite zdravije, srećnije i ispunjenije. Upoznajte se sa proizvodima.</h2>
						</div>
					</div>
					<div class="padding-top-md padding-top-0@md text-center">
						<g-link to="/proizvodi/" class="btn btn--md btn--primary margin-right-xs@md margin-bottom-sm">Pogledaj sve proizvode </g-link>
						<g-link to="/istorija-kompanije/" class="btn btn--md btn--subtle hover-text"> Saznaj više o Forever karijeri </g-link>
					</div>
				</div>
			</div>
		</section>
		<section class="bg-secondary">
			<div class="container max-width-adaptive-lg padding-bottom-xxl">
				<div class="grid gap-md padding-bottom-md">
					<a class="card-v11 col-4@md radius-lg" href="/napici/aloja-vera-gel/" style="background-image: url(../aloe-vera-gel.webp)" aria-label="Link description">
						<div class="card-v11__box width-90% border border-2 border-contrast-low border-opacity-50% radius-lg">
							<div class="padding-sm text-center text-md">
								<p class="color-white">Forever Aloe Vera Gel</p>
							</div>
						</div>
					</a>
					<a class="card-v11 col-4@md radius-lg display@md" href="/preparati-za-higijenu/pasta-za-zube/" style="background-image: url(../pasta-za-zube.webp)" aria-label="Link description">
						<div class="card-v11__box width-90% border border-2 border-contrast-low border-opacity-50% radius-lg">
							<div class="padding-sm text-center text-md">
								<p class="color-white">Pasta za zube</p>
							</div>
						</div>
					</a>
					<a class="card-v11 col-4@md radius-lg display@md" href="/preparati-za-negu-koze/aloe-first/" style="background-image: url(../aloe-first.jpg)" aria-label="Link description">
						<div class="card-v11__box width-90% border border-2 border-contrast-low border-opacity-50% radius-lg">
							<div class="padding-sm text-center text-md">
								<p class="color-white">Aloe First</p>
							</div>
						</div>
					</a>
				</div>
			</div>
		</section>

		<section class="feature-v2 padding-y-xl bg-secondary">
			<div class="container max-width-adaptive-sm">
				<div class="grid gap-md">
					<div class="text-center">
						<div class="text-component margin-bottom-lg">
							<h2 class="text-xxl color-white">Aloe vera je lekovita biljka koju ljudi koriste hiljadama godina.</h2>
							<p class="text-md color-tertiary-light">
								O njoj se treba brinuti kako bi gel aloje u njenom lišću ostao svež i moćan sa zdravim prednostima! Zato svake godine, Forever Living prati 50 miliona biljaka tokom njihovog životnog ciklusa, od sadnice do berbe. Koristi se
								od lečenja opekotina do poboljšanja vašeg imuno sistema!
							</p>
						</div>
						<div class="flex flex-wrap flex-center gap-sm">
							<a class="btn btn--md btn--primary" href="/proizvodi/">Saznaj više o Aloji</a>
						</div>
					</div>
				</div>
			</div>
		</section>
		<section style="background-image: url(../pozadina.png); background-size: contain; background-repeat: no-repeat">
			<div class="container max-width-adaptive-md">
				<div class="grid">
					<div class="col">
						<g-image class="block width-100%" :immediate="true" src="~/assets/img/pocetna-zadnja-sekcija.png" alt="flp klijenti" />
					</div>
				</div>
			</div>
		</section>

		<div class="container max-width-adaptive-md padding-y-xl">
			<div class="radius-lg inner-glow shadow-xs padding-md padding-lg@md bg-secondary">
				<div class="grid gap-md items-center">
					<div class="col text-center">
						<div class="text-component">
							<h2 class="text-xl color-white">Inovativna rešenja</h2>
							<p class="color-bg-darker">Povećanje nivoa energije, jačanje imuno sistema i održavanje zdravlja, sa prirodnim sastojcima bez dodavanja hemikalija i konzervansa. To je Forever Living</p>
						</div>
						<div class="flex padding-top-md justify-center@md">
							<a href="/kontakt/" class="btn btn--primary"> Kontaktirajte nas</a>
						</div>
					</div>
				</div>
			</div>
		</div>
	</Layout>
</template>

<script>
export default {
	metaInfo() {
		// meta deskripcija
		return {
			title: "Forever Living Proizvodi - Aloja Vera",
			titleTemplate: "Forever Living Proizvodi - Aloja Vera",
			meta: [
				{
					name: "description",
					content: "Proizvodi od aloe vere koji pomažu u poboljšanju zdravlja i blagostanja. Besplatne informacije o proizvodima, ishrani i zdravlju. Kontaktirajte nas i ostvarite popuste."
				},
				{
					name: "og:image",
					content: "https://www.alojanaklik.rs/assets/static/pocetna-kartica-1.71307f6.c41812ecc77912f15e9cd0d465c2cdf6.jpg"
				}
			]
		};
	},

	// pozivanje codyhouse javascript ui
	mounted() {
		let frontEnd = document.createElement("script");
		frontEnd.setAttribute("src", "../main-header.js");
		frontEnd.setAttribute("id", "main-header-js");

		document.body.appendChild(frontEnd);
		let sticky = document.createElement("script");
		sticky.setAttribute("src", "../sticky.js");
		sticky.setAttribute("id", "sticky-js");

		document.body.appendChild(sticky);
		// 👈 load the JS code once the component is mounted
	},
	destroyed() {
		document.getElementById("sticky-js").remove();
		document.getElementById("main-header-js").remove();

		// remove the JS code once the component has been destroyed
	}
};
</script>

<style>
.hover-text:hover {
	color: white;
}
</style>
