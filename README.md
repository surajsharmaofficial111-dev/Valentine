<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<title>Happy Valentine’s Day ❤️</title>

<style>
body {
    margin:0;
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:linear-gradient(135deg,#ff4b7d,#ff758c);
    font-family:Arial, sans-serif;
}

.card {
    background:white;
    padding:40px;
    border-radius:20px;
    text-align:center;
    max-width:350px;
    box-shadow:0 10px 30px rgba(0,0,0,.2);
}

h1 {
    color:#ff3366;
}

.heart {
    font-size:60px;
    animation:pulse 1.2s infinite;
}

@keyframes pulse {
    0% {transform:scale(1);}
    50% {transform:scale(1.2);}
    100% {transform:scale(1);}
}

button {
    background:#ff3366;
    border:none;
    padding:10px 20px;
    color:white;
    border-radius:20px;
    cursor:pointer;
}

.hidden {
    display:none;
}
</style>
</head>

<body>

<div class="card">
    <div class="heart">❤️</div>
    <h1>Happy Valentine’s Day!</h1>
    <p>You make my world brighter every single day.</p>

    <button onclick="showMessage()">Click me</button>

    <p id="msg" class="hidden">
        I love you endlessly 💕<br>
        Thank you for being mine.
    </p>
</div>

<script>
function showMessage() {
    document.getElementById("msg").classList.remove("hidden");
}
</script>

</body>
</html>
