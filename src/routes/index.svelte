<script>
	const sendEmailAddress = async () => {
		console.log('Email sent');
	};

	const style = {
		wrapper: `bg-white flex justify-center items-center w-full `,
		bannerContainer: `px-10 py-6 flex justify-center items-center`,
		banner: `bg-white grid md:grid-cols-2 items-center max-w-6xl`,
		bannerImageContainer: `w-10%`,
		bannerImage: `max-w-10`,
		tagLine: `flex flex-col justify-center items-center`,
		investButton: `py-1 px-6 bg-[#D1EFCB]`,

		container: `px-10 py-6 flex flex-col justify-center items-center`,
		containerContent: `flex justify-center items-center gap-6 max-w-6xl`,
		greenContainer: `bg-[#D1EFCB]`,
		containerTitle: `text-2xl font-bold`,
		containerInfo: `flex flex-col gap-4 w-full`,
		containerImage: `w-1/4 hidden sm:block`,

		stepItems: `p-4 gap-4 grid md:grid-cols-3 justify-center items-center max-w-6xl`,
		stepItem: `flex flex-col justify-center items-center gap-6`,
		stepImage: `h-40`,
		// stepInfo: `invisible lg:visible`,
		stepInfo: `text-center hidden sm:block sm:max-w-md`,
		stepTitle: `text-xl font-bold`,

		containerInfoTitle: `text-xl font-bold`,
		containerBoldInfo: `font-bold`,

		signUpForm: `flex flex-col py-4 px-16 m-4 gap-2 bg-[#D1EFCB] items-center`,
		button: `py-1 px-6 bg-[#071E26] text-[#D1EFCB]`,

		trimMobile: `hidden lg:block`
		// trimMobile: `invisible lg:visible,
	};
</script>

<svelte:head>
	<link rel="icon" href="/images/favicon2.png" type="image/x-icon" />
	<title>Daoment: Democratized Real Estate Investing</title>
</svelte:head>

<div id={style.wrapper}>
	<!--Landing-->
	<div class={style.bannerContainer}>
		<div class={style.banner}>
			<div class={style.bannerImage}>
				<img class={style.bannerImage} alt="Daoment illustration" src="/images/ilustracion.png" />
			</div>
			<div class={style.tagLine}>
				<img
					class="illustration"
					alt="Daoment Democratized Real Estate Investing"
					src="/images/DREI.svg"
				/>

				<a class={style.investButton} href="#"> Join Now </a>
			</div>
		</div>
	</div>
	<!-- <div class={style.banner}>
		<div class={style.bannerImage}>
			<img class={style.bannerImage} alt="Daoment illustration" src="/images/ilustracion.png" />
		</div>
		<div class={style.tagLine}>
			<img
				class="illustration"
				alt="Daoment Democratized Real Estate Investing"
				src="/images/DREI.svg"
			/>

			<a class={style.investButton} href="#"> Join Now </a>
		</div>
	</div> -->

	<!--Adquiere Propiedades Mexicanas-->
	<div class={`${style.container} ${style.greenContainer}`}>
		<div class={style.containerContent}>
			<div class={style.containerInfo}>
				<div class={style.containerTitle}>A new way to invest</div>
				<h2>
					Buy income-producing Mexican properties and earn monthly dividends plus land appreciation
				</h2>
			</div>
			<img
				class={style.containerImage}
				alt="Earn Monthly Dividends"
				src="/images/NewWaytoInvest.png"
			/>
		</div>
	</div>

	<!--How Does it Work?-->
	<div class={style.container}>
		<div class={style.containerTitle}>How it works</div>
		<div class={style.containerContent}>
			<div class={style.stepItems}>
				<div class={style.stepItem}>
					<div class={style.stepTitle}>Buy</div>
					<p class={style.stepInfo}>
						Buy equity shares of hand picked real estate deals, open to both accredited and
						non-accredited investors.
					</p>
					<img class={style.stepImage} alt="Own" src="/images/Buy.svg" />
				</div>
				<div class={style.stepItem}>
					<div class={style.stepTitle}>Earn</div>
					<p class={style.stepInfo}>
						Recieve monthly rental distributions and accrue apreciation as the value of the asset
						goes up over time.
					</p>
					<img class={style.stepImage} alt="Earn" src="/images/Earn.svg" />
				</div>
				<div class={style.stepItem}>
					<div class={style.stepTitle}>Trade</div>
					<p class={style.stepInfo}>
						Exit your position without lockups or holding periods. Sell your shares to a global
						market in a global platform.
					</p>
					<img class={style.stepImage} alt="Trade" src="/images/Trade.svg" />
				</div>
			</div>
		</div>
	</div>

	<!--Benefits-->
	<div class={`${style.container} ${style.greenContainer}`}>
		<div class={style.containerTitle}>Benefits</div>
		<div class={style.containerContent}>
			<div class={style.containerInfo}>
				<div class="">
					<div class={style.containerInfoTitle}>Real Estate</div>
					<p>
						<span class={style.containerBoldInfo}>Passive income:</span> when buildings generate income,
						investors receive distributions
					</p>
					<p>
						<span class={style.containerBoldInfo}>Inflation hedge:</span> rising rents create opportunities
						for higher distributions
					</p>
				</div>
				<div>
					<div class={style.containerInfoTitle}>Tokenized Real Estate</div>
					<p>
						<span class={style.containerBoldInfo}>Diversification:</span> individual real estate asset
						performance is generally less correlated to public markets
					</p>
					<p>
						<span class={style.containerBoldInfo}>Greater control:</span> take part in relevant investment
						decisions such as when to sell and what property improvements to invest in
					</p>
				</div>
				<div id="Button">
					<a class={style.button} href="#">Learn More</a>
				</div>
			</div>
			<img class={style.containerImage} alt="liquidity" src="/images/Liquidity.png" />
		</div>
	</div>

	<!--Sign Up-->
	<div class={style.container} style="background-image: url(../images/Industrial.jpg)">
		<div class={style.containerTitle}>Real Estate investment, available for all.</div>
		<div id="sign-up">
			<form action="action_page.php">
				<div class={style.signUpForm}>
					<h1 class="text-center">Get notifications about our first tokenized property</h1>

					<label for="email"><b>Email</b></label>
					<input class="text-center" type="text" placeholder="Enter Email" name="email" required />

					<a class={style.button} on:click={sendEmailAddress} href="/emailsent">Enter</a>
				</div>
			</form>
		</div>
	</div>
</div>
