# olowotrade

This app will allow you to trade whatever you have 
<!DOCTYPE html>
<html lang="en">
    <head>
        <!-- Title -->
        <title>OlowoTrade</title>

        <!-- Required Meta Tags Always Come First -->
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">

    <!-- C U S T O M -->
    <link rel="stylesheet" type="text/css" href="assets/css/custom.css">
    <link rel="stylesheet" href="assets/owlcarousel/assets/owl.carousel.min.css">
    <link rel="stylesheet" href="assets/owlcarousel/assets/owl.theme.default.min.css">
        <!-- Favicon -->
        <link rel="shortcut icon" href="favicon.png">

        <!-- Google Fonts -->
        <link href="https://fonts.googleapis.com/css?family=Open+Sans:300,300i,400,400i,600,600i,700,700i,800,800i&display=swap" rel="stylesheet">

        <!-- CSS Implementing Plugins -->
        <link rel="stylesheet" href="assets/vendor/font-awesome/css/fontawesome-all.min.css">
        <link rel="stylesheet" href="assets/css/font-electro.css">
        
        <link rel="stylesheet" href="assets/vendor/animate.css/animate.min.css">
        <link rel="stylesheet" href="assets/vendor/hs-megamenu/src/hs.megamenu.css">
        <link rel="stylesheet" href="assets/vendor/ion-rangeslider/css/ion.rangeSlider.css">
        <link rel="stylesheet" href="assets/vendor/malihu-custom-scrollbar-plugin/jquery.mCustomScrollbar.css">
        <link rel="stylesheet" href="assets/vendor/fancybox/jquery.fancybox.css">
        <link rel="stylesheet" href="assets/vendor/slick-carousel/slick/slick.css">
        <link rel="stylesheet" href="assets/vendor/bootstrap-select/dist/css/bootstrap-select.min.css">

        <!-- CSS Electro Template -->
        <link rel="stylesheet" href="assets/css/theme.css">
    </head>

    <body>

  <header class="main-header">
        <div class="container">
    
            <div class="home-logo">
                <a href="home">OLOWOTRADE LOGO</a>
            </div>
    
            <div class="gift-search">     
                <!-- Login and Get started area -->
                <form method="post" action="/giftsearch">
                    <input type="hidden" name="_token" v-model="$attrs.csrf">   
                    <input type="text" placeholder="Search for items" name="search"><button><i class="fas fa-search"></i></button>
                </form>
                
            <div class="login">
                <div class="login-a">
                    <a id="sidebarNavToggler" href="javascript:;" role="button" class="u-header-topbar__nav-link"
                                            aria-controls="sidebarContent"
                                            aria-haspopup="true"
                                            aria-expanded="false"
                                            data-unfold-event="click"
                                            data-unfold-hide-on-scroll="false"
                                            data-unfold-target="#sidebarContent"
                                            data-unfold-type="css-animation"
                                            data-unfold-animation-in="fadeInRight"
                                            data-unfold-animation-out="fadeOutRight"
                                            data-unfold-duration="500">Signin</a>
                    <a>|</a>
                    <a  id="sidebarNavToggler" href="javascript:;" role="button" class="u-header-topbar__nav-link"
                                            aria-controls="sidebarContent"
                                            aria-haspopup="true"
                                            aria-expanded="false"
                                            data-unfold-event="click"
                                            data-unfold-hide-on-scroll="false"
                                            data-unfold-target="#sidebarContent"
                                            data-unfold-type="css-animation"
                                            data-unfold-animation-in="fadeInRight"
                                            data-unfold-animation-out="fadeOutRight"
                                            data-unfold-duration="500">Register</a>
                    <a  id="sidebarNavToggler" href="javascript:;" role="button"
                                            aria-controls="sidebarContent"
                                            aria-haspopup="true"
                                            aria-expanded="false"
                                            data-unfold-event="click"
                                            data-unfold-hide-on-scroll="false"
                                            data-unfold-target="#sidebarContent"
                                            data-unfold-type="css-animation"
                                            data-unfold-animation-in="fadeInRight"
                                            data-unfold-animation-out="fadeOutRight"
                                            data-unfold-duration="500"class="sell-btn">Start Selling</a>
                </div>
            </div>
            </div>
            
        </div>
        
    </header><!-- ========== MAIN CONTENT ========== -->
