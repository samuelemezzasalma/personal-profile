<script>
	import Fa from 'svelte-fa/src/fa.svelte'
	import { faLinkedin, faGithub, faYoutube, faTwitter } from '@fortawesome/free-brands-svg-icons';
	</script>
	
	<svelte:head>
		<title>Samuele Mezzasalma</title>
		<meta name="description" content="Personal page" />
	</svelte:head>
	
	<div id="profile" class="g-cont profile">
		<section class="g-item profile-img">
			<!-- src="https://avatars.githubusercontent.com/u/4698607?v=4" -->
			<img src="BaD9Ui98_400x400.png"  alt="profile picture">
		</section>
		<section id="welcome-section" class="profile-data g-item">
			<h1 id="title">Hey! I am Sam</h1>
			<h4><i>a web developer based in Italy</i></h4>
			<!-- <p id="subtitle"></p> -->
			<div class="contacts">
				<ul class="contact-list">
				<!-- width="712" height="484"  -->
					<li class="contact-link">
						<a class="profile-svg" id="profile-link" href="https://www.freecodecamp.org/fcc0f2c6d8b-46c7-4668-bc07-140db56f0171" target="_blank">
							<svg class="link"
								xmlns="http://www.w3.org/2000/svg"
								xmlns:xlink="http://www.w3.org/1999/xlink" preserveAspectRatio="xMidYMid meet" version="1.1" viewBox="0 0 712 484">
								<defs>
									<path fill="#fffffe" id="a1UGBK5Jf" d="M136.83 9.96C139.18 12.3 141.53 15.67 141.54 19.06C141.55 24.92 134.67 32.87 121.95 45.93C68.91 97 42.23 159.54 42.41 234.97C42.61 318.42 70.67 385.44 125.21 437.38C136.68 447.63 141.39 455.69 141.41 462.59C141.41 465.97 139.08 469.49 136.74 472.88C134.54 475.23 129.85 477.59 126.47 477.59C113.85 477.62 96.19 462.7 73.13 433.67C28.23 378.64 7.93 317.87 6.79 235.05C5.74 152.19 31.72 96 82.57 37.99C100.87 17.26 116.13 6.49 126.54 6.47C129.92 6.46 133.44 7.62 136.83 9.96Z"/>
									<path fill="#fffffe" id="a8LR3SBcZL" d="M415.42 249.9C395.49 244.81 477.27 148.19 331.92 32.51C331.92 32.51 350.99 93.1 254.83 228.31C158.62 363.47 297.61 443.99 297.61 443.99C297.61 443.99 232.38 409.23 308.21 285.47C321.78 263.02 339.54 242.69 361.59 196.93C361.59 196.93 381.11 224.48 370.92 284.21C355.68 374.47 437.01 348.64 438.27 349.9C466.68 383.35 414.74 442.14 411.58 443.99C408.43 445.79 559.91 352.87 452.29 213.03C444.92 220.4 435.34 255 415.42 249.9Z"/>
									<path fill="#fffffe" id="eYLbcOweH" d="M575.26 9.9C572.91 12.24 570.56 15.61 570.55 19C570.54 24.86 577.42 32.81 590.14 45.87C643.18 96.93 669.86 159.48 669.68 234.91C669.48 318.36 641.42 385.38 586.88 437.32C575.41 447.57 570.7 455.63 570.68 462.53C570.68 465.91 573.01 469.43 575.35 472.82C577.55 475.17 582.24 477.52 585.62 477.53C598.24 477.56 615.9 462.64 638.96 433.61C683.86 378.58 704.16 317.81 705.3 234.99C706.35 152.13 680.37 95.94 629.52 37.93C611.22 17.2 595.96 6.43 585.55 6.41C582.17 6.4 578.65 7.56 575.26 9.9Z"/>
								</defs>
								<g>
									<g>
										<g>
											<use fill="#000" fill-opacity="1" opacity="1" xlink:href="#a1UGBK5Jf"/>
											<g>
												<use fill-opacity="0" stroke="#000" stroke-opacity="0" stroke-width="1" opacity="1" xlink:href="#a1UGBK5Jf"/>
											</g>
										</g>
										<g>
											<use fill="#000" fill-opacity="1" opacity="1" xlink:href="#a8LR3SBcZL"/>
											<g>
												<use fill-opacity="0" stroke="#000" stroke-opacity="0" stroke-width="1" opacity="1" xlink:href="#a8LR3SBcZL"/>
											</g>
										</g>
										<g>
											<use fill="#000" fill-opacity="1" opacity="1" xlink:href="#eYLbcOweH"/>
											<g>
												<use fill-opacity="0" stroke="#000" stroke-opacity="0" stroke-width="1" opacity="1" xlink:href="#eYLbcOweH"/>
											</g>
										</g>
									</g>
								</g>
							</svg>
						</a>
					</li>
					<li class="contact-link">
						<a id="profile-link" href="https://github.com/samuelemezzasalma" target="_blank">
							<Fa class="link" icon={faGithub} />
						</a>
					</li>
					<li class="contact-link">
						<a href="https://www.linkedin.com/in/samuele-mezzasalma/" target="_blank">
							<Fa class="link" icon={faLinkedin} />
						</a>
					</li>
					<!-- <li class="contact-link">
						<a href="https://twitter.com/sam_halfcorpse">
							<Fa icon={faTwitter} />
						</a>
					</li> -->
				</ul>	
			</div>
		</section>
	</div>
	
	<section id="projects" class="projects g-item">
		<h4>These are some of my projects</h4>
		<div class="project-gallery g-cont">
			<div class="card project-tile" >
				<a href="https://codepen.io/freeCodeCamp/full/zNqgVx" target="_blank" class="project project-tile">
					<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute.jpg" class="card-img-top" alt="" />
				</a>
				<div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				</div>
			</div>
			<div class="card project-tile" >
				<a href="https://codepen.io/freeCodeCamp/full/qRZeGZ" target="_blank" class="project project-tile">
					<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" class="card-img-top" alt="project" >
				</a>
				<div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				</div>
			</div>
			<div class="card project-tile" >
				<a href="https://codepen.io/freeCodeCamp/full/wgGVVX" target="_blank" class="project project-tile">
					<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/calc.png" class="card-img-top" alt="project" >
				</a>
				<div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				</div>
			</div>
			<div class="card project-tile" >
				<a href="https://codepen.io/freeCodeCamp/full/mVEJag" target="_blank" class="project project-tile">
					<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/map.jpg" class="card-img-top" alt="project" >
				</a>
				<div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				</div>
			</div>
			<div class="card" >
				<a href="https://codepen.io/freeCodeCamp/full/wGqEga" target="_blank" >
					<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/wiki.png" class="card-img-top" alt="project" >
				</a>
				<div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				</div>
			</div>
			<div class="card project-tile" >
				<a href="https://codepen.io/freeCodeCamp/full/KzXQgy" target="_blank" class="project project-tile">
					<img src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tic-tac-toe.png" class="card-img-top" alt="project" >
				</a>
				<div class="card-body">
					<h5 class="card-title">Card title</h5>
					<p class="card-text">Some quick example text to build on the card title and make up the bulk of the card's content.</p>
					<a href="#" class="btn btn-primary">Go somewhere</a>
				</div>
			</div>
	
	<!-- --------------------------------------------------------------------- -->
	
	
			<!-- <article class="g-item project-tile"><div class="card">
				<a href="https://codepen.io/freeCodeCamp/full/zNqgVx" target="_blank" class="project project-tile">
					<img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tribute.jpg" alt="project">
				</a>
				<div class="container">
					<h4><b>John Doe</b></h4>
					<p>Architect & Engineer</p>
				</div>
			</div></article>
			<article class="g-item project-tile"><div class="card">
				<a href="https://codepen.io/freeCodeCamp/full/qRZeGZ" target="_blank" class="project project-tile">
					<img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/random-quote-machine.png" alt="project">
				</a>
				<div class="container">
					<h4><b>John Doe</b></h4>
					<p>Architect & Engineer</p>
				</div>
			</div></article>
			<article class="g-item project-tile"><div class="card">
				<a href="https://codepen.io/freeCodeCamp/full/wgGVVX" target="_blank" class="project project-tile">
					<img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/calc.png" alt="project">
				</a>
				<div class="container">
					<h4><b>John Doe</b></h4>
					<p>Architect & Engineer</p>
				</div>
			</div></article>
			<article class="g-item project-tile"><div class="card">
				<a href="https://codepen.io/freeCodeCamp/full/mVEJag" target="_blank" class="project project-tile">
					<img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/map.jpg" alt="project">
				</a>
				<div class="container">
					<h4><b>John Doe</b></h4>
					<p>Architect & Engineer</p>
				</div>
			</div></article>
			<article class="g-item project-tile"><div class="card">
				<a href="https://codepen.io/freeCodeCamp/full/wGqEga" target="_blank" class="project project-tile">
					<img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/wiki.png" alt="project">
				</a>
				<div class="container">
					<h4><b>John Doe</b></h4>
					<p>Architect & Engineer</p>
				</div>
			</div></article>
			<article class="g-item project-tile"><div class="card">
				<a href="https://codepen.io/freeCodeCamp/full/KzXQgy" target="_blank" class="project project-tile">
					<img class="project-image" src="https://cdn.freecodecamp.org/testable-projects-fcc/images/tic-tac-toe.png" alt="project">
				</a>
				<div class="container">
					<h4><b>John Doe</b></h4>
					<p>Architect & Engineer</p>
				</div>
			</div></article> -->
		</div>
	</section>
	
	
	
	<style>
	
	</style>
	