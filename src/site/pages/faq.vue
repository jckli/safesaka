<template>
	<!-- eslint-disable max-len -->
	<div class="container has-text-left">
		<h2 class="subtitle">
			What is SafeSaka?
		</h2>
		<article class="message">
			<div class="message-body">
				SafeSaka is a private CDN for hayasaka.moe. It utilizes ChibiSafe, which you can find <a target="_blank" href="https://github.com/WeebDev/chibisafe">here</a>. 
			</div>
		</article>

		<h2 class="subtitle">
			Can I create an account?
		</h2>
		<article class="message">
			<div class="message-body">
				Probably not. As of right now, I want to keep this site private. If you really need one and we are mutuals, message me.
			</div>
		</article>

	</div>
</template>

<script>
export default {
	name: 'Faq',
	data() {
		return {};
	},
	head() {
		return {
			title: 'FAQ'
		};
	}
};
</script>

<style lang="scss" scoped>
	@import '~/assets/styles/_colors.scss';
	article.message { background-color: #ffffff; }
</style>
