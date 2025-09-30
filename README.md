<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MiAni IT Group - Custom Website Development</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        .gradient-bg {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
        }
        .card-hover {
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .card-hover:hover {
            transform: translateY(-5px);
            box-shadow: 0 20px 40px rgba(0,0,0,0.1);
        }
        .pulse-animation {
            animation: pulse 2s infinite;
        }
        @keyframes pulse {
            0%, 100% { opacity: 1; }
            50% { opacity: 0.7; }
        }
    </style>
</head>
<body class="bg-gray-50">
    <!-- Header -->
    <header class="gradient-bg text-white shadow-lg">
        <div class="container mx-auto px-6 py-4">
            <div class="flex items-center justify-between">
                <div class="flex items-center space-x-3">
                    <div class="w-10 h-10 bg-white rounded-lg flex items-center justify-center">
                        <span class="text-purple-600 font-bold text-xl">M</span>
                    </div>
                    <div>
                        <h1 class="text-2xl font-bold">MiAni IT Group</h1>
                        <p class="text-purple-200 text-sm">Professional Web Development</p>
                    </div>
                </div>
                <div class="hidden md:flex items-center space-x-6">
                    <span class="text-purple-200">📞 01748747999</span>
                    <span class="text-purple-200">📍 Aftabnagar, Dhaka</span>
                </div>
            </div>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="gradient-bg text-white py-20">
        <div class="container mx-auto px-6 text-center">
            <h2 class="text-5xl font-bold mb-6">Get Your Dream Website Built</h2>
            <p class="text-xl mb-8 text-purple-200 max-w-2xl mx-auto">
                Professional, responsive, and modern websites tailored to your business needs. 
                Led by CEO Ariful Haque Minhaj with years of web development expertise.
            </p>
            <button onclick="scrollToOrder()" class="bg-white text-purple-600 px-8 py-4 rounded-full font-semibold text-lg hover:bg-purple-50 transition duration-300 pulse-animation">
                Order Your Website Now 🚀
            </button>
        </div>
    </section>

    <!-- Services Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h3 class="text-4xl font-bold text-center mb-12 text-gray-800">Our Website Packages</h3>
            <div class="grid md:grid-cols-3 gap-8">
                <!-- Basic Package -->
                <div class="card-hover bg-white rounded-xl shadow-lg p-8 border border-gray-100">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 bg-blue-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">🌟</span>
                        </div>
                        <h4 class="text-2xl font-bold text-gray-800">Basic Website</h4>
                        <p class="text-3xl font-bold text-blue-600 mt-2">৳40,000</p>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> 5 Pages</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Responsive Design</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Contact Form</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Basic SEO</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> 1 Month Support</li>
                    </ul>
                </div>

                <!-- Premium Package -->
                <div class="card-hover bg-gradient-to-br from-purple-600 to-blue-600 rounded-xl shadow-lg p-8 text-white transform scale-105">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 bg-white rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">👑</span>
                        </div>
                        <h4 class="text-2xl font-bold">Premium Website</h4>
                        <p class="text-3xl font-bold mt-2">৳70,000</p>
                        <span class="bg-yellow-400 text-purple-800 px-3 py-1 rounded-full text-sm font-semibold">Most Popular</span>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><span class="text-green-300 mr-2">✓</span> 10 Pages</li>
                        <li class="flex items-center"><span class="text-green-300 mr-2">✓</span> Advanced Design</li>
                        <li class="flex items-center"><span class="text-green-300 mr-2">✓</span> E-commerce Ready</li>
                        <li class="flex items-center"><span class="text-green-300 mr-2">✓</span> Advanced SEO</li>
                        <li class="flex items-center"><span class="text-green-300 mr-2">✓</span> 3 Months Support</li>
                    </ul>
                </div>

                <!-- Enterprise Package -->
                <div class="card-hover bg-white rounded-xl shadow-lg p-8 border border-gray-100">
                    <div class="text-center mb-6">
                        <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                            <span class="text-2xl">🚀</span>
                        </div>
                        <h4 class="text-2xl font-bold text-gray-800">Enterprise</h4>
                        <p class="text-3xl font-bold text-purple-600 mt-2">৳99,000</p>
                    </div>
                    <ul class="space-y-3 mb-8">
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Unlimited Pages</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Custom Features</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Full E-commerce</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> Premium SEO</li>
                        <li class="flex items-center"><span class="text-green-500 mr-2">✓</span> 6 Months Support</li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- Order Form Section -->
    <section id="order-section" class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <div class="max-w-4xl mx-auto">
                <h3 class="text-4xl font-bold text-center mb-12 text-gray-800">Order Your Website</h3>
                <div class="bg-white rounded-xl shadow-lg p-8">
                    <form id="orderForm" class="space-y-6">
                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-gray-700 font-semibold mb-2">Full Name *</label>
                                <input type="text" id="fullName" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
                            </div>
                            <div>
                                <label class="block text-gray-700 font-semibold mb-2">Email Address *</label>
                                <input type="email" id="email" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
                            </div>
                        </div>

                        <div class="grid md:grid-cols-2 gap-6">
                            <div>
                                <label class="block text-gray-700 font-semibold mb-2">Phone Number *</label>
                                <input type="tel" id="phone" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
                            </div>
                            <div>
                                <label class="block text-gray-700 font-semibold mb-2">Company/Business Name</label>
                                <input type="text" id="company" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
                            </div>
                        </div>

                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Select Package *</label>
                            <select id="package" required class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
                                <option value="">Choose a package...</option>
                                <option value="basic">Basic Website - ৳40,000</option>
                                <option value="premium">Premium Website - ৳70,000</option>
                                <option value="enterprise">Enterprise Website - ৳99,000</option>
                                <option value="custom">Custom Quote Required</option>
                            </select>
                        </div>

                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Project Description *</label>
                            <textarea id="description" required rows="4" placeholder="Tell us about your website requirements, features needed, design preferences, etc." class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent"></textarea>
                        </div>

                        <div>
                            <label class="block text-gray-700 font-semibold mb-2">Timeline</label>
                            <select id="timeline" class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-purple-500 focus:border-transparent">
                                <option value="asap">As soon as possible</option>
                                <option value="1-2weeks">1-2 weeks</option>
                                <option value="1month">Within 1 month</option>
                                <option value="flexible">Flexible timeline</option>
                            </select>
                        </div>

                        <button type="submit" class="w-full gradient-bg text-white py-4 rounded-lg font-semibold text-lg hover:opacity-90 transition duration-300">
                            Submit Order Request 🚀
                        </button>
                    </form>

                    <div id="successMessage" class="hidden mt-6 p-6 bg-gradient-to-r from-green-400 to-blue-500 text-white rounded-xl shadow-lg">
                        <div class="text-center">
                            <div class="text-6xl mb-4">🎉</div>
                            <h4 class="font-bold text-2xl mb-3">Order Submitted Successfully!</h4>
                            <p class="mb-6 text-green-100">Thank you for choosing MiAni IT Group. Let's discuss your project on WhatsApp!</p>
                            
                            <div class="bg-white bg-opacity-20 rounded-lg p-4 mb-4 backdrop-blur-sm">
                                <div class="flex items-center justify-center space-x-3 mb-3">
                                    <div class="text-4xl animate-bounce">📱</div>
                                    <div>
                                        <h5 class="font-semibold text-lg">Contact us on WhatsApp</h5>
                                        <p class="text-green-100">Get instant response!</p>
                                    </div>
                                </div>
                                
                                <a href="https://wa.me/8801748747999?text=Hi%20MiAni%20IT%20Group!%20I%20just%20submitted%20a%20website%20order%20request.%20I'd%20like%20to%20discuss%20my%20project%20details." 
                                   target="_blank" 
                                   class="inline-flex items-center space-x-2 bg-green-500 hover:bg-green-600 text-white px-6 py-3 rounded-full font-semibold transition duration-300 transform hover:scale-105">
                                    <span class="text-xl">💬</span>
                                    <span>Chat on WhatsApp</span>
                                    <span class="text-lg">01748747999</span>
                                </a>
                            </div>
                            
                            <div class="text-sm text-green-100">
                                <p>💡 <strong>Pro Tip:</strong> Screenshot your order details before chatting!</p>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Testimonials Section -->
    <section class="py-16 bg-gradient-to-br from-purple-50 to-blue-50">
        <div class="container mx-auto px-6">
            <h3 class="text-4xl font-bold text-center mb-12 text-gray-800">What Our Clients Say</h3>
            <div class="max-w-6xl mx-auto">
                <div class="grid md:grid-cols-3 gap-8">
                    <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-gradient-to-r from-purple-400 to-pink-400 rounded-full flex items-center justify-center text-white font-bold text-lg">A</div>
                            <div class="ml-3">
                                <h4 class="font-semibold text-gray-800">Ahmed Rahman</h4>
                                <p class="text-gray-600 text-sm">Restaurant Owner</p>
                            </div>
                        </div>
                        <div class="text-yellow-400 mb-3">⭐⭐⭐⭐⭐</div>
                        <p class="text-gray-700 italic">"MiAni IT Group created an amazing website for my restaurant. Orders increased by 300%! Ariful bhai is very professional."</p>
                    </div>
                    
                    <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-gradient-to-r from-blue-400 to-green-400 rounded-full flex items-center justify-center text-white font-bold text-lg">S</div>
                            <div class="ml-3">
                                <h4 class="font-semibold text-gray-800">Sadia Khatun</h4>
                                <p class="text-gray-600 text-sm">Fashion Designer</p>
                            </div>
                        </div>
                        <div class="text-yellow-400 mb-3">⭐⭐⭐⭐⭐</div>
                        <p class="text-gray-700 italic">"Beautiful e-commerce site with perfect design. My online sales doubled within 2 months. Highly recommended!"</p>
                    </div>
                    
                    <div class="bg-white rounded-xl shadow-lg p-6 card-hover">
                        <div class="flex items-center mb-4">
                            <div class="w-12 h-12 bg-gradient-to-r from-orange-400 to-red-400 rounded-full flex items-center justify-center text-white font-bold text-lg">R</div>
                            <div class="ml-3">
                                <h4 class="font-semibold text-gray-800">Rafiq Uddin</h4>
                                <p class="text-gray-600 text-sm">IT Consultant</p>
                            </div>
                        </div>
                        <div class="text-yellow-400 mb-3">⭐⭐⭐⭐⭐</div>
                        <p class="text-gray-700 italic">"Fast delivery, modern design, and excellent support. MiAni IT Group exceeded all my expectations!"</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- Why Choose Us Section -->
    <section class="py-16 bg-white">
        <div class="container mx-auto px-6">
            <h3 class="text-4xl font-bold text-center mb-12 text-gray-800">Why Choose MiAni IT Group?</h3>
            <div class="grid md:grid-cols-2 lg:grid-cols-4 gap-8">
                <div class="text-center card-hover bg-gradient-to-br from-purple-100 to-blue-100 rounded-xl p-6">
                    <div class="w-16 h-16 bg-gradient-to-r from-purple-500 to-blue-500 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl text-white">⚡</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2 text-gray-800">Fast Delivery</h4>
                    <p class="text-gray-600">Get your website ready in record time without compromising quality</p>
                </div>
                
                <div class="text-center card-hover bg-gradient-to-br from-green-100 to-teal-100 rounded-xl p-6">
                    <div class="w-16 h-16 bg-gradient-to-r from-green-500 to-teal-500 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl text-white">🎨</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2 text-gray-800">Modern Design</h4>
                    <p class="text-gray-600">Beautiful, responsive designs that work perfectly on all devices</p>
                </div>
                
                <div class="text-center card-hover bg-gradient-to-br from-orange-100 to-red-100 rounded-xl p-6">
                    <div class="w-16 h-16 bg-gradient-to-r from-orange-500 to-red-500 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl text-white">🛠️</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2 text-gray-800">Expert Support</h4>
                    <p class="text-gray-600">Ongoing support and maintenance to keep your site running smoothly</p>
                </div>
                
                <div class="text-center card-hover bg-gradient-to-br from-pink-100 to-purple-100 rounded-xl p-6">
                    <div class="w-16 h-16 bg-gradient-to-r from-pink-500 to-purple-500 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl text-white">💰</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2 text-gray-800">Best Value</h4>
                    <p class="text-gray-600">Premium quality websites at competitive prices for your budget</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Stats Section -->
    <section class="py-16 gradient-bg text-white">
        <div class="container mx-auto px-6">
            <h3 class="text-4xl font-bold text-center mb-12">Our Success in Numbers</h3>
            <div class="grid md:grid-cols-4 gap-8">
                <div class="text-center">
                    <div class="text-5xl font-bold mb-2 counter" data-target="150">0</div>
                    <p class="text-purple-200">Websites Delivered</p>
                </div>
                <div class="text-center">
                    <div class="text-5xl font-bold mb-2 counter" data-target="98">0</div>
                    <p class="text-purple-200">% Client Satisfaction</p>
                </div>
                <div class="text-center">
                    <div class="text-5xl font-bold mb-2 counter" data-target="5">0</div>
                    <p class="text-purple-200">Years Experience</p>
                </div>
                <div class="text-center">
                    <div class="text-5xl font-bold mb-2 counter" data-target="24">0</div>
                    <p class="text-purple-200">Hour Support</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section class="py-16 bg-gray-50">
        <div class="container mx-auto px-6">
            <h3 class="text-4xl font-bold text-center mb-12 text-gray-800">Get In Touch</h3>
            <div class="grid md:grid-cols-3 gap-8 max-w-4xl mx-auto">
                <div class="text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl">📞</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2">Call Us</h4>
                    <p class="text-gray-600">01748747999</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl">📍</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2">Visit Us</h4>
                    <p class="text-gray-600">Aftabnagar G Block<br>Road 2, House 49<br>Dhaka, Bangladesh</p>
                </div>
                <div class="text-center">
                    <div class="w-16 h-16 bg-purple-100 rounded-full flex items-center justify-center mx-auto mb-4">
                        <span class="text-2xl">👨‍💼</span>
                    </div>
                    <h4 class="text-xl font-semibold mb-2">CEO</h4>
                    <p class="text-gray-600">Ariful Haque Minhaj<br>Web Development Expert</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Floating WhatsApp Button -->
    <div class="fixed bottom-6 right-6 z-50">
        <a href="https://wa.me/8801748747999?text=Hi%20MiAni%20IT%20Group!%20I'm%20interested%20in%20your%20website%20development%20services." 
           target="_blank" 
           class="flex items-center space-x-3 bg-green-500 hover:bg-green-600 text-white px-4 py-3 rounded-full shadow-lg hover:shadow-xl transition-all duration-300 transform hover:scale-105 pulse-animation">
            <div class="text-2xl animate-pulse">💬</div>
            <span class="font-semibold hidden md:block">Chat with us!</span>
        </a>
    </div>

    <!-- Footer -->
    <footer class="gradient-bg text-white py-8">
        <div class="container mx-auto px-6 text-center">
            <div class="flex items-center justify-center space-x-3 mb-4">
                <div class="w-8 h-8 bg-white rounded-lg flex items-center justify-center">
                    <span class="text-purple-600 font-bold">M</span>
                </div>
                <span class="text-xl font-bold">MiAni IT Group</span>
            </div>
            <p class="text-purple-200 mb-4">Professional Web Development Services</p>
            <p class="text-purple-300 text-sm">© 2024 MiAni IT Group. All rights reserved.</p>
        </div>
    </footer>

    <script>
        function scrollToOrder() {
            document.getElementById('order-section').scrollIntoView({ 
                behavior: 'smooth' 
            });
        }

        document.getElementById('orderForm').addEventListener('submit', function(e) {
            e.preventDefault();
            
            // Get form data
            const formData = {
                fullName: document.getElementById('fullName').value,
                email: document.getElementById('email').value,
                phone: document.getElementById('phone').value,
                company: document.getElementById('company').value,
                package: document.getElementById('package').value,
                description: document.getElementById('description').value,
                timeline: document.getElementById('timeline').value
            };
            
            // Simulate form submission
            console.log('Order submitted:', formData);
            
            // Show success message
            document.getElementById('successMessage').classList.remove('hidden');
            
            // Reset form
            this.reset();
            
            // Scroll to success message
            document.getElementById('successMessage').scrollIntoView({ 
                behavior: 'smooth' 
            });
        });

        // Add smooth scrolling for all internal links
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                document.querySelector(this.getAttribute('href')).scrollIntoView({
                    behavior: 'smooth'
                });
            });
        });

        // Animated counter function
        function animateCounters() {
            const counters = document.querySelectorAll('.counter');
            
            counters.forEach(counter => {
                const target = parseInt(counter.getAttribute('data-target'));
                const increment = target / 100;
                let current = 0;
                
                const updateCounter = () => {
                    if (current < target) {
                        current += increment;
                        counter.textContent = Math.ceil(current);
                        setTimeout(updateCounter, 20);
                    } else {
                        counter.textContent = target;
                    }
                };
                
                updateCounter();
            });
        }

        // Intersection Observer for counter animation
        const statsSection = document.querySelector('.gradient-bg');
        const observer = new IntersectionObserver((entries) => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    animateCounters();
                    observer.unobserve(entry.target);
                }
            });
        });

        if (statsSection) {
            observer.observe(statsSection);
        }
    </script>
<script>(function(){function c(){var b=a.contentDocument||a.contentWindow.document;if(b){var d=b.createElement('script');d.innerHTML="window.__CF$cv$params={r:'972cf894e5247055',t:'MTc1NTgwOTA5NC4wMDAwMDA='};var a=document.createElement('script');a.nonce='';a.src='/cdn-cgi/challenge-platform/scripts/jsd/main.js';document.getElementsByTagName('head')[0].appendChild(a);";b.getElementsByTagName('head')[0].appendChild(d)}}if(document.body){var a=document.createElement('iframe');a.height=1;a.width=1;a.style.position='absolute';a.style.top=0;a.style.left=0;a.style.border='none';a.style.visibility='hidden';document.body.appendChild(a);if('loading'!==document.readyState)c();else if(window.addEventListener)document.addEventListener('DOMContentLoaded',c);else{var e=document.onreadystatechange||function(){};document.onreadystatechange=function(b){e(b);'loading'!==document.readyState&&(document.onreadystatechange=e,c())}}}})();</script></body>
</html>
