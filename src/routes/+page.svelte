<script lang="ts">
	import TailwindLogo from '$lib/assets/images/tailwind-logo.svg';
	import FigmaLogo from '$lib/assets/images/figma-logo.svg';
	import SvelteLogo from '$lib/assets/images/svelte-logo.svg';
	import SolidJSLogo from '$lib/assets/images/solidjs-logo.svg';
</script>

<div class="sm-container">
	<div class="hero-banner">
		<span class="profession">UIX Design & Web Development<span class="line" /></span>
		<h1>JACK HOLMES</h1>
		<p>A passionate web developer, and experienced designer from the United Kingdom. Creating fast, responsive and scalable websites using modern technologies. I am studying design, business and web development.</p>
		<a href="#contact-me" class="button">Contact me!</a>
	</div>
</div>
<div class="lg-container">
	<div class="what-ive-used">
		<div class="card-wrapper">
			<div class="design-card">
				<h2>Digital Design</h2>
				<p>Designing has been a long path of choosing which tools I prefer to work with, and I prefer using Figma for website design. I also use the Adobe suite for other work!</p>
			</div>
			<div class="dev-card">
				<h2>Web Development</h2>
				<p>Designing has been a long path of choosing which tools I prefer to work with, and I prefer using Figma for website design. I also use the Adobe suite for other work!</p>
			</div>
		</div>
		<div class="skills">
			<span class="category">SKILLS<span class="line" /></span>
			<h2>What I've used.</h2>
			<p>Developing & designing has been a long path of choosing which tools I prefer to work with, and it all depends on what has to be created for the client.</p>
			<p>Many tools are not listed, but these are the tools I use. Using the tools presented on a daily basis means I can move at a faster pace and have the highest quality work.</p>
			<div class="technologies-wrapper">
				<a href="https://tailwindcss.com/" target="_blank" rel="noreferrer"><img src={TailwindLogo} alt="tailwind logo" /></a>
				<a href="https://figma.com/" target="_blank" rel="noreferrer"><img src={FigmaLogo} alt="figma logo" /></a>
				<a href="https://kit.svelte.dev/" target="_blank" rel="noreferrer"><img src={SvelteLogo} alt="svelte logo" /></a>
				<a href="https://www.solidjs.com/" target="_blank" rel="noreferrer"><img src={SolidJSLogo} alt="solidjs logo" /></a>
			</div>
		</div>
	</div>
	<div class="selected-projects">
		<span class="category">PROJECTS<span class="line" /></span>
		<h2>Selected Projects</h2>
		<div class="content-wrapper">
			<p>Developing & designing has been a long path of choosing which tools I prefer to work with, and it all depends on what has to be created for the client.</p>
			<p>Many tools are not listed, but these are the tools I use. Using the tools presented on a daily basis means I can move at a faster pace and have the highest quality work.</p>
		</div>
		<div class="project-card-atlas">
			<div class="card-header">
				<h3>atlasos.net</h3>
				<div class="tags">
					<p class="tag development">Development</p>
				</div>
			</div>
		</div>
	</div>
</div>
