<script lang="ts">
	import TailwindLogo from '$lib/assets/images/tailwind-logo.svg';
	import FigmaLogo from '$lib/assets/images/figma-logo.svg';
	import SvelteLogo from '$lib/assets/images/svelte-logo.svg';
	import SolidJSLogo from '$lib/assets/images/solidjs-logo.svg';
	import Email from '$lib/assets/images/email.svg';
	import LinkedIn from '$lib/assets/images/linkedin.svg';
	import GitHub from '$lib/assets/images/github.svg';
	import Discord from '$lib/assets/images/discord.svg';
	import BigBen from '$lib/assets/images/big_ben.png';
	import ExeterIOT from '$lib/assets/images/exeter_iot.png';
	import Office from '$lib/assets/images/office.png';
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
		<h2>Selected Projects.</h2>
		<div class="content-wrapper">
			<p>Developing & designing has been a long path of choosing which tools I prefer to work with, and it all depends on what has to be created for the client.</p>
			<p>Many tools are not listed, but these are the tools I use. Using the tools presented on a daily basis means I can move at a faster pace and have the highest quality work.</p>
		</div>
		<div class="project-cards gap">
			<div class="project-card atlas">
				<div class="card-header">
					<h3>atlasos.net</h3>
					<div class="tag-wrapper">
						<p class="tag development">Development</p>
						<p class="tag ui-ux">UI/UX</p>
					</div>
				</div>
				<div class="card-content">
					<div class="industry">
						<span>INDUSTRY</span>
						<p>Gaming & Technology</p>
					</div>
					<div class="technologies">
						<span>TECHNOLOGIES</span>
						<p><a class="figma-link" href="https://figma.com" target="_blank" rel="noreferrer">Figma</a> & <a class="svelte-link" href="https://kit.svelte.dev" target="_blank" rel="noreferrer">SvelteKit</a></p>
					</div>
				</div>
				<div class="visit-link">
					<p>Visit project -></p>
				</div>
			</div>
			<div class="project-card imjack">
				<div class="card-header">
					<h3>imjack.me</h3>
					<div class="tag-wrapper">
						<p class="tag development">Development</p>
						<p class="tag ui-ux">UI/UX</p>
					</div>
				</div>
				<div class="card-content">
					<div class="industry">
						<span>INDUSTRY</span>
						<p>Personal</p>
					</div>
					<div class="technologies">
						<span>TECHNOLOGIES</span>
						<p><a class="figma-link" href="https://figma.com" target="_blank" rel="noreferrer">Figma</a> & <a class="svelte-link" href="https://kit.svelte.dev" target="_blank" rel="noreferrer">SvelteKit</a></p>
					</div>
				</div>
				<div class="visit-link">
					<p>Visit respository -></p>
				</div>
			</div>
		</div>
		<div class="project-cards">
			<div class="project-card eclean">
				<div class="card-header">
					<h3>eclean.gg</h3>
					<div class="tag-wrapper">
						<p class="tag ui-ux">UX</p>
					</div>
				</div>
				<div class="card-content">
					<div class="industry">
						<span>INDUSTRY</span>
						<p>Gaming & Techology</p>
					</div>
					<div class="technologies">
						<span>TECHNOLOGIES</span>
						<p><a class="figma-link" href="https://figma.com" target="_blank" rel="noreferrer">Figma</a></p>
					</div>
				</div>
				<div class="visit-link">
					<p>Visit project -></p>
				</div>
			</div>
		</div>
	</div>
</div>
<div class="sm-container">
	<div class="contact-me-container">
		<div class="contact-me-wrapper">
			<div class="content">
				<span class="category">PROJECTS<span class="line" /></span>
				<h1>Let’s connect.</h1>
				<p class="description">Thanks for browsing my website. If you have a project in mind, and you’re looking for support; I’m always open for freelance or contracted work. So, let’s talk!</p>
			</div>
			<div class="connections-container">
				<div class="connections-wrapper">
					<div class="column">
						<div class="email">
							<img src={Email} alt="email icon" />
							<div class="content">
								<span>Email</span>
								<a href="mailto:jackholmes@onmail.com">jackholmes@onmail.com</a>
							</div>
						</div>
						<div class="discord">
							<img src={Discord} alt="discord icon" />
							<div class="content">
								<span>Discord</span>
								<a href="https://discordapp.com/users/497444619131551745">Syrm#0001</a>
							</div>
						</div>
					</div>
					<div class="column">
						<div class="linkedin">
							<img src={LinkedIn} alt="linkedin icon" />
							<div class="content">
								<span>LinkedIn</span>
								<a href="https://www.linkedin.com/in/jack-holmes-408929225/">@jack-holmes</a>
							</div>
						</div>
						<div class="github">
							<img src={GitHub} alt="github icon" />
							<div class="content">
								<span>GitHub</span>
								<a href="https://github.com/SyrmGIT">@SyrmGIT</a>
							</div>
						</div>
					</div>
				</div>
				<div class="mb-connections">
					<div class="mb-wrapper">
						<a href="mailto:jackholmes@onmail.com"><img src={Email} alt="email icon" /></a>
						<a href="https://discordapp.com/users/497444619131551745"><img src={Discord} alt="discord icon" /></a>
						<a href="https://www.linkedin.com/in/jack-holmes-408929225/"><img src={LinkedIn} alt="linkedin icon" /></a>
						<a href="https://github.com/SyrmGIT"><img src={GitHub} alt="github icon" /></a>
					</div>
					<a class="mb-cv" href="https://google.com">Download my CV -></a>
				</div>
			</div>
		</div>
		<div class="cv-section">
			<div class="photos">
				<div class="column">
					<img src={BigBen} alt="big ben" />
					<a href="https://google.com">Download my CV -></a>
				</div>
				<div class="column">
					<img src={Office} alt="office space" />
					<img src={ExeterIOT} alt="exeter iot building" />
				</div>
			</div>
		</div>
	</div>
	<div class="footer">
		<p><a href="https://imjack.me">imjack.me</a> © 2023</p>
	</div>
</div>
