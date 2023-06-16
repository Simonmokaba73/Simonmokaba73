
<!DOCTYPE html >
<html lang="en">
    <head>
        <title>My Coin Auction - View Auctions</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=0, minimal-ui">
        <meta http-equiv="X-UA-Compatible" content="IE=edge" />
        <meta name="description" content="" />
        <meta name="keywords" content=""/>
        <meta name="author" content=""/>

        <!-- Favicon icon -->
        <link rel="icon" href="https://www.mca2023.com/Icons/favicon.png" type="image/x-icon">
        <!-- fontawesome icon -->
        <link rel="stylesheet" href="https://www.mca2023.com/css/fontawesome-all.min.css">
        <!-- animation css -->
        <link rel="stylesheet" href="https://www.mca2023.com/css/animate.min.css">
        <!-- vendor css -->
        
        <link href="https://www.mca2023.com/css/style.css" rel="stylesheet">
        <link rel="stylesheet" type="text/css" href="https://www.mca2023.com/css/timer.css">

        <style>
            .fixed-button.active {
                bottom: 50px;
                opacity: 1;
                visibility: hidden;
            }


            .fixed-button {
                bottom: 50px;
                opacity: 1;
                visibility: hidden;
            }
        </style>
            <!-- Global site tag (gtag.js) - Google Analytics -->
        <script async src="https://www.googletagmanager.com/gtag/js?id=G-NGZW11GB1G"></script>
        <script>
            window.dataLayer = window.dataLayer || [];
            function gtag(){dataLayer.push(arguments);}
            gtag('js', new Date());

            gtag('config', 'G-NGZW11GB1G');
        </script><script src="https://unpkg.com/sweetalert/dist/sweetalert.min.js"></script>

    </head>
    <body>

            <nav class="pcoded-navbar">
    <div class="navbar-wrapper">
        <div class="navbar-brand header-logo">
            <a href="https://www.mca2023.com/User/dashboard" class="b-brand">
                <div class="b-bg">
                    <i class="feather icon-trending-up"></i>
                </div>
                <span class="b-title">My Coin Auction</span>
            </a>
            <a class="mobile-menu" id="mobile-collapse" href="javascript:"><span></span></a>
            </div>

            <div class="slimScrollDiv" style="position: relative; overflow: auto; width: 100%; height: calc(100vh - 70px);"><div class="navbar-content scroll-div" style="overflow: auto; width: 100%; height: calc(100vh - 70px);">
            
                    <ul class="nav pcoded-inner-navbar">
        <li class="nav-item pcoded-menu-caption">
            <label>Navigation</label>
        </li>
        <li data-username="dashboard Default Ecommerce CRM Analytics Crypto Project"
            class="nav-item ">
            <a href="https://www.mca2023.com/User/dashboard" class="nav-link "><span class="pcoded-micon">
                <i class="feather icon-home"></i></span><span class="pcoded-mtext">Dashboard</span>
            </a>
        </li>
        <li class="nav-item pcoded-menu-caption">
            <label>Auction</label>
        </li>
        <li data-username="basic components Button Alert Badges breadcrumb Paggination progress Tooltip popovers Carousel Cards Collapse Tabs pills Modal Grid System Typography Extra Shadows Embeds"
            class="nav-item pcoded-hasmenu active">
            <a href="javascript:" class="nav-link "><span class="pcoded-micon">
                <i class="feather icon-box"></i></span><span class="pcoded-mtext">Auction Menu</span>
            </a>
            <ul class="pcoded-submenu">
                <li class=""><a href="https://www.mca2023.com/User/auction/view" class="">View Auction</a></li>
                <li class=""><a href="https://www.mca2023.com/User/auction/pay-bids" class="">Pay Bids</a></li>
                <li class=""><a href="https://www.mca2023.com/User/auction/received" class="">Receive Payments</a></li>
                
                <li class=""><a href="https://www.mca2023.com/User/auction/sales" class="">Sale On Auction</a></li>
                <li class=""><a href="https://www.mca2023.com/User/affiliates/bonuses" class="">Bonuses</a></li>
                <li class=""><a href="https://www.mca2023.com/User/affiliates" class="">Affiliates</a></li>
                <li class=""><a href="" class="">Auction History</a></li>
            </ul>
        </li>
        <li class="nav-item pcoded-menu-caption">
            <label>Advanced Settings</label>
        </li>
        <li data-username="form elements advance componant validation masking wizard picker select"
            class="nav-item">
            <a href="https://www.mca2023.com/User/account-settings/bank-info" class="nav-link "><span class="pcoded-micon">
                <i class="feather icon-file-text"></i></span><span class="pcoded-mtext">Banking Details</span>
            </a>
        </li>

        <li data-username="Table bootstrap datatable footable" class="nav-item">
            <a href="https://www.mca2023.com/User/account-settings/profile" class="nav-link "><span class="pcoded-micon">
                <i class="feather icon-server"></i></span><span class="pcoded-mtext">Account Information</span></a>
        </li>

        <li data-username="Table bootstrap datatable footable" class="nav-item">
            <a href="https://www.mca2023.com/User/account-settings/change-password" class="nav-link "><span class="pcoded-micon">
                <i class="feather icon-server"></i></span><span class="pcoded-mtext">Change Password</span></a>
        </li>


        <li class="nav-item pcoded-menu-caption">
            <label>Authentication</label>
        </li>
        <li data-username="Sample Page" class="nav-item">
            <a class="nav-link" href="https://www.mca2023.com/logout" onclick="event.preventDefault(); document.getElementById('logout-form').submit();">
               <span class="pcoded-micon"><i class="feather icon-power"></i></span>
               <span class="pcoded-mtext">Sign Out</span>
            </a>
            <form id="logout-form" action="https://www.mca2023.com/logout" method="POST" class="d-none">
                <input type="hidden" name="_token" value="AxNQUNuDdwI42NJ6kc7X8KwoDVC6x5PtXGx8jA3w">            </form>
        </li>
    </ul>
            

            </div>
        <div class="slimScrollBar" style="background: rgba(0, 0, 0, 0.5); width: 5px; position: absolute; top: 0px; opacity: 0.4; display: none; border-radius: 7px; z-index: 99; right: 1px; height: 595.2px;"></div><div class="slimScrollRail" style="width: 5px; height: 100%; position: absolute; top: 0px; display: none; border-radius: 7px; background: rgb(51, 51, 51); opacity: 0.2; z-index: 90; right: 1px;"></div></div>


    </div>
