<template>
	<nav class="navbar bg-body-tertiary fixed-top">
		<div class="container-fluid">
			<a class="navbar-brand" >Isaac's To do List</a>
			<button class="navar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasNavbar" aria-controls="offcanvasNavbar" aria-label="Toggle Navigation">
				<span class="navbar-toggler-icon"/>
			</button>
			<div class="offcanvas offcanvas-end" data-bs-scroll="true" tabindex="-1" id="offcanvasNavbar" aria-labelledby="offcanvasNavbarLabel">
				<div class="offcanvas-header">
					<h5 class="offcanvas-title" id="offcanvasNavbarLabel">ToDoList</h5>
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
				showMenu: false
			}
		},
		methods: {
			showOffCanvas(){
				console.log(this.showMenu);
				this.showMenu ? this.showMenu = false : this.showMenu = true;
			}
		}
	}
</script>

<style scoped>

.nav-link {
	border-radius: 25px;
	padding-left: 10px;
}
.navbar-brand {
	border-radius: 25px;
	padding-left: 10px;
	padding-right: 10px;
}
.navbar-toggler {
	border-radius: 25px;
}

.offcanvas {
	max-width: 30%
}
</style>
