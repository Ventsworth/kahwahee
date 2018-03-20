<template>
	<!-- App -->
	<div id="app">
		
		<!-- Statusbar -->
		<f7-statusbar></f7-statusbar>
		
		<!-- Main Views -->
		<f7-views>
			<f7-view id="main-view" navbar-through :dynamic-navbar="true" main>
				<!-- Navbar -->
				<f7-navbar>
					<f7-nav-center sliding>Queue Tea Cup</f7-nav-center>
				</f7-navbar>

		
				<div data-page = "login-screen" class = "page no-navbar no-toolbar no-swipeback">
					<div class = "page-content login-screen-content">
						<br>
						<br>
						<div class = "login-screen-title">Kahwahee Login</div>
						<form>
							<div class = "list-block">
								<ul>
								<li class = "item-content">
									<div class = "item-inner">
										<div class = "item-title label">Username</div>
										<div class = "item-input">
											<input type = "text" name = "username" placeholder = "Enter the username">
										</div>
									</div>
								</li>
								
								<li class = "item-content">
									<div class = "item-inner">
										<div class = "item-title label">Password</div>
										<div class = "item-input">
											<input type = "password" name = "password" placeholder = "Enter the password">
										</div>
									</div>
								</li>
								</ul>
							</div>
							
							<div class = "list-block">
								<ul>
								<li><a href = "#" class = "button button-big button-outline">Log In</a></li>
								</ul>
							</div>
						</form>
					</div>
				</div>

			</f7-view>
		</f7-views>
	</div>
</template>

<script>
	export default {}
</script>

<style scoped>
.order {
	/* padding-left: 0.2em; */
	/* border: 1em white; */
	border: white;
	border-style: solid;
}

.order-specifications {
	padding-right: 35%;
	/* margin: 0 auto; */
}

.page {
	padding: 0px;
}

#order {
	height: 10em;
}

.back {
	background-color: purple;
}

#coconut {
	background-color: blue;
}

#brew {
	background-color: chocolate;
}

#strawberry {
	 background-color: red;
}
</style>
