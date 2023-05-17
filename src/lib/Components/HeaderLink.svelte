<script>
	export let link;
	export let text;
</script>

<a
	class="flex flex-col xl:flex-row items-center xl:space-x-2 text-2xl group hover:text-pink-600 transition-colors"
	href={link}
>
	<slot name="icon" />
	<p class="w-20 md:w-fit mt-1 text-center mx-auto text-xs xl:w-fit xl:text-2xl">{text}</p>
</a>
