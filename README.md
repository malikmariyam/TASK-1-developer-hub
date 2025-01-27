<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>E-Commerce Website</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">
  
  <header class="bg-white-100 shadow py-2">
    <!-- First Row -->
    <div class="container mx-auto flex items-center justify-between px-6">
      <!-- Logo Section -->
      <div class="flex items-center space-x-2">
        <img src="images/logo.jpg" alt="Brand Logo" class="h-12 md:h-10"> <!-- Logo reverted to previous size -->
      </div>
<!-- Search Bar with Adjusted Width and Height -->
<div class="flex items-center flex-grow max-w-lg mx-auto border border-blue-500 rounded-md overflow-hidden focus-within:ring-2 focus-within:ring-blue-500">
  <!-- Search Input -->
  <input
    type="text"
    placeholder="Search"
    class="flex-grow px-3 py-1 text-sm focus:outline-none"
  />
  
  <!-- Divider Line Next to Input -->
  <div class="h-full w-px bg-blue-500"></div>
  
  <!-- All Categories Dropdown -->
  <select class="px-3 py-1 text-sm focus:outline-none">
    <option>All Categories</option>
    <option>Electronics</option>
    <option>Clothing</option>
    <option>Books</option>
  </select>
  
  <!-- Divider Line Next to Dropdown -->
  <div class="h-full w-px bg-blue-500"></div>
  
  <!-- Search Button -->
  <button class="bg-blue-500 text-white px-5 py-1 text-sm hover:bg-blue-600 focus:outline-none">
    Search
  </button>
</div>


<!-- Profile and Cart Section -->
<div class="flex items-center space-x-6">
  <a href="#" class="text-gray-600 hover:text-blue-500 flex items-center space-x-1">
    <img src="images/user (1).png" alt="Profile" class="h-6 w-6">
    <span class="text-sm">Profile</span>
  </a>
  <a href="#" class="text-gray-600 hover:text-blue-500 flex items-center space-x-1">
    <img src="images/masg.png" alt="Messages" class="h-6 w-6">
    <span class="text-sm">Messages</span>
  </a>
  <a href="#" class="text-gray-600 hover:text-blue-500 flex items-center space-x-1">
    <img src="images/order-delivery.png" alt="Orders" class="h-6 w-6">
    <span class="text-sm">Orders</span>
  </a>
  <a href="#" class="text-gray-600 hover:text-blue-500 flex items-center space-x-1">
    <img src="images/carttt.png" alt="My Cart" class="h-6 w-6">
    <span class="text-sm">My Cart</span>
  </a>
</div>
</div>       

 <!-- Second Row -->
<div class="bg-white py-2">
  <div class="container mx-auto flex items-center justify-between px-6">
    <!-- Left Section: All Categories and Menu Items -->
    <div class="flex items-center space-x-6">
      <!-- Hamburger Menu -->
      <button class="lg:hidden p-2 text-gray-600">
        <span class="block w-6 h-1 bg-gray-600 mb-1"></span>
        <span class="block w-6 h-1 bg-gray-600 mb-1"></span>
        <span class="block w-6 h-1 bg-gray-600"></span>
      </button>
      <span class="text-gray-600 font-semibold">All Categories</span>
      <!-- Menu Items -->
      <ul class="flex space-x-6 text-gray-600 list-none">
        <li><a href="#" class="hover:text-blue-500">Hot offers</a></li>
        <li><a href="#" class="hover:text-blue-500">Gift boxes</a></li>
        <li><a href="#" class="hover:text-blue-500">Projects</a></li>
        <li><a href="#" class="hover:text-blue-500">Menu item</a></li>
        <li><a href="#" class="hover:text-blue-500">Help</a></li>
      </ul>
    </div>

    <!-- Right Section: Language and Shipping -->
    <div class="flex items-center space-x-4 text-sm">
      <a href="#" class="hover:text-blue-500">English, USD</a>
      <a href="#" class="hover:text-blue-500 flex items-center space-x-1">
        <span>Ship to</span>
        <img src="images/usa.png" alt="Country Flag" class="h-4 w-4 rounded-full">
      </a>
    </div>
  </div>
</div>
  </header>
  

