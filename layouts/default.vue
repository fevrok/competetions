<template>
	<div dir="rtl">
		<nuxt />
	</div>
</template>

<script>
export default {
	head() {
		return {
			meta: [
				{ property: 'og:url', content: 'https://free-fire.competition.fevrok.com' },
				{ property: 'og:title', content: '41000 جوهرة فري فاير مجانا' },
				{ property: 'og:image', content: 'https://d18a0eh5u1wsd3.cloudfront.net/images/142/fevrok_games_free_fire-_competition.png' },
				{ property: 'og:video', content: 'https://www.youtube.com/v/LmDiYZ0OM14' },
				{ property: 'twitter:card', content: 'شارك واربح 41000 جوهرة فري فاير مجانا' },
				{ property: 'twitter:image', content: 'https://d18a0eh5u1wsd3.cloudfront.net/images/142/fevrok_games_free_fire-_competition.png' },
				{ property: 'fb:app_id', content: '152351391599356' }
			]
		}
	}
}
</script>

<style>
html {
	font-family: 'Markazi Text', 'Source Sans Pro', -apple-system, BlinkMacSystemFont, 'Segoe UI',
		Roboto, 'Helvetica Neue', Arial, sans-serif;
	font-size: 16px;
	word-spacing: 1px;
	-ms-text-size-adjust: 100%;
	-webkit-text-size-adjust: 100%;
	-moz-osx-font-smoothing: grayscale;
	-webkit-font-smoothing: antialiased;
	box-sizing: border-box;
}

body {
	background-image: url('~assets/bg.jpg');
	/* background-image: url('https://media.alienwarearena.com/media/background-o3.jpg'); */
	background-size: cover;
}

*,
*:before,
*:after {
	box-sizing: border-box;
	margin: 0;
}
</style>
