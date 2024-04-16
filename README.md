![uyh](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/d2d82225-3d14-47ef-80f1-ad763758ea0b)
![palesa](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/5ccbc8ca-662b-4d60-884b-e9fa268d3d3e)
![nhekeleng](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/2072bb6f-8bdc-4baa-9e57-914ab8bc30be)
![mpho](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/f5eb21dd-f222-4d7a-95eb-984d7b4c9545)
![logo](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/aa291dff-c725-4e05-a543-4941f16657df)
![kani](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/f55e4ee3-4834-4d9b-8757-e85686b51bb7)
![jhjk](https://github.com/HydraBalance/Hydra-Balance/assets/167212525/99772ab3-ea48-4ca1-a03c-bc0e73c51edf)
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cosmetic Store</title>
    <link rel="stylesheet" href="home.css">
</head>
<body>
    <header>
       <div class="heading">
	  <h1>Hydra Balance</h1>
       </div>    	
	
       <div class="navigation">
	 <nav>
            <ul>
                <li><a href="home.html" class="active">Home</a></li>			
                <li><a href="about.html">About Us</a></li>
                <li><a href="contactUs.html">Contact Us</a></li>
            </ul>
    	</nav>
       </div>

       <div class="logo">
	   <img src="logo.jpg" alt="Hydra Balance Logo" id="logo">
       </div>    
</header>
<h2>Our Product</h2>
<main id="products">    	
	<div class="product">
	    <img src="logo.jpg">
	    <p>....more items to hit the store, soon</p>
        </div>
        <div class="product">
            <div id="overlay" class="overlay" onclick="closeOverlay()">
            <img id="overlay-img" src="" alt="Enlarged Image">
            </div>
	    <h3>Face Serum</h3>
	    <p>The number one face wash in the L.</p>
    	    <p class="price">M150.00</p>
        </div>
        <div class="product">
	    <h3>Directions of use</h3>		
	    <p>Apply gently on face with hands in a circular motion .</p>
	    <p>Rinse face with warm water after application and wipe with damp towel.</p>
	    <p>Most effective when used twice a day, morning and evening</p>
        </div>   
</main>
<footer>
    <p class="fooTer">&copy; 2024 Lotions Bar</p>
    <p class="fooTer">hydrabalance266@yahoo.mail</p>
</footer>
<script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/js/all.min.js"></script>
<script>
    var images = ["er.jpg", "uyh.jpg", "grery.jpg"];
    var currentIndex = 0;
    var interval;

    function startSlideshow() {
         interval = setInterval(function() {
                currentIndex = (currentIndex + 1) % images.length;
                updateDisplayedImage();
         }, 2000);
    }

    function stopSlideshow() {
         clearInterval(interval);
    }

    function updateDisplayedImage() {
         var overlayImg = document.getElementById('overlay-img');
         overlayImg.src = images[currentIndex];
    }

    function openOverlay(imageSrc) {
         var overlay = document.getElementById('overlay');
         var overlayImg = document.getElementById('overlay-img');
         overlayImg.src = imageSrc;
         overlay.style.display = 'flex';
         stopSlideshow();
    }

    function closeOverlay() {
         var overlay = document.getElementById('overlay');
         overlay.style.display = 'none';
         startSlideshow();
    }

    startSlideshow();
</script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cosmetic Store</title>
    <link rel="stylesheet" href="about.css">
</head>
<body>
    <header>
       <div class="heading">
	<h1>Hydra Balance</h1>
       </div>    	
	
       <div class="navigation">
	 <nav>
            <ul>
                <li><a href="home.html">Home</a></li>			
                <li><a href="about.html" class="active">About Us</a></li>
                <li><a href="contactUs.html">Contact Us</a></li>
            </ul>
    	</nav>
       </div>

       <div class="logo">
	<img src="logo.jpg" alt="Hydra Balance Logo" id="logo">
       </div>    
</header>
<main id="products">    	
        <div class="product">
            <h3>Hydra Balance was founded in 2024 by Palesa Ramoreki</h3>
	    <p>A dermatologist based in Maseru, Lesotho. “Most of my patients’ skin get irritated by sun burn 
	       in summer and causes them to have major skin complications such as hyper-pigmentation.”
	    </p>
	    <p> 
	       She further stated that some patients’ skin gets dry in cold weather conditions and
	       it gets worse in cold weather conditions thus it gets worse in winter and because it dries 
	       up they suffer from eczema and peeling skin
	    </p>
	    <p> “So I thought to bring them a doctor in a cabinet 
	       by producing the miracle working serum to
	       assist them in balancing their skin’s hydration during cold and hot season,” she said.
	    </p>
        </div>

        <div class="product">
            <div id="overlay" class="overlay" onclick="closeOverlay()">
               <img id="overlay-img" src="" alt="">
            </div>
	    <h4>Employees</h4>
	    <h3>hydrabalance@gmail.com</h3>
    	    <h4>+266 22432586</h4>
        </div>

	<div class="product">
            <h3>The science behind hydra balance facial serum</h3>
	    <p>At the core of this serum lies a cautiously organized blend of powerful elements that
	       work in harmony to nourish and restore your skin.</p>
	    <p> Hydra Balance serum is an intense
	       skin treatment packed with powerful ingredients that penetrate deeper into the skin layers
	       to tackle specific problems associated with the skin, such as sun damage, hyperpigmentation, 
	       eczema and peeling skin.</p>
	    <p>Hydra Balance serum is efficient in penetrating the skin and giving 
	       the skin higher bioavailability with the aid of the delivery system that is ideal for a radiant
	       healthy skin because of the antioxidant and antimicrobial properties.
	    </p>
        </div>
</main>
<script src="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0-beta3/js/all.min.js"></script>
<script>
        var images = ["boity.jpg", "kani.jpg", "mpho.jpg", "ffff.jpg", "jhjk.jpg",
		      "nhekeleng.jpg", "palesa.jpg"];
        var currentIndex = 0;
        var interval;

        function startSlideshow() {
            interval = setInterval(function() {
                currentIndex = (currentIndex + 1) % images.length;
                updateDisplayedImage();
            }, 2000);
        }

        function stopSlideshow() {
            clearInterval(interval);
        }

        function updateDisplayedImage() {
            var overlayImg = document.getElementById('overlay-img');
            overlayImg.src = images[currentIndex];
        }

        function openOverlay(imageSrc) {
            var overlay = document.getElementById('overlay');
            var overlayImg = document.getElementById('overlay-img');
            overlayImg.src = imageSrc;
            overlay.style.display = 'flex';
            stopSlideshow();
        }

        function closeOverlay() {
            var overlay = document.getElementById('overlay');
            overlay.style.display = 'none';
            startSlideshow();
        }
        startSlideshow();
</script>
</body>
</html>
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cosmetic Store</title>
    <link rel="stylesheet" href="contact.css">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body>
    <header>
       <div class="heading">
        
	<h1>Hydra Balance</h1>
       </div>    	
	
       <div class="navigation">
	 <nav>
            <ul>
                <li><a href="home.html">Home</a></li>			
                <li><a href="about.html">About Us</a></li>
                <li><a href="contactUs.html" class="active">Contact Us</a></li>
            </ul>
    	</nav>
       </div>

       <div class="logo">
	<img src="logo.jpg" alt="Hydra Balance Logo" id="logo">
       </div>    
</header>
<div class="centered-content">
        <address>
	     <p><a href="#"><i class="fa fa-twitter-square" aria-hidden="true"></i>..HydraBalance266</a></p>
	     <p><a href="#"><i class="fa fa-facebook-official" aria-hidden="true"></i>..HydraBalance266</a></p>
	     <p><a href="#"><i class="fa fa-instagram" aria-hidden="true"></i>..hydraBalce266</a></p>
	     <p><a href="#"><i class="fa fa-whatsapp" aria-hidden="true"></i>..+266 56789023</a></p>
   	     <p><a href="#"><i class="fa fa-phone-square" aria-hidden="true"></i>..+266 22432586</a></p>
	     <p><a href="#"><i class="fa fa-envelope" aria-hidden="true"></i>..hydrabalance@gmail.com</a></p>
        </address>
</div>
<footer>
    <p class="fooTer">&copy; 2024 Lotions Bar</p>
    <p class="fooTer">hydrabalance266@yahoo.mail</p>
</footer>
</body>
</html>
