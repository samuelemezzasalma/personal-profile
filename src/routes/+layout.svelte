<script>
	// import './styles.css';
	import './styles2.css';
</script>

<div class="app">

	<header class="g-cont">
	<div class="header-left-block g-item"></div>
		<nav id="navbar" class="g-item">
			
			<input id="dropdown" class="input-box" type="checkbox" >
			<label for="dropdown" class="dropdown">
				<span class="icon" aria-hidden="true">A</span>
			</label>
			<ul class="menu-list">
				<li><a href="#about">About</a></li>
				<li><a href="#speaking">Speaking</a></li>
				<li><a href="#writing">Writing</a></li>
				<li><a href="#uses">Uses</a></li>
				<li><a href="#contact">Contact</a></li>
				<li><a href="#dark-mode">Dark mode</a></li>
			</ul>
		</nav>
	</header>

	<main>
		<slot />
	</main>

	<footer>
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
