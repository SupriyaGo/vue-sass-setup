<!-- @format -->

<template>
	<div class="card">
		<div class="card-header">
			<h2>Hello world</h2>
		</div>
		<div class="card-content">
			<p>
				Lorem ipsum dolor sit, amet consectetur adipisicing elit. Possimus
				ratione libero est voluptates cumque, corrupti deserunt dolorum ullam
				non nihil, autem eveniet quasi ducimus iste blanditiis distinctio sequi
				ipsum reprehenderit!
			</p>
		</div>
		<div class="card-footer">
			<button>Submit</button>
		</div>
	</div>
</template>

<script>
	export default {
		name: "Card",
	};
</script>

<style lang="scss" scoped>
	.card {
		width: 40%;
		padding: 2em 4em;
		box-shadow: 5px 5px 40px 5px #ccc;
		margin: 5em auto;
		&-header {
			border-bottom: 1px solid #ccc;
		}
		&-content {
			padding: 2em 1em;
		}
		&-footer {
			button {
				background: chocolate;
				padding: 1em 2em;
				outline: none;
				color: #fff;
				font-size: 1rem;
				border-radius: 6px;
				text-align: center;
				text-decoration: none;
				display: inline-block;
				transition: 0.3s;
				border: 1px solid chocolate;
				cursor: pointer;
			}
			button:hover {
				background: oldlace;
				color: chocolate;
				border: 1px solid chocolate;
			}
		}
	}
</style>
