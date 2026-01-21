<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>My First Website</title>

<!-- CSS LINK (IMPORTANT) -->
<link rel="stylesheet" href="style.css">
</head>

<body>

<nav>
<a href="#" onclick="showSection('home')">Home</a>
<a href="#" onclick="showSection('news')">News</a>
<a href="#" onclick="showSection('events')">Events</a>
<a href="#" onclick="showSection('contact')">Contact</a>
</nav>

<div id="home" class="section">
<h1>Welcome Parmila</h1>
<p>This is my first website</p>
</div>

<div id="news" class="section">
<h1>News</h1>
<p>Latest news will appear here.</p>
</div>

<div id="events" class="section">
<h1>Events</h1>
<p>Upcoming events will appear here.</p>
</div>

<div id="contact" class="section">
<h1>Contact</h1>
<p>Email: example@email.com</p>
</div>

<!-- JS LINK -->
<script src="script.js"></script>

</body>
</html>
