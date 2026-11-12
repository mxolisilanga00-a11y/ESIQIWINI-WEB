
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Your Name | Developer</title>
<style>
*{margin:0;padding:0;box-sizing:border-box;font-family:Arial,sans-serif}
body{background:#0f0f0f;color:#fff;text-align:center;padding:40px 20px}
.pfp{width:140px;height:140px;object-fit:cover;border-radius:50%;border:4px solid #00ff88}
h1{margin:15px 0 5px;font-size:28px}
p{color:#aaa;margin-bottom:25px}
.btn{display:inline-flex;align-items:center;gap:10px;text-decoration:none;font-weight:bold;padding:15px 25px;border-radius:30px;font-size:16px;margin:5px}
.wa{background:#25D366;color:#fff}
.wa img{width:24px;height:24px}
.portfolio{background:#222;color:#fff;border:1px solid #333}
.float-wa{position:fixed;bottom:20px;right:20px;background:#25D366;width:60px;height:60px;border-radius:50%;display:flex;align-items:center;justify-content:center;box-shadow:0 5px 20px rgba(37,211,102,.5);z-index:999}
.float-wa img{width:35px;height:35px}
</style>
</head>
<body>

<img class="pfp" src="https://i.pravatar.cc/300" alt="Profile">
<h1>Your Name</h1>
<p>Developer • Pretoria, SA<br>Click below to chat to me directly on WhatsApp</p>

<!-- 1. MAIN WHATSAPP BUTTON - GOES STRAIGHT TO CHAT -->
<a class="btn wa" href="https://wa.me/27712345678?text=Hi%20I%20saw%20your%20portfolio" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
  Chat On WhatsApp
</a>

<br>

<a class="btn portfolio" href="#projects">View My Work</a>

<!-- 2. FLOATING WHATSAPP BUTTON - ALWAYS THERE -->
<a class="float-wa" href="https://wa.me/27712345678?text=Hi%20I%20want%20to%20chat" target="_blank">
  <img src="https://upload.wikimedia.org/wikipedia/commons/6/6b/WhatsApp.svg" alt="WhatsApp">
</a>

</body>
</html>
