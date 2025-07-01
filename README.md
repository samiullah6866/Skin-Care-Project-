# Skin-Care-Project-
This is the First Client project That I was created at Trazwi Soluation  




![image](https://github.com/user-attachments/assets/d06a6d71-3972-4ae3-b812-ec6ee9ccdaf7)


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <link rel="stylesheet" href="fonts/static/Raleway-SemiBold.ttf">
    <link href="https://fonts.googleapis.com/css2?family=Raleway:ital,wght@0,100..900;1,100..900&display=swap"
        rel="stylesheet">
    <link rel="stylesheet"
        href="https://fonts.googleapis.com/css2?family=Material+Symbols+Outlined:opsz,wght,FILL,GRAD@20..48,100..700,0..1,-50..200" />
    <link rel="stylesheet" href="style.css">
    <link rel="stylesheet" href="fonts/JustLovelySlanted.ttf">
    <script src="https://code.jquery.com/jquery-3.7.1.min.js"
        integrity="sha256-/JqT3SQfawRcv/BIHPThkBvs0OEvtFFmqPF/lYI/Cxo=" crossorigin="anonymous"></script>
    <link rel="stylesheet" type="text/css" href="slick-theme.css" />
    <link rel="stylesheet" type="text/css" href="slick.css" />
    <link rel="stylesheet" href="fonts/JustLovely.ttf">
    <link href="https://fonts.googleapis.com/css2?family=Just+Lovely&display=swap" rel="stylesheet">
    <title>SKIN CARE</title>







    <script>
        function openNav() {
            document.getElementById("mySidepanel").style.width = "250px";
        }

        function closeNav() {
            document.getElementById("mySidepanel").style.width = "0";
        }

        document.addEventListener("DOMContentLoaded", function () {
            const cardSlider = document.querySelector(".card-slider");
            const prevButton = document.querySelector(".prev-button");
            const nextButton = document.querySelector(".next-button");
            let cardIndex = 0;

            function showCard(index) {
                const cardWidth = document.querySelector(".card").offsetWidth;
                cardSlider.style.transform = `translateX(${-index * cardWidth}px)`;
            }

            function nextCard() {
                cardIndex = (cardIndex + 1) % document.querySelectorAll(".card").length;
                showCard(cardIndex);
            }

            function prevCard() {
                cardIndex = (cardIndex - 1 + document.querySelectorAll(".card").length) % document.querySelectorAll(".card").length;
                showCard(cardIndex);
            }

            nextButton.addEventListener("click", nextCard);
            prevButton.addEventListener("click", prevCard);
        });
    </script>
    <script>
        function setActive(element) {
            var links = document.querySelectorAll('.op a');
            links.forEach(function (link) {
                link.classList.remove('active');
            });
            element.classList.add('active');
        }

    </script>

</head>

<body>
    <div class="main-container full-width">
        <div class="inear-container ">
            <!---------------SECTION-TOP---------------------------------------->
            <div class="topbar-clr">
                <div class="topbar">
                    <div class="inear-top">
                        <div class="top-text">
                            <p>Lorem Ipsum Dolor Sit</p>
                        </div>
                        <div class="top-login">
                            <div class="tip">
                                <a href="#">Login</a> |
                                <a href="#">Signup</a>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!-----------NAVBAR---------------------->
            <div class="header ">
                <div class="inear-header">
                    <div class="logo">
                        <div class="logo-image"><img src="images/logo.png" alt=""></div>
                    </div>
                    <div class="navbar">
                        <div class="nav">
                            <div class="op">
                                <a href="#" class="active" onclick="setActive(this)">Home</a>
                            </div>
                            <div class="op">
                                <a href="product.html" onclick="setActive(this)">Shop</a>
                            </div>
                            <div class="op">
                                <a href="#" onclick="setActive(this)">Best Seller</a>
                            </div>
                            <div class="op">
                                <a href="#" onclick="setActive(this)">Explore</a>
                            </div>
                            <div class="op">
                                <a href="#" onclick="setActive(this)">About</a>
                            </div>
                            <div class="op">
                                <a href="#" onclick="setActive(this)">Press</a>
                            </div>
                        </div>
                    </div>
                    <div class="icons">
                        <div class="inear-icon">
                            <div class="input">
                                <div class="a"><input type="text" placeholder="Text"></div>
                                <div class="b"><span class="material-symbols-outlined">search</span></div>
                            </div>
                            <div class="heart"><span class="material-symbols-outlined">favorite</span></div>
                            <div class="cart"><span class="material-symbols-outlined">shopping_cart</span></div>
                        </div>
                    </div>
                    <div class="nav-header">
                        <button class="openbtn" onclick="openNav()">☰</button>

                        <div id="mySidepanel" class="sidepanel">

                            <a href="javascript:void(0)" class="closebtn" onclick="closeNav()">×</a>


                            <a href="#">Home</a>
                            <a href="product.html">Shop</a>
                            <a href="#">Best Seller</a>
                            <a href="#">About Us</a>
                            <a href="#">Contact US</a>
                        </div>
                    </div>
                </div>
            </div>
            <!-----------------SECTION-ONE------------------------------------->
            <div class="section-one full-width">
                <div class="inear-one section-width">
                    <div class="one-data">
                        <div class="one-txt">
                            <div class="flex-txt">
                                <div class="one-main">
                                    <h1>SELECT THE BEST <br>FOR HEALTHY SKIN</h1>
                                </div>
                                <div class="one-para">
                                    <p>lorem ipsum dolor sit amet consectetur. Euismod id pulvinar ut nunc feugiat purus
                                        tortor ut. Non cursus tortor in blandit. Amet ullamcorper luctus donec arcu.</p>
                                </div>
                                <div class="one-button">
                                    <a href="product.html">SHOP ALL</a>
                                </div>
                            </div>
                        </div>
                        <div class="one-image">
                            <div class="images"><img src="images/1.png" alt=""></div>
                        </div>
                    </div>
                </div>
            </div>
            <!--------SECTION-TWO--------------------------------->
            <div class="section-two ">
                <div class="inear-two">
                    <div class="sec-txt">
                        <h2>FEATURED <span class="design">IN</span></h2>
                    </div>
                    <div class="sec-images">
                        <div class="sec-images-flex">
                            <div class="images-data">
                                <div class="img-1 gum"><img src="images/yoga.png" alt=""></div>
                                <div class="img-1 hide"><img src="images/oxygen1.png" alt=""></div>
                                <div class="img-1  hide"><img src="images/cosmo1.png" alt=""></div>
                                <div class="img-1 "><img src="images/total (1).png" alt=""></div>
                                <div class="img-1 gum1"> <img src="images/losa1.png" alt=""></div>
                                <div class="img-1  gum2"> <img src="images/allure.png" alt=""></div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!--------SECTION-Thrd--------------------------------->
            <div class="thrd-section">
                <div class="inear-thrd">
                    <div class="thrd-heading">
                        <h2>shop by <span class="design">category</span></h2>
                    </div>
                    <div class="thrd-images">
                        <div class="thrd-main-img-data">
                            <div class="thrd-img-data">
                                <div class="thrd-one-container">
                                    <div class="img-2">
                                        <img src="images/Rectangle 15.png" alt="">
                                    </div>
                                    <div class="thrd-image-txt">
                                        <p>Cleansers</p>
                                    </div>
                                </div>
                                <div class="thrd-one-container">
                                    <div class="img-2">
                                        <img src="images/Rectangle 10.png" alt="">
                                    </div>
                                    <div class="thrd-image-txt">
                                        <p>Toners + Swipes</p>
                                    </div>
                                </div>
                                <div class="thrd-one-container">
                                    <div class="img-2">
                                        <img src="images/Rectangle 11.png" alt="">
                                    </div>
                                    <div class="thrd-image-txt">
                                        <p>Serums</p>
                                    </div>
                                </div>
                                <div class="thrd-one-container">
                                    <div class="img-2">
                                        <img src="images/Rectangle 12.png" alt="">
                                    </div>
                                    <div class="thrd-image-txt">
                                        <p>Moisturizers</p>
                                    </div>
                                </div>
                                <div class="thrd-one-container">
                                    <div class="img-2">
                                        <img src="images/Rectangle 41.png" alt="">
                                    </div>
                                    <div class="thrd-image-txt">
                                        <p>body</p>
                                    </div>
                                </div>

                            </div>
                        </div>
                    </div>

                </div>
            </div>
            <!--------SECTION-FOURTH--------------------------------->
            <div class="section-fourth">
                <div class="inear-four-a">
                    <div class="inear-four">
                        <img src="images/Background_Edit_170242 1.png" alt="">

                    </div>
                    <div class="for-main">
                        <div class="fourth-txt ">
                            <div class="for-flex">
                                <div class="for-heading">
                                    <h2>shop our Bio Peptide <span class="Lovely">Hydrating Lotion</span> </h2>
                                </div>
                                <div class="buttonf">
                                    <div class="textf">SHOP NOW</div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!--------SECTION-Fifth--------------------------------->
            <div class="fifth-section ">
                <div class="inear-fifth">
                    <div class="fifth-heading">
                        <h2>FEATURED <span class="design">PRODUCTS</span> </h2>
                    </div>
                    <div class="main-cart-width">
                        <div class="cart-main-flex">
                            <div class="a">
                                <div class="fifth-cards">
                                    <div class="fifth-img">
                                        <img src="images/bottle.png" alt="">
                                    </div>
                                    <div class="card-data">
                                        <div class="data-flex">
                                            <div class="card-para ">
                                                <p>Bio Peptide <br> Hydrating Lotion</p>
                                            </div>
                                            <div class="stars">
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star_half</span>
                                            </div>
                                            <div class="card-para puwa">
                                                <p>Lorem ipsum dolor sit amet <br>consectetur. </p>
                                            </div>
                                            <div class="price">
                                                <p>$150</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="buttonw">
                                        <div class="textw">ADD TO CART</div>
                                    </div>
                                </div>
                            </div>
                            <div class="a">
                                <div class="fifth-cards">
                                    <div class="fifth-img">
                                        <img src="images/bottle.png" alt="">
                                    </div>
                                    <div class="card-data">
                                        <div class="data-flex">
                                            <div class="card-para  ">
                                                <p>Bio Peptide <br> Hydrating Lotion</p>
                                            </div>
                                            <div class="stars">
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star_half</span>
                                            </div>
                                            <div class="card-para puwa">
                                                <p>Lorem ipsum dolor sit amet <br>consectetur. </p>
                                            </div>
                                            <div class="price">
                                                <p>$150</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="buttonw">
                                        <div class="textw">ADD TO CART</div>
                                    </div>
                                </div>
                            </div>
                            <div class="a">
                                <div class="fifth-cards">
                                    <div class="fifth-img">
                                        <img src="images/bottle.png" alt="">
                                    </div>
                                    <div class="card-data">
                                        <div class="data-flex">
                                            <div class="card-para ">
                                                <p>Bio Peptide <br> Hydrating Lotion</p>
                                            </div>
                                            <div class="stars">
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star_half</span>
                                            </div>
                                            <div class="card-para puwa">
                                                <p>Lorem ipsum dolor sit amet <br>consectetur. </p>
                                            </div>
                                            <div class="price">
                                                <p>$150</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="buttonw">
                                        <div class="textw">ADD TO CART</div>
                                    </div>
                                </div>
                            </div>
                            <div class="a">
                                <div class="fifth-cards">
                                    <div class="fifth-img">
                                        <img src="images/bottle.png" alt="">
                                    </div>
                                    <div class="card-data">
                                        <div class="data-flex">
                                            <div class="card-para ">
                                                <p>Bio Peptide <br> Hydrating Lotion</p>
                                            </div>
                                            <div class="stars">
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star</span>
                                                <span class="material-symbols-outlined star vb">star_half</span>
                                            </div>
                                            <div class="card-para puwa">
                                                <p>Lorem ipsum dolor sit amet <br>consectetur. </p>
                                            </div>
                                            <div class="price">
                                                <p>$150</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="buttonw">
                                        <div class="textw">ADD TO CART</div>
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
            <!--------SECTION-SIXTH--------------------------------->
            <div class="section-six section-width">
                <div class="inear-six">
                    <div class="six-flex">
                        <div class="sec-one">
                            <div class="flex-sixth">
                                <div class="bb">
                                    <img src="images/white.png" alt="">
                                </div>
                                <div class="six-images">
                                    <div class="big">
                                        <img class="" src="images/white 1.png " alt="">
                                    </div>
                                    <div class="small">
                                        <img src="images/face.png" alt="">
                                    </div>

                                </div>
                            </div>
                        </div>
                        <div class="sec-two">
                            <div class="inear-sixth-second">
                                <div class="six-heading">
                                    <h2>OUR <span class="design">Story</span></h2>
                                </div>
                                <div class="six-para">
                                    <p>Mikel Kristi Skincare is formulated and clinically-validated by experts in the
                                        field of cosmetic
                                        dermatology. Developed in Arizona, our products perform in even the harshest of
                                        climates,
                                        proving that if you can have gorgeous skin living in the desert, you can have it
                                        anywhere on
                                        earth.
                                    </p>
                                </div>
                                <div class="six-button">
                                    <div class="textwe">Read More</div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>
            </div>
            <!--------SECTION-SEVEN--------------------------------->
            <div class="seven-clr full-width">
                <div class="seven-section ">
                    <div class="inear-seven">
                        <div class="seven-main-width">
                            <div class="seven-flex">
                                <div class="seven-txt-conainer">
                                    <div class="sec-twoo">
                                        <div class="inear-sixth-second">
                                            <div class="six-heading">
                                                <h2>CHECK OUT THE<span class="design"> Results</span></h2>
                                            </div>
                                            <div class="seven-para">
                                                <p>
                                                    Lorem ipsum dolor sit amet consectetur. Ac egestas ipsum hac
                                                    suspendisse quis risus eu. Tellus id nulla vitae orci. Accumsan
                                                    ullamcorper nisl sit tempus sed. Dignissim metus et tortor elementum
                                                    sed nibh urna.
                                                </p>
                                            </div>
                                            <div class="buttonn">
                                                <div class="textn">READ MORE</div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="seven-slider">
                                    <div class="txt-postion-div">
                                        <div class="inear-seven-slider">
                                            <div class="slider-one set">
                                                <div class="fix fixe"><img src="images/after.png" alt="image1"></div>
                                                <div class="fix fixo"><img src="images/after.png" alt="image1"></div>
                                                <div class="fix fixe"><img src="images/after.png" alt="image1"></div>
                                                <div class="fix fixq"><img src="images/after.png" alt="image1"></div>
                                                <div class="fix fixr"><img src="images/after.png" alt="image1"></div>

                                            </div>
                                        </div>
                                        <div class="after-before-txt">
                                            <h2>BEFORE</h2>
                                        </div>
                                        <div class="after-before-txtt">
                                            <h2>AFTER</h2>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
            <!--------SECTION-EIGHT--------------------------------->
            <div class="section-eight full-width">
                <div class="inear-eight">
                    <div class="eight-flex-heading">
                        <div class="eight-sub-heading">
                            <h4>TESTIMONIAL</h4>
                        </div>
                        <div class="eight-main-heading">
                            <h2>What Our Clients Say!</h2>
                        </div>
                    </div>
                    <div class="eight-slider">
                        <div class="inear-slider">
                            <div class="main-container1 set1">
                                <div class="fix2 fixe1">
                                    <div class="eight-cart">
                                        <div class="eight-cart-flex">
                                            <div class="cart-para">
                                                <p>"Ahasellus pellentesque Proin tempus tempor diam, non pellentesque
                                                    quam ornare vel.
                                                    Aenean laoreet. Praesent in nunc vel urna consequat mattis eget vel
                                                    libero.
                                                    ." </p>
                                            </div>
                                            <div class="cart-icons">
                                                <span class="check">
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                </span>
                                            </div>
                                            <div class="cart-images">
                                                <div class="image-flex">
                                                    <div class="cart-img">
                                                        <img src="images/cart-img.png" alt="">
                                                    </div>
                                                    <div class="ei-cart-image-txt">
                                                        <div class="ai">
                                                            <h6>XYZ, Core Collection</h6>
                                                        </div>
                                                        <div class="ia">
                                                            <p>6 months ago</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="fix2 fixo1">
                                    <div class="eight-cart">
                                        <div class="eight-cart-flex">
                                            <div class="cart-para">
                                                <p>"Ahasellus pellentesque Proin tempus tempor diam, non pellentesque
                                                    quam ornare vel.
                                                    Aenean laoreet. Praesent in nunc vel urna consequat mattis eget vel
                                                    libero.
                                                    " </p>
                                            </div>
                                            <div class="cart-icons">
                                                <span class="check">
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                </span>
                                            </div>
                                            <div class="cart-images">
                                                <div class="image-flex">
                                                    <div class="cart-img">
                                                        <img src="images/cart-img.png" alt="">
                                                    </div>
                                                    <div class="ei-cart-image-txt">
                                                        <div class="ai">
                                                            <h6>XYZ, Core Collection</h6>
                                                        </div>
                                                        <div class="ia">
                                                            <p>6 months ago</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="fix2 fixe1">
                                    <div class="eight-cart">
                                        <div class="eight-cart-flex">
                                            <div class="cart-para">
                                                <p>"Ahasellus pellentesque Proin tempus tempor diam, non pellentesque
                                                    quam ornare vel.
                                                    Aenean laoreet. Praesent in nunc vel urna consequat mattis eget vel
                                                    libero.
                                                    " </p>
                                            </div>
                                            <div class="cart-icons">
                                                <span class="check">
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                </span>
                                            </div>
                                            <div class="cart-images">
                                                <div class="image-flex">
                                                    <div class="cart-img">
                                                        <img src="images/cart-img.png" alt="">
                                                    </div>
                                                    <div class="ei-cart-image-txt">
                                                        <div class="ai">
                                                            <h6>XYZ, Core Collection</h6>
                                                        </div>
                                                        <div class="ia">
                                                            <p>6 months ago</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="fix2 fixq1">
                                    <div class="eight-cart">
                                        <div class="eight-cart-flex">
                                            <div class="cart-para">
                                                <p>"Ahasellus pellentesque Proin tempus tempor diam, non pellentesque
                                                    quam ornare vel.
                                                    Aenean laoreet. Praesent in nunc vel urna consequat mattis eget vel
                                                    libero.
                                                    " </p>
                                            </div>
                                            <div class="cart-icons">
                                                <span class="check">
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                </span>
                                            </div>
                                            <div class="cart-images">
                                                <div class="image-flex">
                                                    <div class="cart-img">
                                                        <img src="images/cart-img.png" alt="">
                                                    </div>
                                                    <div class="ei-cart-image-txt">
                                                        <div class="ai">
                                                            <h6>XYZ, Core Collection</h6>
                                                        </div>
                                                        <div class="ia">
                                                            <p>6 months ago</p>
                                                        </div>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                                <div class="fix2 fixr1">
                                    <div class="eight-cart">
                                        <div class="eight-cart-flex">
                                            <div class="cart-para">
                                                <p>"Ahasellus pellentesque Proin tempus tempor diam, non pellentesque
                                                    quam ornare vel.
                                                    Aenean laoreet. Praesent in nunc vel urna consequat mattis eget vel
                                                    libero.
                                                    " </p>
                                            </div>
                                            <div class="cart-icons">
                                                <span class="check">
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                    <span class="material-symbols-outlined star">star</span>
                                                </span>
                                            </div>
                                            <div class="cart-images">
                                                <div class="image-flex">
                                                    <div class="cart-img">
                                                        <img src="images/cart-img.png" alt="">
                                                    </div>
                                                    <div class="ei-cart-image-txt">
                                                        <div class="ai">
                                                            <h6>XYZ, Core Collection</h6>
                                                        </div>
                                                        <div class="ia">
                                                            <p>6 months ago</p>
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
            </div>
            <!--------SECTION-NINE--------------------------------->
            <div class="section-nine section-width">
                <div class="inear-nine">
                    <div class="nine-one">
                        <div class="nine-main-heading">
                            <h2>our latest blogs</h2>
                        </div>
                        <div class="nine-sub-heading">
                            <p>Lorem ipsum dolor sit amet consectetur. Euismod id pulvinar ut nunc feugiat purus tortor
                                ut.</p>
                        </div>
                    </div>
                    <div class="nineth-two">
                        <div class="nine-two">
                            <div class="two-flex">
                                <div class="image-nine">
                                    <img src="images/9 1.png" alt="">
                                </div>
                                <div class="nine-txt">
                                    <div class="nine-first">
                                        <p>THE BASIC OF SKINCARE | <br>
                                            PART TWO</p>
                                    </div>
                                    <div class="nine-sec">
                                        <p>Lorem ipsum dolor sit amet consectetu... <span class="red">READ <br>
                                                MORE</span>
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="nine-two">
                            <div class="two-flex">
                                <div class="image-nine">
                                    <img src="images/9 2.png" alt="">
                                </div>
                                <div class="nine-txt">
                                    <div class="nine-first">
                                        <p>The basic of skincare | <br>
                                            Part two</p>
                                    </div>
                                    <div class="nine-sec">
                                        <p>Lorem ipsum dolor sit amet consectetu... <span class="red">READ <br>
                                                MORE</span>
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="nine-two">
                            <div class="two-flex">
                                <div class="image-nine">
                                    <img src="images/9 3g.png" alt="">
                                </div>
                                <div class="nine-txt">
                                    <div class="nine-first">
                                        <p>The basic of skincare | <br>
                                            Part two</p>
                                    </div>
                                    <div class="nine-sec">
                                        <p>Lorem ipsum dolor sit amet consectetu... <span class="red">READ <br>
                                                MORE</span>
                                        </p>
                                    </div>
                                </div>
                            </div>
                        </div>

                    </div>
                </div>
            </div>
            <!--------SECTION-TENTH--------------------------------->
            <div class="section-ten">
                <div class="inear-section-ten">
                    <div class="ten-section-first">
                        <div class="ten-main-heading">
                            <h2>our community</h2>
                        </div>
                        <div class="ten-para">
                            <p>lorem ipsum dolor sit amet consectetur. Euismod id pulvinar ut nunc feugiat purus tortor
                                ut.</p>
                        </div>
                    </div>
                    <div class="section-ten-sec">
                        <div class="tex-sec-main-flex">
                            <div class="inear-ten-sec">
                                <div class="inear-ten-sec-flex">
                                    <div class="ten-inear-first">
                                        <img src="images/flower.png" alt="">
                                    </div>
                                    <div class="ten-txt-one">
                                        <div class="ten-inear-flex">
                                            <div class="ten-inear-image">
                                                <img src="images/leave.png" alt="">
                                            </div>
                                            <div class="teninear-para">
                                                <h3>LOYALTY PROGRAM</h3>
                                            </div>
                                            <div class="ten-inear-button">
                                                <a href="#">Learn more</a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>
                            <div class="inear-ten-sec">
                                <div class="inear-ten-sec-flex">
                                    <div class="ten-inear-first">
                                        <img src="images/bot.png" alt="">
                                    </div>
                                    <div class="ten-txt-one">
                                        <div class="ten-inear-flex">
                                            <div class="ten-inear-image">
                                                <img src="images/leave.png" alt="">
                                            </div>
                                            <div class="teninear-para">
                                                <h3>LOYALTY PROGRAM</h3>
                                            </div>
                                            <div class="ten-inear-button">
                                                <a href="#">Learn more</a>
                                            </div>
                                        </div>
                                    </div>
                                </div>
                            </div>

                        </div>
                    </div>

                </div>
            </div>
            <!--------SECTION-ELEVEN--------------------------------->
            <div class="section-eleven">
                <div class="inear-elven">
                    <div class="eleven-heading">
                        <div class="ele-parar">
                            <p>INSTASHOP</p>
                        </div>
                        <div class="eleven-heading">
                            <h4>@mikelkristi</h4>
                        </div>
                    </div>
                    <div class="ele-images">
                        <div class="ele-img-flex">
                            <div class="ele"><img src="images/flor.png" alt=""></div>
                            <div class="ele"><img src="images/hand.png" alt=""></div>
                            <div class="ele"><img src="images/view.png" alt=""></div>
                            <div class="ele"><img src="images/read.png" alt=""></div>
                        </div>
                    </div>
                </div>
            </div>
            <!--------SECTION-Twelve--------------------------------->
            <div class="section-clr">
                <div class="section-twelve">
                    <div class="inear-twel">
                        <div class="twel-width">
                            <div class="twel-flex">
                                <div class="twel-one">
                                    <div class="twel-image"><img src="images/colo.png" alt=""></div>
                                    <div class="twel-sub-para">
                                        <p>CRUELTY FREE</p>
                                    </div>
                                </div>
                                <div class="twel-one">
                                    <div class="twel-image"><img src="images/colo.png" alt=""></div>
                                    <div class="twel-sub-para">
                                        <p>CRUELTY FREE</p>
                                    </div>
                                </div>
                                <div class="twel-one ww">
                                    <div class="twel-image"><img src="images/colo.png" alt=""></div>
                                    <div class="twel-sub-para">
                                        <p>CRUELTY FREE</p>
                                    </div>
                                </div>
                                <div class="twel-one ww">
                                    <div class="twel-image"><img src="images/colo.png" alt=""></div>
                                    <div class="twel-sub-para">
                                        <p>CRUELTY FREE</p>
                                    </div>
                                </div>
                                <div class="twel-one ww">
                                    <div class="twel-image"><img src="images/colo.png" alt=""></div>
                                    <div class="twel-sub-para">
                                        <p>CRUELTY FREE</p>
                                    </div>
                                </div>

                            </div>
                        </div>

                    </div>
                </div>
            </div>
            <!--------FOOTER--------------------------------->
            <div class="footer-color">
                <div class="footer">
                    <div class="inside-footer">
                        <div class="footer-flex">
                            <div class="footer-one">
                                <div class="footer-one-flex  ">
                                    <div class="sub-head vi">
                                        <h3>MAIN MENU</h3>
                                    </div>
                                    <div class="sub-bulit">
                                        <div class="sub-bulit"><a href="#">HOME</a></div>
                                        <div class="sub-bulit"><a href="#">SHOP</a></div>
                                        <div class="sub-bulit"><a href="#">BESt SELLERS</a></div>
                                        <div class="sub-bulit"><a href="#">EXPLORE</a></div>
                                        <div class="sub-bulit"><a href="#">OUR BLOG</a></div>
                                        <div class="sub-bulit"><a href="#">ABOUT</a></div>
                                        <div class="sub-bulit"><a href="#">PRESS</a></div>

                                    </div>
                                </div>
                            </div>
                            <div class="footer-one">
                                <div class="footer-one-flex ">
                                    <div class="sub-head vi">
                                        <h3>POLICIES</h3>
                                    </div>
                                    <div class="sub-bulit">
                                        <div class="sub-bulit"><a href="#">Refund & Exchange Policy</a></div>
                                        <div class="sub-bulit"><a href="#">Privacy Policy</a></div>
                                        <div class="sub-bulit"><a href="#">Terms of services</a></div>
                                        <div class="sub-bulit"><a href="#">Shipping Policy</a></div>
                                        <div class="sub-bulit"><a href="#">Growers</a></div>
                                        <div class="sub-bulit"><a href="#">Landscapers</a></div>


                                    </div>
                                </div>
                            </div>
                            <div class="footer-one">
                                <div class="footer-one-flex ">
                                    <div class="sub-head vi">
                                        <h3>COMMUNITY</h3>
                                    </div>
                                    <div class="sub-bulit">
                                        <div class="sub-bulit"><a href="#">Loyality rewards</a></div>
                                        <div class="sub-bulit"><a href="#">subscription program</a></div>
                                        <div class="sub-bulit"><a href="#">affiliate</a></div>
                                        <div class="sub-bulit"><a href="#">wholesale</a></div>
                                    </div>
                                </div>
                            </div>
                            <div class="footer-onee">
                                <div class="footer-one-flex ">
                                    <div class="fooeter-sub-section">
                                        <div class="sub-foter-clr">
                                            <div class="f-sub-flex">
                                                <div class="ki">
                                                    <div class="f-sub-head">
                                                        <h3>newsletter</h3>
                                                    </div>
                                                    <div class="f-sub-para">
                                                        <p>Get news and offers to your inbox</p>
                                                    </div>
                                                </div>
                                                <div class="ik">
                                                    <div class="inputt">
                                                        <input type="email" name="email" id="" placeholder="Email">
                                                    </div>
                                                    <div class="f-button">
                                                        <a href="#">SEND</a>
                                                    </div>
                                                </div>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="footer-icons">
                                        <div class="icons-flex">
                                            <div class="icon-f">
                                                <img src="images/fb.png" alt="">
                                            </div>
                                            <div class="icon-f">
                                                <img src="images/insta.png" alt="">
                                            </div>
                                            <div class="icon-f">
                                                <img src="images/pre.png" alt="">
                                            </div>
                                            <div class="icon-f">
                                                <img src="images/video.png" alt="">
                                            </div>

                                        </div>
                                    </div>
                                    <div class="footer-number">
                                        <div class="mk">
                                            <div class="f-number-icon"><img src="images/call.png" alt=""></div>
                                            <div class="f-number-para">
                                                <p>0367452819</p>
                                            </div>
                                        </div>
                                    </div>
                                    <div class="mk">
                                        <div class="f-number-iconn"><img src="images/msg.png" alt=""></div>
                                        <div class="f-number-para">
                                            <p>mikelkristi@mail.com</p>
                                        </div>
                                    </div>
                                </div>
                            </div>
                        </div>
                        <div class="footer-line">
                            <p>©2023 Mikel Kristi Skincare | All Rights Reserved | Sitemap</p>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
















































































    <script type="text/javascript" src="slick.js"></script>
    <script type="text/javascript" src="slick.min.js"></script>
    <script>

        $('.set').slick({
            dots: false,
            infinite: true, // Overall slider is not infinite
            speed: 300,
            slidesToShow: 2,
            slidesToScroll: 1,
            prevArrow: '<button type="button" class="slick-prev hi">Previous</button>',
            nextArrow: '<button type="button" class="slick-next hi">Next</button>',
            responsive: [
                {
                    breakpoint: 1024,
                    settings: {
                        slidesToShow: 2,
                        slidesToScroll: 1,
                        dots: true // Dots are still available
                    }
                },
                {
                    breakpoint: 600,
                    settings: {
                        slidesToShow: 2,
                        slidesToScroll: 2,
                        infinite: true // At this breakpoint, slider becomes infinite again
                    }
                },
                {
                    breakpoint: 480,
                    settings: {
                        slidesToShow: 2,
                        slidesToScroll: 1,
                        infinite: true // At this breakpoint, slider becomes infinite again
                    }
                }
            ]
        });
        $('.set1').slick({
            dots: true,
            infinite: true,
            speed: 300,
            slidesToShow: 3,
            slidesToScroll: 1,
            centerMode: true,
            prevArrow: '<button type="button" class="slick-prev ho">Previous</button>',
            nextArrow: '<button type="button" class="slick-next hy">Next</button>',
            responsive: [
                {
                    breakpoint: 1024,
                    settings: {
                        slidesToShow: 1,
                        slidesToScroll: 1,
                        infinite: true,
                        dots: true
                    }
                },
                {
                    breakpoint: 600,
                    settings: {
                        slidesToShow: 1,
                        slidesToScroll: 1
                    }
                },
                {
                    breakpoint: 480,
                    settings: {
                        slidesToShow: 1,
                        slidesToScroll: 1
                    }
                }
            ]
        });
    </script>

</body>

</html>

// ----------------------------Css Code-----------//
* {
    padding: 0;
    margin: 0;
}

@font-face {
    font-family: 'Just Lovely';
    src: local('Just Lovely Regular'), local('Just-Lovely-Regular'),
        url('JustLovely.woff2') format('woff2'),
        url('JustLovely.woff') format('woff'),
        url('JustLovely.ttf') format('truetype');
    font-weight: 400;
    font-style: normal;
}

.full-width {
    /* max-width: 1400px;
    margin: 0 auto; */
}

.section-width {
    width: 80%;
    margin: 0 auto;
}

.topbar-clr {
    background-color: #726E6A;
}

.topbar {
    width: 87%;
    margin: 0 auto;
}

.inear-top {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
    height: 30px;
}

.top-text {
    width: 17%;
}

.top-text p {
    color: #ffffff;
    font-size: 12px;
    line-height: 16px;
    font-style: normal;
    font-weight: 300;
    font-family: "Raleway", sans-serif;
    letter-spacing: 1.0px;
    text-transform: uppercase;
    text-align: center;
}

.top-login {
    width: 15%;
}

.top-login a {
    color: #ffffff;
    font-size: 13px;
    line-height: 16px;
    font-weight: 400;
    font-family: "Raleway", sans-serif;
}

.tip {
    display: flex;
    justify-content: end;
    align-items: center;
    column-gap: 13px;
}

/* -------------NAVBAR---------------------------- */
.header {
    width: 85%;
    margin: 0 auto;
}

.inear-header {
    display: flex;
    justify-content: space-between;
    align-items: center;
    height: 82px;
}

.logo {
    width: 15%;
}

.logo-image {
    width: 100%;
    line-height: 0;
}

.logo-image img {
    width: 100%;
}

.navbar {
    width: 50%;
    padding-bottom: 10px;
}

.nav {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.op {
    width: 15%;
}

.op a {
    text-decoration: none;
    color: #454545;
    font-size: 15px;
    font-family: "Raleway", sans-serif;
    font-weight: 500;
}

.op a:hover {
    font-size: 15px;
    font-weight: 700;
    color: #6D1A38;
}

.active {
    color: #6D1A38;
}

.navbar .op a.active {
    border-bottom: 1px solid #6D1A38;
    padding-bottom: 36px;
    font-weight: bold;
    color: #6D1A38;
}

.icons {
    width: 22%;
}

.inear-icon {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.input {
    display: flex;
    position: relative;
    justify-content: center;
    align-items: center;
}

input[type="text"] {
    border: none;
    border-radius: 15px;
    padding: 6px 6px;
    width: 96%;
    background-color: #F9F7F2;
}

.b {
    position: absolute;
    top: 4px;
    bottom: 0;
    left: 156px;
    right: 0;
    color: #6D1A38;
}

.material-symbols-outlined {
    font-size: 23px !important;
}
span.material-symbols-outlined.star.vb {
    font-size: 15px !important;
}

.heart {
    color: #6D1A38;
    line-height: 0;
}

.cart {
    color: #6D1A38;
    line-height: 0;
}

.nav-header {
    display: block;
}

.sidepanel {
    width: 0;
    position: fixed;
    z-index: 1;
    height: 100%;
    top: 0;
    right: 0;
    background-color: white;
    overflow-x: hidden;
    transition: 0.5s;
    padding-top: 60px;
}

.sidepanel a {
    padding: 8px 8px 8px 32px;
    text-decoration: none;
    font-size: 14px;
    color: #818181;
    display: block;
    transition: 0.3s;
}

.sidepanel a:hover {
    color: #f1f1f1;
}

.sidepanel .closebtn {
    position: absolute;
    top: 10px;
    left: 0px;
    font-size: 26px;
    color: black;
    font-weight: 800;
}

.openbtn {
    float: right;
    font-size: 22px;
    cursor: pointer;
    color: black;
    padding: 10px 15px;
    border: none;
    background-color: transparent;

}

.openbtn:hover {
    font-size: 22px;
}

/* ---------------SECTION-ONE------------------------------------ */
.section-one {
    background-color: #D9AEB2;


}

.one-data {
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.one-image {
    width: 55%;
    padding-top: 20px;
}

.images {
    width: 100%;
    line-height: 0;
}

.images img {
    width: 100%;
}

.one-txt {
    width: 45%;
}

.flex-txt {
    display: flex;
    flex-direction: column;
    justify-content: center;
    row-gap: 20px;
}

.one-main {
    width: 100%;
}

.one-main h1 {
    font-family: "Raleway", sans-serif;
    font-size: 42px;
    line-height: 50px;
    font-weight: 600;
    color: #ffffff;
    letter-spacing: 1.0px;
    word-spacing: 6px;
}

.one-para {
    width: 81%;
}

.one-para p {
    color: #ffffffbe;
    font-size: 13px;
    font-weight: 400;
    line-height: 23px;
    letter-spacing: 0.3px;
    word-spacing: 0px;
}

.one-button {
    width: 27%;
    border: 1px solid #6D1A38;
    background-color: transparent;
    padding: 7px 0px;
    text-align: center;
    cursor: pointer;
    background: linear-gradient(to right, #6D1A38 50%, #D9AEB2 50%);
    background-size: 200% 100%;
    background-position: right bottom;
    transition: all .5s ease-out;
}

.one-button:hover {
    background-position: left bottom;

}

.one-button a {
    color: #6D1A38;
    font-size: 12px;
    text-decoration: none;
    transition: all .6s ease-out;

}

.one-button a:hover {
    color: white;
}

/* ----------SECTION-TWO------------------------------------- */
.section-two {
    width: 85%;
    margin: 0 auto;
    padding: 20px 0;
}

.inear-two {
    width: 100%;
    padding-top: 30px;
    padding-bottom: 20px;
}

.sec-txt {
    width: 100%;
    padding-top: 25px;
    padding-bottom: 30px;
}

.img-1.gum {
    width: 7%;
}

.sec-txt h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 33px;
    line-height: 50px;
    font-weight: 600;
    text-align: center;
    letter-spacing: 1px;
    word-spacing: 4px;
}

.sec-images {
    width: 100%;
    padding-bottom: 20px;
}

.sec-images-flex {
    padding: 20px 0;
}

.images-data {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding-bottom: 20px;
}

.img-1 {
    width: 15%;
}

.img-1.gum1 {
    width: 12%;
}

.img-1.gum2 {
    width: 9%;
}

.img-1 img {
    width: 100%;
}

/* ----------SECTION-Thrd------------------------------------- */
.thrd-section {
    width: 100%;
    padding-top: 20px;
}

.inear-thrd {
    width: 100%;
    padding-bottom: 20px;
}

.thrd-heading {
    width: 100%;
    padding-bottom: 20px;
}

.thrd-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 29px;
    line-height: 50px;
    font-weight: 600;
    text-align: center;
    letter-spacing: 1.3px;
    text-transform: uppercase;
}

.thrd-main-img-data {
    width: 100%;
}

.thrd-images {
    width: 100%;
    padding-top: 20px;
}

.thrd-img-data {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding-bottom: 20px;

}

.img-2 {
    width: 100%;
    line-height: 0;

}

.thrd-main-img-data {
    width: 100%;
    padding-bottom: 20px;
}

.thrd-one-container {
    transition: width 2s;
    transition-timing-function: ease-out;
    width: 19%;

}

.img-2 img {
    width: 100%;

}

.thrd-image-txt {
    width: 100%;
}

.thrd-image-txt p {
    text-align: center;
    padding-top: 20px;
    font-size: 20px;
    text-transform: uppercase;
    color: rgba(0, 0, 0, 0.712);
    font-weight: 600;
    letter-spacing: 1.6px;
}

.thrd-txt {
    width: 100%;
}

/* ----------SECTION-FOURTH------------------------------------- */
.section-fourth {
    width: 100%;
    padding-top: 20px;
}

.inear-four {
    width: 100%;
    line-height: 0;
    padding-bottom: 20px;
}

.inear-four-a {
    width: 100%;
    position: relative;
    padding-bottom: 20px;
}

.inear-four img {
    width: 100%;
}

.for-main {
    position: absolute;
    top: 0;
    bottom: 0;
    left: 0;
    right: 0;
}

.fourth-txt {
    width: 50%;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

.for-flex {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    row-gap: 40px;
}

.for-heading {
    width: 60%;
}

.for-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 37px;
    line-height: 50px;
    font-weight: 500;
    text-align: center;
    letter-spacing: 1.3px;
    text-transform: uppercase;
}

span.Lovely {
    font-family: just lovely;
    font-size: 60px;
    text-transform: capitalize;
}




.buttonf {
    border: 1px solid #6D1A38;
    border-bottom: 2px solid #6D1A38;
    border-radius: 1px;
    width: 140px;
    height: 30px;
    display: block;
    background: linear-gradient(to right, #6D1A38 50%, transparent 50%);
    background-size: 200% 100%;
    background-position: right bottom;
    transition: all .5s ease-out;
}

.buttonf:hover {
    background-position: left bottom;
}

.textf {
    text-align: center;
    font-size: 12px;
    line-height: 30px;
    color: black;
    transition: all .6s ease-out;
    display: block;
}

.textf:hover {
    color: white;
}

/*----------SECTION-Fifth------------------------------------- */
.fifth-section {
    width: 85%;
    padding: 20px 0px;
    margin: 0 auto;
}

.inear-fifth {
    padding: 20px 0px;
}

.fifth-heading {
    width: 100%;
    padding: 20px 0px;
}

.fifth-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 29px;
    line-height: 50px;
    font-weight: 600;
    text-align: center;
    letter-spacing: 1.3px;
}

.main-cart-width {
    width: 100%;
    padding-top: 20px;
    padding-bottom: 20px;
}

.cart-main-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 30px;
}

.a {
    width: 100%;

}

.a input::placeholder {
    color: #81818169;
}

.fifth-cards {
    width: 100%;
}

.fifth-img {
    width: 77%;
    border: 2px solid #D8AEB2;
    padding: 25px;

}

.fifth-img img {
    width: 100%;

}

.fifth-cards {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    row-gap: 20px;
    flex-wrap: wrap;
}

.card-para.puwa p {
    font-size: 8px;
}

.card-data {
    width: 100%;
}

.data-flex {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    row-gap: 13px;
}

.card-para {
    width: 100%;
}

.card-para p {
    font-size: 10px;
    color: rgba(0, 0, 0, 0.788);
    text-align: center;
    font-family: "Raleway", sans-serif;
    font-weight: 700;
    line-height: 2.2;
    letter-spacing: 1.3px;
    text-transform: uppercase;
}

.material-symbols-outlined {
    font-family: 'Material Symbols Outlined';
    font-weight: normal;
    font-style: normal;
    font-size: 15px;
    line-height: 1;
    letter-spacing: normal;
    text-transform: none;
    display: inline-block;
    white-space: nowrap;
    word-wrap: normal;
    direction: ltr;
    -webkit-font-feature-settings: 'liga';
    -webkit-font-smoothing: antialiased;
}

.star {
    color: #D8AEB2;
}

.stars {
    width: 100%;
    text-align: center;
}

.price {
    width: 100%;
}

.price p {
    color: #6D1A38;
    font-size: 14px;
    text-align: center;
    font-weight: 700;
}

.buttonw {
    border: 1px solid #6D1A38;
    border-bottom: 2px solid #6D1A38;
    border-radius: 1px;
    width: 260px;
    height: 30px;
    display: block;

    background: linear-gradient(to right, #6D1A38 50%, white 50%);
    background-size: 200% 100%;
    background-position: right bottom;
    transition: all .5s ease-out;
}

.buttonw:hover {
    background-position: left bottom;
}

.textw {
    text-align: center;
    font-size: 12px;
    line-height: 30px;
    color: black;
    transition: all .6s ease-out;
    display: block;
    font-family: 'Raleway';
}

.textw:hover {
    color: white;
}

/*----------SECTION-SIXTH------------------------------------- */
.section-six {
    padding-top: 20px;
    padding-bottom: 30px;
}

.inear-six {
    padding-top: 20px;
    padding-bottom: 30px;
    width: 100%;
}

.six-flex {
    display: flex;
    flex-direction: row;
    justify-content: space-between;
    align-items: center;
}

.sec-one {
    width: 65%;
}

.sec-two {
    width: 30%;
}

.flex-sixth {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: row;
    column-gap: 15px;
}

.bb {
    width: 50%;
}

.bb img {
    width: 100%;
}

.six-images {
    width: 52%;
}

.big {
    width: 100%;
}

.big img {
    width: 100%;
}

.small {
    width: 90%;
}

.small img {
    width: 100%;
}

.inear-sixth-second {
    display: flex;
    justify-content: center;
    flex-direction: column;
    row-gap: 40px;
}

.six-heading {
    width: 100%;
}

.six-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 32px;
    line-height: 50px;
    font-weight: 600;
    letter-spacing: 1.5px;
}

.six-para {
    width: 100%;
}

.six-para p {

    font-size: 20px;
    text-align: justify;
    font-weight: 300;
}
span.design {
    font-size: 28px;
    font-weight: 600;
}

.six-button {
    border: 1px solid #6D1A38;
    border-radius: 1px;
    width: 145px;
    height: 45px;
    display: block;

    background: linear-gradient(to right, #6D1A38 50%, white 50%);
    background-size: 200% 100%;
    background-position: right bottom;
    transition: all .5s ease-out;
}

.six-button:hover {
    background-position: left bottom;
}

.textwe {
    text-align: center;
    font-size: 14px;
    line-height: 45px;
    color: #6D1A38;
    transition: all .6s ease-out;
    display: block;
}

.textwe:hover {
    color: white;
}

/*----------SECTION-SEVEN------------------------------------- */
.seven-clr {
    background-color: #F7F6F2;
    padding: 30px 20px;
    margin-top: 20px;
    margin-bottom: 30px;
}

.seven-section {
    width: 90%;
    margin: 0 auto;
    padding-top: 30px;
    padding-bottom: 20px;
}

.inear-seven {
    padding-top: 20px;
    padding-bottom: 20px;
}

.seven-main-width {
    width: 100%;
    padding-bottom: 30px;
}

.seven-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 20px;
    flex-wrap: wrap;
    padding-top: 20px;
}

.sec-twoo {
    width: 66%;
}

.seven-txt-conainer {
    width: 26%;
}

.buttonn {
    border: 1px solid #6D1A38;
    border-bottom: 2px solid #6D1A38;
    border-radius: 1px;
    width: 140px;
    height: 40px;
    display: block;
    background: linear-gradient(to right, #6D1A38 50%, transparent 50%);
    background-size: 200% 100%;
    background-position: right bottom;
    transition: all .5s ease-out;
  }
  
  .buttonn:hover {
    background-position: left bottom;
  }
  
  .textn {
    text-align: center;
    font-size: 12px;
    line-height: 40px; 
    color: black;
    transition: all .6s ease-out;
    display: block;
  }
  
  .textn:hover {
    color: white;  
  }

.seven-slider {
    width: 73%;
}

.seven-para {
    width: 100%;
}

.seven-para p {
    font-size: 20px;
    text-align: justify;
    font-weight: 300;
}

.txt-postion-div {
    position: relative;
    width: 100%;
}

.inear-seven-slider {
    width: 100%;
}

.slider-one {}

.slick-slide img {
    display: block;
    width: 100%;
}
.slick-initialized .slick-slide {
    display: block;
    margin-left: 14px;
}

.fix {
    display: block;

}

.fixe img {
    width: 100%;
}

.slick-prev,
.slick-next {
    font-size: 0;
    line-height: 0;
    position: absolute;
    top: 56% !;
    display: block;
    width: 2%;
    height: 26px;
    padding: 0;
    -webkit-transform: translate(0, -50%);
    -ms-transform: translate(0, -50%);
    transform: translate(0, -50%);
    cursor: pointer;
    background: transparent !important;

    outline: none;

}

.slick-prev:before,
.slick-next:before {
    font-family: 'slick';
    font-size: 20px;
    line-height: 1;
    opacity: .75;
    border: 2px solid #6D1A38 !important;
    color: #6D1A38 !important;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
    /* background-color: transparent; */

}

.slick-prev {}

.after-before-txt {
    position: absolute;
    top: 310px;
    left: 38px;
    bottom: 0;
    right: 0;
    display: inline-block;
}

.after-before-txt h2 {
    color: #ffffff;
    display: inline-block;
    font-size: 20px;
    font-weight: 400;

}

.after-before-txtt {
    position: absolute;
    top: 310px;
    left: 524px;
    bottom: 0;
    right: 0;
}

.after-before-txtt h2 {
    color: #ffffff;
    display: inline-block;
    font-size: 20px;
    font-weight: 400;

}
.slick-initialized .slick-slide {
    display: block;
    margin-left: 10px;
}

/*----------SECTION-EIGHT------------------------------------ */
.section-eight {
    padding-top: 20px;
    width: 100%;
}

.inear-eight {
    width: 80%;
    margin: 0 auto;
    padding-bottom: 20px;
    padding-top: 20px;
}

.eight-flex-heading {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    row-gap: 10px;
    padding-bottom: 20px;
    padding-top: 20px;
}

.eight-sub-heading {
    width: 100%;
}

.eight-sub-heading h4 {
    color: #454545;
    font-size: 16px;
    font-weight: 100;
    font-style: normal;
    text-align: center;
}

.eight-main-heading {
    width: 100%;
}

.eight-main-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 29px;
    line-height: 50px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-align: center;
    text-transform: uppercase;
}

.eight-slider {
    width: 100%;
}

.inear-slider {
    width: 100%;
    margin: 0 auto;
}

.eight-cart {
    width: 100%;
    margin: 0 auto;
    padding-top: 20px;
    border: 2px solid white;
    border-radius: 8px;
}

.eight-cart-flex {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    row-gap: 24px;
    flex-wrap: wrap;
}

.cart-para {
    width: 75%;
}

.cart-para p {
    color: #66666666;
    font-size: 16px;
    line-height: 1.3;
    font-style: normal;
}

.cart-icons {
    width: 45%;
    font-size: 37px;
}

.cart-images {
    width: 60%;
}

.cart-image img {
    width: 100%;
}

.image-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.cart-img {
    width: 17%;
}

.ei-cart-image-txt {
    width: 75%;
}

.ai {
    width: 100%;
}

.ai h6 {
    font-size: 13px;
    font-style: normal;
    line-height: 1.7;
    font-weight: 600;
}

.ia {
    width: 100%;
}

.ia p {
    color: #66666666;
    font-size: 17px;
    font-style: normal;
}

.slick-dots li button:before {
    font-size: 22px !important;
}

.ho {
    display: none !important;
}

.hy {
    display: none !important;
}

.main-container1 {
    width: 90%;
    margin: 0 auto;
}

.fix1 {
    display: block;
    width: 90%;
    margin: 0 auto;
}

/*----------SECTION-NINTH------------------------------------ */
.section-nine {
    width: 100%;
    padding: 20px 0;
    margin-top: 20px;
}

.inear-nine {
    width: 97%;
    margin: 0 auto;
    padding-top: 40px;
    margin-top: 20px;
}
.nine-one {
    width: 100%;
    padding-top: 30px;
}

.nine-main-heading {
    width: 90%;
}

.nine-main-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 29px;
    line-height: 50px;
    font-weight: 600;
    letter-spacing: 1.5px;
    text-align: center;
    padding-bottom: 10px;
    text-transform: uppercase;
}

.nine-sub-heading {
    width: 95%;
    padding-bottom: 20px;
}

.nine-sub-heading p {
    text-align: center;
    font-size: 22px;
    color: #726E6A;
}

.nineth-two {
    width: 100%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding-bottom: 40px;
}

.two-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    row-gap: 20px;
}

