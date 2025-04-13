<!DOCTYPE html><html lang="en"><head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>My Portfolio</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head><body class="bg-white text-gray-800 font-sans">
  <!-- Header -->
  <header class="bg-blue-600 text-white p-6">
    <h1 class="text-4xl font-bold">Your Name</h1>
    <p class="text-lg">Web Developer | Designer | Problem Solver</p>
  </header>  <!-- About Me -->  <section class="p-6">
    <h2 class="text-2xl font-semibold mb-4">About Me</h2>
    <div class="flex flex-col md:flex-row items-center">
      <img src="https://via.placeholder.com/150" alt="Profile" class="w-32 h-32 rounded-full mb-4 md:mb-0 md:mr-6">
      <p class="max-w-xl">Hi! I'm a passionate developer who loves building web applications and learning new technologies. Let's create something amazing together!</p>
    </div>
  </section>  <!-- Skills -->  <section class="bg-gray-100 p-6">
    <h2 class="text-2xl font-semibold mb-4">Skills</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      <div>HTML</div>
      <div>CSS</div>
      <div>JavaScript</div>
      <div>React</div>
      <div>Node.js</div>
      <div>Tailwind CSS</div>
      <div>Git</div>
      <div>Figma</div>
    </div>
  </section>  <!-- Projects -->  <section class="p-6">
    <h2 class="text-2xl font-semibold mb-4">Projects</h2>
    <div class="grid md:grid-cols-3 gap-6">
      <div class="border p-4 rounded-lg shadow">
        <h3 class="text-xl font-bold">Project One</h3>
        <p>A short description of your awesome project.</p>
        <a href="#" class="text-blue-600 mt-2 inline-block">View Demo</a>
      </div>
      <div class="border p-4 rounded-lg shadow">
        <h3 class="text-xl font-bold">Project Two</h3>
        <p>Another cool project that solves a problem.</p>
        <a href="#" class="text-blue-600 mt-2 inline-block">View Demo</a>
      </div>
      <div class="border p-4 rounded-lg shadow">
        <h3 class="text-xl font-bold">Project Three</h3>
        <p>Creative and fun—show your personality!</p>
        <a href="#" class="text-blue-600 mt-2 inline-block">View Demo</a>
      </div>
    </div>
  </section>  <!-- Contact -->  <section class="bg-gray-100 p-6">
    <h2 class="text-2xl font-semibold mb-4">Contact</h2>
    <form class="max-w-md space-y-4">
      <input type="text" placeholder="Your Name" class="w-full p-2 border rounded" />
      <input type="email" placeholder="Your Email" class="w-full p-2 border rounded" />
      <textarea placeholder="Your Message" class="w-full p-2 border rounded"></textarea>
      <button type="submit" class="bg-blue-600 text-white px-4 py-2 rounded">Send</button>
    </form>
    <div class="mt-4">
      <a href="#" class="text-blue-600">LinkedIn</a> |
      <a href="#" class="text-blue-600">GitHub</a>
    </div>
  </section>  <footer class="text-center p-4 bg-blue-600 text-white mt-6">
    &copy; 2025 Your Name. All rights reserved.
  </footer>
</body></html>
