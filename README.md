<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Personal Page - Mamun Sikder</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font: Inter */
        body {
            font-family: 'Inter', sans-serif;
        }
    </style>
</head>
<body class="bg-gray-100 text-gray-800">
    <header class="bg-white shadow-md py-4">
        <div class="container mx-auto px-4 flex justify-between items-center">
            <a href="#" class="text-2xl font-bold text-blue-800 rounded-md p-2 hover:bg-gray-50 transition duration-300">
                Mamun Sikder
            </a>
            <nav>
                <ul class="flex space-x-6">
                    <li><a href="#services" class="text-gray-700 hover:text-blue-800 font-medium rounded-md p-2 hover:bg-gray-100 transition duration-300">Services</a></li>
                    <li><a href="#about" class="text-gray-700 hover:text-blue-800 font-medium rounded-md p-2 hover:bg-gray-100 transition duration-300">About Me</a></li>
                    <li><a href="#contact" class="text-gray-700 hover:text-blue-800 font-medium rounded-md p-2 hover:bg-gray-100 transition duration-300">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section class="bg-gradient-to-r from-blue-800 to-blue-600 text-white py-20 md:py-28">
        <div class="container mx-auto px-4 text-center">
            <h1 class="text-4xl md:text-6xl font-extrabold leading-tight mb-6 rounded-lg p-2">
                Hello, I'm Mamun Sikder
            </h1>
            <p class="text-lg md:text-xl mb-10 max-w-3xl mx-auto rounded-md p-2 bg-white bg-opacity-10">
                A passionate Digital Marketing Specialist dedicated to helping businesses grow online. Explore my services and learn more about my expertise.
            </p>
            <a href="#services" class="inline-block bg-white text-blue-800 font-bold py-3 px-8 rounded-full text-lg shadow-lg hover:bg-gray-100 transform hover:scale-105 transition duration-300 ease-in-out">
                View My Services
            </a>
        </div>
    </section>

    <section id="services" class="py-16 md:py-24 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl md:text-4xl font-bold text-center mb-12 text-gray-900">What I Offer</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="bg-gray-50 p-8 rounded-xl shadow-md transform hover:scale-105 transition duration-300 ease-in-out border border-gray-200">
                    <div class="text-blue-700 mb-4">
                        <svg class="h-12 w-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 19v-6a2 2 0 00-2-2H5a2 2 0 00-2 2v6m3 0V7a2 2 0 012-2h2a2 2 0 012 2v12m0 0V5a2 2 0 012-2h2a2 2 0 012 2v14m0 0H9"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4 text-gray-900">Google Ads Management</h3>
                    <p class="text-gray-600 text-center">
                        Strategizing, setting up, and optimizing your Google Ads campaigns to maximize ROI and reach your target audience.
                    </p>
                </div>

                <div class="bg-gray-50 p-8 rounded-xl shadow-md transform hover:scale-105 transition duration-300 ease-in-out border border-gray-200">
                    <div class="text-green-700 mb-4">
                        <svg class="h-12 w-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M9 12l2 2 4-4m6 2a9 9 0 11-18 0 9 9 0 0118 0z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4 text-gray-900">Google Ads Conversion Tracking</h3>
                    <p class="text-gray-600 text-center">
                        Implementing precise conversion tracking to measure the effectiveness of your campaigns and optimize for desired actions.
                    </p>
                </div>

                <div class="bg-gray-50 p-8 rounded-xl shadow-md transform hover:scale-105 transition duration-300 ease-in-out border border-gray-200">
                    <div class="text-orange-700 mb-4">
                        <svg class="h-12 w-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M11 3.055A9.001 9.001 0 1020.945 13H11V3.055z"></path><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M20.488 9H15V3.512A9.025 9.025 0 0120.488 9z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4 text-gray-900">Google Analytics 4 Setup</h3>
                    <p class="text-gray-600 text-center">
                        Setting up GA4 properties to provide comprehensive insights into user behavior and website performance.
                    </p>
                </div>

                <div class="bg-gray-50 p-8 rounded-xl shadow-md transform hover:scale-105 transition duration-300 ease-in-out border border-gray-200">
                    <div class="text-purple-700 mb-4">
                        <svg class="h-12 w-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M3 6l3 1m0 0l-3 9a5 5 0 001.241 2.521A5 5 0 0012 18.5c.341 0 .676-.041 1-.122m-3-15V4a2 2 0 00-2-2H6a2 2 0 00-2 2v16a2 2 0 002 2h12a2 2 0 002-2V7.5M14 7l-3-3m0 0L7 7m0 0l3 3m0-3h4"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4 text-gray-900">GA4 E-commerce Tracking</h3>
                    <p class="text-gray-600 text-center">
                        Configuring detailed e-commerce tracking within GA4 to monitor sales funnels and product performance.
                    </p>
                </div>

                <div class="bg-gray-50 p-8 rounded-xl shadow-md transform hover:scale-105 transition duration-300 ease-in-out border border-gray-200">
                    <div class="text-red-700 mb-4">
                        <svg class="h-12 w-12 mx-auto" fill="none" stroke="currentColor" viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M13 10V3L4 14h7v7l9-11h-7z"></path></svg>
                    </div>
                    <h3 class="text-xl font-semibold text-center mb-4 text-gray-900">Facebook Pixel Setup</h3>
                    <p class="text-gray-600 text-center">
                        Installing and configuring Facebook Pixel for effective audience targeting, retargeting, and campaign optimization.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <section id="about" class="py-16 md:py-24 bg-gray-100">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-8 text-gray-900">About Mamun Sikder</h2>
            <p class="text-lg text-gray-700 max-w-4xl mx-auto mb-8">
                Hi there! I'm Mamun Sikder, a Digital Marketing Specialist with a passion for helping businesses achieve their online advertising goals. I thrive on optimizing campaigns and providing actionable insights. My goal is to drive measurable results and maximize your return on ad spend.
            </p>
            <img src="uploaded:MAMUN SIKDER.jpg-47eade30-452f-44d5-97ac-c0b07b515831" alt="Mamun Sikder's Profile Photo" class="mx-auto rounded-full shadow-lg max-w-full h-auto w-48 h-48 object-cover">
        </div>
    </section>

    <section id="contact" class="bg-blue-800 text-white py-16 md:py-20">
        <div class="container mx-auto px-4 text-center">
            <h2 class="text-3xl md:text-4xl font-bold mb-6">Ready to Boost Your Online Presence?</h2>
            <p class="text-lg mb-8 max-w-2xl mx-auto">
                Let's discuss how my expertise in Google Ads, GA4, and Facebook Pixel can help your business succeed.
            </p>
            <div class="flex flex-col items-center space-y-4 mb-8">
                <a href="mailto:skmamun.service@gmail.com" class="inline-block bg-white text-blue-800 font-bold py-3 px-8 rounded-full text-lg shadow-lg hover:bg-gray-100 transform hover:scale-105 transition duration-300 ease-in-out">
                    Email: skmamun.service@gmail.com
                </a>
                <a href="tel:+8801719972512" class="inline-block bg-white text-blue-800 font-bold py-3 px-8 rounded-full text-lg shadow-lg hover:bg-gray-100 transform hover:scale-105 transition duration-300 ease-in-out">
                    Phone: +8801719972512
                </a>
                <div class="flex space-x-6">
                    <a href="https://shorturl.at/JQv8H" target="_blank" rel="noopener noreferrer" class="text-white hover:text-blue-300 transition duration-300">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path fill-rule="evenodd" d="M22 12c0-5.523-4.477-10-10-10S2 6.477 2 12c0 4.991 3.657 9.128 8.438 9.878v-6.987h-2.54V12h2.54V9.797c0-2.506 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562V12h2.773l-.443 2.89h-2.33V22C18.343 21.128 22 16.991 22 12z" clip-rule="evenodd" />
                        </svg>
                    </a>
                    <a href="https://shorturl.at/w5yll" target="_blank" rel="noopener noreferrer" class="text-white hover:text-blue-300 transition duration-300">
                        <svg class="w-8 h-8" fill="currentColor" viewBox="0 0 24 24" aria-hidden="true">
                            <path d="M0 0h24v24H0z" fill="none"/>
                            <path d="M19 3a2 2 0 012 2v14a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h14zM8.6 15.6H6V9h2.6v6.6zM7.3 7.5a1.5 1.5 0 100-3 1.5 1.5 0 000 3zm6.7 8.1h-2.4V12c0-.6.1-1.1.3-1.4.3-.7.9-1.4 2.1-1.4s1.8.8 1.8 2.2v4.2h-2.4v-3.7c0-.9-.2-1.6-1.1-1.6-.8 0-1.3.6-1.3 1.6v3.7H14z"/>
                        </svg>
                    </a>
                </div>
            </div>
            <p class="text-lg mb-8 max-w-2xl mx-auto">
                Connect with me on social media or send an email to discuss your digital marketing needs.
            </p>
        </div>
    </section>

    <footer class="bg-gray-900 text-gray-300 py-8">
        <div class="container mx-auto px-4 text-center">
            <p>&copy; 2025 Mamun Sikder. All rights reserved.</p>
            <div class="flex justify-center space-x-6 mt-4">
                <a href="#" class="hover:text-white transition duration-300">Privacy Policy</a>
                <a href="#" class="hover:text-white transition duration-300">Terms of Service</a>
            </div>
        </div>
    </footer>
</body>
</html>
