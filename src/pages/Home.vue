<template>
	<div class="container mx-auto px-4">

		<div class="py-16">
			<div>
				<a href="#" class="px-2 text-xs text-green-400 bg-gray-300 rounded uppercase">&#60; Go back</a>
			</div>

			<div class="mt-8">
				<div class="flex flex-row justify-between flex-wrap">
					<div>
						<span class="text-green-500 bg-green-200 rounded-full px-2 py-1 py-1 text-xs font-bold mr-3">In progress</span>
						<div class="my-2">
							<h1 class="text-2xl text-black font-bold">The Accredited Sales Executive (ASE) End-point app</h1>
						</div>
						<div>
							<button class="bg-green-500 hover:bg-green-700 text-sm text-white py-2 px-4 rounded uppercase">
								Add update
							</button>
						</div>
					</div>

					<div class="flex mt-2">
						<div class="border border-gray-400 rounded text-center mr-2 text-black">
							<div class="py-2 px-6 bg-green-300 bg-opacity-50 rounded-t">
								<span class="font-bold">Due Date</span>
							</div>
							<div class="p-6">
								<span class="font-lg">12/02/20</span>
							</div>
						</div>
						<div class="border border-gray-400 rounded text-center text-black">
							<div class="py-2 px-6 bg-green-300 bg-opacity-50 rounded-t">
								<span class="font-bold">Amount (USD)</span>
							</div>
							<div class="p-6">
								<span class="font-lg">$250,000.00</span>
							</div>
						</div>
					</div>
				</div>
			</div>

			<div class="mt-4">
				<Tabs />

				<div class="flex flex-col md:flex-row relative">
					<div class="activity-bg bg-gray-200 flex-1 py-12 px-8 md:pl-0 md:pr-16 md:border-r border-gray-300">
						<div class="">
							<Card />
						</div>
					</div>
					<div class="flex-1 bg-white py-12 px-8 md:pl-0 md:pl-16">
						<h2 class="text-xl text-black font-bold">History</h2>
						<div class="mt-8">
							<Timeline />
						</div>
					</div>
				</div>
			</div>
		</div>

	</div>
</template>

<script>
    import Timeline from "@/components/Timeline";
    import Card from "@/components/Card";
    import Tabs from "@/components/Tabs";
    export default {
        name: "pages",
        components: {Tabs, Card, Timeline}
    }
</script>

<style>
@media (min-width: 768px) {
	.activity-bg {
		position: relative;
	}
	.activity-bg::before {
		content: "";
		position: absolute;
		width: calc(100vw / 2);
		height: 100%;
		background-color: #edf2f7;
		top: 0;
		left: -50vw;
		z-index: 0;
	}
}
</style>