<main id="content" role="main" class="main-slider">
    <!-- Slider Section -->
    <div class="mb-4">
        <div class="bg-img-hero" style="background-image: url(img/slide1.jpg);">
            <div class="container overflow-hidden">
                <div class="js-slick-carousel u-slick home-slide"
                data-pagi-classes="text-center position-absolute right-0 bottom-0 left-0 u-slick__pagination u-slick__pagination--long justify-content-center mb-3 mb-md-4">
                <div class="js-slide">
                    <div class="slide-text">
                        <h1 class="font-size-46 text-lh-50 font-weight-light"
                        data-scs-animation-in="fadeInUp"
                        data-scs-animation-delay="200"><stong class="font-weight-bold">Flash Sale</stong>
                    </h1>
                    <h2 class="font-weight-bold">Small appliances, massive savings.</h2>
                    <a href="register" class="btn btn-primary transition-3d-hover rounded-lg font-weight-normal py-2 px-md-7 px-3 font-size-16"
                    data-scs-animation-in="fadeInUp"
                    data-scs-animation-delay="300">
                    Start selling
                </a>
            </div>
        </div> <div class="js-slide">
            <div class="slide-text">
                <h1 class="font-size-46 text-lh-50 font-weight-light"
                data-scs-animation-in="fadeInUp"
                data-scs-animation-delay="200"><stong class="font-weight-bold">Flash Sale</stong>
            </h1>
            <h2 class="font-weight-bold">Small appliances, massive savings.</h2>
            <a href="register" class="btn btn-primary transition-3d-hover rounded-lg font-weight-normal py-2 px-md-7 px-3 font-size-16"
            data-scs-animation-in="fadeInUp"
            data-scs-animation-delay="300">
            Start selling
        </a>
    </div>
</div>
<div class="js-slide">
    <div class="slide-text">
        <h1 class="font-size-46 text-lh-50 font-weight-light"
        data-scs-animation-in="fadeInUp"
        data-scs-animation-delay="200"><stong class="font-weight-bold">Flash Sale</stong>
    </h1>
    <h2 class="font-weight-bold">Small appliances, massive savings.</h2>
    <a href="register" class="btn btn-primary transition-3d-hover rounded-lg font-weight-normal py-2 px-md-7 px-3 font-size-16"
    data-scs-animation-in="fadeInUp"
    data-scs-animation-delay="300">
    Start selling
