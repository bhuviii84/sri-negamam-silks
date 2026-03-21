# sri-negamam-silks
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>A Story Woven For You</title>

<style>
body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(to right, #fff5f7, #ffe4ec);
    overflow-x: hidden;
}

/* Section Styling */
section {
    height: 100vh;
    display: flex;
    justify-content: center;
    align-items: center;
    text-align: center;
    flex-direction: column;
    padding: 20px;
}

/* Opening */
.hero {
    background: black;
    color: white;
}

.hero h1 {
    font-size: 2.5rem;
    animation: fadeIn 2s ease-in-out;
}

/* Threads animation */
.thread {
    width: 2px;
    height: 100px;
    background: red;
    margin: 5px;
    display: inline-block;
    animation: drop 2s infinite;
}

@keyframes drop {
    0% {transform: translateY(-100px);}
    100% {transform: translateY(100px);}
}

/* Colors section */
.colors div {
    width: 100px;
    height: 100px;
    margin: 10px;
    display: inline-block;
    border-radius: 10px;
    color: white;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: bold;
}

/* Final message */
.final {
    background: #ffdde1;
}

button {
    padding: 10px 20px;
    border: none;
    background: black;
    color: white;
    cursor: pointer;
    margin-top: 20px;
    border-radius: 5px;
}

@keyframes fadeIn {
    from {opacity: 0;}
    to {opacity: 1;}
}
</style>
</head>

<body>

<!-- 🎬 Opening -->
<section class="hero">
    <h1>
        Just like silk is woven thread by thread… <br>
        Something beautiful is being created between us ❤️
    </h1>
</section>

<!-- 🧵 Threads Section -->
<section>
    <h2>Threads of Us</h2>
    <div>
        <div class="thread"></div>
        <div class="thread"></div>
        <div class="thread"></div>
        <div class="thread"></div>
    </div>
    <p>Every moment with you is a thread in my story…</p>
</section>

<!-- 🎨 Colors Section -->
<section class="colors">
    <h2>Colors of You</h2>
    <div style="background:red;">Love</div>
    <div style="background:blue;">Trust</div>
    <div style="background:purple;">Magic</div>
    <div style="background:orange;">Energy</div>
</section>

<!-- 🎥 Video Section -->
<section>
    <h2>Our Story</h2>
    <video width="300" controls>
        <source src="your-video.mp4" type="video/mp4">
    </video>
    <p>Watch how everything started…</p>
</section>

<!-- 💌 Final Message -->
<section class="final">
    <h1>
        If this is just the beginning… <br>
        Imagine what we can weave together 💫
    </h1>

    <button onclick="showMessage()">Click Me</button>
    <p id="msg"></p>
</section>

<script>
function showMessage() {
    document.getElementById("msg").innerHTML =
    "You are not just part of my story… you are the most beautiful chapter ❤️";
}
</script>

</body>
</html>
