<script>
	import Fa from 'svelte-fa/src/fa.svelte'
	import { faLinkedin, faGithub, faYoutube, faTwitter } from '@fortawesome/free-brands-svg-icons';
</script>

<svelte:head>
	<title>Home</title>
	<meta name="description" content="Svelte demo app" />
	<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.2/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-Zenh87qX5JnK2Jl0vWa8Ck2rdkQ2Bzep5IDxbcnCeuOxjzrPF/et3URy9Bv1WTRi" crossorigin="anonymous">
	<link href="src/routes/styles2.css" rel="stylesheet">
</svelte:head>

<div class="g-cont app">

	<header class="g-cont header">
		<div class=" header-icon ">
		</div>
		<div class=" header-title ">
		</div>
		<div class=" header-menu">
			<nav id="navbar">
				<span tabindex="0" class="icon" aria-hidden="true">E</span>
				<ul class="menu-list">
					<li class="header-link" ><a href="#profile">Profile</a></li>
					<li class="header-link" ><a href="#projects">Projects</a></li>
					<li class="header-link" ><a href="#footer">Contacts</a></li>
				</ul>
			</nav>
		</div>
	</header>

	<main class="g-cont main-container">
		<slot />
	</main>

	<footer id="footer" class=" footer">
		<div class="footer-wrap">
			<section class="footer-main">
				<p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
			</section>
			<section class="footer-col">
				<h3>Find me</h3>
				<a href="https://github.com/samuelemezzasalma">
					Github</a>
				<a href="https://www.linkedin.com/in/samuele-mezzasalma/">
					Linkedin
				</a>
			</section>
		</div>
		<section class="footer-copyright">
			<p>©2022 Samuele Mezzasalma. All Rights Reserved.</p>
		</section>
	</footer>
</div>

<style>
</style>