</nav>



<header class="navbar pcoded-header navbar-expand-lg navbar-light">
    <div class="m-header">
        <a class="mobile-menu" id="mobile-collapse1" href="javascript:"><span></span></a>
        <a href="https://www.mca2023.com/User/dashboard" class="b-brand">
            <div class="b-bg">
                <i class="feather icon-trending-up"></i>
            </div>
            <span class="b-title">My Coin Auction</span>
        </a>
    </div>
    <a class="mobile-menu" id="mobile-header" href="javascript:">
        <i class="feather icon-more-horizontal"></i>
    </a>
    <div class="collapse navbar-collapse">
    </div>
</header>



    <style>
        .isBidding{
            display: none;
        }
    </style>

    <div class="pcoded-main-container">
        <div class="pcoded-wrapper">
            <div class="pcoded-content">
                <div class="pcoded-inner-content">

                    <div class="page-header">
            <div class="page-block">
                <div class="row align-items-center">
                    <div class="col-md-12">
                        <ul class="breadcrumb">
                            <li class="breadcrumb-item"><a href="dash"><i class="feather icon-home"></i></a>
                            </li>
                            <li class="breadcrumb-item"><a href="javascript:">All Auctions</a></li>
                        </ul>
                    </div>
                </div>
            </div>
        </div>

        <div class="main-body">
            <div class="page-wrapper">

                <div class="row">
                    <div class="col-xl-6 col-md-6">
                        <div class="card card-event">
                            <div class="card-block">
                                <div class="row align-items-center justify-content-center">
                                    <div class="col">
                                        <h5 class="m-0">Next Auction Entries</h5>
                                    </div>
                                </div>
                                <h2 class="mt-3 f-w-300">

                                  R21088                                                  <sub
                                        class="text-muted f-14">Coins</sub>
                                </h2>
                                <h6 class="text-muted mt-4 mb-0">You can participate in event </h6>
                                <i class="fab fa-angellist text-c-purple f-50"></i>
                            </div>
                        </div>
                    </div>


                    <div class="col-xl-6 col-md-6" id="auctionTimer">
                        <div class="card">
                            <div class="card-block border-bottom">
                                <div class="row d-flex align-items-center">
                                    <div class="col-auto">
                                        <i class="feather icon-zap f-30 text-c-green"></i>
                                    </div>
                                    <div class="col">
                                        <h3 class="f-w-300 at ">
                                            <p>
    

    <span class="tDigit" id="hourP"></span><span class="tLetter">H</span> <span class="tDot">:</span>

    <span class="tDigit" id="minP"></span><span class="tLetter">M</span> <span class="tDot">:</span>

    <span class="tDigit" id="secP"></span><span class="tLetter">S</span> <span class="tDot"></span>
