<script>
	const style = {
		wrapper: `px-10 py-4 flex justify-between items-center sticky top-0 text-[#D1EFCB] bg-black z-10`,
		nav: `flex items-center gap-2`,
		navItems: `mx-1 text-lg`,
		logo: `w-10`,
		accountInfo: `flex items-center gap-2`,
		createAccountButton: `p-2 text-black bg-[#D1EFCB]`
	};
</script>

<header>
	<div class={style.wrapper}>
		<div class={style.nav}>
			<a href="/"><img class={style.logo} src="/images/IconoVerde.svg" alt="" /></a>
		</div>

		<div>
			<nav class={style.navItems}>
				<!-- <a class={style.navItems} href="/">Home</a> -->

				<!-- <a
					class={style.navItems}
					href="https://daoment.gitbook.io/copy-of-daoment-faqs/"
					target="_blank">FAQ</a
				> -->
				<a class={style.navItems} href="/marketplace">Marketplace</a>
			</nav>
		</div>
		<!-- <div class={style.accountInfo}>
			<div class="in"><a href="/marketplace">Sign In</a></div>
			<div class={style.createAccountButton}>
				<a href="/marketplace" class="create">Create Account</a>
			</div>
		</div> -->
	</div>

	<!-- <div class="ddgroup">
		<img class="logo" src="/images/IconoNegro.png" />
		Menu
		<div class="ddsub">
			<a href="#">Marketplace</a>
			<a href="#">FAQs</a>
			<a href="#">Sign-In</a>
			<a href="#">Create Account</a>
		</div>
	</div> -->
</header>
