<script>
	export let title = 'Schools';
	export let desc = 'Chose which schools to search from';
	export let value = false;
</script>

<div class="space-y-5">
	<div class="relative flex items-start">
		<div class="flex h-6 items-center">
			<input
				id="comments"
				aria-describedby="comments-description"
				name="comments"
				type="checkbox"
				class="h-4 w-4 rounded border-gray-300 text-indigo-600 focus:ring-indigo-600"
				checked={value}
			/>
		</div>
		<div class="ml-3 text-sm leading-6">
			<label for="comments" class="font-medium text-gray-900">{title}</label>
			<span id="comments-description" class="text-gray-500"
				><span class="sr-only">{title} </span>{desc}</span
			>
		</div>
	</div>
</div>
