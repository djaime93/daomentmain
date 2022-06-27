<svelte:head>
	<link rel="icon" href="/images/favicon2.png" type="image/x-icon" />
	<link rel="stylesheet" href="/css/reset.css" />
	<link rel="stylesheet" href="/css/style.css" />
	<link
		rel="stylesheet"
		type="text/css"
		href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css"
	/>
	<link rel="preconnect" href="https://fonts.googleapis.com" />
	<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
	<link
		href="https://fonts.googleapis.com/css2?family=Roboto:ital,wght@0,400;0,500;0,700;1,400;1,500;1,700&display=swap"
		rel="stylesheet"
	/>
	<title>Daoment: Democratized Real Estate Investing</title>
</svelte:head>

<!--Header-->
<header>
	<div class="menu">
		<div class="left">
			<img class="logo" src="/images/IconoVerde.svg" />
			<nav class="desktop">
				<ul>
					<li><a href="/" class="home">Home</a></li>
					<li><a href="/marketplace">Marketplace</a></li>
					<li>
						<a href="https://daoment.gitbook.io/copy-of-daoment-faqs/" target="_blank">FAQ</a>
					</li>
				</ul>
			</nav>
		</div>
		<div class="sign">
			<div class="in"><a href="#">Sign In</a></div>
			<div class="up"><a href="#" class="create">Create Account</a></div>
		</div>
	</div>

	<div class="ddgroup">
		<img class="logo" src="/images/IconoNegro.png" />
		Menu
		<div class="ddsub">
			<a href="#">Marketplace</a>
			<a href="#">FAQs</a>
			<a href="#">Sign-In</a>
			<a href="#">Create Account</a>
		</div>
	</div>
</header>

<div id="container">
	<!--Landing-->

	<div class="landing">
		<div class="drawing">
			<img class="illustration" alt="Daoment illustration" src="/images/ilustracion.png" />
		</div>
		<div class="tag-line">
			<img
				class="illustration"
				alt="Daoment Democratized Real Estate Investing"
				src="/images/DREI.svg"
			/>
			<div class="button">
				<a class="invest-button" href="#">
					<p>Join Now</p>
				</a>
			</div>
		</div>
	</div>

	<!--Adquiere Propiedades Mexicanas-->
	<div id="container2">
		<div class="buy-banner">
			<div class="invitation">
				<strong>A new way to invest</strong>
				<h2>
					Buy income-producing Mexican properties and earn monthly dividends plus land appreciation
				</h2>
			</div>
			<div class="left-banner">
				<div id="center">
					<div class="icons">
						<img class="Icon1" alt="Earn Monthly Dividends" src="/images/NewWaytoInvest.png" />
					</div>
				</div>
			</div>
		</div>
	</div>

	<!--How Does it Work?-->
	<div id="container3">
		<div class="how-to-invest">
			<strong>How it works</strong>
			<div id="steps">
				<div id="step1">
					<h2>Buy</h2>
					<p>
						Buy equity shares of hand picked real estate deals, open to both accredited and
						non-accredited investors.
					</p>
					<img class="Buy" alt="Own" src="/images/Buy.svg" />
				</div>
				<div id="step2">
					<h2>Earn</h2>
					<p>
						Recieve monthly rental distributions and accrue apreciation as the value of the asset
						goes up over time.
					</p>
					<img class="Earn" alt="Earn" src="/images/Earn.svg" />
				</div>
				<div id="step3">
					<h2>Trade</h2>
					<p>
						Exit your position without lockups or holding periods. Sell your shares to a global
						market in a global platform.
					</p>
					<img class="Trade" alt="Trade" src="/images/Trade.svg" />
				</div>
			</div>
		</div>
	</div>

	<!--Benefits-->
	<div id="container4">
		<div class="benefits">
			<div id="writing">
				<div id="margin-bottom">
					<strong>Benefits</strong>
				</div>
				<h2>Real Estate</h2>
				<p>
					<span>Passive income:</span> when buildings generate income, investors receive distributions
				</p>
				<p>
					<span>Inflation hedge:</span> rising rents create opportunities for higher distributions
				</p>
				<h2>Tokenized Real Estate</h2>
				<p>
					<span>Diversification:</span> individual real estate asset performance is generally less correlated
					to public markets
				</p>
				<p>
					<span>Greater control:</span> take part in relevant investment decisions such as when to sell
					and what property improvements to invest in
				</p>
				<div id="Button">
					<a id="Learn-More" href="#"><p>Learn More</p></a>
				</div>
			</div>
			<div id="liquidity">
				<img class="liquidity" alt="liquidity" src="/images/Liquidity.png" />
			</div>
		</div>
	</div>

	<!--Sign Up-->
	<div id="container5">
		<strong class="democratized">Real Estate investment, available for all.</strong>
		<div id="sign-up">
			<form action="action_page.php">
				<div class="container6">
					<h1>Sign Up</h1>

					<label for="email"><b>Email</b></label>
					<input type="text" placeholder="Enter Email" name="email" required />

					<div id="button2">
						<a id="Learn-More2" href="#"><p>Enter</p></a>
					</div>
				</div>
			</form>
		</div>
	</div>

	<!--Footer-->
	<footer>
		<div class="footerdisplay">
			<img class="sello" src="/images/Daomentsello.png" />
			<div id="footermenu">
				<ul class="footermenu">
					<li><a href="#">How it works</a></li>
					<li><a href="#">Marketplace</a></li>
					<li><a href="#" target="_blank">Sign Up</a></li>
					<li><a href="#" target="_blank">Contact Us</a></li>
				</ul>
			</div>
		</div>
	</footer>
</div>