</a>
</div>
</div>
</div>
</div>
</div>
</div>
</div>

            <div class="container">
                <div class="row">
                    <div class="d-xl-block col-xl-3 col-wd-2gdot5">
                        <div class="mb-6 border border-width-2 border-color-3 borders-radius-6">
                            <!-- List -->
                            <ul id="sidebarNav" class="list-unstyled mb-0 sidebar-navbar view-all">
                                <li><div class="dropdown-title">Browse Categories</div></li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav1Collapse" data-target="#sidebarNav1Collapse">
                                        Accessories<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav1Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav1" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Accessories<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Cameras & Photography<span class="text-gray-25 font-size-12 font-weight-normal"> (11)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Computer Components<span class="text-gray-25 font-size-12 font-weight-normal"> (22)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Gadgets<span class="text-gray-25 font-size-12 font-weight-normal"> (5)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Home Entertainment<span class="text-gray-25 font-size-12 font-weight-normal"> (7)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Laptops & Computers<span class="text-gray-25 font-size-12 font-weight-normal"> (42)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Printers & Ink<span class="text-gray-25 font-size-12 font-weight-normal"> (63)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Smart Phones & Tablets<span class="text-gray-25 font-size-12 font-weight-normal"> (11)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">TV & Audio<span class="text-gray-25 font-size-12 font-weight-normal"> (66)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Video Games & Consoles<span class="text-gray-25 font-size-12 font-weight-normal"> (31)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav2Collapse" data-target="#sidebarNav2Collapse">
                                        Cameras & Photography<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav2Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav2" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Cameras<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav3Collapse" data-target="#sidebarNav3Collapse">
                                        Computer Components<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav3Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav3" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Computer Cases<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav4Collapse" data-target="#sidebarNav4Collapse">
                                        Gadgets<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav4Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav4" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Smartwatches<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Wearables<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav5Collapse" data-target="#sidebarNav5Collapse">
                                        Home Entertainment<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav5Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav5" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Tvs<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav6Collapse" data-target="#sidebarNav6Collapse">
                                        Laptops & Computers<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav6Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav6" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Accessories<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Cameras & Photography<span class="text-gray-25 font-size-12 font-weight-normal"> (11)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Computer Components<span class="text-gray-25 font-size-12 font-weight-normal"> (22)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Gadgets<span class="text-gray-25 font-size-12 font-weight-normal"> (5)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Home Entertainment<span class="text-gray-25 font-size-12 font-weight-normal"> (7)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Laptops & Computers<span class="text-gray-25 font-size-12 font-weight-normal"> (42)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Printers & Ink<span class="text-gray-25 font-size-12 font-weight-normal"> (63)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Smart Phones & Tablets<span class="text-gray-25 font-size-12 font-weight-normal"> (11)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">TV & Audio<span class="text-gray-25 font-size-12 font-weight-normal"> (66)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Video Games & Consoles<span class="text-gray-25 font-size-12 font-weight-normal"> (31)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav7Collapse" data-target="#sidebarNav7Collapse">
                                        Printers & Ink<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav7Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav7" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Printers<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav8Collapse" data-target="#sidebarNav8Collapse">
                                        Smart Phones & Tablets<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav8Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav8" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Smartphones<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <li><a class="dropdown-item" href="category-single">Tablets<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav9Collapse" data-target="#sidebarNav9Collapse">
                                        TV & Audio<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav9Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav9" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Audio Speakers<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                                <li>
                                    <a class="dropdown-toggle dropdown-toggle-collapse" href="javascript:;" role="button" data-toggle="collapse" aria-expanded="false" aria-controls="sidebarNav10Collapse" data-target="#sidebarNav10Collapse">
                                        Video Games & Consoles<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span>
                                    </a>

                                    <div id="sidebarNav10Collapse" class="collapse" data-parent="#sidebarNav">
                                        <ul id="sidebarNav10" class="list-unstyled dropdown-list">
                                            <!-- Menu List -->
                                            <li><a class="dropdown-item" href="category-single">Game Consoles<span class="text-gray-25 font-size-12 font-weight-normal"> (56)</span></a></li>
                                            <!-- End Menu List -->
                                        </ul>
                                    </div>
                                </li>
                            </ul>
                            <!-- End List -->
                        </div>
                    </div>
                    <div class="col-xl-9 col-wd-9gdot5">
                        <!-- Recommended Products -->
                        <div class="mb-6 d-xl-block">
                            <div class="position-relative">
                                <div class="border-bottom border-color-1 mb-2">
                                    <h3 class="d-inline-block section-title section-title__full mb-0 pb-2 font-size-22">Recommended Products</h3>
                                </div>
                                <div class="js-slick-carousel u-slick position-static overflow-hidden u-slick-overflow-visble pb-7 pt-2 px-1"
                                    data-pagi-classes="text-center right-0 bottom-1 left-0 u-slick__pagination u-slick__pagination--long mb-0 z-index-n1 mt-3 mt-md-0"
                                    data-slides-show="5"
                                    data-slides-scroll="1"
                                    data-arrows-classes="position-absolute top-0 font-size-17 u-slick__arrow-normal top-10"
                                    data-arrow-left-classes="fa fa-angle-left right-1"
                                    data-arrow-right-classes="fa fa-angle-right right-0"
                                    data-responsive='[{
                                      "breakpoint": 1400,
                                      "settings": {
                                        "slidesToShow": 4
                                      }
                                    }, {
                                        "breakpoint": 1200,
                                        "settings": {
                                          "slidesToShow": 4
                                        }
                                    }, {
                                      "breakpoint": 992,
                                      "settings": {
                                        "slidesToShow": 3
                                      }
                                    }, {
                                      "breakpoint": 768,
                                      "settings": {
                                        "slidesToShow": 2
                                      }
                                    }, {
                                      "breakpoint": 554,
                                      "settings": {
                                        "slidesToShow": 2
                                      }
                                    }]'>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img1.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img2.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img3.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img4.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img5.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img6.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img7.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img1.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="js-slide products-group">
                                        <div class="product-item">
                                            <div class="product-item__outer h-100">
                                                <div class="product-item__inner px-wd-4 p-2 p-md-3">
                                                    <div class="product-item__body pb-xl-2">
                                                        <div class="mb-2"><a href="category-single" class="font-size-12 text-gray-5">Speakers</a></div>
                                                        <h5 class="mb-1 product-item__title"><a href="single" class="text-blue font-weight-bold">Wireless Audio System Multiroom 360 degree Full base audio</a></h5>
                                                        <div class="mb-2">
                                                            <a href="single" class="d-block text-center"><img class="img-fluid" src="assets/img/212X200/img1.jpg" alt="Image Description"></a>
                                                        </div>
                                                        <div class="flex-center-between mb-1">
                                                            <div class="prodcut-price">
                                                                <div class="text-gray-100">₦685,00</div>
                                                            </div>
                                                            
                                                        </div>
                                                    </div>
                                                    <div class="product-item__footer">
                                                        <div class="border-top pt-2 flex-center-between flex-wrap">
                                                            <a href="single" class="text-gray-6 font-size-13"><i class="ec ec-favorites mr-1 font-size-15"></i> Wishlist</a>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <!-- End Recommended Products -->
                    </div>
                </div>
            </div>

<div class="container">
    <div class="sample-break">
        <img src="img/3693601180325606789.jpg" class="web-show"/>
        <img src="img/16660324573901197749.jpg" class="mobile-show"/>
    </div>
</div>

<div class="products-grid"> 
    <div class="wrap">
        <h1>Top Ads</h1>
        <div class="owl-carousel owl-theme" id="prodCarousel">
          <div class="item">     
            <a href="single">
            <div class="product">
            <div class="img-hold">
              <img src="img/product-1.jpg"/>