<div class="flex bg-blue p-6 space-x-4">
    <!-- Sidebar (Left) -->
    <div class="w-1/4 bg-white rounded-lg p-4 shadow">
      <ul class="space-y-4">
        <li class="text-blue-500 font-semibold">Automobiles</li>
        <li>Clothes and wear</li>
        <li>Home interiors</li>
        <li>Computer and tech</li>
        <li>Tools, equipment</li>
        <li>Sports and outdoor</li>
        <li>Animal and pets</li>
        <li>Machinery tools</li>
        <li>More category</li>
      </ul>
    </div>
  
    <div class="w-1/2 rounded-lg shadow relative overflow-hidden">
      <style>
        @keyframes fade-in-out {
          0%, 25%, 100% { opacity: 0; } /* Hidden at the start, middle, and end */
          30%, 90% { opacity: 1; } /* Fully visible for most of the time */
        }
    
        .animate-fade-in-out {
          animation: fade-in-out 9s infinite; /* Smooth 12-second cycle for each image */
        }
    
        .slide:nth-child(2) {
          animation-delay: 7s; /* Start second slide after 4 seconds */
        }
    
        .slide:nth-child(3) {
          animation-delay: 8s; /* Start third slide after 8 seconds */
        }
      </style>
    
      <!-- Slideshow Wrapper -->
      <div class="relative w-full h-96 rounded-lg">
        <!-- Slide 1 -->
        <div class="slide bg-cover bg-center w-full h-full absolute inset-0 animate-fade-in-out"
          style="background-image: url('images/background1.jpg');">
        </div>
        <!-- Slide 2 -->
        <div class="slide bg-cover bg-center w-full h-full absolute inset-0 animate-fade-in-out"
          style="background-image: url('images/background3.jpg');">
        </div>
        <!-- Slide 3 -->
        <div class="slide bg-cover bg-center w-full h-full absolute inset-0 animate-fade-in-out"
          style="background-image: url('images/background4.jpg');">
        </div>
      </div>
    </div>
    
  
    <!-- Sidebar (Right) -->
    <div class="w-1/4 space-y-4">
      <div class="bg-blue-100 p-4 rounded-lg shadow h-32 flex flex-col justify-center">
        <p class="text-gray-700 font-semibold">Hi, user</p>
        <p class="text-sm text-gray-500">Let's get started</p>
        <div class="flex gap-2 mt-4">
          <button class="bg-blue-500 text-white px-4 py-2 rounded shadow">
            Join now
          </button>
          <button class="border border-blue-500 text-blue-500 px-4 py-2 rounded shadow">
            Log in
          </button>
        </div>
      </div>
      <div class="bg-orange-100 p-4 rounded-lg shadow h-32 flex items-center">
        <p class="text-gray-700">Get US $10 off with a new supplier</p>
      </div>
      <div class="bg-teal-100 p-4 rounded-lg shadow h-32 flex items-center">
        <p class="text-gray-700">Send quotes with supplier preferences</p>
      </div>
    </div>
  </div>
  
    
   <!-- Deals and Offers Section -->
