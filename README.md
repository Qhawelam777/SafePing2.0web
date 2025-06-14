# SafePing2.0web<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>SafePing App | Personal Safety Made Simple</title>
  <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css">
  <link rel="icon" type="image/png" href="logo.png" />
</head>
<body class="bg-orange-50 font-sans">
  <header class="bg-white shadow p-4 flex justify-between items-center">
    <img src="logo.png" alt="SafePing Logo" class="h-10">
    <h1 class="text-xl font-bold text-orange-600">SafePing</h1>
  </header>  <main class="max-w-4xl mx-auto px-4 py-10">
    <section class="text-center">
      <h2 class="text-3xl font-bold text-orange-700 mb-4">Your Personal Safety Companion</h2>
      <p class="text-gray-700 mb-6">SafePing is a mobile safety app designed to protect users in high-risk situations by instantly notifying their loved ones, capturing live location, and integrating with emergency services in future releases.</p>
      <img src="app_preview.png" alt="SafePing App Preview" class="mx-auto shadow-lg rounded-lg mb-6 max-w-sm">
      <a href="#signup" class="bg-orange-600 text-white px-6 py-2 rounded-full font-semibold hover:bg-orange-500 transition">Join the Waitlist</a>
    </section><section class="mt-16">
  <h3 class="text-2xl font-semibold text-orange-700 mb-4">Key Features</h3>
  <ul class="grid md:grid-cols-2 gap-6 text-gray-700">
    <li class="bg-white p-4 rounded shadow">🚨 One-button emergency ping to 3 contacts</li>
    <li class="bg-white p-4 rounded shadow">📍 Live location sharing via SMS</li>
    <li class="bg-white p-4 rounded shadow">📷 Auto photo capture during alert</li>
    <li class="bg-white p-4 rounded shadow">📖 Medical profile & QR emergency card (coming soon)</li>
  </ul>
</section>

<section id="signup" class="mt-16">
  <h3 class="text-xl font-semibold text-orange-700 mb-4">Get Early Access</h3>
  <form name="waitlist" method="POST" data-netlify="true" class="bg-white shadow p-6 rounded">
    <input type="hidden" name="form-name" value="waitlist" />
    <div class="mb-4">
      <label class="block text-gray-600">Full Name</label>
      <input type="text" name="name" class="w-full border p-2 rounded" required />
    </div>
    <div class="mb-4">
      <label class="block text-gray-600">Email Address</label>
      <input type="email" name="email" class="w-full border p-2 rounded" required />
    </div>
    <button type="submit" class="bg-orange-600 text-white px-4 py-2 rounded hover:bg-orange-500">Sign Up</button>
  </form>
</section>

  </main>  <footer class="text-center text-gray-500 py-6 text-sm">
    © 2025 Busisiwe Maphela. All rights reserved.
  </footer>
</body>
</html>
