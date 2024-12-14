<script>
	let navLinks = ["Home", "Features", "Team", "About Us", "Contact Us"];
</script>

<nav class="bg-gradient-to-r from-blue-500 to-teal-400 px-8 py-4 text-white shadow-md">
	<div class="container mx-auto flex items-center justify-between">
		<!--		Navigation Links-->
		<ul class="flex space-x-8">
			{#each navLinks as link}
				<li>
					<a
						href={link === "Home" ? "/" : link.toLowerCase()}
						class="hover:text-teal-200 transition duration-300"
					>{link}</a>
				</li>
				{/each}
		</ul>
	</div>
</nav>