<div class="bg-white p-6 rounded-lg shadow-md max-w-7xl mx-auto">
  <!-- Header and Timer -->
  <div class="flex">
    <!-- Timer Section -->
    <div class="w-1/4 bg-gray-100 p-4 rounded-lg text-center">
      <p class="text-lg font-bold text-gray-800">Deals and offers</p>
      <p class="text-sm text-gray-500">Hygiene equipments</p>
      <div class="flex justify-center space-x-2 mt-4">
        <!-- Timer Elements -->
        <div class="text-center">
          <p class="text-xl font-bold bg-gray-200 rounded p-2">04</p>
          <p class="text-sm text-gray-500 mt-1">Days</p>
        </div>
        <div class="text-center">
          <p class="text-xl font-bold bg-gray-200 rounded p-2">13</p>
          <p class="text-sm text-gray-500 mt-1">Hours</p>
        </div>
        <div class="text-center">
          <p class="text-xl font-bold bg-gray-200 rounded p-2">34</p>
          <p class="text-sm text-gray-500 mt-1">Minutes</p>
        </div>
        <div class="text-center">
          <p class="text-xl font-bold bg-gray-200 rounded p-2">56</p>
          <p class="text-sm text-gray-500 mt-1">Seconds</p>
        </div>
      </div>
    </div>

    <!-- Product Section -->
    <div class="w-3/4 grid grid-cols-5 gap-0 ml-6">
      <!-- Product 1 -->
      <div class="text-center border rounded-md p-2">
        <img src="images/smart watches.jpg" alt="Smart Watch" class="h-32 w-32 mx-auto">
        <p class="text-sm text-gray-700 mt-2">Smart watches</p>
        <p class="text-red-500 text-sm font-semibold mt-1">-25%</p>
      </div>
      <!-- Product 2 -->
      <div class="text-center border rounded-md p-2">
        <img src="images/laptop.jpg" alt="Laptops" class="h-32 w-32 mx-auto">
        <p class="text-sm text-gray-700 mt-2">Laptops</p>
        <p class="text-red-500 text-sm font-semibold mt-1">-15%</p>
      </div>
      <!-- Product 3 -->
      <div class="text-center border rounded-md p-2">
        <img src="images/canon cameras.jpg" alt="GoPro Cameras" class="h-32 w-32 mx-auto">
        <p class="text-sm text-gray-700 mt-2">GoPro cameras</p>
        <p class="text-red-500 text-sm font-semibold mt-1">-40%</p>
      </div>
      <!-- Product 4 -->
      <div class="text-center border rounded-md p-2">
        <img src="images/head phones.png" alt="Headphones" class="h-32 w-32 mx-auto">
        <p class="text-sm text-gray-700 mt-2">Headphones</p>
        <p class="text-red-500 text-sm font-semibold mt-1">-25%</p>
      </div>
      <!-- Product 5 -->
      <div class="text-center border rounded-md p-2">
        <img src="images/iphone.png" alt="Canon Cameras" class="h-32 w-32 mx-auto">
        <p class="text-sm text-gray-700 mt-2">Canon cameras</p>
        <p class="text-red-500 text-sm font-semibold mt-1">-25%</p>
      </div>
    </div>
  </div>
</div>

 <!-- Home and Outdoor Section -->
<section class="bg-white p-6 rounded-lg shadow-md max-w-7xl mx-auto">
  <!-- Section Header -->
  <div class="flex mb-6">
    <!-- Left Content with Background Image -->
    <div class="w-1/4 bg-cover bg-center rounded-md flex flex-col justify-center items-start p-6"
      style="background-image: url('images/home\ outdoor.jpg'); height: calc(16rem + 1rem);">
      <h2 class="text-2xl font-bold text-blue-700 leading-tight">
        Home and outdoor
      </h2>
      <button class="mt-6 px-6 py-3 bg-blue-500 text-white font-semibold rounded hover:bg-blue-600">
        Source now
      </button>
    </div>
    <!-- Right Content -->
    <div class="w-3/4 grid grid-cols-4 gap-4 pl-6">
      <!-- Product Item 1 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/sofa cahirs.jpg"alt="Soft Chairs" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 2 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/sofa cahir.jpg" alt="Sofa & Chair" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 3 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/kitchen dishes.jpg" alt="Kitchen Dishes" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 4 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/smart watchess 2.jpg" alt="Smart Watches" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 5 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/kitchen mixer.jpg" alt="Kitchen Mixer" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 6 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/blenders.jpg" alt="Blenders" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 7 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/home appliance.jpg" alt="Home Appliance" class="w-full h-32 object-cover">
      </div>
      <!-- Product Item 8 -->
      <div class="bg-gray-50 border rounded-md overflow-hidden">
        <img src="images/coffee maker.jpg" alt="Coffee Maker" class="w-full h-32 object-cover">
      </div>
    </div>
  </div>
</section>

 <!-- Consumer Electronics Section -->
  <section class="bg-white p-6 rounded-lg shadow-md max-w-7xl mx-auto">
    <!-- Section Header -->
    <div class="flex mb-6">
      <!-- Left Content with Background Image -->
      <div class="w-1/4 bg-cover bg-center rounded-md flex flex-col justify-center items-start p-6"
        style="background-image: url('images/electronics\,jpg.jpg'); height: calc(16rem + 1rem);">
        <h2 class="text-2xl font-bold text-green-700 leading-tight">
          Consumer electronics and gadgets
        </h2>
        <button class="mt-6 px-6 py-3 bg-yellow-400 text-black font-semibold rounded hover:bg-yellow-500">
          Source now
        </button>
      </div>
      <!-- Right Content -->
      <div class="w-3/4 grid grid-cols-4 gap-4 pl-6">
        <!-- Product Item 1 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/smart watches 3.jpg" alt="Smart Watches" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 2 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/cameras.jpg" alt="Cameras" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 3 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/headphones2.jpg" alt="Headphones" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 4 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/smart watches 4.jpg" alt="Smart Watches 2" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 5 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/gaming set.jpg" alt="Gaming Set" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 6 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/laptop pc.jpg" alt="Laptops & PC" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 7 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/smart phones.jpg" alt="Smartphones" class="w-full h-32 object-cover">
        </div>
        <!-- Product Item 8 -->
        <div class="bg-gray-50 border rounded-md overflow-hidden">
          <img src="images/electric kettle.jpg" alt="Electric Kettle" class="w-full h-32 object-cover">
        </div>
      </div>
    </div>
  </section>

