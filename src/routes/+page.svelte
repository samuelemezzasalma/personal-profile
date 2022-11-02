<script>
import Fa from 'svelte-fa/src/fa.svelte'
import { faLinkedin, faGithub, faYoutube, faTwitter } from '@fortawesome/free-brands-svg-icons';
</script>

<svelte:head>
	<title>Samuele Mezzasalma</title>
	<meta name="description" content="Personal page" />
</svelte:head>

<div class="g-cont">

<section class="profile">
		<img src="https://avatars.githubusercontent.com/u/4698607?v=4" alt="profile picture">
	</section>
	<section id="welcome-section" class="profile-data">
		<h1 id="title">Hello I'm Samuele Mezzasalma</h1>
		<p id="subtitle">Developer based in Italy</p>
		<div class="contacts">
			<ul>
				<li><Fa icon={faTwitter} /></li>
				<li><Fa icon={faYoutube} /></li>
				<li><Fa icon={faGithub} /></li>
				<li><Fa icon={faLinkedin} /></li>
			</ul>	
		</div>
	</section>

	<section id="projects">
		<article class="project-tile"></article>
	</section>
	
</div>



<style>

</style>
