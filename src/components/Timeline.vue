<template>
	<div>
		<div class="pl-6 pb-10 border-tl-green-circle border-l-2 border-green-500">
			<h4 class="font-bold">Now</h4>
		</div>
		<div class="pl-6 pb-10 border-tl-green-circle border-l-2 border-green-500">
			<span class="text-gray-400 text-sm">Tue 5/02/2019</span>
			<h4 class="font-bold">Onsite meeting</h4>
			<div class="mt-2">
				<div class="flex text-gray-600">
					<div class="md:w-1/5 pr-2">
						<span class="font-bold">Attendees:</span>
					</div>
					<div class="w-4/5">
						<p>Art Vamdelay, Jackie Chiles</p>
					</div>
				</div>
				<div class="flex text-gray-600">
					<div class="md:w-1/5 pr-2">
						<span class="font-bold">Discussed:</span>
					</div>
					<div class="w-4/5">
						<p>Current network infrastructure design and big5 focus areas for next FY. Proposed product test drive and/r SLR for next steps.</p>
					</div>
				</div>
			</div>
		</div>
		<div class="pl-6 pb-10 border-tl-green-circle border-l-2 border-green-500">
			<span class="text-gray-400 text-sm">Wed 6/02/2019</span>
			<h4 class="font-bold">Prospects added from Penske Inc.</h4>
			<div class="mt-2">
				<a href="#" class="px-2 text-xs text-green-400 font-bold rounded uppercase">View prospects ></a>
			</div>
		</div>
		<div class="pl-6 border-tl-green-circle border-l-2 border-transparent">
			<span class="text-gray-400 text-sm">Thur 7/02/2019</span>
			<h4 class="font-bold">HPE Activity approved</h4>
		</div>
	</div>
</template>

<script>
    export default {
        name: "Timeline"
    }
</script>

<style>
	.border-tl-green-circle {
		position: relative;
	}
	.border-tl-green-circle::before {
		position: absolute;
		content: '';
		top: 0;
		left: -8px;
		width: 15px;
		height: 15px;
		background-color: #48bb78;
		border-radius: 50%;
	}
</style>
