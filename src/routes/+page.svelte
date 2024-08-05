<script>
	import supervisor from '$lib/images/icon-supervisor.svg';
	import team_builder from '$lib/images/icon-team-builder.svg';
	import karma from '$lib/images/icon-karma.svg';
	import calculator from '$lib/images/icon-calculator.svg';
</script>

<div class="container">
	<div class="wrap">
		<h1 class="heading">
			Reliable, efficient delivery
			<div class="highlight">Powered by Technology</div>
		</h1>
		<p class="text">
			Our Artificial Intelligence powered tools use millions of project data points to ensure that
			your project is successful
		</p>
	</div>
	<div class="cards">
		<div class="card1">
			<div class="line1"></div>
			<div class="title">Supervisor</div>
			<div class="text-alt">Monitors activity to identify project roadblocks</div>
			<img class="icon" src={supervisor} alt="" />
		</div>
		<div class="card2">
			<div class="card-alt1">
				<div class="line2"></div>
				<div class="title">Team Builder</div>
				<div class="text-alt">
					Scans our talent network to create the optimal team for your project
				</div>
				<img class="icon" src={team_builder} alt="" />
			</div>
			<div class="card-alt2">
				<div class="line3"></div>
				<div class="title">Karma</div>
				<div class="text-alt">Regularly evaluates our talent to ensure quality</div>
				<img class="icon" src={karma} alt="" />
			</div>
		</div>
		<div class="card3">
			<div class="line4"></div>
			<div class="title">Calculator</div>
			<div class="text-alt">Uses data from past projects to provide better delivery estimates</div>
			<img class="icon" src={calculator} alt="" />
		</div>
	</div>
</div>

<style>
	.wrap {
		text-align: center;
		display: flex;
		flex-direction: column;
		align-items: center;
	}
	.heading {
		color: #4d4f62;
		font-size: 36px;
		font-weight: 200;
		letter-spacing: 0.25px;
	}
	.highlight {
		font-weight: 600;
		margin-bottom: 13px;
	}
	.text {
		color: #4d4f62;
		font-size: 15px;
		line-height: 25px;
		letter-spacing: 0.1px;
		width: 540px;
		margin-bottom: 64px;
	}
	.cards {
		display: flex;
		flex-direction: row;
		gap: 30px;
		align-items: center;
	}
	.card2 {
		display: flex;
		flex-direction: column;
		gap: 30px;
	}
	.card1,
	.card3,
	.card-alt1,
	.card-alt2 {
		position: relative;
		display: flex;
		flex-direction: column;
		width: 350px;
		height: 250px;
		border-radius: 8px;
		background-color: white;
		box-shadow: 0 15px 30px -11px rgba(131, 166, 210, 0.5);
	}
	.line1,
	.line2,
	.line3,
	.line4 {
		width: 100%;
		height: 4px;
		border-radius: 8px 8px 0 0;
	}
	.line1 {
		background-color: #44d3d2;
	}
	.line2 {
		background-color: #ea5454;
	}
	.line3 {
		background-color: #fcae4a;
	}
	.line4 {
		background-color: #549ef2;
	}
	.title {
		margin-top: 32px;
		margin-left: 32px;
		font-size: 20px;
		font-weight: 600;
		margin-bottom: 6px;
		color: #4d4f62;
	}
	.text-alt {
		margin-left: 32px;
		width: 286px;
		font-size: 13px;
		line-height: 23px;
		letter-spacing: 0.09px;
		color: #4d4f62;
	}
	.icon {
		position: absolute;
		right: 32px;
		bottom: 32px;
	}
	@media only screen and (max-width: 375px) {
		.heading {
			font-size: 24px;
			letter-spacing: 0.17px;
		}
		.text {
			width: 311px;
			margin-bottom: 76px;
		}
		.cards {
			flex-direction: column;
			gap: 25px;
		}
		.card2 {
			gap: 25px;
		}
		.card1,
		.card3,
		.card-alt1,
		.card-alt2 {
			width: 311px;
			height: 222px;
		}
		.title {
			margin-top: 17px;
			margin-left: 28px;
			margin-bottom: 1px;
		}
		.text-alt {
			margin-left: 28px;
			width: 254px;
		}
		.icon {
			position: absolute;
			right: 28px;
			bottom: 28px;
		}
	}
</style>
