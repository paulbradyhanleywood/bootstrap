---
layout: hw_layout
title: HW Multisite Components
description: HW Multisite Components
group: hw
---

<style>
.jumbotron {
	background: url( 'http://cdn.houseplans.com/product/83pciobqpkr9nvk6r2v9fofap5/w940x400.jpg' ) center center;
	background-size: cover;
}
</style>



<div class="container p-0 mt-4">

	<!-- Site Header -->
	<header>
		<!-- Call Text / Cart -->
		<div class="d-flex flex-row justify-content-center hidden-sm-up">
			<div class="mt-1 mr-3"><b>Call us at <a class="text-info" href="tel:877-803-2251">877-803-2251</a></b></div>
			<div class="mt-1 mr-3 float-right hidden-xs-down">Questions? <b>Call us at <a class="text-info" href="tel:877-803-2251">877-803-2251</a></b></div>
			<div><button class="btn btn-default btn-primary btn-sm float-right mr-2"><i class="fa fa-shopping-cart" aria-hidden="true"></i> Cart</button></div>
		</div>
		<div class="d-flex flex-row justify-content-end hidden-xs-down">
			<div class="mt-1 mr-3 float-right hidden-xs-down">Questions? <b>Call us at <a class="text-info" href="tel:877-803-2251">877-803-2251</a></b></div>
			<div><button class="btn btn-default btn-primary btn-sm float-right mr-2"><i class="fa fa-shopping-cart" aria-hidden="true"></i> Cart</button></div>
		</div>

		<nav class="navbar navbar-toggleable-md navbar-light">
			<button class="navbar-toggler navbar-toggler-right mt-2 px-2" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
				<span class="navbar-toggler-icon"></span>
			</button>
			<a class="navbar-brand" href="#"><img class="ml-2" src="http://placehold.it/220x50/c7b0c6/011a47?text=FLOORPLANS" alt="floorplans"></a>
			<div class="collapse navbar-collapse" id="navbarSupportedContent">
				<ul class="navbar-nav mr-auto">
					<li class="nav-item text-uppercase"><a class="text-info nav-link active" href="#">Search</a></li>
					<li class="nav-item text-uppercase"><a class="text-info nav-link" href="#">Styles</a></li>
					<li class="nav-item text-uppercase"><a class="text-info nav-link" href="#">Collections</a></li>
					<li class="nav-item text-uppercase"><a class="text-info nav-link" href="#">Designers</a></li>
					<li class="nav-item text-uppercase"><a class="text-info nav-link" href="#">Magazines</a></li>
				</ul>
			</div>
		</nav>
	</header>

	<!-- Hero with Search -->
	<div class="jumbotron rounded-0">
		<div class="text-center">
			<div class="row">
				<div class="col-sm-1"></div>
				<div class="col-sm-7 col-md-5 col-lg-4 mx-4 p-3 bg-faded">
					<h3>SEARCH FLOOR PLANS</h3>
					<h6 class="mt-2 mb-1">Bedrooms</h6>
					<div class="btn-group" data-toggle="buttons">
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bed_option1" checked> 1
						</label>
						<label class="btn btn-secondary active">
							<input type="radio" name="options" id="sfp_bed_option2"> 2
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bed_option3"> 3
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bed_option4"> 4
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bed_option5"> 5+
						</label>
					</div>

					<h6 class="mt-1 mb-1">Bathrooms</h6>
					<div class="btn-group" data-toggle="buttons">
						<label class="btn btn-secondary active">
							<input type="radio" name="options" id="sfp_bath_option1" checked> 1
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bath_option2"> 2
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bath_option3"> 3
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bath_option4"> 4
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_bath_option5"> 5+
						</label>
					</div>

					<h6 class="mt-1 mb-1">Floors</h6>
					<div class="btn-group" data-toggle="buttons">
						<label class="btn btn-secondary active">
							<input type="radio" name="options" id="sfp_flrs_option1" checked> 1
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_flrs_option2"> 2
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_flrs_option3"> 3
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_flrs_option4"> 4
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_flrs_option5"> 5+
						</label>
					</div>

					<h6 class="mt-1 mb-1">Garage Bays</h6>
					<div class="btn-group" data-toggle="buttons">
						<label class="btn btn-secondary active">
							<input type="radio" name="options" id="sfp_gar_option1" checked> 1
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_gar_option2"> 2
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_gar_option3"> 3
						</label>
						<label class="btn btn-secondary">
							<input type="radio" name="options" id="sfp_gar_option4"> 4+
						</label>
					</div><br>
					<div class="mx-5"><button type="button" class="btn btn-primary btn-block text-uppercase">Search Plans</button></div>
				</div>
			</div><!-- ./row -->
		</div>
	</div><!-- ./jumbotron -->

	<!-- Featured Styles & Designs -->
	<section>
		<h2 class="h4 text-uppercase text-center mt-5"><span>Featured Styles &amp; Designs</span></h2>
		<hr class="mx-auto mt-0 pt-0">
		<div class="row">
			<div class="col-sm-4 p-0">
				<div class="card">
					<img src="http://cdn.houseplans.com/product/o2d2ui14afb1sov3cnslpummre/w940x400.jpg" class="img-fluid" alt="Responsive image">
					<div class="card-block">
						<h6 class="card-title text-center text-primary"><a href="#"><strong>3 BEDROOM FLOOR PLANS</strong></a></h6>
						<p class="card-text"><em>3-bedroom floor plans are very popular and it's easy to see why.  The versatility of having 3 bedrooms makes this a...</em></p>
					</div>
				</div>
			</div>
			<div class="col-sm-4 p-0">
				<div class="card">
					<img src="http://cdn.houseplans.com/product/2f50bfq27ig6qogbkms91mud82/w940x400.jpg" class="img-fluid" alt="Responsive image">
					<div class="card-block">
						<h6 class="card-title text-center text-primary"><a href="#"><strong>TWO STORY FLOOR PLANS</strong></a></h6>
						<p class="card-text"><em>The majority of plans build today have two stories, as this provides a traditional layout and separation of public &amp; private...</em></p>
					</div>
				</div>
			</div>
			<div class="col-sm-4 p-0">
				<div class="card">
					<img src="http://cdn.houseplans.com/product/4f7c9q2ei6r5ldvhbmonpthvep/w940x400.jpg" class="img-fluid" alt="Responsive image">
					<div class="card-block">
						<h6 class="card-title text-center text-primary"><a href="#"><strong>A-FRAME FLOOR PLANS</strong></a></h6>
						<p class="card-text"><em>A-Frame homes are a contemporary, folk style of home reminiscent of a Swiss chalet, perfect in a mountain setting...</em></p>
					</div>
				</div>
			</div>
		</div>
	</section>



	<!-- Exclusive Feature -->
	<section class="mt-5 mb-5">
		<div class="row no-gutters">
			<div class="col-lg-8">

				<!-- Desktop -->
				<div class="hidden-sm-down">
					<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
						<ol class="carousel-indicators">
							<li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
							<li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
							<li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
						</ol>
						<div class="carousel-inner" role="listbox">
							<div class="carousel-item active">
								<img class="d-block img-fluid" src="http://cdn.houseplans.com/product/o2d2ui14afb1sov3cnslpummre/w940x400.jpg" alt="First slide">
							</div>
							<div class="carousel-item">
								<img class="d-block img-fluid" src="http://cdn.houseplans.com/product/2f50bfq27ig6qogbkms91mud82/w940x400.jpg" alt="Second slide">
							</div>
							<div class="carousel-item">
								<img class="d-block img-fluid" src="http://cdn.houseplans.com/product/4f7c9q2ei6r5ldvhbmonpthvep/w940x400.jpg" alt="Third slide">
							</div>
						</div>
						<a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
							<span class="carousel-control-prev-icon" aria-hidden="true"></span>
							<span class="sr-only">Previous</span>
						</a>
						<a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
							<span class="carousel-control-next-icon" aria-hidden="true"></span>
							<span class="sr-only">Next</span>
						</a>
					</div>
				</div>


				<!-- Mobile -->
				<div class="hidden-md-up">
					<img class="img-fluid" src="http://cdn.houseplans.com/product/o2d2ui14afb1sov3cnslpummre/w940x400.jpg" alt="First slide">
				</div>

			</div>
			<div class="col-lg-4 px-4 d-flex flex-column align-items-stretch justify-content-end" style="border-top: 1px solid lightgray; border-bottom: 1px solid lightgray;">
				<div><h2 class="h6 mt-3">Exclusive Feature</h2></div>
				<div><h3 class="my-3">THE MODERN CABIN COLLECTION</h3></div>
				<div class="align-items-stretch">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
					quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
					consequat. Duis aute irure dolor in reprehenderit.
				</div>
				<div class="mt-auto pt-2 pb-4">
					<button type="button" class="btn btn-primary btn-block py-2 text-uppercase">View Collection</button>
				</div>
			</div><!-- ./col -->

		</div><!-- ./row -->
	</section>


	<!-- Featured Designer -->
	<section class="mt-5">
		<div class="d-md-flex flex-row justify-content-around">
			<div>
				<img src="http://cdn.houseplans.com/product/2f50bfq27ig6qogbkms91mud82/w940x400.jpg" class="img-fluid" alt="Responsive image">
			</div>
			<div class="border text-center px-3"  style="border: 1px solid lightgray;"><!-- BS4 .border class missing -->

				<div class="d-flex flex-column justify-content-end"  style="height: 100%"><!-- to use actual bottom edge -->
					<div><h2 class="h6 mt-3">Featured Designer</h2></div>
					<div><h3 class="text-uppercase">David Wiggins</h3></div>
					<div class="align-items-stretch">Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
					tempor incididunt ut labore et dolore.</div>
					<div class="mt-auto pt-2 pb-4"><button class="btn btn-primary btn-block text-uppercase">See All Plans</button></div>
				</div>

			</div>
			<div class="hidden-md-down">
				<img src="http://cdn.houseplans.com/product/4f7c9q2ei6r5ldvhbmonpthvep/w940x400.jpg" class="img-fluid" alt="Responsive image">
			</div>
		</div>
	</section>



	<!-- More Floorplans Designers -->
	<section id="more-floorplan-designers" class="mt-5">
		<h2 class="h4 text-uppercase text-center"><span>More Floorplan Designers</span></h2>
		<hr class="mx-auto mt-0 pt-0">

		<!-- Desktop version -->
		<div class="hidden-sm-down">
			<div class="row text">
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">Visbeen Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
			</div>
			<div class="row">
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">Visbeen Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
			</div>
			<div class="row">
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">Visbeen Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
			</div>
			<div class="row">
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">Visbeen Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
			</div>
			<div class="row">
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">Visbeen Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
			</div>
		</div>

		<!-- Mobile version -->
		<div class="hidden-md-up">

			<div class="row mx-auto">
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">Visbeen Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
				<div class="col-md mt-2">

					<div class="media">
						<img class="d-flex mr-3" src="http://placehold.it/150x100/66ff66/ffffff" alt="Generic placeholder image">
						<div class="media-body text-info align-self-center">
							<a href="#" class="text-info"><h3 class="h5 text-uppercase">David Gardner Architects</h3></a>
							Classic, large houses with curb appeal
						</div>
					</div>

				</div>
			</div>

		</div><!-- ./ (mobile) hidden-md-up -->

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
		<div class="d-flex flex-column flex-md-row justify-content-start justify-content-md-around p-2 bg-success text-white">
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


