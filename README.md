# tomoboriowo185-svg.github.io
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Name | Video Editor</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-black text-white">
    <!-- Hero -->
    <section class="min-h-screen flex items-center justify-center text-center p-6">
        <div>
            <h1 class="text-6xl font-bold mb-4">YOUR NAME</h1>
            <p class="text-xl text-gray-400 mb-8">Video Editor & Motion Designer</p>
            <a href="#work" class="bg-red-500 px-8 py-3 rounded-full">View My Work</a>
        </div>
    </section>

    <!-- Work Section -->
    <section id="work" class="py-20 px-6 max-w-6xl mx-auto">
        <h2 class="text-4xl font-bold mb-12">Selected Work</h2>
        
        <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
            <!-- Project 1 -->
            <div class="group cursor-pointer">
                <div class="aspect-video bg-gray-800 mb-4 overflow-hidden">
                    <video class="w-full h-full object-cover group-hover:scale-105 transition" 
                           poster="YOUR-THUMBNAIL.jpg" controls>
                        <source src="YOUR-VIDEO.mp4" type="video/mp4">
                    </video>
                </div>
                <h3 class="text-xl font-bold">Project Title</h3>
                <p class="text-gray-500">Client Name • 2024</p>
            </div>
            
            <!-- Add more projects by copying the block above -->
        </div>
    </section>

    <!-- Contact -->
    <section class="py-20 text-center">
        <h2 class="text-3xl font-bold mb-6">Let's Work Together</h2>
        <a href="mailto:youremail@example.com" class="text-2xl text-red-500 border-b-2 border-red-500">
            youremail@example.com
        </a>
    </section>
</body>
</html>
