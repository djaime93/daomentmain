<script>
	const style = {
		warpper: `bg-[#071E26] px-6 sm:px-10 py-6 text-[#D1EFCB] flex items-center`,
		logo: `flex max-w-20 max-h-20 sm:max-w-32 sm:max-h-32`,
		infoWrapper: `flex flex-col justify-center w-full gap-1`,
		inline: `items-center text-end`,
		link: ``
	};
</script>

<div class={style.warpper}>
	<img class={style.logo} src="/images/Daomentsello.png" alt="" fill="none" />
	<div class={style.infoWrapper}>
		<a class={style.inline} href="/marketplace">How it works</a>
		<a class={style.inline} href="/marketplace">Marketplace</a>
		<a class={style.inline} href="/marketplace">Sign Up</a>
		<a class={style.inline} href="/marketplace">Contact Us</a>
	</div>
</div>