</p>





<script>
    var x = setInterval(function() {
        var startH = "13:00";
        var endH = "13:20";
        var present = new Date();
        var customDate;
        var convertedTArray = startH.split(':');
        var convertedH = +convertedTArray[0];
        var convertedM = +convertedTArray[1];


        let convertedTArrayEnd = endH.split(':');
        let convertedEH = +convertedTArrayEnd[0];
        let convertedEM = +convertedTArrayEnd[1];

        let startMS = new Date(present.getFullYear(), present.getMonth(), present.getDate(), convertedH, convertedM, 0);


        let endMSUnchanged = new Date(present.getFullYear(), present.getMonth(), present.getDate(), convertedEH, convertedEM, 0);


        if (present.getTime() < startMS.getTime()) {
          customDate = present.getDate();
        } else {
          customDate = present.getDate() + 1;
        }


        if (present.getTime() < endMSUnchanged.getTime() && present.getTime() > startMS.getTime()) {
          document.getElementById('openMe').style.display = 'block';
          document.getElementById('auctionTimer').style.display = 'none';
        } else if(present.getTime() > endMSUnchanged.getTime()) {
          document.getElementById('openMe').style.display = 'none';
          document.getElementById('auctionTimer').style.display = 'block';
        }

        let emdMS = new Date(present.getFullYear(), present.getMonth(), customDate, convertedEH, convertedEM, 0).getTime();

        let countTo = new Date(present.getFullYear(), present.getMonth(), customDate, convertedH, convertedM, 0)

        let distance = countTo.getTime() - present.getTime();

        let actD = Math.floor(distance / (1000 * 60 * 60 * 24));
        let actH = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        let actM = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        let actS = Math.floor((distance % (1000 * 60)) / (1000));

        // var days = document.getElementById('dayP');
        var hours = document.getElementById('hourP');
        var minutes = document.getElementById('minP');
        var seconds = document.getElementById('secP');

        // days.innerHTML = actD;
        hours.innerHTML = actH;
        minutes.innerHTML = actM;
        seconds.innerHTML = actS;

    }, 1000);