.nine-two {
    width: 32%;
    padding-top: 20px;
}

.nine-card-one {
    width: 100%;
}

.image-nine {
    width: 100%;
    line-height: 0;
}

.image-nine img {
    width: 100%;
}

.nine-txt {
    width: 100%;
}

.nine-first {
    width: 100%;
}

.nine-first p {
    font-size: 20px;
    font-style: normal;
    font-weight: 600;
    line-height: normal;
    padding-bottom: 6px;
    font-family: 'Raleway';
    color: #383838;
    letter-spacing: 1.9px;
}

.nine-sec {
    width: 100%;
}

.nine-sec p {
    font-size: 15px;
    font-style: normal;
    line-height: normal;
    font-weight: 500;
    padding-bottom: 6px;
    font-family: 'Raleway';
    color: #383838;
    letter-spacing: 1.4px;
}

.red {
    color: #6D1A38;
    font-weight: 700;
    font-style: italic;
    font-size: 15px;
}

/*----------SECTION-TENTH------------------------------------ */
.section-ten {
    width: 100%;
    padding-top: 30px;
    padding-bottom: 20px;
}

.inear-section-ten {
    width: 85%;
    margin: 0 auto;
    padding: 20px 0;
    margin-top: 20px;
}

.rb {
    width: 100%;
}

