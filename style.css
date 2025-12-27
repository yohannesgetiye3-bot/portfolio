<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MDT TOURS | ETHIOPIA</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@900&display=swap');
        body { background-color: #050505; color: white; font-family: 'Inter', sans-serif; }
        .glass { background: rgba(255, 255, 255, 0.03); backdrop-filter: blur(10px); border: 1px solid rgba(255,255,255,0.1); border-radius: 20px; }
        .ethiopia-green { color: #2ecc71; }
    </style>
</head>
<body class="p-4 md:p-10">

    <nav class="flex justify-between items-center mb-10">
        <h1 class="text-3xl font-black italic tracking-tighter">MDT <span class="ethiopia-green">TOURS</span></h1>
        <div class="px-6 py-2 glass text-[10px] font-bold tracking-widest uppercase">Ethiopia Luxury</div>
    </nav>

    <div class="glass w-full h-[500px] relative overflow-hidden mb-10">
        <img src="image_667e1f.jpg" class="w-full h-full object-cover" alt="Lalibela">
        <div class="absolute inset-0 bg-gradient-to-t from-black to-transparent"></div>
        <div class="absolute bottom-10 left-10">
            <h2 class="text-7xl font-black uppercase italic leading-none">Lalibela</h2>
            <p class="text-[#2ecc71] font-bold tracking-[0.3em] text-xs mt-4">WORLD HERITAGE SITE</p>
        </div>
    </div>

    <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-4 gap-6" id="main-grid">
        </div>

    <script>
        // These file names must match your folder EXACTLY
        const photos = [
            { name: "Gonder", file: "image_668504.jpg" },
            { name: "Aksum", file: "image_668562.jpg" },
            { name: "Simien Mtns", file: "image_6681f8.png" },
            { name: "Tis Abay", file: "image_668941.jpg" },
            { name: "Harar", file: "image_668c69.jpg" },
            { name: "Sof Omar", file: "image_668ce7.png" },
            { name: "Bishoftu", file: "image_66902b.jpg" }
        ];

        const grid = document.getElementById('main-grid');
        
        grid.innerHTML = photos.map(p => `
            <div class="glass overflow-hidden group">
                <div class="h-60 overflow-hidden">
                    <img src="${p.file}" class="w-full h-full object-cover group-hover:scale-110 transition duration-700">
                </div>
                <div class="p-6">
                    <h3 class="text-xl font-black uppercase italic">${p.name}</h3>
                    <div class="w-10 h-1 bg-[#2ecc71] mt-2"></div>
                </div>
            </div>
        `).join('');
    </script>
</body>
</html>