</div>              <p>Google pixels 4a 128GB - just Black unlocked</p>
            <h3>₦2999.99</h3>

        </div>
    </a>
    </div>
    <div class="item">    
        <a href="single">
        <div class="product">
        <div class="img-hold">
          <img src="img/product-2.jpg" />
      </div>
          <p>Google pixels 4a 128GB - just Black unlocked</p>
        <h3>₦2999.99</h3>

    </div>
</a>
</div>
<div class="item">    
    <a href="single">
    <div class="product">
    <div class="img-hold">
      <img src="img/product-3.jpg" />
  </div>
      <p>Google pixels 4a 128GB - just Black unlocked</p>
    <h3>₦2999.99</h3>

</div>
</a>
</div>
<div class="item">    
    <a href="single">
    <div class="product">
    <div class="img-hold">
      <img src="img/product-4.jpg" />
  </div>
      <p>Google pixels 4a 128GB - just Black unlocked</p>
    <h3>₦2999.99</h3>

</div>
</a>
</div>
<div class="item">    
    <a href="single">
    <div class="product">
    <div class="img-hold">
      <img src="img/product-5.jpg" />
  </div>
      <p>Google pixels 4a 128GB - just Black unlocked</p>
    <h3>₦2999.99</h3>

</div>
</a>
</div>

<div class="item">    
    <a href="single">
    <div class="product">
    <div class="img-hold">
      <img src="img/product-2.jpg" />
  </div>
      <p>Google pixels 4a 128GB - just Black unlocked</p>
    <h3>₦2999.99</h3>

</div>
</a>
</div>

<div class="item">    
    <a href="single">
    <div class="product">
    <div class="img-hold">
      <img src="img/product-2.jpg" />
  </div>
      <p>Google pixels 4a 128GB - just Black unlocked</p>
    <h3>₦2999.99</h3>

</div>
</a>
</div>
</div>

<a><button class="p-btn">Explore Latest and Greatest Tech</button></a>
</div>
</div>

</div>
</div>
<!-- ========== FOOTER ========== -->
<footer>
    <!-- Footer-bottom-widgets -->
    <div class="pt-8 pb-4 bg-gray-13">
        <div class="container mt-1">
            <div class="row">
                <div class="col-lg-5">
                    <div class="mb">
                        <a href="#" class="d-inline-block">
                            OLOWOTRADE LOGO
                        </a>
                </div>
                <div class="mb-4">
                    <div class="row no-gutters">
                        <div class="col-auto">
                            <i class="ec ec-support text-primary font-size-56"></i>
                        </div>
                        <div class="col pl-3">
                            <div class="font-size-13 font-weight-light">Got questions? Call us 24/7!</div>
                            <a href="tel:+80080018588" class="font-size-20 text-gray-90">(800) 8001-8588, </a><a href="tel:+0600874548" class="font-size-20 text-gray-90">(0600) 874 548</a>
                        </div>
                    </div>
                </div>
                <div class="mb-4">
                    <h6 class="mb-1 font-weight-bold">Contact info</h6>
                    <address class="">
                        173 Baja lane, Iyapo Abuja.
                    </address>
                </div>
                <div class="my-4 my-md-4">
                    <ul class="list-inline mb-0 opacity-7">
                        <li class="list-inline-item mr-0">
                            <a class="btn font-size-20 btn-icon btn-soft-dark btn-bg-transparent rounded-circle" href="#">
                                <span class="fab fa-facebook-f btn-icon__inner"></span>
                            </a>
                        </li>
                        <li class="list-inline-item mr-0">
                            <a class="btn font-size-20 btn-icon btn-soft-dark btn-bg-transparent rounded-circle" href="#">
                                <span class="fab fa-google btn-icon__inner"></span>
                            </a>
                        </li>
                        <li class="list-inline-item mr-0">
                            <a class="btn font-size-20 btn-icon btn-soft-dark btn-bg-transparent rounded-circle" href="#">
                                <span class="fab fa-twitter btn-icon__inner"></span>
                            </a>
                        </li>
                        <li class="list-inline-item mr-0">
                            <a class="btn font-size-20 btn-icon btn-soft-dark btn-bg-transparent rounded-circle" href="#">
                                <span class="fab fa-github btn-icon__inner"></span>
                            </a>
                        </li>
                    </ul>
                </div>
            </div>
            <div class="col-lg-7">
                <div class="row">
                    <div class="col-12 col-md mb-4 mb-md-0">
                        <h6 class="mb-3 font-weight-bold">Find it Fast</h6>
                        <!-- List Group -->
                        <ul class="list-group list-group-flush list-group-borderless mb-0 list-group-transparent">
                            <li><a class="list-group-item list-group-item-action" href="category-single">Laptops & Computers</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">Home Accessories</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">Properties for sale</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">Properties for rent</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">TV & Audio</a></li>
                        </ul>
                        <!-- End List Group -->
                    </div>

                    <div class="col-12 col-md mb-4 mb-md-0">
                        <!-- List Group -->
                        <ul class="list-group list-group-flush list-group-borderless mb-0 list-group-transparent mt-md-6">
                            <li><a class="list-group-item list-group-item-action" href="category-single">Cars for sale</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">Software</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">Office Supplies</a></li>
                            <li><a class="list-group-item list-group-item-action" href="category-single">Fashion</a></li>
                        </ul>
                        <!-- End List Group -->
                    </div>

                    <div class="col-12 col-md mb-4 mb-md-0">
                        <h6 class="mb-3 font-weight-bold">Customer Care</h6>
                        <!-- List Group -->
                        <ul class="list-group list-group-flush list-group-borderless mb-0 list-group-transparent">
                            <li><a class="list-group-item list-group-item-action" href="../shop/my-account.html">My Account</a></li>
                            <li><a class="list-group-item list-group-item-action" href="../home/terms-and-conditions.html">Customer Service</a></li>
                            <li><a class="list-group-item list-group-item-action" href="../home/faq.html">FAQs</a></li>
                            <li><a class="list-group-item list-group-item-action" href="../home/terms-and-conditions.html">Product Support</a></li>
                        </ul>
                        <!-- End List Group -->
                    </div>
                </div>
            </div>
        </div>
    </div>