.ten-section-first {
    width: 100%;
    padding-top: 20px;
}

.ten-main-heading {
    width: 95%;
    padding-top: 20px;
}

.ten-main-heading h2 {
    font-family: "Raleway", sans-serif;
    color: #6D1A38;
    font-size: 29px;
    line-height: 50px;
    font-weight: 700;
    letter-spacing: 1.5px;
    text-align: center;
    padding-bottom: 8px;
    text-transform: uppercase;
}

.ten-para {
    width: 95%;
}

.ten-para p {
    color: #726E6A;
    font-size: 19px;
    font-style: normal;
    font-weight: 500;
    line-height: normal;
    text-align: center;
    font-family: 'raleway';
}

.ten-section-image {
    width: 100%;
    padding: 20px 0;
    position: relative;
}

.ten-image-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 20px 0;
}

.ten-section-image {
    width: 100%;
}

.tex-sec-main-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 20px 0;
}

.ten-image img {
    width: 100%;
}

.section-ten-sec {
    width: 100%;
    padding: 20px 0;
}

.inear-ten-sec {
    width: 49%;
    position: relative;
}

.inear-ten-sec-flex {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.ten-inear-first {
    width: 100%;
    line-height: 0;
}

.ten-inear-first img {
    width: 100%;
}

.inear-ten-sec-flex {
    display: flex;
    flex-direction: column;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.ten-txt-one {
    width: 100%;
    position: absolute;
    top: 80px;
    bottom: 0;
    left: 0px;
    right: 0;
}

.ten-inear-flex {
    display: flex;
    justify-content: space-between;
    flex-direction: column;
    flex-wrap: wrap;
    row-gap: 24px;
    align-items: center;
}

.ten-inear-image {
    width: 15%;
}

.ten-inear-image img {
    width: 100%;
}

.teninear-para {
    width: 100%;
    text-align: center;
}

.teninear-para h3 {
    font-size: 32px;
    color: #ffffff;
    font-style: normal;
    font-weight: 500;
    letter-spacing: 4px;
    word-spacing: 1.2px;
    font-family: "Raleway", sans-serif;
}

.ten-inear-button {
    width: 25%;
    border: 1px solid #ffffffb7;
    text-align: center;
}

.ten-inear-button a {
    text-decoration: none;
    color: #ffffff;
    font-size: 16px;
    padding: 17px 5px;
    display: block;
}

/*----------SECTION-ELEVEN------------------------------------ */
.section-eleven {
    width: 100%;
    padding-top: 20px;
    margin-bottom: 20px;
}

.inear-elven {
    width: 100%;
    padding-top: 20px;
    padding-bottom: 20px;
    margin-bottom: 20px;
}

.eleven-heading {
    width: 100%;
    text-align: center;
    padding: 3px 0;
}

.ele-parar {
    width: 100%;
    text-align: center;
    padding-bottom: 2px;
}

.ele-parar p {
    font-size: 12px;
    font-style: normal;
    font-weight: 400;
    color: #726E6A;
    letter-spacing: 1px;
    font-family: "Raleway", sans-serif;
}

.eleven-heading {
    width: 100%;
    text-align: center;
    padding: 3px 0;
}

.eleven-heading h4 {
    font-size: 24px;
    color: #6D1A38;
    line-height: 1.3;
    letter-spacing: 3px;
    font-family: "Raleway", sans-serif;
}

.ele-images {
    padding: 20px 0;
    width: 100%;
    margin-bottom: 20px;
}

.ele-img-flex {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-wrap: wrap;
}

.ele {
    width: 25%;
    padding: 20px 0;
    line-height: 0;
}

.ele img {
    width: 100%;
}

/*----------SECTION-twelve------------------------------------ */
.section-clr {
    background-color: #FCFBF8;
    padding: 20px 0;
}

.section-twelve {
    width: 100%;
    padding: 20px 0;
}

.inear-twel {
    width: 85%;
    margin: 0 auto;
    padding: 20px 0;
}

.twel-width {
    width: 100%;
}

.twel-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.twel-one {
    width: 13%;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    row-gap: 8px;
}

.twel-image img {
    width: 100%;
}

.twel-image {
    width: 30%;
}
.twel-sub-para p {
    font-size: 17px;
    font-weight: 550;
    font-family: "Raleway", sans-serif;
    color: #383838;
}


/* ----------FOOTER---------------------------------------- */
.footer-color {
    background-color: #F9F7F2;
}

.footer {
    width: 100%;
    padding-top: 40px;
    padding-bottom: 20px;
}

.inside-footer {
    width: 85%;
    margin: 0 auto;
}

.footer-flex {
    display: flex;
    justify-content: space-between;
    flex-wrap: wrap;
    padding-bottom: 40px;
}

.footer-one {
    width: 20%;
}

.footer-one-flex {
    display: flex;
    flex-direction: column;
    row-gap: 15px;
    justify-content: space-between;
    flex-wrap: wrap;
}

.sub-head {
    width: 100%;
}
.sub-head.vi {
    /* margin-bottom: 20px; */
}

.sub-head h3 {
    font-size: 17px;
    font-style: normal;
    font-weight: 500;
    color: #383838;
    font-family: 'Raleway';
}

.sub-bulit {
    width: 100%;
    line-height: 1.9;
}

.sub-bulit a {
    text-decoration: none;
    color: #383838;
    font-size: 12px;
    line-height: 1.9;
    font-weight: 600;
    letter-spacing: 0.6px;
    text-transform: uppercase;
    font-family: "Raleway", sans-serif;

}

.fooeter-sub-section {
    width: 100%;
}

.footer-onee {
    width: 35%;
}

.sub-foter-clr {
    background-color: #ffffff;
    box-shadow: 0px 8px 15px rgba(0, 0, 0, 0.1);
}

.f-sub-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-direction: column;
    flex-wrap: wrap;
}

.ki {
    width: 100%;
    text-align: center;
    margin-top: 20px;
}

.f-sub-head {
    margin: 10px 0;
    width: 100%;
    margin-bottom: 15px;
}

.f-sub-head h3 {
    text-transform: uppercase;
    font-size: 18px;
    font-weight: 600;
    color: #383838;
    line-height: normal;
    font-family: "Raleway", sans-serif;
}



.f-sub-para {
    padding-bottom: 20px;
    width: 100%;
}

.f-sub-para p {
    font-size: 15px;
    font-style: normal;
    font-weight: 400;
    color: #818181;
}

.ik {
    width: 100%;
    text-align: center;
    padding-bottom: 20px;
}

.inputt {
    width: 100%;
    padding-bottom: 15px;
}

.inputt input[type="email"] {
    padding: 13px 12px;
    width: 70%;
    border: 2px solid #D8AEB2;
    font-style: italic;
}

.f-button {
    width: 25%;
    text-align: center;
    border: 1px solid #6D1A38;
    display: inline;
    padding: 4px 12px;
}


.f-button a {
    font-size: 13px;
    text-decoration: none;
    color: #6D1A38;
    padding: 4px 14px;
}

.icons-flex {
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.footer-icons {
    width: 35%;
    margin: 0 auto;
}

.icon-f img {
    width: 85%;
}

.footer-number {
    width: 50%;
    margin: 0 auto;
}

.mk {
    display: flex;
    justify-content: center;
    align-items: center;
    column-gap: 13px;
}

.f-number-icon {
    line-height: 0;
    width: 9%;

}

.f-number-icon img {
    width: 100%;

}
.f-number-para p {
    color: #726E6A;
    font-size: 15px;
    line-height: 4px;
}

.f-number-iconn {
    width: 4%;
}

.f-number-iconn img {
    width: 100%;
}
.footer-line {
    width: 100%;
}
.footer-line p {
    font-size: 14px;
    font-family: 'Raleway';
    font-style: normal;
    letter-spacing: 0.9px;
    color: #383838;
    font-weight: 500;
}






@media screen and (min-width:769px) {
    .nav-header {
        display: none;
    }
}
















@media screen and (max-width:768px) {
    .topbar {
        display: none;
    }

    .navbar {
        display: none;
    }

    .icons {
        display: none;
    }

    .inear-header {
        height: 80px;
    }

    .logo {
        width: 30%;
    }

    .one-data {
        justify-content: center;
        flex-wrap: wrap;
    }

    .one-txt {
        width: 100%;
        padding-bottom: 20px;
    }

    .flex-txt {
        justify-content: center;
        row-gap: 27px;
        flex-wrap: wrap;
        align-items: center;
    }

    .one-main {
        padding-top: 20px;
        width: 100%;
    }

    .one-main h1 {
        text-align: center;
        font-size: 30px;
    }

    .one-para {
        width: 100%;
    }

    .one-para p {
        font-size: 13px;
        text-align: center;
    }

    .one-button {

        width: 40%;
        border: 1px solid #6D1A38;
        background-color: #6D1A38;
        color: white;
        text-align: center;
    }

    .one-button a {
        color: #6D1A38;
        font-size: 12px;
    }

    .one-image {
        width: 100%;
        padding-top: 20px;
    }

    .gum {
        display: none;
    }

    .img-1 {
        width: 25%;
    }
    .img-1.gum1 {
        width: 27%;
    }
    .img-1.gum2 {
        width: 15%;
    }
    .hide {
        display: none;
    }

    .design {
        font-family: just lovely;
        font-weight: normal;
        font-style: normal;
        font-size: 43px;
    }
    .section-two{
        padding: 0 0;
    }
    .thrd-img-data {
        row-gap: 35px;
    }

    .thrd-one-container {
        width: 100%;
    }

    .thrd-section {
        width: 100%;
        padding-top: 0px;
    }

    .inear-thrd {

        padding-bottom: 20px;
    }

    .thrd-heading {

        padding-bottom: 20px;
    }

    .thrd-images {
        padding-bottom: 20px;
    }

    .img-2 {
        width: 90%;
        margin: 0 auto;
        line-height: 0;
    }

    .img-2 p {
        padding-top: 27px
    }

    .for-main {
        position: static;
    }

    .fourth-txt {
        width: 100%;
    }

    .for-flex {
        row-gap: 3px;
    }

    .for-heading {
        width: 64%;
    }
    span.Lovely {
        font-family: just lovely;
        font-size: 42px;
    }

    .for-heading h2 {
        font-size: 30px;
    }
    .fifth-heading h2{
        font-size: 28px;
    }
    .design{
        font-size: 36px;
    }
    .for-btn {
        width: 33%;
    }

    .cart-main-flex {
        flex-wrap: wrap;
    }

    .a {
        width: 100%;
        position: relative;
    }

    .add-to-cart {
        width: 73%;
        position: absolute;
        left: 45px;
        top: 284px;
        right: 0;
        bottom: 0;
    }

    .add-to-cart a {
        background-color: #6D1A38;
        color: white;
        font-size: 9px;
    }

    .fifth-cards {
        row-gap: 25px;
    }

    .cart-main-flex {
        row-gap: 25px;
    }

    .six-flex {
        flex-wrap: wrap;
        flex-direction: column-reverse;
        row-gap: 40px;
    }

    .six-heading h2 {
        text-align: center;
    }

    .inear-sixth-second {
        row-gap: 48px;
    }

    .six-button {
        width: 100%;
        text-align: center;
        padding-bottom: 20px;
    }

    .sec-one {
        width: 100%;
    }

    .sec-two {
        width: 100%;
    }

    .seven-txt-conainer {
        width: 100%;
    }

    .sec-twoo {
        width: 100%;
    }

    .seven-slider {
        width: 100%;
    }

    .seven-slider {
        width: 100%;
    }

    .slick-prev:before {
        line-height: 19 !important;
    }

    .slick-prev:before,
    .slick-next:before {
        line-height: 19 !important;
    }

    .after-before-txt {
        top: 114px;
        left: 13px;
        display: none;
    }

    .after-before-txt h2 {
        color: black;
    }

    .after-before-txtt {
        display: none;
        top: 110px;
        left: 170px;
    }

    .after-before-txtt h2 {
        color: black;
    }

    .eight-sub-heading {
        width: 30%;
    }

    .eight-main-heading {
        width: 80%;
    }

    .eight-main-heading h2 {
        font-size: 25px;
    }

    .nine-two {
        width: 100%;
        padding-top: 20px;
    }

    .ten-image {
        width: 100%;
        line-height: 0;
    }

    .ten-txt-one {
        width: 100%;
        /* top: 29px; */
    }

    /* .ten-inear-flex {
        row-gap: 17px;
    } */

    .teninear-para h3 {
        font-size: 26px;
    }

    .ten-inear-button {
        width: 30%;
    }

    .ten-inear-button a {
        font-size: 9px;
        padding: 10px 16px;
    }

    .inear-ten-sec {
        width: 100%;
        position: relative;
    }

    .inear-section-ten {
        width: 100%;
    }

    .ele {
        width: 50%;
        line-height: 0;
        padding: 0 0;
    }

    .twel-one {
        width: 50%;
    }

    .ww {
        display: none;
    }

    .inside-footer {
        width: 90%;
        margin: 0 auto;
    }

    .footer-one {
        width: 100%;
    }

    .sub-bulit a {
        font-size: 9px;
    }

    .footer-one-flex {
        padding-bottom: 12px;
    }

    .footer-one-flex {
        font-size: 16px;
    }

    .footer-onee {
        width: 100%;
    }
}



