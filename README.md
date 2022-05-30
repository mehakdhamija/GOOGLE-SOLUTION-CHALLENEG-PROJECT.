# lokah-samsthah-sukhino-bhavantuh
<!DOCTYPE html>
<html>
    <head>
        <meta name="viewport" content="'width=device-width, initial scale=1.0">
        <title>THE VEDA LIFE </title>
        <link rel="stylesheet" href="style.css">
        <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:ital,wght@0,300;0,500;0,600;0,700;1,300&display=swap" rel="stylesheet">
<link href="stylesheet"  href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@5.15.4/css/fontawesome.min.css"> 
</head>
    <body>
        <section class ="header">
            <nav>
                <a href="index.html"><img src= "Images/logo.png"></a>
                <div class="nav-links" id="navLinks">
                <i class="fa fa-times" onclick="hideMenu()"></i>
                    <ul>
                        <li><a href="">HOME</a></li>
                        <li><a href="">ABOUT</a></li>
                        <li><a href="">NGO'S</a></li>
                        <li><a href="">BLOG</a></li>
                        <li><a href="">CONTACT</a></li>
                    </ul>
                </div>
                <i class="fa fa-bars" onclick="showMenu()"></i>
            </nav>
        <div class="text-box">
            <h1>लोका: समस्ता: सुखिनो भवन्तु:</h1>
            <p>ॐ सर्वेशां स्वस्तिर्भवतु
                सर्वेशां शान्तिर्भवतु
                <br>सर्वेशां पूर्णंभवतु
                सर्वेशां मङ्गलंभवतु
                <br>लोका: समस्ता: सुखिनो भवन्तु
                <br>ॐ शान्तिः शान्तिः शान्तिः
                <br>हरि ॐ ! श्री गुरुभ्यो नम: ! हरि ॐ</p>
                <a href="" class="hero-btn">don't know what to add</a>
        </div> 
        </section>
<!---------course------->
<section class="course">
    <h1>DIVE DEEP INTO A HEALTHY LIFE</h1>
    <p>xyz</p>
    <div class="row">
        <div class="course-col">
            <h3>Mind,Body and Soul</h3>
            <p></p>
        </div>
        <div class="course-col">
            <h3>The Vedic Remedies</h3>
            <p></p>
        </div>
        <div class="course-col">
            <h3>NGO'S </h3>
            <p></p>
        </div>
    </div>
    
</section>
<!------campus------>
<section class="campus">
    <h1>The Chakras of your Body</h1>
    <p> 
        Literally means “wheel”. Refers to centers of energy in the astral spine.

As this energy enters the body, it travels down the astral spine and is dispersed into<br>
the body from six centers, or chakras, located along the astral spine. This subtle spine<br>
can be visualized as a tube of light running centrally through the body from the base of the<br>
spine to the brain. The central nervous system is the physical expression of the astral spine<br>
and, interestingly, has major centers near the areas of each of the chakras, where groups of <br>
nerves branch out from the spinal cord.

There is a vast and somewhat complex yogic science dealing with the chakras.<br>
Each chakra is associated with a quality of consciousness; an element; a planet;<br>
two astrological signs (one as the energy ascends and one as it descends); a sound;<br>
a spiritual quality; and so forth. As energy passes through or rests in any chakra,<br>
the mind is influenced by the qualities of that center. In the deepest states of meditation,<br>
all prana is withdrawn from the body into the chakras and then directed to the spiritual eye,<br>
enabling enlightenment to take place.
    </p>

    <div class="row">
        <div class="campus-col">
            <img src="images/root-chakra.png">
            <div class="layer">
                <h3>मूलाधार चक्र</h3>
            </div>
        </div>
        <div class="campus-col">
            <img src="images/sacral-chakra.webp">
            <div class="layer">
                <h3>स्वाधिष्ठान चक्र</h3>
            </div>
        </div>
        <div class="campus-col">
            <img src="images/solar-plexus-chakra.webp">
            <div class="layer">
                <h3>मणिपूरक चक्र</h3>
            </div>
        </div>
    </div>   
    <div class="row">
        <div class="campus-col">
            <img src="images/heart-chakra.webp">
            <div class="layer">
                <h3>अनाहत चक्र</h3>
            </div>
        </div>
        <div class="campus-col">
            <img src="images/throat-chakra.webp">
            <div class="layer">
                <h3>विशुद्धि चक्र</h3>
            </div>
        </div>
        <div class="campus-col">
            <img src="images/third-eye-chakra.webp">
            <div class="layer">
                <h3>आज्ञा चक्र</h3>
            </div>
        </div>
        <div class="campus-col">
            <img src="images/crown-chakra.webp">
            <div class="layer">
                <h3>सहस्रार चक्र</h3>
            </div>
        </div>
    </div>
</section>



<!--------Javascript for toggle menu-------------->        
        <script>
            var navLinks = document.getElementById({"navLinks");
            function showMenu(){
                navlinks.style.right ="0";
            }
            function hideMenu(){
                navLinks.style.right = "-200px";
            }
        </script>
    </body>
</html>