<!-- Section: Send Requests to Suppliers -->
<div class="flex items-center justify-between bg-gradient-to-r from-blue-500 to-blue-400 text-white p-8 rounded-lg" style="background-image: url('images/newsletter.jpg'); background-size: cover; background-position: center;">
  <!-- Left Content -->
  <div class="w-1/2">
    <h2 class="text-4xl font-bold mb-2">An easy way to send requests to all suppliers</h2> <!-- Increased font size -->
    <p class="text-sm">
      Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt.
    </p>
  </div>

  <!-- Right Form -->
  <div class="w-1/2 bg-white p-6 rounded-lg shadow-md">
    <h3 class="text-lg font-semibold mb-4 text-gray-800">Send quote to suppliers</h3>
    <form>
      <!-- Item Input -->
      <div class="mb-4">
        <input
          type="text"
          placeholder="What item you need?"
          class="w-full border border-gray-300 rounded px-3 py-2 text-gray-700 focus:ring-2 focus:ring-blue-500 focus:outline-none"
        />
      </div>

      <!-- Details Textarea -->
      <div class="mb-4">
        <textarea
          placeholder="Type more details"
          rows="4"
          class="w-full border border-gray-300 rounded px-3 py-2 text-gray-700 focus:ring-2 focus:ring-blue-500 focus:outline-none"
        ></textarea>
      </div>

      <!-- Quantity and Unit -->
      <div class="flex items-center space-x-4 mb-4">
        <input
          type="number"
          placeholder="Quantity"
          class="w-1/2 border border-gray-300 rounded px-3 py-2 text-gray-700 focus:ring-2 focus:ring-blue-500 focus:outline-none"
        />
        <select
          class="w-1/2 border border-gray-300 rounded px-3 py-2 text-gray-700 focus:ring-2 focus:ring-blue-500 focus:outline-none"
        >
          <option value="pcs">Pcs</option>
          <option value="kg">Kg</option>
          <option value="liters">Liters</option>
        </select>
      </div>

      <!-- Submit Button -->
      <button
        type="submit"
        class="w-full bg-blue-500 text-white py-2 rounded hover:bg-blue-600 focus:ring-2 focus:ring-blue-500 focus:ring-offset-2"
      >
        Send inquiry
      </button>
    </form>
  </div>
</div>


<!-- Recommended Items Section -->
<div class="p-8 bg-gray-50">
  <!-- Section Header -->
  <h2 class="text-xl font-bold mb-6">Recommended items</h2>

  <!-- Grid Layout for Products -->
  <div class="grid grid-cols-5 gap-6">
    <!-- Product Card -->
    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/T shirt.jpg" alt="T-shirt" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/jeans short.jpg" alt="Jeans shorts" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/winter coat.jpg" alt="Winter coat" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/jeans bag.jpg" alt="Jeans bag" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/lether wallet.jpg" alt="Leather wallet" class="w-full h-full object-contain" />
    </div>

    <!-- More Product Cards -->
    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/canon camera 2.jpg" alt="Canon camera" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/headset.jpg" alt="Headset for gaming" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/smart watch 5.jpg" alt="Smartwatch" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/blue wallet.jpg" alt="Blue wallet" class="w-full h-full object-contain" />
    </div>

    <div class="bg-white border border-gray-200 rounded-lg p-4 flex justify-center items-center">
      <img src="images/jeans bags.jpg" alt="Jeans bag for travel" class="w-full h-full object-contain" />
    </div>
  </div>
</div>

