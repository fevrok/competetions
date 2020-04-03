<style>
.price-moving {
	animation: price-moving .5s infinite;
	animation-direction: alternate;
}

@keyframes price-moving {
	from { transform: rotate(-2deg) }
	to { transform: rotate(2deg) }
}

.chevron-moving {
	animation: chevron-moving .5s infinite;
	animation-direction: alternate;
}

@keyframes chevron-moving {
	from { transform: translateY(-10px) }
	to { transform: translateY(10px) }
}
</style>

<template>
	<div class="text-blue-900">
		<section>
			<div class="container mx-auto px-5 py-10">
				<div class="flex justify-center mb-10">
					<div class="text-center font-bold text-3xl px-10 py-5 rounded-lg bg-white shadow">
						اتمم المهام اسفله و احصل على مكافأة
					</div>
				</div>
				<div class="flex text-center justify-center mb-10 text-2xl">
					<span class="font-bold text-red-600 price-moving">41.000 💎</span>
					&nbsp;
					للربح 
					حسب المراتب
				</div>
				<div class="flex flex-wrap justify-center -mx-5">
					<div class="lg:w-1/5 sm:w-1/3 w-2/3 px-5 mb-10">
						<div class="bg-white shadow-lg p-3 rounded-lg flex flex-col items-cente text-center transform hover:scale-105 transition duration-200 ease-in-out">
							<div class="flex justify-center">
								<div class="leading-none px-5 py-2 rounded-full bg-blue-100 text-blue-700 mb-3">
									من 1 الى 3
								</div>
							</div>
							<div class="px-10">
								<diamond width="100%" color="blue" />
							</div>
							<div class="text-2xl font-bold text-blue-600">2226 جوهرة</div>
							<!-- <div class="text-xs font-bold text-gray-500">110 MAD</div> -->
						</div>	
					</div>
				</div>
				<div class="flex flex-wrap justify-center -mx-5">
					<div class="lg:w-1/5 sm:w-1/3 w-2/3 px-5 mb-10">
						<div class="bg-white shadow-lg p-3 rounded-lg flex flex-col items-cente text-center transform hover:scale-105 transition duration-200 ease-in-out">
							<div class="flex justify-center">
								<div class="leading-none px-5 py-2 rounded-full bg-pink-100 text-pink-700 mb-3">
									من 4 الى 10 
								</div>
							</div>
							<div class="px-10">
								<diamond width="100%" color="pink" />
							</div>
							<div class="text-2xl font-bold text-pink-600">1092 جوهرة</div>
							<!-- <div class="text-xs font-bold text-gray-500">55 MAD</div> -->
						</div>	
					</div>
					<div class="lg:w-1/5 sm:w-1/3 w-2/3 px-5 mb-10">
						<div class="bg-white shadow-lg p-3 rounded-lg flex flex-col items-cente text-center transform hover:scale-105 transition duration-200 ease-in-out">
							<div class="flex justify-center">
								<div class="leading-none px-5 py-2 rounded-full bg-yellow-100 text-yellow-700 mb-3">
									من 10 الى 50 
								</div>
							</div>
							<div class="px-10">
								<diamond width="100%" color="yellow" />
							</div>
							<div class="text-2xl font-bold text-yellow-600">651 جوهرة</div>
							<!-- <div class="text-xs font-bold text-gray-500">35 MAD</div> -->
						</div>	
					</div>
				</div>
				<div class="flex justify-center mt-10 mb-32">
					<div class="px-10 py-5 rounded-lg text-3xl font-bold">
						شارك من هنا
						<div class="flex justify-center mt-5 text-red-600 chevron-moving">
							<svg xmlns="http://www.w3.org/2000/svg" width="48" height="48" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" class="feather feather-chevrons-down"><polyline points="7 13 12 18 17 13"></polyline><polyline points="7 6 12 11 17 6"></polyline></svg>
						</div>
					</div>
				</div>
			</div>
		</section>
		<section class="-mt-32">
			<div class="container mx-auto px-5 py-10">
				<a class="e-widget no-button" href="https://gleam.io/6AtsJ/free-fire-giveaway-1" rel="nofollow"></a>
				<script type="text/javascript" src="https://widget.gleamjs.io/e.js" async="true"></script>
				<div class="flex justify-center my-10">
					<div class="text-center font-bold text-xl px-10 py-5 bg-white shadow">
						سنعلن عن الفائزين من خلال ديسكورد مع فيديو مباشر على يوتيوب
					</div>
				</div>
			</div>
		</section>
	</div>
</template>

<script>
export default {
	components: {
		Diamond: {
			props: {
				color: { type: String, default: 'red' }
			},
			render() {
				return <svg v-bind={this.$attrs} viewBox="0 0 512 512">
					<polygon class={`text-${this.color}-100 fill-current`} points="105.931,39.724 0,172.138 151.871,172.138" />
					<polygon class={`text-${this.color}-200 fill-current`} points="256,39.724 105.931,39.724 151.871,172.138 " />
					<polygon class={`text-${this.color}-300 fill-current`} points="360.129,172.138 256,39.724 151.871,172.138" />
					<polygon class={`text-${this.color}-400 fill-current`} points="406.069,39.724 256,39.724 360.129,172.138 " />
					<polygon class={`text-${this.color}-500 fill-current`} points="360.129,172.138 512,172.138 406.069,39.724" />
					<polygon class={`text-${this.color}-300 fill-current`} points="0,172.138 256,472.276 151.871,172.138 " />
					<polygon class={`text-${this.color}-400 fill-current`} points="151.871,172.138 256,472.276 360.129,172.138 " />
					<polygon class={`text-${this.color}-300 fill-current`} points="360.129,172.138 256,472.276 512,172.138" />
				</svg>
			}
		}
	}
}
</script>

<style>

</style>