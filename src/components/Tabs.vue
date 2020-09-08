<template>
	<ul class="flex border-b">
		<li class="-mb-px mr-1">
			<div class="inline-flex bg-white py-2 px-4 border-l border-t border-r rounded-t text-green-700 cursor-pointer">
				<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="height: auto;width: 25px;">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M16 8v8m-4-5v5m-4-2v2m-2 4h12a2 2 0 002-2V6a2 2 0 00-2-2H6a2 2 0 00-2 2v12a2 2 0 002 2z" />
				</svg>
				<a class="font-semibold" href="#">Activity</a>
			</div>
		</li>
		<li class="mr-1">
			<div class="inline-flex bg-white py-2 px-4 text-gray-500 hover:text-green-500 cursor-pointer">
				<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor" style="height: auto;width: 25px;">
					<path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4M7.835 4.697a3.42 3.42 0 001.946-.806 3.42 3.42 0 014.438 0 3.42 3.42 0 001.946.806 3.42 3.42 0 013.138 3.138 3.42 3.42 0 00.806 1.946 3.42 3.42 0 010 4.438 3.42 3.42 0 00-.806 1.946 3.42 3.42 0 01-3.138 3.138 3.42 3.42 0 00-1.946.806 3.42 3.42 0 01-4.438 0 3.42 3.42 0 00-1.946-.806 3.42 3.42 0 01-3.138-3.138 3.42 3.42 0 00-.806-1.946 3.42 3.42 0 010-4.438 3.42 3.42 0 00.806-1.946 3.42 3.42 0 013.138-3.138z" />
				</svg>
				<a class="font-semibold pl-2" href="#">Details</a>
			</div>
		</li>
	</ul>
</template>

<script>
    export default {
        name: "Tabs"
    }
</script>