<!-- Extra Services Section -->
<div class="p-8 bg-gray-50">
  <!-- Section Header -->
  <h2 class="text-xl font-bold mb-6">Our extra services</h2>

  <!-- Grid Layout for Services -->
  <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
    <!-- Service Card 1 -->
    <div class="bg-white border border-gray-200 rounded-lg overflow-hidden">
      <img src="images/industry hubs.jpg" alt="Industry Hubs" class="w-full h-48 object-cover" />
    </div>

    <!-- Service Card 2 -->
    <div class="bg-white border border-gray-200 rounded-lg overflow-hidden">
      <img src="images/customize products.jpg" alt="Customize Products" class="w-full h-48 object-cover" />
    </div>

    <!-- Service Card 3 -->
    <div class="bg-white border border-gray-200 rounded-lg overflow-hidden">
      <img src="images/reliable shipping.jpg" alt="Reliable Shipping" class="w-full h-48 object-cover" />
    </div>

    <!-- Service Card 4 -->
    <div class="bg-white border border-gray-200 rounded-lg overflow-hidden">
      <img src="images/product monitoring.jpg" alt="Product Monitoring" class="w-full h-48 object-cover" />
    </div>
  </div>
</div>


<div class="bg-gray-50 p-6">
  <!-- Section Header -->
  <h2 class="text-xl font-bold mb-4">Suppliers by region</h2>
  
  <!-- Grid Layout for Regions -->
  <div class="grid grid-cols-2 sm:grid-cols-4 gap-6">
    <!-- Region Card 1 -->
    <div class="flex items-center space-x-2">
      <img src="images/arabic emirates.jpg" alt="UAE Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">Arabic Emirates</p>
        <p class="text-gray-500 text-sm">shopname.ae</p>
      </div>
    </div>
    <!-- Region Card 2 -->
    <div class="flex items-center space-x-2">
      <img src="images/australia.jpg" alt="Australia Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">Australia</p>
        <p class="text-gray-500 text-sm">shopname.ae</p>
      </div>
    </div>
    <!-- Region Card 3 -->
    <div class="flex items-center space-x-2">
      <img src="images/united states.jpg" alt="United States Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">United States</p>
        <p class="text-gray-500 text-sm">shopname.ae</p>
      </div>
    </div>
    <!-- Region Card 4 -->
    <div class="flex items-center space-x-2">
      <img src="images/russia.jpg" alt="Russia Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">Russia</p>
        <p class="text-gray-500 text-sm">shopname.ru</p>
      </div>
    </div>
    <!-- Region Card 5 -->
    <div class="flex items-center space-x-2">
      <img src="images/italy.jpg" alt="Italy Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">Italy</p>
        <p class="text-gray-500 text-sm">shopname.it</p>
      </div>
    </div>
    <!-- Region Card 6 -->
    <div class="flex items-center space-x-2">
      <img src="images/denmark.jpg" alt="Denmark Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">Denmark</p>
        <p class="text-gray-500 text-sm">denmark.com.dk</p>
      </div>
    </div>
    <!-- Region Card 7 -->
    <div class="flex items-center space-x-2">
      <img src="images/france.jpg" alt="France Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">France</p>
        <p class="text-gray-500 text-sm">shopname.com.fr</p>
      </div>
    </div>
    <!-- Region Card 8 -->
    <div class="flex items-center space-x-2">
      <img src="images/china.jpg" alt="China Flag" class="w-6 h-6">
      <div>
        <p class="text-gray-800 font-medium">China</p>
        <p class="text-gray-500 text-sm">shopname.ae</p>
      </div>
    </div>
  </div>
</div>

<!-- Newsletter Subscription Section -->
<section class="bg-gray-100 py-12">
  <div class="container mx-auto text-center">
    <h3 class="text-2xl font-bold">Subscribe to Our Newsletter</h3>
    <p class="mt-2 text-gray-600">Get daily news on upcoming offers from many suppliers all over the world.</p>
    <form class="mt-6 flex justify-center">
      <input type="email" placeholder="Email" 
             class="px-4 py-2 border rounded-l-md focus:outline-none focus:ring-2 focus:ring-blue-500">
      <button type="submit" 
              class="bg-blue-500 text-white px-6 py-2 rounded-r-md hover:bg-blue-700">
        Subscribe
      </button>
    </form>
  </div>
