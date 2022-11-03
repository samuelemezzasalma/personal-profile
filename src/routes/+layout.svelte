<script>
	import './styles.css';
</script>

<div class="app">

	<header>
		<nav id="navbar">
			<span class="icon" aria-hidden="true">A</span>
			<ul>
				<li></li>
				<li>Speaking</li>
				<li>Writing</li>
				<li>Uses</li>
				<li>Contact</li>
				<li>Dark mode</li>
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
