<template>
    <div class="scroll-smooth">

<!-- 
    
<nav class="border-gray-200 bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
  <div class="max-w-screen-xl flex flex-wrap items-center justify-between mx-auto p-4">
    <a href="#" class="flex items-center">
        <img src="https://flowbite.com/docs/images/logo.svg" class="h-8 mr-3" alt="Flowbite Logo" />
        <span class="self-center text-2xl font-semibold whitespace-nowrap dark:text-white">Flowbite</span>
    </a>
    <button data-collapse-toggle="navbar-hamburger" type="button" class="inline-flex items-center justify-center p-2 w-10 h-10 ml-3 text-sm text-gray-500 rounded-lg hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-hamburger" aria-expanded="false">
      <span class="sr-only">Open main menu</span>
      <svg class="w-5 h-5" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 17 14">
          <path stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M1 1h15M1 7h15M1 13h15"/>
      </svg>
    </button>
    <div class="hidden w-full" id="navbar-hamburger">
      <ul class="flex flex-col font-medium mt-4 rounded-lg bg-gray-50 dark:bg-gray-800 dark:border-gray-700">
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-white bg-blue-700 rounded dark:bg-blue-600" aria-current="page">Home</a>
        </li>
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">Services</a>
        </li>
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 md:dark:hover:text-white dark:hover:bg-gray-700 dark:hover:text-white">Pricing</a>
        </li>
        <li>
          <a href="#" class="block py-2 pl-3 pr-4 text-gray-900 rounded hover:bg-gray-100 dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white">Contact</a>
        </li>
      </ul>
    </div>
  </div>
</nav>

 -->

        <!-- main nav -->
        <nav class="fixed bg-ash-500 w-full md:h-20">
            <div class="text-white md:px-40">
                <div class="hidden md:flex mx-auto md:px-6 items-center">

                    <!-- logo -->

                    <div class="flex ">
                        <img src="~/assets/mti.png" class="w-8" alt="">
                        <p class="text-2xl tracking-widest ">MetaMask</p>
                    </div>
                    <!-- primary nav -->
                    <div class="flex mx-auto py-6 items-center space-x-10">
                        <a href="#">Features </a>
                        <a href="#">Build </a>
                        <a href="#">Resourses </a>
                        <a href="#">Learn </a>

                        <button class="bg-blue-500 hover:bg-blue-700 cursor-pointer rounded-full h-10 py-2 px-4 inline-flex items-center font-bold text-white">
                            Download
                        </button>
<div>
    <svg xmlns="http://www.w3.org/2000/svg" width="40" height="40" viewBox="0 0 512 512"><path fill="white" d="M368 112H144a144 144 0 0 0 0 288h224a144 144 0 0 0 0-288Zm0 230a86 86 0 1 1 86-86a85.88 85.88 0 0 1-86 86Z"/></svg>
</div>
    
</div>
                    
                </div>


            <!-- mobile menu -->
<div id="mobile-menu" class="sm:hidden">
<div class="justify-between px-6 py-4 flex items-center">
    <div class="flex items-center space-x-2">
        <img src="~/assets/mti.png" class="h-10" alt="">
        <p class="text-2xl text-white tracking-widest ">MetaMask</p>
    </div>
    <div class=" mobile-menu-button hover:cursor-pointer hover:bg-gray-800 hover:rounded-sm text-white">
        <!-- menu Icon -->
        <svg xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24"><path fill="none" stroke="currentColor" stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M6 8h12M6 12h12M6 16h12"/></svg>
    </div>
</div>
</div>
</div>
<!-- mobile menu goes here -->
<div class="hidden mobile-menu md:hidden py-2 px-8 text-white">
    <a href="#" class="block pt-2">Features </a>
    <a href="#" class="block pt-4">Build </a>
    <a href="#" class="block pt-4">Resourses </a>
    <a href="#" class="block pt-4">Learn </a>