</section>

  <!-- Footer Section -->
  <footer class="bg-white py-8 border-t border-gray-200">
    <div class="container mx-auto px-6 lg:px-16">
      <div class="grid grid-cols-1 lg:grid-cols-5 gap-8 items-start">
        <!-- Brand Section -->
        <div class="col-span-1 text-center lg:text-left">
          <img src="images/logo.jpg" alt="Brand Logo" class="h-12 mx-auto lg:mx-0">
          <h2 class="text-lg font-bold text-gray-800 mt-4">Brand</h2>
          <p class="text-sm text-gray-600 mt-2">Best information about the company goes here but now lorem ipsum is</p>
          <div class="flex justify-center lg:justify-start mt-4 space-x-3">
            <a href="#" class="text-gray-500 hover:text-gray-800">
              <i class="fab fa-facebook-f"></i>
            </a>
            <a href="#" class="text-gray-500 hover:text-gray-800">
              <i class="fab fa-twitter"></i>
            </a>
            <a href="#" class="text-gray-500 hover:text-gray-800">
              <i class="fab fa-linkedin"></i>
            </a>
            <a href="#" class="text-gray-500 hover:text-gray-800">
              <i class="fab fa-instagram"></i>
            </a>
            <a href="#" class="text-gray-500 hover:text-gray-800">
              <i class="fab fa-youtube"></i>
            </a>
          </div>
        </div>

        <!-- Links Section -->
        <div class="col-span-3 grid grid-cols-2 lg:grid-cols-4 gap-4">
          <!-- About Section -->
          <div>
            <h3 class="text-md font-semibold text-gray-800">About</h3>
            <ul class="mt-2 space-y-2 text-sm text-gray-600">
              <li><a href="#" class="hover:underline">About Us</a></li>
              <li><a href="#" class="hover:underline">Find Store</a></li>
              <li><a href="#" class="hover:underline">Categories</a></li>
              <li><a href="#" class="hover:underline">Blogs</a></li>
            </ul>
          </div>

          <!-- Partnership Section -->
          <div>
            <h3 class="text-md font-semibold text-gray-800">Partnership</h3>
            <ul class="mt-2 space-y-2 text-sm text-gray-600">
              <li><a href="#" class="hover:underline">About Us</a></li>
              <li><a href="#" class="hover:underline">Find Store</a></li>
              <li><a href="#" class="hover:underline">Categories</a></li>
              <li><a href="#" class="hover:underline">Blogs</a></li>
            </ul>
          </div>

          <!-- Information Section -->
          <div>
            <h3 class="text-md font-semibold text-gray-800">Information</h3>
            <ul class="mt-2 space-y-2 text-sm text-gray-600">
              <li><a href="#" class="hover:underline">Help Center</a></li>
              <li><a href="#" class="hover:underline">Money Refund</a></li>
              <li><a href="#" class="hover:underline">Shipping</a></li>
              <li><a href="#" class="hover:underline">Contact Us</a></li>
            </ul>
          </div>

          <!-- For Users Section -->
          <div>
            <h3 class="text-md font-semibold text-gray-800">For Users</h3>
            <ul class="mt-2 space-y-2 text-sm text-gray-600">
              <li><a href="#" class="hover:underline">Login</a></li>
              <li><a href="#" class="hover:underline">Register</a></li>
              <li><a href="#" class="hover:underline">Settings</a></li>
              <li><a href="#" class="hover:underline">My Orders</a></li>
            </ul>
          </div>
        </div>

        <!-- Get App Section -->
        <div class="col-span-1 text-center lg:text-left">
          <h3 class="text-md font-semibold text-gray-800">Get App</h3>
          <div class="mt-4">
            <a href="#">
              <img src="images/app store.png" alt="App Store" class="h-10 mx-auto lg:mx-0">
            </a>
            <a href="#">
              <img src="images/google play.jpg" alt="Google Play" class="h-10 mx-auto lg:mx-0">
            </a>
          </div>
        </div>
      </div>

      <!-- Footer Bottom -->
<div class="mt-8 flex justify-between items-center text-gray-500 text-sm">
  <p>&copy; 2023 Ecommerce.</p>
  <div class="flex items-center space-x-2">
    <img src="images/united states.jpg" alt="Flag" class="h-4 w-6 object-cover">
    <a href="#" class="text-gray-500 hover:underline">English</a>
  </div>
</div>