</div>
<!-- End Footer-bottom-widgets -->
<!-- Footer-copy-right -->
<div class="bg-gray-14 py-2">
    <div class="container">
        <div class="flex-center-between d-block d-md-flex">
            <div class="mb-3 mb-md-0">© <a href="#" class="font-weight-bold text-gray-90">Olowotrade</a> - All rights Reserved</div>
            <div class="text-md-right">
                <span class="d-inline-block bg-white border rounded p-1">
                    <img class="max-width-5" src="assets/img/100X60/img1.jpg" alt="Image Description">
                </span>
                <span class="d-inline-block bg-white border rounded p-1">
                    <img class="max-width-5" src="assets/img/100X60/img2.jpg" alt="Image Description">
                </span>
                <span class="d-inline-block bg-white border rounded p-1">
                    <img class="max-width-5" src="assets/img/100X60/img3.jpg" alt="Image Description">
                </span>
                <span class="d-inline-block bg-white border rounded p-1">
                    <img class="max-width-5" src="assets/img/100X60/img4.jpg" alt="Image Description">
                </span>
                <span class="d-inline-block bg-white border rounded p-1">
                    <img class="max-width-5" src="assets/img/100X60/img5.jpg" alt="Image Description">
                </span>
            </div>
        </div>
    </div>
</div>
<!-- End Footer-copy-right -->
</footer>
<!-- ========== END FOOTER ========== -->

