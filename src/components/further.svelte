<main id="about">
	<div class="wrapper">
		<h1><u>Frequently Asked Questions</u></h1>
		<p class="lead">
			Any other questions? <a href="mailto:help@hexafalls.tech" class="primary-green"
				>Send us a message →</a
			>
		</p>

		<div class="grid">
			<div class="box">
				<h3>Hacking? That sounds scary.</h3>
				<p class="answer">
					We’re not “hacking into the mainframe”, it’s being redefined as an umbrella term for
					coding and tinkering with computers.
				</p>
			</div>
			<div class="box">
				<h3>I’m not very good at coding...</h3>
				<p class="answer">
					That’s OK! We’ll have workshops teaching you the basics of making websites, games, and
					more!
				</p>
			</div>
			<div class="box">
				<h3>What should I bring?</h3>
				<p class="answer">
					Bring a laptop, chargers and anything else you’ll need for your hack (hardware?)!
				</p>
			</div>
			<div class="box">
				<h3>Will food be provided?</h3>
				<p class="answer">Yes! Food and snacks will be provided throughout the event.</p>
			</div>
			<div class="box">
				<h3>How much does entry cost?</h3>
				<p class="answer">
					Nothing at all! The event is 100% free of charge to all eligible hackers.
				</p>
			</div>
			<div class="box">
				<h3>Do I need a team to join?</h3>
				<p class="answer">
					Nope! You’ll have dedicated time to meet new hackers and form teams [4 per. max] or work
					alone.
				</p>
			</div>
		</div>

		<h1><u>Our Sponsors</u></h1>
		<p class="lead">
			Want to sponsor Hexa Falls? <a href="mailto:admin@hexafalls.tech" class="primary-green"
				>Get in touch →</a
			>
		</p>
		<div style="display: flex; align-items: center; gap: 3rem; flex-wrap: wrap; max-width: 90vw">
			<a href="https://balsamiq.com">
				<img src="wordmark.png" alt="37signals Logo" style="width: 300px; max-width: 90vw;">
			  </a>
			  <a href="https://certifyme.online/">
				<img src="cert.png" alt="37signals Logo" style="width: 300px; max-width: 90vw;">
			  </a>
			  <a href="https://interviewbuddy.net/">
				<img src="intbud.png" alt="37signals Logo" style="width: 300px; max-width: 90vw;">
			  </a>
			  <a href="https://codecrafters.io/">
				<img src="codecraf.png" alt="37signals Logo" style="width: 300px; max-width: 90vw;">
			  </a>
			  <a href="https://www.interviewcake.com/">
				<img src="cake.png" alt="37signals Logo" style="width: 300px; max-width: 90vw;">
			  </a>
			  
			  
		</div>
	</div>
</main>

<style>
	main {
		height: max-content;
		background-color: #f3e9d0;
		color: black;
		display: flex;
		justify-content: center;
		padding-top: 3rem;
		padding-bottom: 7rem;
	}

	h1 {
		margin: 0;
		font-size: 4rem;
		width: 90vw;
	}

	p {
		font-size: 1.8rem;
	}

	.answer {
		margin-block-start: 0em;
		margin-block-end: 0em;
		font-size: 1.1rem;
	}

	.lead {
		width: 90vw;
		line-height: 3.5rem;
		font-size: 1.8rem;
	}

	.grid {
		display: grid;
		grid-template-columns: 30vw 30vw 30vw;
		grid-template-rows: auto;
		gap: 24px 24px;
		margin-bottom: 72px;
		margin-top: 48px;
	}

	.box {
		display: flex;
		flex-direction: column;
		gap: 8px;
		border: 2px solid var(--primary-green);
		padding: 1rem;
	}

	h2 {
		font-size: 2.5rem;
		margin: 0;
		margin-block-end: 0em;
	}

	.m-hidden {
		display: flex;
	}

	.m-shown {
		display: none !important;
	}

	h3 {
		margin-block-start: 0em;
		margin-block-end: 0em;
		font-size: 1.3em;
	}

	@media (max-width: 850px) {
		.grid {
			grid-template-columns: 90vw;
		}
		.m-hidden {
			display: none !important;
		}
		.m-shown {
			display: flex;
		}
	}
</style>