</div>
</nav>


        <!-- Hero header -->
        <div class="bg-black pt-40 text-white">
        <div class="container mx-auto md:pl-40 md:flex items-center">
            <div class="">
                <h1 class="text-center md:w-80 md:text-left text-white text-4xl font-extrabold leading-normal tracking-tight ">
                    A crypto wallet & gateway to blockchain apps
                </h1>
                <p class="text-center md:text-left md:w-80">
                    Start exploring blockchain applications in seconds. Trusted by over 30 million users worldwide.
                </p>
                <div class="md:justify-start flex pt-4 justify-center">
                    <button class="bg-blue-500 hover:bg-blue-600 text-white font-bold py-2 px-4 rounded-full md:items-center  ">
                        Download for <span class="px-2 "><Icon name="logos:chrome" /></span>
                    </button>
                </div>
            </div>
            <img src="~/assets/pic2.jpg" class="max-w-md mx-auto" alt="">
            </div>
            
            <div class="mx-auto items-center">
                <p class="text-center">LEARN MORE</p>
            </div> 

               <div class="text-center">
            <Icon name="ps:down" color="white" class="text-center" />   
            </div>

            <!-- hero 1 -->
            <div class="bg-black pt-40 text-white">
        <div class="container mx-auto md:pl-40 md:flex items-center">
            <div class="">
                <h1 class="text-center md:text-left text-white text-2xl font-bold leading-normal tracking-tight ">
                    Buy, store, send and swap tokens</h1>
                <p class="text-center md:text-left md:w-96">
                    Available as a browser extension and as a mobile app, MetaMask equips you with a key vault, secure login, token wallet, and token exchange—everything you need to manage your digital assets.
                </p>
            </div>
            <img src="~/assets/pic3.png" class="max-w-md mx-auto" alt="">
            </div>
            </div>

            <!-- hero 2 -->
        <div class="lg:hidden mx-auto items-center px-4 md:flex">
            <div>
                <h1 class="text-left sm:text-center max-w-md text-3xl font-semibold leading-normal text-gray-100">
                    Explore blockchain apps</h1>
                    <p class="flex sm:text-center">
                        MetaMask provides the simplest yet most secure way to connect to blockchain-based applications. You are always in control when interacting on the new decentralized web.
                    </p>
                </div>
                <div class="">
                    <img src="~/assets/Explore-illo.svg" class="h-auto max-w-md mx-auto" alt="">
                </div>
            </div>
<!-- small screen -->
        <div class="hidden md:flex md:mx-auto items-center px-4">
            <div class="">
                <img src="~/assets/Explore-illo.svg" class="h-auto max-w-md mx-auto" alt="">
            </div>
            <div>
                <h1 class="text-left max-w-lg text-3xl font-semibold leading-normal text-gray-100">
                    A crypto wallet & gateway to blockchain apps
                </h1>
                <p class="text-left">
                    Start exploring blockchain applications in seconds. Trusted by over 30 million users worldwide.
                </p>
            </div>
            </div>


            <!-- hero 3 -->
        <div class="container mx-auto items-center px-4 md:flex">
            <div>
                <h1 class="text-left max-w-lg text-3xl font-semibold leading-normal text-gray-100">
                    A crypto wallet & gateway to blockchain apps
                </h1>
                <p class="text-left">
                    Start exploring blockchain applications in seconds. Trusted by over 30 million users worldwide.
                </p>
            </div>
                    <img src="~/assets/Browse-illo.svg" class="h-auto max-w-md mx-auto" alt="">
            </div>

            <div class="p-10 bg-gray-800 text-center mx-auto items-center ">

                <img class=" mx-auto w-60" src="~/assets/mt2.png" alt="">

                <p class="mt-20 mb-8 font-semibold text-2xl text-white ">Get Started</p>
                <button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:ring-4 focus:ring-blue-300 font-medium rounded-full text-sm px-5 py-2.5 mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 focus:outline-none dark:focus:ring-blue-800">
                    Download Metamask Today
                </button>
            </div>
        </div>

            <div class="w-full max-w-screen-lg mx-auto p-4">
  <div class="aspect-w-16 aspect-h-9">
    <p class="text-center font-bold text-2xl p-4">What is MetaMask?</p>
    <iframe
      class="w-full h-full"
      src="https://youtu.be/YVgfHZMFFFQ"
      frameborder="0"
      allowfullscreen
    ></iframe>
  </div>