</script>
                                        </h3>
                                        <span class="d-block text-uppercase">Next Auction</span>

                                    </div>
                                </div>



                            </div>
                            <div class="card-block">
                                <div class="row d-flex align-items-center">
                                    <div class="col-auto">
                                        <i class="feather icon-map-pin f-30 text-c-blue"></i>
                                    </div>
                                    <div class="col">
                                        <h3 class="f-w-300">Daily Auction Times</h3>
                                        <span class="d-block text-uppercase">
                                            13:00  Hrs
                                        </span>
                                        <span class="d-block text-uppercase">
                                            13:20  Hrs
                                        </span>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                    

                </div>

                <div id="openMe">
                                        <div class="row">
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R168</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 0)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 0)" type="radio" class="custom-control-input" id="pack1_0" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_0">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 0)" type="radio" class="custom-control-input" id="pack2_0" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_0">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_0">
                                        <input type="hidden" id="thePlanID_0">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(309, 0, 168, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_0"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>TYME BANK </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,180</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 1)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 1)" type="radio" class="custom-control-input" id="pack1_1" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_1">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 1)" type="radio" class="custom-control-input" id="pack2_1" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_1">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_1">
                                        <input type="hidden" id="thePlanID_1">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(333, 1, 1180, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_1"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>TYME BANK </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,000</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 2)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 2)" type="radio" class="custom-control-input" id="pack1_2" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_2">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 2)" type="radio" class="custom-control-input" id="pack2_2" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_2">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_2">
                                        <input type="hidden" id="thePlanID_2">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(343, 2, 1000, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_2"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R600</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 3)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 3)" type="radio" class="custom-control-input" id="pack1_3" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_3">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 3)" type="radio" class="custom-control-input" id="pack2_3" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_3">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_3">
                                        <input type="hidden" id="thePlanID_3">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(307, 3, 600, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_3"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R900</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 4)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 4)" type="radio" class="custom-control-input" id="pack1_4" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_4">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 4)" type="radio" class="custom-control-input" id="pack2_4" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_4">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_4">
                                        <input type="hidden" id="thePlanID_4">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(325, 4, 900, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_4"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,680</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 5)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 5)" type="radio" class="custom-control-input" id="pack1_5" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_5">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 5)" type="radio" class="custom-control-input" id="pack2_5" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_5">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_5">
                                        <input type="hidden" id="thePlanID_5">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(344, 5, 1680, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_5"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,680</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 6)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 6)" type="radio" class="custom-control-input" id="pack1_6" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_6">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 6)" type="radio" class="custom-control-input" id="pack2_6" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_6">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_6">
                                        <input type="hidden" id="thePlanID_6">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(345, 6, 1680, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_6"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,200</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 7)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 7)" type="radio" class="custom-control-input" id="pack1_7" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_7">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 7)" type="radio" class="custom-control-input" id="pack2_7" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_7">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_7">
                                        <input type="hidden" id="thePlanID_7">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(351, 7, 1200, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_7"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R680</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 8)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 8)" type="radio" class="custom-control-input" id="pack1_8" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_8">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 8)" type="radio" class="custom-control-input" id="pack2_8" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_8">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_8">
                                        <input type="hidden" id="thePlanID_8">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(352, 8, 680, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_8"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,200</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 9)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 9)" type="radio" class="custom-control-input" id="pack1_9" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_9">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 9)" type="radio" class="custom-control-input" id="pack2_9" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_9">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_9">
                                        <input type="hidden" id="thePlanID_9">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(353, 9, 1200, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_9"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R600</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 10)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 10)" type="radio" class="custom-control-input" id="pack1_10" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_10">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 10)" type="radio" class="custom-control-input" id="pack2_10" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_10">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_10">
                                        <input type="hidden" id="thePlanID_10">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(354, 10, 600, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_10"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R2,400</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 11)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 11)" type="radio" class="custom-control-input" id="pack1_11" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_11">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 11)" type="radio" class="custom-control-input" id="pack2_11" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_11">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_11">
                                        <input type="hidden" id="thePlanID_11">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(355, 11, 2400, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_11"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,200</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 12)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 12)" type="radio" class="custom-control-input" id="pack1_12" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_12">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 12)" type="radio" class="custom-control-input" id="pack2_12" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_12">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_12">
                                        <input type="hidden" id="thePlanID_12">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(360, 12, 1200, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_12"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R300</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 13)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 13)" type="radio" class="custom-control-input" id="pack1_13" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_13">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 13)" type="radio" class="custom-control-input" id="pack2_13" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_13">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_13">
                                        <input type="hidden" id="thePlanID_13">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(334, 13, 300, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_13"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,680</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 14)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 14)" type="radio" class="custom-control-input" id="pack1_14" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_14">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 14)" type="radio" class="custom-control-input" id="pack2_14" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_14">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_14">
                                        <input type="hidden" id="thePlanID_14">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(336, 14, 1680, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_14"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R600</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 15)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 15)" type="radio" class="custom-control-input" id="pack1_15" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_15">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 15)" type="radio" class="custom-control-input" id="pack2_15" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_15">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_15">
                                        <input type="hidden" id="thePlanID_15">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(348, 15, 600, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_15"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,680</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 16)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 16)" type="radio" class="custom-control-input" id="pack1_16" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_16">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 16)" type="radio" class="custom-control-input" id="pack2_16" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_16">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_16">
                                        <input type="hidden" id="thePlanID_16">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(349, 16, 1680, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_16"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R600</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 17)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 17)" type="radio" class="custom-control-input" id="pack1_17" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_17">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 17)" type="radio" class="custom-control-input" id="pack2_17" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_17">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_17">
                                        <input type="hidden" id="thePlanID_17">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(359, 17, 600, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_17"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>Capitec bank </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R1,200</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 18)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 18)" type="radio" class="custom-control-input" id="pack1_18" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_18">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 18)" type="radio" class="custom-control-input" id="pack2_18" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_18">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_18">
                                        <input type="hidden" id="thePlanID_18">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(361, 18, 1200, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_18"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                                
                        <div class="col-xl-6">
                            <div class="card card-event">
                                <div class="card-header">
                                    <h5>ABSA </h5>
                                </div>
                                <div class="card-body">
                                    <div class="text-center">
                                        <h5>Total Amount: R540</h5>
                                    </div>

                                    <form>
                                        <div class="form-group mt-4">
                                        <label>Enter Amount</label>
                                        <input onkeyup="getAmount(this, 19)" type="number" name="amount" class="form-control bg-dark-input">
                                        </div>

                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 19)" type="radio" class="custom-control-input" id="pack1_19" name="planPack" value="1">
                                            <label class="custom-control-label" for="pack1_19">40% in 2 Days (Min. Invest Amount: R100)</label>
                                        </div>
                                                                                <div class="custom-control custom-radio mb-2">
                                            <input onchange="getPlanID(this.value, 19)" type="radio" class="custom-control-input" id="pack2_19" name="planPack" value="2">
                                            <label class="custom-control-label" for="pack2_19">100% in 4 Days (Min. Invest Amount: R300)</label>
                                        </div>
                                        
                                        <input type="hidden" id="inputAmount_19">
                                        <input type="hidden" id="thePlanID_19">
                                        <div class="text-center mt-5">
                                            <button onclick="submitOrder(281, 19, 540, 0)" class="btn btn-primary isNotBidding" type="button" id="isNotBidding">BID NOW</button>

                                            <button class="btn btn-primary isBidding" type="button" id="isBidding_19"><i class="fa fa-spinner fa-spin"></i> BIDDING</button>
                                        </div>
                                </form>
                                </div>
                            </div>
                        </div>
                                            </div>
                                    </div>

            </div>
        </div>

                </div>
            </div>
        </div>
    </div>




    <!-- ERROR MODAL -->
    <div class="modal" id="errorModal">
        <div class="modal-dialog">
        <div class="modal-content">
            <!-- Modal body -->
            <div class="modal-body" style="background: red">
            <span style="color: #fff" id="errMssg"> </span> <span class="float-right" data-dismiss="modal" style="color: #fff; font-size: 20px; cursor: pointer;">*</span>
            </div>
        </div>
        </div>
    </div>

    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script>
        function getPlanID(value, count) {
            document.getElementById("thePlanID_" + count).value = value;
        }

        function getAmount(amount, count) {
            document.getElementById("inputAmount_" + count).value = amount.value;
        }


        function submitOrder(auctID, count, availBal, recoitID) {
            console.log(auctID);
            var amount = document.getElementById("inputAmount_" + count).value;
            var planID = document.getElementById("thePlanID_" + count).value;

            if (amount == '' || !amount) {
                document.getElementById('errMssg').innerHTML = "Please enter amount to continue";
                $("#errorModal").modal();
            } else if(planID == '' || !planID) {
                document.getElementById('errMssg').innerHTML = "Please select duration";
                $("#errorModal").modal();
            } else {
                var isNotBidding = document.getElementsByClassName('isNotBidding');
                for (var i = 0; i < isNotBidding.length; i++) {
                    isNotBidding[i].style.display = 'none';
                }
                document.getElementById('isBidding_' + count).style.display = 'inline';

                $.ajax({
                  url: "/User/auction/buy_coin/process_coin/" + auctID + "/" + planID + "/" + amount + "/" + availBal + "/" + recoitID,
                  type: "Get",
                  success: function(data){
                    data = data.split('|');
                    if(data && Number(data[0]) == 1) {
                        window.location.href =  "/User/auction/pay-bids/details/" + data[1];
                    } else {
                        var isNotBidding = document.getElementsByClassName('isNotBidding');
                        for (var i = 0; i < isNotBidding.length; i++) {
                            isNotBidding[i].style.display = 'inline';
                        }
                        document.getElementById('isBidding_' + count).style.display = 'none';
                        document.getElementById("errMssg").innerHTML = data;
                        $("#errorModal").modal();
                    }
                  }
                });
            }
        }
    </script>



    <!--Start of Tawk.to Script-->
    <script type="text/javascript">
        var Tawk_API=Tawk_API||{}, Tawk_LoadStart=new Date();
        (function(){
            var s1=document.createElement("script"),s0=document.getElementsByTagName("script")[0];
            s1.async=true;
            s1.src='https://embed.tawk.to/609f74d8b1d5182476b91339/1f5ne0t7c';
            s1.charset='UTF-8';
            s1.setAttribute('crossorigin','*');
            s0.parentNode.insertBefore(s1,s0);
        })();
    </script>
    <!--End of Tawk.to Script-->
    <script src="https://www.mca2023.com/js/vendor-all.min.js"></script>
    <script src="https://www.mca2023.com/js/bootstrap.min.js"></script>
    <script src="https://www.mca2023.com/js/pcoded.min.js"></script>
    </body>
</html>

<script>
    // Add the following code if you want the name of the file appear on select
    $(".custom-file-input").on("change", function() {
      var fileName = $(this).val().split("\\").pop();
      $(this).siblings(".custom-file-label").addClass("selected").html(fileName);
    });
</script>

