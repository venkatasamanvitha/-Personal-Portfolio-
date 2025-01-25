# -Personal-Portfolio-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Portfolio</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100 text-gray-800">
    <!-- Header -->
    <header class="bg-white shadow-md fixed w-full top-0 z-10">
        <div class="container mx-auto px-4 py-4 flex justify-between items-center">
            <h1 class="text-xl font-bold">My Portfolio</h1>
            <nav>
                <ul class="flex space-x-4">
                    <li><a href="#about" class="hover:text-blue-500">About</a></li>
                    <li><a href="#portfolio" class="hover:text-blue-500">Portfolio</a></li>
                    <li><a href="#contact" class="hover:text-blue-500">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Hero Section -->
    <section class="bg-blue-500 text-white h-screen flex items-center justify-center">
        <div class="text-center">
            <h2 class="text-4xl font-bold">Hi, I'm [Your Name]</h2>
            <p class="text-xl mt-4">I build amazing websites and applications.</p>
            <a href="#portfolio" class="mt-6 inline-block bg-white text-blue-500 font-bold py-2 px-4 rounded-lg hover:bg-gray-200">View My Work</a>
        </div>
    </section>

    <!-- About Section -->
    <section id="about" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">About Me</h2>
            <p class="text-center max-w-2xl mx-auto">I'm a passionate web developer with experience in creating modern, responsive, and user-friendly websites. I enjoy solving problems and bringing ideas to life through code.</p>
        </div>
    </section>

    <!-- Portfolio Section -->
    <section id="portfolio" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Portfolio</h2>
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <!-- Portfolio Item -->
                <div class="bg-gray-100 rounded-lg shadow-md overflow-hidden">
                    <img src="https://via.placeholder.com/400x300" alt="Project Image" class="w-full">
                    <div class="p-4">
                        <h3 class="text-lg font-bold">Project Title</h3>
                        <p class="mt-2 text-sm">A brief description of the project goes here.</p>
                    </div>
                </div>
                <!-- Add more portfolio items as needed -->
            </div>
        </div>
    </section>

    <!-- Contact Section -->
    <section id="contact" class="py-16 bg-gray-100">
        <div class="container mx-auto px-4">
            <h2 class="text-3xl font-bold text-center mb-8">Contact Me</h2>
            <form class="max-w-xl mx-auto bg-white p-6 rounded-lg shadow-md">
                <div class="mb-4">
                    <label for="name" class="block text-sm font-bold mb-2">Name</label>
                    <input type="text" id="name" class="w-full px-4 py-2 border rounded-lg" placeholder="Your Name">
                </div>
                <div class="mb-4">
                    <label for="email" class="block text-sm font-bold mb-2">Email</label>
                    <input type="email" id="email" class="w-full px-4 py-2 border rounded-lg" placeholder="Your Email">
                </div>
                <div class="mb-4">
                    <label for="message" class="block text-sm font-bold mb-2">Message</label>
                    <textarea id="message" class="w-full px-4 py-2 border rounded-lg" rows="4" placeholder="Your Message"></textarea>
                </div>
                <button type="submit" class="w-full bg-blue-500 text-white py-2 px-4 rounded-lg hover:bg-blue-600">Send Message</button>
            </form>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-gray-800 text-white py-4">
        <div class="container mx-auto text-center">
            <p>&copy; 2025 [Your Name]. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