</div>

<div class="border bg-gray-200">
    <p class="font-bold text-center p-4 text-2xl ">your key to blockchain applications</p>
    <p class="text-center">MetaMask is the leading self-custodial wallet. The safe and simple way to access blockchain applications and web3. Trusted by millions of users worldwide.</p>
    <div class="container  grid grid-cols-4">
        <div>
            <img src="~/assets/dapp-aave.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-axieinfinity.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-compound.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-gitcoin.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-maker.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-opensea.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-rarible.webp" alt="">
        </div>
        <div>
            <img src="~/assets/dapp-uniswap.webp" alt="">
        </div>
        
    </div>
</div>

<div class="border bg-gray-800 p-10 text-center text-white">
    <p class="">Developers</p>
    <p>MetaMask is powered by a strong community from across the globe. Interested in contributing? Find out how and what to contribute using the resources below.</p>
    <p>Open Issues></p>
    <p>Open Bounties></p>
    <p>Documentation></p>
    <p>Contributing Guidelines></p>
</div>

<div class="border bg-gray-500 flex mx-auto items-center">
    <div>
        <img class="w-80" src="~/assets/pic1.jpg" alt="">
        <button class="text-center">Shop Now</button>
        <p class="font-bold text-white text-center text-2xl p-4">Shop MetaMask Swag</p>
    </div>
</div>

<div>
    <p>
        Recieve our Newsletters
    </p>
    <p>
        signup to recieve updates and announcements
    </p>
</div>
<button type="button" class="text-white bg-blue-700 hover:bg-blue-800 focus:outline-none focus:ring-4 focus:ring-blue-300 font-medium rounded-full text-sm px-5 py-2.5 text-center mr-2 mb-2 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Sign Up</button>

<!-- ////////////////////FOOTER -->

<footer class="bg-gray-950 ">
    <div class="flex text-white ">
                    <img src="~/assets/mti.png" class="w-8 " alt="">
                    <p class="font-bold-sm tracking-widest ">MetaMask</p>
                    </div>

    <div class="grid grid-cols-1 md:grid-cols-3 text-white text-center mx-auto gap-4">
        

<div class="">
    <p>LEARN MORE</p>
    <ul class="">
        <li>
            About
        </li>
        <li>
            Developers Docs
        </li>
        <li>
            Download
        </li>
        <li>
            Metamask Mask
        </li>
        <li>
            Institutional News
        </li>
        <li>
            Security
        </li>
    </ul>
</div>

<div class="">
    <p>GET INVOLVED</p>
    <ul class="">
        <li>
            GitHub
        </li>
        <li>
            GitCoin
        </li>
        <li>
            Open Positions
        </li>
        <li>
            SwagShip
        </li>
        <li>
            Press & Partnershops
        </li>
    </ul>
</div>

<div>
    <p>LEGAL</p>
    <ul>
        <li>Privacy Policy</li>
        <li>Terms of use</li>
        <li>Contributor License Agreement</li>
        <li>Site Map</li>
    </ul>
</div>
                    </div>
                    <div class="px-4 py-6 md:flex md:items-center md:justify-between">
        <span class="text-sm text-gray-500 dark:text-gray-300 sm:text-center">© 2023 <a href="https://metamask.io/">MetaMask</a> • A Consensys Formation
        </span>
      </div>
      
    </footer>
        
    </div>
</template>

<script>
// grab everything we need
// const btn = document.querySelector("button.mobile-menu-button");
// const menu = document.querySelector(".mobile-menu");

// add event listeners
// btn.addEventListener("click", (e) => {
//     menu.classList.toggle('hidden');
// });

export default{};
</script>