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
		<span class="profession">UIX Design & Software Engineer<span class="line" /></span>
		<h1>JACK HOLMES</h1>
		<p>I am a web developer and designer from the United Kingdom, passionate about creating fast, responsive, and scalable websites using modern technologies. I am currently studying design, business, and web development.</p>
		<a href="#contact-me" class="button">Contact me!</a>
	</div>
</div>
<div class="lg-container">
	<div class="what-ive-used">
		<div class="card-wrapper">
			<div class="design-card">
				<h2>Digital Design</h2>
				<p>I have been on a journey of selecting my preferred design tools, and I have chosen Figma as my go-to tool for website design. I also use the Adobe suite for other design projects.</p>
			</div>
			<div class="dev-card">
				<h2>Web Development</h2>
				<p>Experimenting with different technologies has been enjoyable. I have played around with Sveltekit, SolidJS and Visual Studio Code is my preferred IDE for development.</p>
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
			<p>A majority of my work experience has been in projects that I own myself. In addition to managing, marketing, and administrating to get the project off the ground, I have also worked specifically on the development and design aspects.</p>
			<p>These are only a selection of the projects I have worked on. I have chosen not to list other projects as I do not consider them to be a comprehensive representation of my abilities or a suitable showcase for my website.</p>
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
					<a href="https://atlasos.net" target="_blank" rel="noreferrer">Visit project -></a>
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
					<a href="https://github.com/SyrmGIT/imjack.me" target="_blank" rel="noreferrer">Visit repository -></a>
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
					<a href="https://eclean.gg" target="_blank" rel="noreferrer">Visit project -></a>
				</div>
			</div>
		</div>
	</div>
</div>
<div class="sm-container">
	<div class="contact-me-container">
		<div class="contact-me-wrapper">
			<div class="content">
				<span class="category">CONTACT<span class="line" /></span>
				<h1>Let’s connect.</h1>
				<p class="description">Thank you for visiting my website. If you have a project in mind and need assistance, I am open to both freelance and contracted work. Please don't hesitate to reach out and let's discuss further.</p>
			</div>
			<div id="contact-me" class="connections-container">
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
						<a href="https://discordapp.com/users/497444619131551745" target="_blank" rel="noreferrer"><img src={Discord} alt="discord icon" /></a>
						<a href="https://www.linkedin.com/in/jack-holmes-408929225/" target="_blank" rel="noreferrer"><img src={LinkedIn} alt="linkedin icon" /></a>
						<a href="https://github.com/SyrmGIT" target="_blank" rel="noreferrer"><img src={GitHub} alt="github icon" /></a>
					</div>
					<a class="mb-cv" href="CV.pdf">Download my CV -></a>
				</div>
			</div>
		</div>
		<div class="cv-section">
			<div class="photos">
				<div class="column">
					<img src={BigBen} alt="big ben" />
					<a href="CV.pdf">Download my CV -></a>
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
