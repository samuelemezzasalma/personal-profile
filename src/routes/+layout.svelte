<script>
	// import './styles.css';
	// import './styles2.css';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
	<link href="src/routes/styles2.css" rel="stylesheet">
</svelte:head>

<div class="g-cont app">

	<header class="g-cont header">
		<div class="g-item header-icon ">
			<!-- <p>Test</p> -->
		</div>
		<div class="g-item header-title ">
			<!-- <p>Test</p> -->
		</div>
		<div class="g-item header-menu">
			<nav id="navbar">
				<!-- <input id="dropdown" class="input-box" type="checkbox" >
				<label for="dropdown" class="burger"></label> -->
				<span tabindex="0" class="icon" aria-hidden="true">E</span>
				<ul class="menu-list">
					<li class="header-link" ><a href="#profile">Profile</a></li>
					<li class="header-link" ><a href="#projects">Projects</a></li>
					<li class="header-link" ><a href="#footer">Contacts</a></li>
					<!-- <li class="header__link" ><a href="#dark-mode">Dark mode</a></li> -->
				</ul>
			</nav>
		</div>
	</header>

	<main class="g-cont main-container">
		<slot />
	</main>

	<footer id="footer" class="g-cont footer">
		<section>
			<h2>Get in touch</h2>
			<ul>
				<li>Twitter</li>
				<li>Youtube</li>
				<li>Github</li>
				<li>Linkedin</li>
			</ul>
		</section>
	</footer>
</div>

<style>
	/* .app {
	}

	main {
	}

	footer {
	}

	footer a {
	}

	@media (min-width: 480px) {
	} */
</style>
