<template>
	<nav class="navbar bg-body-tertiary fixed-top">
		<div class="container-fluid">
			<a class="navbar-brand" href=#>To do List</a>
			<button class="navar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle Navigation">
				<span class="navbar-toggler-icon"/>
			</button>
			<div class="offcanvas offcanvas-end" data-bs-scroll="true" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
				<div class="offcanvas-header">
					<h5 class="offcanvas-title" id="offcanvasNavbarLabel">ToDoList</h5>
					<button type="button" class="btn-close" data-bs-dimiss="offcanvas" data-bs-target="#offcanvasNavbar" aria-label="Close"></button>
				</div>
				<div class="offcanvas-body">
					<ul class="navbar-nav justify-content-end">
						<li class="nav-item">
							<a class="nav-link" href="#"> Manage Lists </a>
						</li>
						<li class="nav-item">
							<a class="nav-link" href="#"> Pomodor Timer </a>
						</li>
						<li class="nav-item">
							<a class="nav-link" href="#"> Preferences </a>
						</li>
					</ul>
				</div>
			</div>
		</div>
	</nav>
</template>

<script>
	export default {
		data() {
			return {
				
			}
		},
		methods: {
		
		}
	}
</script>
