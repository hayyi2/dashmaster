<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<title>Dashboard &middot; Dasmaster Template</title>
	<base href="">

	<!-- Bootstrap Core CSS -->
	<link href="css/bootstrap.min.css?v1" rel="stylesheet">

	<!-- vendor -->
	<!-- fontawesome -->
	<link href="css/style.min.css?v1" rel="stylesheet">
	<!-- dataTables -->
	<link href="vendor/dataTables/dataTables.bootstrap4.min.css" rel="stylesheet">

	<!-- custom style -->
	<link href="vendor/fontawesome/css/all.min.css" rel="stylesheet">

	<!-- jQuery -->
	<script src="js/jquery-3.2.1.min.js"></script>
	<!-- Bootstrap Core JavaScript -->
	<script src="js/popper.min.js"></script>
	<script src="js/bootstrap.min.js"></script>
	<script src="js/bs-custom-file-input.min.js"></script>
	<!-- vendor -->
	<!-- dataTables -->
	<script src="vendor/dataTables/jquery.dataTables.min.js"></script>
	<script src="vendor/dataTables/dataTables.bootstrap4.min.js"></script>
	<!-- text editor tinymce -->
	<script type="text/javascript" src="vendor/tinymce/tinymce.min.js"></script>
	<!-- chartjs -->
	<script src="vendor/chartjs/chart.min.js"></script>
	<script src="vendor/chartjs/chart-data.js"></script>

	<!-- custom script -->
	<script src="js/script.js"></script>