<!-- ========== SECONDARY CONTENTS ========== -->
<!-- Account Sidebar Navigation -->
<aside id="sidebarContent" class="u-sidebar u-sidebar__lg" aria-labelledby="sidebarNavToggler">
    <div class="u-sidebar__scroller">
        <div class="u-sidebar__container">
            <div class="js-scrollbar u-header-sidebar__footer-offset pb-3">
                <!-- Toggle Button -->
                <div class="d-flex align-items-center pt-4 px-7">
                    <button type="button" class="close ml-auto"
                    aria-controls="sidebarContent"
                    aria-haspopup="true"
                    aria-expanded="false"
                    data-unfold-event="click"
                    data-unfold-hide-on-scroll="false"
                    data-unfold-target="#sidebarContent"
                    data-unfold-type="css-animation"
                    data-unfold-animation-in="fadeInRight"
                    data-unfold-animation-out="fadeOutRight"
                    data-unfold-duration="500">
                    <i class="ec ec-close-remove"></i>
                </button>
            </div>
            <!-- End Toggle Button -->

            <!-- Content -->
            <div class="js-scrollbar u-sidebar__body">
                <div class="u-sidebar__content u-header-sidebar__content">
                    <form class="js-validate">
                        <!-- Login -->
                        <div id="login" data-target-group="idForm">
                            <!-- Title -->
                            <header class="text-center mb-7">
                                <h2 class="h4 mb-0">Welcome Back!</h2>
                                <p>Login to manage your account.</p>
                            </header>
                            <!-- End Title -->

                            <!-- Form Group -->
                            <div class="form-group">
                                <div class="js-form-message js-focus-state">
                                    <label class="sr-only" for="signinEmail">Email</label>
                                    <div class="input-group">
                                        <div class="input-group-prepend">
                                            <span class="input-group-text" id="signinEmailLabel">
                                                <span class="fas fa-user"></span>
                                            </span>
                                        </div>
                                        <input type="email" class="form-control" name="email" id="signinEmail" placeholder="Email" aria-label="Email" aria-describedby="signinEmailLabel" required
                                        data-msg="Please enter a valid email address."
                                        data-error-class="u-has-error"
                                        data-success-class="u-has-success">
                                    </div>
                                </div>
                            </div>
                            <!-- End Form Group -->

                            <!-- Form Group -->
                            <div class="form-group">
                                <div class="js-form-message js-focus-state">
                                  <label class="sr-only" for="signinPassword">Password</label>
                                  <div class="input-group">
                                    <div class="input-group-prepend">
                                        <span class="input-group-text" id="signinPasswordLabel">
                                            <span class="fas fa-lock"></span>
                                        </span>
                                    </div>
                                    <input type="password" class="form-control" name="password" id="signinPassword" placeholder="Password" aria-label="Password" aria-describedby="signinPasswordLabel" required
                                    data-msg="Your password is invalid. Please try again."
                                    data-error-class="u-has-error"
                                    data-success-class="u-has-success">
                                </div>
                            </div>
                        </div>
                        <!-- End Form Group -->

                        <div class="d-flex justify-content-end mb-4">
                            <a class="js-animation-link small link-muted" href="javascript:;"
                            data-target="#forgotPassword"
                            data-link-group="idForm"
                            data-animation-in="slideInUp">Forgot Password?</a>
                        </div>

                        <div class="mb-2">
                            <button type="submit" class="btn btn-block btn-sm btn-primary transition-3d-hover">Login</button>
                        </div>

                        <div class="text-center mb-4">
                            <span class="small text-muted">Do not have an account?</span>
                            <a class="js-animation-link small text-dark" href="javascript:;"
                            data-target="#signup"
                            data-link-group="idForm"
                            data-animation-in="slideInUp">Signup
                        </a>
                    </div>

                    <div class="text-center">
                        <span class="u-divider u-divider--xs u-divider--text mb-4">OR</span>
                    </div>

                    <!-- Login Buttons -->
                    <div class="d-flex">
                        <a class="btn btn-block btn-sm btn-soft-facebook transition-3d-hover mr-1" href="#">
                          <span class="fab fa-facebook-square mr-1"></span>
                          Facebook
                      </a>
                      <a class="btn btn-block btn-sm btn-soft-google transition-3d-hover ml-1 mt-0" href="#">
                          <span class="fab fa-google mr-1"></span>
                          Google
                      </a>
                  </div>
                  <!-- End Login Buttons -->
              </div>

              <!-- Signup -->
              <div id="signup" style="display: none; opacity: 0;" data-target-group="idForm">
                <!-- Title -->
                <header class="text-center mb-7">
                    <h2 class="h4 mb-0">Welcome to Olowotrade.</h2>
                    <p>Fill out the form to get started.</p>
                </header>
                <!-- End Title -->

                <!-- Form Group -->
                <div class="form-group">
                    <div class="js-form-message js-focus-state">
                        <label class="sr-only" for="signupEmail">Email</label>
                        <div class="input-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text" id="signupEmailLabel">
                                    <span class="fas fa-user"></span>
                                </span>
                            </div>
                            <input type="email" class="form-control" name="email" id="signupEmail" placeholder="Email" aria-label="Email" aria-describedby="signupEmailLabel" required
                            data-msg="Please enter a valid email address."
                            data-error-class="u-has-error"
                            data-success-class="u-has-success">
                        </div>
                    </div>
                </div>
                <!-- End Input -->

                <!-- Form Group -->
                <div class="form-group">
                    <div class="js-form-message js-focus-state">
                        <label class="sr-only" for="signupPassword">Password</label>
                        <div class="input-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text" id="signupPasswordLabel">
                                    <span class="fas fa-lock"></span>
                                </span>
                            </div>
                            <input type="password" class="form-control" name="password" id="signupPassword" placeholder="Password" aria-label="Password" aria-describedby="signupPasswordLabel" required
                            data-msg="Your password is invalid. Please try again."
                            data-error-class="u-has-error"
                            data-success-class="u-has-success">
                        </div>
                    </div>
                </div>
                <!-- End Input -->

                <!-- Form Group -->
                <div class="form-group">
                    <div class="js-form-message js-focus-state">
                        <label class="sr-only" for="signupConfirmPassword">Confirm Password</label>
                        <div class="input-group">
                            <div class="input-group-prepend">
                                <span class="input-group-text" id="signupConfirmPasswordLabel">
                                    <span class="fas fa-key"></span>
                                </span>
                            </div>
                            <input type="password" class="form-control" name="confirmPassword" id="signupConfirmPassword" placeholder="Confirm Password" aria-label="Confirm Password" aria-describedby="signupConfirmPasswordLabel" required
                            data-msg="Password does not match the confirm password."
                            data-error-class="u-has-error"
                            data-success-class="u-has-success">
                        </div>
                    </div>
                </div>
                <!-- End Input -->

                <div class="mb-2">
                    <button type="submit" class="btn btn-block btn-sm btn-primary transition-3d-hover">Get Started</button>
                </div>

                <div class="text-center mb-4">
                    <span class="small text-muted">Already have an account?</span>
                    <a class="js-animation-link small text-dark" href="javascript:;"
                    data-target="#login"
                    data-link-group="idForm"
                    data-animation-in="slideInUp">Login
                </a>
            </div>

            <div class="text-center">
                <span class="u-divider u-divider--xs u-divider--text mb-4">OR</span>
            </div>

            <!-- Login Buttons -->
            <div class="d-flex">
                <a class="btn btn-block btn-sm btn-soft-facebook transition-3d-hover mr-1" href="#">
                    <span class="fab fa-facebook-square mr-1"></span>
                    Facebook
                </a>
                <a class="btn btn-block btn-sm btn-soft-google transition-3d-hover ml-1 mt-0" href="#">
                    <span class="fab fa-google mr-1"></span>
                    Google
                </a>
            </div>
            <!-- End Login Buttons -->
        </div>
        <!-- End Signup -->

        <!-- Forgot Password -->
        <div id="forgotPassword" style="display: none; opacity: 0;" data-target-group="idForm">
            <!-- Title -->
            <header class="text-center mb-7">
                <h2 class="h4 mb-0">Recover Password.</h2>
                <p>Enter your email address and an email with instructions will be sent to you.</p>
            </header>
            <!-- End Title -->

            <!-- Form Group -->
            <div class="form-group">
                <div class="js-form-message js-focus-state">
                    <label class="sr-only" for="recoverEmail">Your email</label>
                    <div class="input-group">
                        <div class="input-group-prepend">
                            <span class="input-group-text" id="recoverEmailLabel">
                                <span class="fas fa-user"></span>
                            </span>
                        </div>
                        <input type="email" class="form-control" name="email" id="recoverEmail" placeholder="Your email" aria-label="Your email" aria-describedby="recoverEmailLabel" required
                        data-msg="Please enter a valid email address."
                        data-error-class="u-has-error"
                        data-success-class="u-has-success">
                    </div>
                </div>
            </div>
            <!-- End Form Group -->

            <div class="mb-2">
                <button type="submit" class="btn btn-block btn-sm btn-primary transition-3d-hover">Recover Password</button>
            </div>

            <div class="text-center mb-4">
                <span class="small text-muted">Remember your password?</span>
                <a class="js-animation-link small" href="javascript:;"
                data-target="#login"
                data-link-group="idForm"
                data-animation-in="slideInUp">Login
            </a>
        </div>
    </div>
    <!-- End Forgot Password -->
