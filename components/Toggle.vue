<div class="flex items-center justify-center w-screen h-screen">

	<!-- Component Start -->
	<input class="hidden" type="checkbox" id="toggle_1" value="1">
	<label class="flex items-center justify-start w-10 border border-black h-6 p-1 rounded-full cursor-pointer" for="toggle_1">
		<span class="w-4 h-4 bg-black rounded-full"></span>
	</label>
	<!-- Component End  -->

	<span class="w-8"></span>

	<!-- Component Start -->
	<input class="hidden" type="checkbox" id="toggle_2" value="2">
	<label class="flex items-center justify-start w-10 border border-black h-6 p-1 cursor-pointer" for="toggle_2">
		<span class="w-4 h-4 bg-black"></span>
	</label>
	<!-- Component End  -->

</div>

<style lang="scss">
input[type="checkbox"]:checked + label {
	justify-content: flex-end;
	background-color: black;
}

input[type="checkbox"]:checked + label span {
	background-color: white;
}
</style>
