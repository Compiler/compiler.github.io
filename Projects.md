---
title: Projects
layout: landing
description: and how they helped me
image: assets/images/pic05.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Forgotten Projects</h2>
		</header>
		<p>For the first 3-4 years of programming, all my projects were stored locally and then backed up to a google drive. This was before I understood the importance of version control, even in solo projects. However, even though they are old, it is funny how much I would over complicate easy tasks just to see if I could. Always challenging yourself is a key part of growth-- working just outside your limits and struggling. Below I list some of the projects that I DO have on GitHub and am excited to show you. </p>
	</div>
</section>

<!-- Two -->
<section id="two" class="spotlights">
	<section>
		<a href="https://github.com/Compiler/Vofog-Game-Engine" class="image">
			<img src="{% link assets/images/vofog.png %}" alt="" data-position="center center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Vofog Engine</h3>
				</header>
				<p>This engine was a long running passion project to explore the intricacies of rendering and opengl. Simultaneously, I was very interested in learning shaders and realtime graphics manipulation, so in the engine I ended up supporting realtime shader compilation and a very intuitive UI for myself to explore and build on the topics.</p>
				<ul class="actions">
					<li><a href="https://github.com/Compiler/Vofog-Game-Engine" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="https://github.com/Compiler/NLParallel_PublicVersion" class="image">
			<img src="{% link assets/images/first_pass.png %}" alt="" data-position="top center" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>NLParallel</h3>
				</header>
				<p>NLParallel was a project that taught me a ton about scraping the web and the technologies, challenges, and power of data mining. I did this project initially under Dr. Kai Wang for computing the novelty of an idea. To do this, we needed data and the data was my first job. One thing that caught me by surprise was the difficulties in being smart about the scraping approach-- I might've accidently created n sub graphs or a big tree, so I also needed a way to visualize data(Image is a picture of that data) and other ways to validate my findings such as predictable results from a Kruskal pass over my graph. I ended up scraping millions of lines of code from open source projects and parsing them into code-comment pairs.</p>
				<ul class="actions">
					<li><a href="https://github.com/Compiler/NLParallel_PublicVersion" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
	<section>
		<a href="https://github.com/Compiler/Ray-Marching-Demo" class="image">
			<img src="{% link assets/images/raymarching.PNG %}" alt="" data-position="25% 25%" />
		</a>
		<div class="content">
			<div class="inner">
				<header class="major">
					<h3>Ray Marching</h3>
				</header>
				<p>Ray marching was a pet project to learn how to morph solid figures in a realistic looking way. It mixes real life optical physics with the deceptive techniques of computer rendering. The image shows a frame from the simulation, and I really enjoyed the process of figuring out these tehcniques. I aim to use these techniques in an upcoming rendering engine.</p>
				<ul class="actions">
					<li><a href="https://github.com/Compiler/Ray-Marching-Demo" class="button">Learn more</a></li>
				</ul>
			</div>
		</div>
	</section>
</section>

<!-- Three -->
<section id="three">
	<div class="inner">
		<header class="major">
			<h2>Present Day Projects</h2>
		</header>
		<p>Currently, I am working with WebRTC to try and stream data into a webclient that will render a depth map from a robot. I build the WebRTC p2p connections myself and added redundancy with TURN servers and other related WebRTC helpers. The end goal is to see if we can't effectively and efficiently control a robot over the web with realtime accuracy. </p>
		<ul class="actions">
			<li><a href="https://github.com/compiler" class="button next">My Github</a></li>
		</ul>
	</div>
</section>

</div>