</form>
</div>
</div>
<!-- End Content -->
</div>
</div>
</div>
</aside>
<!-- End Account Sidebar Navigation -->
<!-- ========== END SECONDARY CONTENTS ========== -->

<!-- Go to Top -->
<a class="js-go-to u-go-to" href="#"
data-position='{"bottom": 15, "right": 15 }'
data-type="fixed"
data-offset-top="400"
data-compensation="#header"
data-show-effect="slideInUp"
data-hide-effect="slideOutDown">
<span class="fas fa-arrow-up u-go-to__inner"></span>
</a>
<!-- End Go to Top -->

<!-- JS Global Compulsory -->
<script src="assets/vendor/jquery/dist/jquery.min.js"></script>
<script src="assets/vendor/jquery-migrate/dist/jquery-migrate.min.js"></script>
<script src="assets/vendor/popper.js/dist/umd/popper.min.js"></script>
<script src="assets/vendor/bootstrap/bootstrap.min.js"></script>

<!-- JS Implementing Plugins -->
<script src="assets/vendor/appear.js"></script>
<script src="assets/vendor/jquery.countdown.min.js"></script>
<script src="assets/vendor/hs-megamenu/src/hs.megamenu.js"></script>
<script src="assets/vendor/svg-injector/dist/svg-injector.min.js"></script>
<script src="assets/vendor/malihu-custom-scrollbar-plugin/jquery.mCustomScrollbar.concat.min.js"></script>
<script src="assets/vendor/jquery-validation/dist/jquery.validate.min.js"></script>
<script src="assets/vendor/fancybox/jquery.fancybox.min.js"></script>
<script src="assets/vendor/typed.js/lib/typed.min.js"></script>
<script src="assets/vendor/slick-carousel/slick/slick.js"></script>
<script src="assets/vendor/bootstrap-select/dist/js/bootstrap-select.min.js"></script>