</head>
<body class="sidenav">
	<header>
		<nav class="navbar navbar-dark fixed-top">
			<button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#mainnav">
				<i class="fas fa-bars"></i>
			</button>
			<a class="navbar-brand" href="index.html">Dashmaster <small class="show-sm">v1.0</small></a>

			<div class="collapsed navbar-collapse" id="mainnav">
				<ul class="navbar-nav mainnav">
					<li class="nav-item active">
						<a class="nav-link" href="index.html"><i class="fa-sm fas fa-tachometer-alt"></i>Dashboard</a>
					</li>
					<li class="divider"></li>
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							<i class="fa-sm fas fa-th-large"></i>Options
						</a>
						<div class="dropdown-menu" aria-labelledby="navbarDropdown">
							<a class="dropdown-item" href="topnav.html">Top Navbar</a>
							<a class="dropdown-item" href="skin-content.html">Skin & Content</a>
						</div>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="widgets.html"><i class="fa-sm far fa-clone"></i>Widgets</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="charts.html"><i class="fa-sm far fa-chart-bar"></i>Charts</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="tables.html"><i class="fa-sm fas fa-table"></i>Tables</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="forms.html"><i class="fa-sm fas fa-edit"></i>Forms</a>
					</li>
					<li class="nav-item">
						<a class="nav-link" href="elements.html"><i class="fa-sm fas fa-laptop"></i>Elements</a>
					</li>
					<li class="divider"></li>
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							<i class="fa-sm far fa-folder"></i>More Page
							<span class="badge badge-primary">3</span>
						</a>
						<div class="dropdown-menu" aria-labelledby="navbarDropdown">
							<a class="dropdown-item" href="login.html">Login</a>
							<a class="dropdown-item" href="blank.html">Blank Page</a>
							<a class="dropdown-item" href="error.html">Errors Page</a>
						</div>
					</li>
					<!-- <li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							<i class="fa-sm far fa-folder"></i>Examples
							<span class="badge badge-info">5</span>
						</a>
						<div class="dropdown-menu" aria-labelledby="navbarDropdown">
							<a class="dropdown-item" href="mailbox.html"><i class="fa-sm far fa-envelope"></i>Mailbox<span class="badge badge-danger">3</span></a>
							<a class="dropdown-item" href="register.html"><i class="fa-sm fas fa-user-plus"></i>Register</a>
							<a class="dropdown-item" href="profile.html"><i class="fa-sm fas fa-user"></i>Profile</a>
							<a class="dropdown-item" href="lock.html"><i class="fa-sm fas fa-lock"></i>Lock Screan</a>
							<a class="dropdown-item" href="invoice.html"><i class="fa-sm fas fa-receipt"></i>Invoice</a>
						</div>
					</li>
					<li class="divider"></li>
					<li class="nav-item">
						<a class="nav-link" href="docs.html"><i class="fa-sm fas fa-book"></i>Documentations</a>
					</li> -->
				</ul>
				<ul class="navbar-nav ml-auto">
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							<i class="far fa-bell"></i><span class="badge badge-success">2</span>
						</a>
						<div class="dropdown-menu dropdown-menu-right dropdown-notivication">
							<!-- <a href="#" class="dropdown-item disabled">No Notivication</a> -->
							<a href="#" class="dropdown-item">
								<i class="fas fa-sm fa-envelope"></i>2 Pesan baru <br>
								<i class="fas fa-sm"></i><small class="text-secondary">5 Mins ago</small>
							</a>
							<a href="#" class="dropdown-item">
								<i class="fas fa-sm fa-user-friends"></i>5 Member Baru
							</a>
							<div class="dropdown-divider"></div>
							<a href="#" class="dropdown-item"><i class="far fa-sm fa-eye"></i>View All</a>
						</div>
					</li>
					<li class="nav-item dropdown">
						<a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
							<span class="show-sm">Keroro Gunsou</span>
							<div class="avatar ml-0 ml-sm-2"><img src="img/user5.PNG" alt="A"></div>
						</a>
						<div class="dropdown-menu dropdown-menu-right" aria-labelledby="navbarDropdown">
							<a class="dropdown-item" href="profile.html"><i class="fa fa-fw fa-user"></i> Profile</a>
							<a class="dropdown-item" href="change-profile.html"><i class="fa fa-fw fa-user-cog"></i> Change Profile</a>
							<div class="dropdown-divider"></div>
							<a class="dropdown-item" href="login.html"><i class="fa fa-fw fa-sign-out-alt"></i> Logout</a>
						</div>
					</li>
				</ul>
			</div>
		</nav>
	</header>
	<div class="body">
		<div class="auto-height">
			<nav aria-label="breadcrumb">
				<div class="max-xl-container">
					<ol class="breadcrumb">
						<li class="breadcrumb-item active" aria-current="page"><i class="fa-fw fas fa-tachometer-alt"></i> Dashboard</li>
					</ol>
				</div>
			</nav>
			<div class="content max-xl-container">
				<div class="content-header">
					<h2 class="content-title">Dashboard</h2>
				</div>
				<div class="content-body">
					<div class="form-row">
						<div class="col-md-3">
							<div class="card card-count card-primary">
								<div class="card-header">
									<div>
										<h4 class="h1 card-title">152</h4>
										<span>New Orders!</span>
									</div>
									<i class="fas fa-fw fa-shopping-cart fa-5x"></i>
								</div>
								<div class="card-footer">
									<a href="#" class="btn-block">
										Read More
										<i class="float-right mt-1 fa fa-fw fa-arrow-alt-circle-right"></i>
									</a>
								</div>
							</div>
							<!-- /.card -->
						</div>
						<div class="col-md-3">
							<div class="card card-count card-success">
								<div class="card-header">
									<div>
										<h4 class="h1 card-title">340</h4>
										<span>New Stock!</span>
									</div>
									<i class="fas fa-fw fa-cubes fa-5x"></i>
								</div>
								<div class="card-footer">
									<a href="#" class="btn-block">
										Read More
										<i class="float-right mt-1 fa fa-fw fa-arrow-alt-circle-right"></i>
									</a>
								</div>
							</div>
							<!-- /.card -->
						</div>
						<div class="col-md-3">
							<div class="card card-count card-warning">
								<div class="card-header">
									<div>
										<h4 class="h1 card-title">98</h4>
										<span>New Tasks!</span>
									</div>
									<i class="fas fa-fw fa-tasks fa-5x"></i>
								</div>
								<div class="card-footer">
									<a href="#" class="btn-block">
										Read More
										<i class="float-right mt-1 fa fa-fw fa-arrow-alt-circle-right"></i>
									</a>
								</div>
							</div>
							<!-- /.card -->
						</div>
						<div class="col-md-3">
							<div class="card card-count card-info">
								<div class="card-header">
									<div>
										<h4 class="h1 card-title">34</h4>
										<span>New User!</span>
									</div>
									<i class="fas fa-fw fa-users fa-5x"></i>
								</div>
								<div class="card-footer">
									<a href="#" class="btn-block">
										Read More
										<i class="float-right mt-1 fa fa-fw fa-arrow-alt-circle-right"></i>
									</a>
								</div>
							</div>
							<!-- /.card -->
						</div>
					</div>
					<!-- /.row -->
					<!-- Line Chart  -->
					<div class="card">
						<div class="card-header">
							<h4 class="card-title">Line Chart</h4>
						</div>
						<div class="card-body">
							<div class="canvas-wrapper">
								<canvas class="main-chart" id="line-chart" height="200" width="600"></canvas>
							</div>
							<script type="text/javascript">
								window.onload = function () {
									var chart1 = document.getElementById("line-chart").getContext("2d");
									window.myLine = new Chart(chart1).Line(lineChartData, {
										responsive: true,
										scaleLineColor: "rgba(0,0,0,.2)",
										scaleGridLineColor: "rgba(0,0,0,.05)",
										scaleFontColor: "#c5c7cc"
									});
								};
							</script>
						</div>
					</div>
					<!-- /Line Chart  -->
					<div class="row">
						<div class="col-sm-6">
							<div class="card">
								<div class="card-header">
									<h4 class="card-title">Unread Messages</h4>
								</div>
								<ul class="list-group list-group-flush">
									<li class="list-group-item">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user8.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body text-truncate">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0"><small class="text-success"><i class="fa fa-circle"></i></small> Carl Rios</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
											</div>
										</div>
									</li>
									<li class="list-group-item">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user3.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body text-truncate">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0"><small class="text-danger"><i class="fa fa-circle"></i></small> Katherine Holland</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
											</div>
										</div>
									</li>
									<li class="list-group-item">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user4.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body text-truncate">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0"><small class="text-success"><i class="fa fa-circle"></i></small> Karen Banks</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
											</div>
										</div>
									</li>
									<li class="list-group-item">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user5.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body text-truncate">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0"><small class="text-success"><i class="fa fa-circle"></i></small> Tammy Torres</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
											</div>
										</div>
									</li>
									<li class="list-group-item">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user6.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body text-truncate">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0"><small class="text-danger"><i class="fa fa-circle"></i></small> Austin Estradas</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
											</div>
										</div>
									</li>
									<li class="list-group-item">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user7.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body text-truncate">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0"><small class="text-success"><i class="fa fa-circle"></i></small> Victoria Lawrence</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
											</div>
										</div>
									</li>
								</ul>
								<div class="card-footer border-top-0">
									<div class="d-flex justify-content-between">
										<a href="#" class="btn btn-sm btn-outline-secondary">Read All</a>
										<a href="#" class="btn btn-sm btn-outline-secondary">Dismiss All</a>
									</div>
								</div>
							</div>
						</div>
						<div class="col-sm-6">
							<div class="card">
								<div class="card-header">
									<h4 class="card-title">Chat</h4>
								</div>
								<div class="card-body py-3" style="height: 300px; overflow: auto;">
									<div class="mb-3">
										<div class="media">
											<div class="media-body">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0">Keroro Gunsou</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												<div class="border rounded-bottom rounded-left px-2 py-1 mb-1">
													Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
												</div>
											</div>
											<img class="ml-2 rounded-circle" src="img/user3.PNG" width="40" alt="Generic placeholder image">
										</div>
									</div>
									<div class="mb-3">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user2.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0">Olivia Chavez</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												<div class="border rounded-bottom rounded-right px-2 py-1 mb-1">
													Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
												</div>
												<div class="btn-group btn-group-sm" role="group" aria-label="First group">
													<button type="button" class="btn btn-outline-secondary">
														<i class="fa fa-fw fa-paperclip"></i> asd.png
													</button>
													<button type="button" class="btn btn-outline-secondary"><i class="fa fa-fw fa-download"></i></button>
												</div>
												<div class="btn-group btn-group-sm" role="group" aria-label="First group">
													<button type="button" class="btn btn-outline-secondary">
														<i class="fa fa-fw fa-paperclip"></i> test-file.doc
													</button>
													<button type="button" class="btn btn-outline-secondary"><i class="fa fa-fw fa-download"></i></button>
												</div>
											</div>
										</div>
									</div>
									<div class="mb-3">
										<div class="media">
											<div class="media-body">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0">Keroro Gunsou</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												<div class="border rounded-bottom rounded-left px-2 py-1 mb-1">
													Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
												</div>
												<div class="border rounded-bottom rounded-left px-2 py-1 mb-1">
													Lorem ipsum dolor sit amet, consectetur adipisicing elit. Deserunt, temporibus.
												</div>
											</div>
											<img class="ml-2 rounded-circle" src="img/user3.PNG" width="40" alt="Generic placeholder image">
										</div>
									</div>
									<div class="mb-3">
										<div class="media">
											<img class="mr-2 rounded-circle" src="img/user2.PNG" width="40" alt="Generic placeholder image">
											<div class="media-body">
												<div class="d-flex justify-content-between align-items-center">
													<b class="mb-0">Olivia Chavez</b>
													<small class="text-secondary">8:03 PM Today</small>
												</div>
												<div class="border rounded-bottom rounded-right px-2 py-1 mb-1">
													Lorem ipsum dolor sit amet.
												</div>
											</div>
										</div>
									</div>
								</div>
								<div class="card-footer">
									<div class="media">
										<div class="media-body">
											<textarea name="name" class="form-control"  placeholder="Type here"></textarea>
											<div class="d-flex justify-content-between align-items-center mt-1">
												<div class="d-flex custom-input-file-icon">
													<div class="input">
														<input type="file" class="icon-file" id="upload" name="" value="" multiple="">
													</div>
												</div>
												<button type="button" class="btn btn-primary btn-sm">Send Message</button>
											</div>
										</div>
										<img class="ml-2 rounded-circle" src="img/user3.PNG" width="40" alt="Generic placeholder image">
									</div>
								</div>
							</div>
						</div>
						<div class="col-sm-6">
							<div class="card">
								<div class="card-header border-bottom-0">
									<h4 class="card-title">To-do List</h4>
								</div>
								<table class="table table-hover table-noborder">
									<tr>
										<td>
											<div class="custom-control custom-checkbox d-flex align-items-center">
												<input class="custom-control-input" id="customCheck1" type="checkbox">
												<label class="custom-control-label" for="customCheck1">Make coffee</label>
											</div>
										</td>
										<td width="5"><i class="fa fa-fw fa-trash-alt"></i></td>
									</tr>
									<tr>
										<td>
											<div class="custom-control custom-checkbox d-flex align-items-center">
												<input class="custom-control-input" id="customCheck2" type="checkbox">
												<label class="custom-control-label" for="customCheck2">Check emails</label>
											</div>
										</td>
										<td width="5"><i class="fa fa-fw fa-trash-alt"></i></td>
									</tr>
									<tr>
										<td>
											<div class="custom-control custom-checkbox d-flex align-items-center">
												<input class="custom-control-input" id="customCheck3" type="checkbox">
												<label class="custom-control-label" for="customCheck3">Reply to Jane</label>
											</div>
										</td>
										<td width="5"><i class="fa fa-fw fa-trash-alt"></i></td>
									</tr>
									<tr>
										<td>
											<div class="custom-control custom-checkbox d-flex align-items-center">
												<input class="custom-control-input" id="customCheck4" type="checkbox">
												<label class="custom-control-label" for="customCheck4">Make more coffee</label>
											</div>
										</td>
										<td width="5"><i class="fa fa-fw fa-trash-alt"></i></td>
									</tr>
									<tr>
										<td>
											<div class="custom-control custom-checkbox d-flex align-items-center">
												<input class="custom-control-input" id="customCheck5" type="checkbox">
												<label class="custom-control-label" for="customCheck5">Work on the new design</label>
											</div>
										</td>
										<td width="5"><i class="fa fa-fw fa-trash-alt"></i></td>
									</tr>
									<tr>
										<td>
											<div class="custom-control custom-checkbox d-flex align-items-center">
												<input class="custom-control-input" id="customCheck6" type="checkbox">
												<label class="custom-control-label" for="customCheck6">Get feedback on design</label>
											</div>
										</td>
										<td width="5"><i class="fa fa-fw fa-trash-alt"></i></td>
									</tr>
								</table>
								<div class="card-footer">
									<div class="input-group">
										<input type="text" class="form-control" placeholder="New Task">
										<div class="input-group-append">
											<button class="btn btn-primary" type="button">New Task</button>
										</div>
									</div>
								</div>
							</div>
						</div>
						<div class="col-sm-6">
							<div class="card">
								<div class="card-header">
									<h4 class="card-title">Timeline</h4>
								</div>
								<div class="card-body">
									<div class="timeline">
										<div class="timeline-date">
											<span>Start</span>
										</div>
										<div class="timeline-item">
											<div class="media">
												<div class="timeline-icon bg-primary text-white">
													<i class="fa fa-fw fa-bullhorn fa-2x"></i>
												</div>
												<div class="media-body">
													<div class="card timeline-card">
														<div class="card-body">
															Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
														</div>
													</div>
												</div>
											</div>
										</div>
										<div class="timeline-date">
											<span>February 18, 2018</span>
										</div>
										<div class="timeline-item">
											<div class="media">
												<div class="timeline-icon bg-danger text-white">
													<i class="fa fa-fw fa-pills fa-2x"></i>
												</div>
												<div class="media-body">
													<div class="card timeline-card">
														<div class="card-body">
															Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
														</div>
													</div>
												</div>
											</div>
										</div>
										<div class="timeline-item">
											<div class="media">
												<div class="timeline-icon bg-info text-white">
													<i class="fa fa-fw fa-link fa-2x"></i>
												</div>
												<div class="media-body">
													<div class="card timeline-card">
														<div class="card-body">
															Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.
														</div>
													</div>
												</div>
											</div>
										</div>
										<div class="timeline-date">
											<span>End</span>
										</div>
									</div>
								</div>
							</div>
						</div>
					</div>
					<!-- /.row -->
				</div>
			</div>
		</div>
		<div class="footer">
			<div class="max-xl-container">
				&copy; 2018 <a href="https://github.com/hayyi2/dashmaster" target="_blank">Dashmaster</a>
			</div>
		</div>
	</div>
</body>
</html>