<script>
	// import './styles.css';
	import './styles2.css';
</script>

<div class="g-cont app">

	<header class="g-cont header">
		<div class="g-item header-icon ">
			<p>Test</p>
		</div>
		<div class="g-item header-title ">
			<p>Test</p>
		</div>
		<div class="g-item header-menu">
			<nav id="navbar">
				<input id="dropdown" class="input-box" type="checkbox" >
				<label for="dropdown" class="burger">
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
		</div>
	</header>

	<main class="g-cont main-container">
		<slot />
	</main>

	<footer class="g-cont footer">
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