<!-- JS Electro -->
<script src="assets/js/hs.core.js"></script>
<script src="assets/js/components/hs.countdown.js"></script>
<script src="assets/js/components/hs.header.js"></script>
<script src="assets/js/components/hs.hamburgers.js"></script>
<script src="assets/js/components/hs.unfold.js"></script>
<script src="assets/js/components/hs.focus-state.js"></script>
<script src="assets/js/components/hs.malihu-scrollbar.js"></script>
<script src="assets/js/components/hs.validation.js"></script>
<script src="assets/js/components/hs.fancybox.js"></script>
<script src="assets/js/components/hs.onscroll-animation.js"></script>
<script src="assets/js/components/hs.slick-carousel.js"></script>
<script src="assets/js/components/hs.show-animation.js"></script>
<script src="assets/js/components/hs.svg-injector.js"></script>
<script src="assets/js/components/hs.go-to.js"></script>
<script src="assets/js/components/hs.selectpicker.js"></script>

<!-- JS Plugins Init. -->
<script>
    $(window).on('load', function () {
                // initialization of HSMegaMenu component
                $('.js-mega-menu').HSMegaMenu({
                    event: 'hover',
                    direction: 'horizontal',
                    pageContainer: $('.container'),
                    breakpoint: 767.98,
                    hideTimeOut: 0
                });
            });

    $(document).on('ready', function () {
                // initialization of header
                $.HSCore.components.HSHeader.init($('#header'));

                // initialization of animation
                $.HSCore.components.HSOnScrollAnimation.init('[data-animation]');

                // initialization of unfold component
                $.HSCore.components.HSUnfold.init($('[data-unfold-target]'), {
                    afterOpen: function () {
                        $(this).find('input[type="search"]').focus();
                    }
                });

                // initialization of popups
                $.HSCore.components.HSFancyBox.init('.js-fancybox');

                // initialization of countdowns
                var countdowns = $.HSCore.components.HSCountdown.init('.js-countdown', {
                    yearsElSelector: '.js-cd-years',
                    monthsElSelector: '.js-cd-months',
                    daysElSelector: '.js-cd-days',
                    hoursElSelector: '.js-cd-hours',
                    minutesElSelector: '.js-cd-minutes',
                    secondsElSelector: '.js-cd-seconds'
                });

                // initialization of malihu scrollbar
                $.HSCore.components.HSMalihuScrollBar.init($('.js-scrollbar'));

                // initialization of forms
                $.HSCore.components.HSFocusState.init();

                // initialization of form validation
                $.HSCore.components.HSValidation.init('.js-validate', {
                    rules: {
                        confirmPassword: {
                            equalTo: '#signupPassword'
                        }
                    }
                });

                // initialization of show animations
                $.HSCore.components.HSShowAnimation.init('.js-animation-link');

                // initialization of fancybox
                $.HSCore.components.HSFancyBox.init('.js-fancybox');

                // initialization of slick carousel
                $.HSCore.components.HSSlickCarousel.init('.js-slick-carousel');

                // initialization of go to
                $.HSCore.components.HSGoTo.init('.js-go-to');

                // initialization of hamburgers
                $.HSCore.components.HSHamburgers.init('#hamburgerTrigger');

                // initialization of unfold component
                $.HSCore.components.HSUnfold.init($('[data-unfold-target]'), {
                    beforeClose: function () {
                        $('#hamburgerTrigger').removeClass('is-active');
                    },
                    afterClose: function() {
                        $('#headerSidebarList .collapse.show').collapse('hide');
                    }
                });

                $('#headerSidebarList [data-toggle="collapse"]').on('click', function (e) {
                    e.preventDefault();

                    var target = $(this).data('target');

                    if($(this).attr('aria-expanded') === "true") {
                        $(target).collapse('hide');
                    } else {
                        $(target).collapse('show');
                    }
                });

                // initialization of unfold component
                $.HSCore.components.HSUnfold.init($('[data-unfold-target]'));

                // initialization of select picker
                $.HSCore.components.HSSelectPicker.init('.js-select');
            });
        </script>

        <script src="assets/owlcarousel/owl.carousel.min.js"></script>
        <script type="text/javascript">
         $('#prodCarousel').owlCarousel({
          loop: true,
          margin: 0,
          responsiveClass: true,
          responsive: {
            0: {
              items: 1,
              nav: true,
              loop: false,
          },
          600: {
              items: 2,
              nav: true,
              margin: 20,
              loop: false,
          },
          900: {
              items: 3,
              nav: true,
              margin: 20,
              loop: false,
          },
          1000: {
              items: 5,
              nav: true,
              loop: false,
              margin: 20
          }
      }
  });
         
</script>
</body>
</html>
