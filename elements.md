---
title: Projects
layout: landing
description: old and new
image: assets/images/pic05.jpg
nav-menu: true
---

<!-- Main -->
<div id="main">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h2>Forgotten projects</h2>
		</header>
		<p>For the first 3-4 years of programming, all my projects were stored locally and then backed up to a google drive. This was before I understood the importance of version control even in solo projects. However, even though they are old it is funny how much I would over complicate easy tasks just to see if I could. Always challenging yourself is a key part of growth-- working just outside your limits and struggling. Below I list some of the projects that I DO have on github and am excited to show you. </p>
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
				<p>This engine took me nearly a year of long hour days to develop. This engine supports scripting in Lua, a photoshop esque drag and drop system, entity component system for faster processing with cache friendliness & data oriented design, realtime Bullet Physics support, and a whole host of other features. The entire rendering pipeline is written in OpenGL and the design is not only aimed at efficiency, but also ease of use. There is realtime updating of shaders to see how your code changes the engine and a customizable UI with ImGUI. The amount of features is endless and it really taught me so many things about architecting a massive system.</p>
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
				<p>NLParallel was a project that taught me a ton about scraping the web and the technologies, challenges, and power of data mining. I did this project initially under Dr. Kai Wang for computing the novelty of an idea. To do this, we needed data and the data was my first job. One thing that caught me by surprise was how to validate that I am even creating a graph when there are millions of nodes-- I might've accidently created n sub graphs or a big tree, so I also needed a way to visualize data(Image is a picture of that data) and other ways to validate my findings such as predictable results from a Kruskal pass over my graph. I didn't know it at the time, but this project helped immensely with the work I do today.</p>
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
				<p>Ray tracing techniques is something that has always been very interesting to me. It mixes real life optical physics with the deceptive techniques of computer rendering. Ray marching was one of those easy introductions to understanding how everything works and can be optimized. The image shows a still image of a frame from the simulation but the techniques involved are really clever and amazing. I aim to use these techniques to accelerate another engine one day.</p>
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
			<h2>Present day projects</h2>
		</header>
		<p>Present day, I am working on a machine learning model to generate comments from code and then unit tests from code. I am also working on a Vulkan backed ray tracing rendering engine in C++ as well as developing my web development and devops skillset. I have many many more projects on my github so go check them out!</p>
		<ul class="actions">
			<li><a href="https://github.com/compiler" class="button next">My Github</a></li>
		</ul>
	</div>
</section>

</div>

