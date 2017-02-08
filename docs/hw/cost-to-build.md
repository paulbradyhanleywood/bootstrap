---
layout: hw_layout
title: HW Multisite Components
description: HW Multisite Components
group: hw
---


<div class="container p-0 mt-4">

	<!-- Site Header -->
	<header>
		<div class="d-flex flex-row justify-content-center hidden-sm-up">
			<div class="mt-1 mr-3"><b>Call us at <a class="text-info" href="tel:877-803-2251">877-803-2251</a></b></div>
			<div class="mt-1 mr-3 float-right hidden-xs-down">Questions? <b>Call us at <a class="text-info" href="tel:877-803-2251">877-803-2251</a></b></div>
			<div><button class="btn btn-primary btn-sm float-right mr-2"><i class="fa fa-shopping-cart" aria-hidden="true"></i> Cart</button></div>
		</div>
		<div class="d-flex flex-row justify-content-end hidden-xs-down">
			<div class="mt-1 mr-3 float-right hidden-xs-down">Questions? <b>Call us at <a class="text-info" href="tel:877-803-2251">877-803-2251</a></b></div>
			<div><button class="btn btn-primary btn-sm float-right mr-2"><i class="fa fa-shopping-cart" aria-hidden="true"></i> Cart</button></div>
		</div>

		<nav class="navbar navbar-toggleable-md navbar-light">
			<button class="navbar-toggler navbar-toggler-right mt-2 px-2" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<a class="navbar-brand" href="/hw/"><img class="ml-2" src="http://placehold.it/220x50/c7b0c6/011a47?text=FLOORPLANS" alt="floorplans"></a>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav ml-auto text-right">
					<li class="nav-item text-uppercase"><h2 class="mb-0"><a class="h5 text-info mb-0 nav-link active" href="#">Search</a></h2></li>
					<li class="nav-item text-uppercase"><h2 class="mb-0"><a class="h5 text-info mb-0 nav-link" href="#">Styles</a></h2></li>
					<li class="nav-item text-uppercase"><h2 class="mb-0"><a class="h5 text-info mb-0 nav-link" href="/hw/collections/">Collections</a></h2></li>
					<li class="nav-item text-uppercase"><h2 class="mb-0"><a class="h5 text-info mb-0 nav-link" href="/hw/designers/">Designers</a></h2></li>
					<li class="nav-item text-uppercase"><h2 class="mb-0"><a class="h5 text-info mb-0 nav-link" href="/hw/magazines/">Magazines</a></h2></li>
				</ul>
			</div>
		</nav>
	</header>


	<!-- Cost-to-build content -->
	<section class="mt-5">
		<h1 class="display-2 mb-2 strong">Find out how much this house will cost to build</h1>
		<h2 class="display-2 mb-2"><small><i>Our report will estimate your costs based on your location &amp; materials</i></small></h2>
	</section>
	<section class="mt-4">
		<div class="row">
			<div class="col-lg-4 col-xs-12">
				<div class="form-group p-4" style="border: 1px solid #f87100"><!-- custom.scss orange -->

					<form class="p-3" action="https://secure.houseplans.com/cart/add_cost_to_build" method="post">
						<input type="hidden" name="planId" value="">
						<label for="postal-code" class="w-100 text-center">
							<h3 class="h6 text-center mb-0"><strong>Postal Code of building location</strong></h3>
							<i>US &amp; Canada only</i>
						</label>
						<input class="form-control" name="postalCode" id="postal-code" size="10" type="text" required="">
						<label for="quality" class="w-100 text-center mt-3">
							<h3 class="h6 text-center mb-0">
								<strong>Desired Build Quality</strong>
							</h3>
						</label>
						<select class="form-control" name="quality" id="quality">
								<option value="ECONOMY">Economy</option>
								<option value="STANDARD">Standard</option>
								<option value="ABOVE_AVERAGE">Above Average</option>
								<option value="PREMIUM">Premium *</option>
						</select>
						<label for="foundation" class="w-100 text-center mt-3">
							<h3 class="h6 text-center mb-0">
								<strong>Foundation Type</strong>
							</h3>
						</label>
						<select class="form-control" name="foundation" id="foundation">
								<option value="BASEMENT">Basement</option>
								<option value="CONCRETE_SLAB">Concrete Slab</option>
								<option value="CRAWLSPACE">Crawlspace</option>
								<option value="PIER">Pier</option>
						</select>
						<button type="submit" class="btn btn-warning btn-lg w-100 text-center mt-4 mb-3">Add Report to Cart</button>
						<div class="w-100 text-center">or give us a call at <a href="tel:1-800-913-2350">1-800-913-2350</a></div>
					</form>

				</div>
			</div>
			<div class="col-lg-8 col-xs-12">

				<div class="media bg-faded p-3">
					<img class="d-flex mr-3" src="https://cdn.houseplans.com/product/ltvvl35n6glj7mrrb9i3j18he0/w180x120.jpg?v=4" width="180" height="120" alt="Craftsman Exterior - Front Elevation Plan #895-25 - Houseplans.com">
					<div class="media-body">
						<h5 class="mt-0">Cost-to-Build Report - <i>$49.99</i></h5>
						<b>Plan #999-99</b>
						<ul class="list-inline clearfix m-0 text-muted">
								<li class="list-inline-item mr-0">2 Bedroom,&nbsp;</li>
								<li class="list-inline-item mr-0">2 Bathroom</li>
						</ul>
						<ul class="list-inline clearfix m-0 text-muted">
								<li class="list-inline-item mr-0">1 Garage,&nbsp;</li>
								<li class="list-inline-item mr-0">999 sq ft,&nbsp;</li>
								<li class="list-inline-item mr-0">1 story</li>								
						</ul>
					</div>
				</div>
				<div class="h6 mt-3 p-1">
					Our Cost-to-Build report is a helpful tool when budgeting for your new home. We will calculate basic build costs for your plan, based on the materials shown in the design and current pricing in your area of the U.S. or Canada. Your Cost-to-Build reports are typically completed within 1 business day and will be sent to the email on your order.
				</div>
				<div class="h6 mt-3 p-1">
					<a class="float-right text-center" href="#" target="_blank">
						<img src="http://www.placehold.it/140x200/ff0000/ff00ff?text=View+Sample" class="rounded mx-3" alt="Sample Report">
						<div class="figure-img text-center mt-3 strong">View Sample</div>
					</a>
					<p class="text-muted">
						<i>
							Houseplans.com Cost-to-Build reports are prepared by our experienced plan experts using up-to-date data supplied by Xactware, Inc. Each plan takes up to an hour to prepare. When you receive your estimate, we can work with you to adjust material and quality variables to make your estimate as accurate as possible.
						</i>
						<div><a href="/cost-to-build-faq">See Frequently Asked Questions</a></div>
					</p>
				</div>

			</div>

		</div>

	</section>



	<!-- Footer -->
	<footer class="footer mt-5">
		<div class="d-flex flex-row justify-content-center bg-faded">
			<div class="p-5">
				<h2 class="h4 text-info text-center">Quality home design at a&nbsp;fraction&nbsp;of&nbsp;the&nbsp;cost.</h2>
			</div>
		</div>
		<div class="d-flex flex-column flex-md-row justify-content-around bg-faded text-white">
			<div class="px-5 pb-5 text-info text-center">
				<img src="http://placehold.it/67x67/3300ff/ffffff" alt="Home"><br>
				<h3 class="h5 my-3">Lorem ipsum dolor sit</h3>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod!</p>
			</div>
			<div class="px-5 pb-5 text-info text-center">
				<img src="http://placehold.it/67x67/3300ff/ffffff" alt="Home"><br>
				<h3 class="h5 my-3">Lorem ipsum dolor sit amet</h3>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing!</p>
			</div>
			<div class="px-5 pb-5 text-info text-center">
				<img src="http://placehold.it/67x67/3300ff/ffffff" alt="Home"><br>
				<h3 class="h5 my-3">Lorem ipsum dolor sit</h3>
				<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
				tempor incididunt!</p>
			</div>
		</div>
		<div class="d-flex flex-column flex-md-row justify-content-center justify-content-md-around px-5 py-4 bg-primary text-white">

			<div class="p-3">
				<h6 class="lead mb-4">STYLES</h6>
				<ul class="list-unstyled">
					<li><a class="text-white" href="#">Contemporary/Modern Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Traditional Floor Plans</a></li>
				</ul>
			</div>

			<div class="p-3">
				<h6 class="lead mb-4">SPECIAL COLLECTIONS</h6>
				<ul class="list-unstyled">
					<li><a class="text-white" href="#">Contemporary/Modern Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Mediterranean Floor Plans</a></li>
				</ul>
			</div>

			<div class="p-3">
				<h6 class="lead mb-4">FEATURED DESIGNERS</h6>
				<ul class="list-unstyled">
					<li><a class="text-white" href="#">Contemporary/Modern Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Colonial Floor Plans</a></li>
					<li><a class="text-white" href="#">Traditional Floor Plans</a></li>
				</ul>
			</div>

		</div>
		<div class="d-flex flex-column flex-md-row justify-content-start justify-content-md-around p-2 bg-danger text-white">
			<div class="d-flex flex-column flex-md-row justify-content-start align-items-left pl-5 pt-3">

				<div class="p-1 pt-2"><a class="text-white" href="#">PLANS</a></div>
				<div class="p-1 pt-2"><a class="text-white" href="#">COLLECTIONS</a></div>
				<div class="p-1 pt-2"><a class="text-white" href="#">ABOUT</a></div>
				<div class="p-1 pt-2"><a class="text-white" href="#">CART</a></div>
				<div class="p-1 pt-2"><a class="text-white" href="#">FAQ</a></div>
				<div class="p-1 pt-2"><a class="text-white" href="#">CONTACT</a></div>

			</div>
			<div class="px-5 py-3">

				<ul class="list-unstyled flex-nowrap list-inline mb-0">
					<li class="list-inline-item"><a href="#"><img src="http://placehold.it/35x35/ff0000/ffffff" alt=""></a></li>
					<li class="list-inline-item"><a href="#"><img src="http://placehold.it/35x35/ffff00/ffffff" alt=""></a></li>
					<li class="list-inline-item"><a href="#"><img src="http://placehold.it/35x35/ff00ff/ffffff" alt=""></a></li>
					<li class="list-inline-item"><a href="#"><img src="http://placehold.it/35x35/00ffff/ffffff" alt=""></a></li>
				</ul>

			</div>
		</div>
		<div class="d-flex flex-wrap justify-content-around bg-info text-white py-4">

			<div class="p-1"><a href="#"><img src="http://placehold.it/120x40/ffffff/000000?text=ARCHITECT" alt="ARCHITECT"></a></div>
			<div class="p-1"><a href="#"><img src="http://placehold.it/120x40/ffffff/000000?text=Residential+Architect" alt="Residential Architect"></a></div>
			<div class="p-1"><a href="#"><img src="http://placehold.it/120x40/ffffff/000000?text=Builder" alt="Builder"></a></div>
			<div class="p-1"><a href="#"><img src="http://placehold.it/120x40/ffffff/000000?text=Custom+Home" alt="Custom Home"></a></div>

		</div>
		<div class="d-flex flex-column flex-md-row justify-content-center px-5 pb-5 bg-info text-white">
			<div class="d-inline-flex justify-content-center align-items-center pr-md-5">

				<a href="#"><img src="http://placehold.it/150x40/ff0033/000000?text=Hanley+Wood" alt="Hanley Wood"></a>

			</div>
			<div class="d-inline-flex justify-content-center align-items-center py-3">

				<div class="pr-md-5"><a class="text-white" href="#">Copyright 2017, HanleyWood LLC.</a> All&nbsp;Rights&nbsp;Reserved.</div>

			</div>
			<div class="d-inline-flex justify-content-center align-items-center py-3">
				
				<div class="flex-nowrap"><a class="text-white" href="#">Privacy Policy</a>&nbsp;&nbsp;&nbsp; <a class="text-white" href="#">Terms&nbsp;&amp;&nbsp;Conditions</a></div>

			</div>
		</div>

	</footer>

</div><!-- ./container -->


{{ callout-include | markdownify }}


<link href="https://maxcdn.bootstrapcdn.com/font-awesome/4.7.0/css/font-awesome.min.css" rel="stylesheet" integrity="sha384-wvfXpqpZZVQGK6TAh5PVlGOfQNHSoD2xbE+QkPxCAFlNEevoEH3Sl0sibVcOQVnN" crossorigin="anonymous">


