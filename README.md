<html lang="en">
 <head>
  <meta charset="utf-8"/>
  <meta content="width=device-width, initial-scale=1.0" name="viewport"/>
  <title>
   Surprise for [HerName]
  </title>
  <script src="https://cdn.tailwindcss.com">
  </script>
  <link href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css" rel="stylesheet"/>
  <link href="https://fonts.googleapis.com/css2?family=Great+Vibes&amp;family=Roboto:wght@400;700&amp;display=swap" rel="stylesheet"/>
  <style>
   body {
            font-family: 'Roboto', sans-serif;
        }
        h1, h2, h3 {
            font-family: 'Great Vibes', cursive;
        }
  </style>
 </head>
 <body class="bg-pink-50 text-gray-800">
  <!-- Navbar -->
  <nav class="bg-pink-200 p-4">
   <div class="container mx-auto flex justify-between items-center">
    <a class="text-3xl font-bold text-pink-700" href="#">
     For [HerName]
    </a>
    <ul class="flex space-x-4">
     <li>
      <a class="hover:text-pink-500" href="#home">
       Home
      </a>
     </li>
     <li>
      <a class="hover:text-pink-500" href="#gallery">
       Gallery
      </a>
     </li>
     <li>
      <a class="hover:text-pink-500" href="#love-notes">
       Love Notes
      </a>
     </li>
     <li>
      <a class="hover:text-pink-500" href="#countdown">
       Countdown
      </a>
     </li>
    </ul>
   </div>
  </nav>
  <!-- Home Section -->
  <section class="bg-pink-100 py-20 text-center" id="home">
   <div class="container mx-auto">
    <h1 class="text-5xl text-pink-700 mb-4">
     To My Dearest [HerName]
    </h1>
    <p class="text-xl">
     You are the love of my life, and I created this special place to celebrate our love and memories together.
    </p>
   </div>
  </section>
  <!-- Gallery Section -->
  <section class="py-12" id="gallery">
   <div class="container mx-auto">
    <h2 class="text-4xl text-center text-pink-700 mb-8">
     Our Memories
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
     <div class="bg-white p-4 rounded shadow">
      <img alt="A romantic photo of the couple at the beach" class="w-full h-48 object-cover rounded mb-4" src="https://placehold.co/300x200"/>
      <p class="text-gray-700">
       Our first beach trip together.
      </p>
     </div>
     <div class="bg-white p-4 rounded shadow">
      <img alt="A photo of the couple at a fancy dinner" class="w-full h-48 object-cover rounded mb-4" src="https://placehold.co/300x200"/>
      <p class="text-gray-700">
       Celebrating our anniversary at a fancy dinner.
      </p>
     </div>
     <div class="bg-white p-4 rounded shadow">
      <img alt="A candid photo of the couple laughing together" class="w-full h-48 object-cover rounded mb-4" src="https://placehold.co/300x200"/>
      <p class="text-gray-700">
       Laughing together, always.
      </p>
     </div>
    </div>
   </div>
  </section>
  <!-- Love Notes Section -->
  <section class="bg-pink-100 py-12" id="love-notes">
   <div class="container mx-auto">
    <h2 class="text-4xl text-center text-pink-700 mb-8">
     Love Notes
    </h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
     <div class="bg-white p-6 rounded shadow">
      <h3 class="text-2xl text-pink-700 mb-4">
       My Love for You
      </h3>
      <p class="text-gray-700">
       You are my sunshine, my only sunshine. You make me happy when skies are gray. You'll never know, dear, how much I love you. Please don't take my sunshine away.
      </p>
     </div>
     <div class="bg-white p-6 rounded shadow">
      <h3 class="text-2xl text-pink-700 mb-4">
       Our Journey
      </h3>
      <p class="text-gray-700">
       From the moment we met, I knew you were the one. Our journey together has been filled with love, laughter, and countless beautiful memories. I can't wait to see what the future holds for us.
      </p>
     </div>
    </div>
   </div>
  </section>
  <!-- Countdown Section -->
  <section class="py-12" id="countdown">
   <div class="container mx-auto text-center">
    <h2 class="text-4xl text-pink-700 mb-8">
     Countdown to Our Special Day
    </h2>
    <div class="text-3xl text-pink-700" id="countdown-timer">
    </div>
   </div>
  </section>
  <!-- Hidden Page -->
  <section class="bg-pink-100 py-12 hidden" id="hidden-page">
   <div class="container mx-auto text-center">
    <h2 class="text-4xl text-pink-700 mb-8">
     A Special Message Just for You
    </h2>
    <p class="text-xl text-gray-700">
     Surprise! I have a special message for you. You are my everything, and I am so grateful to have you in my life. I love you more than words can express.
    </p>
   </div>
  </section>
  <!-- Footer -->
  <footer class="bg-pink-200 text-gray-800 py-8">
   <div class="container mx-auto text-center">
    <p>
     © 2023 Surprise for [HerName]. All rights reserved.
    </p>
    <div class="flex justify-center space-x-4 mt-4">
     <a class="hover:text-pink-500" href="#">
      <i class="fab fa-facebook-f">
      </i>
     </a>
     <a class="hover:text-pink-500" href="#">
      <i class="fab fa-twitter">
      </i>
     </a>
     <a class="hover:text-pink-500" href="#">
      <i class="fab fa-linkedin-in">
      </i>
     </a>
     <a class="hover:text-pink-500" href="#">
      <i class="fab fa-instagram">
      </i>
     </a>
    </div>
   </div>
  </footer>
  <script>
   // Countdown Timer
        const countdownDate = new Date("Dec 31, 2023 00:00:00").getTime();
        const countdownTimer = document.getElementById('countdown-timer');

        const updateCountdown = () => {
            const now = new Date().getTime();
            const distance = countdownDate - now;

            const days = Math.floor(distance / (1000 * 60 * 60 * 24));
            const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
            const minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
            const seconds = Math.floor((distance % (1000 * 60)) / 1000);

            countdownTimer.innerHTML = `${days}d ${hours}h ${minutes}m ${seconds}s`;

            if (distance < 0) {
                clearInterval(countdownInterval);
                countdownTimer.innerHTML = "The special day is here!";
            }
        };

        const countdownInterval = setInterval(updateCountdown, 1000);
  </script>
 </body>
</html>
