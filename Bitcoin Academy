<!DOCTYPE html>
<html>
<head>
    <title>Bitcoin Academy</title>
    <style>
        body {
            background-color: #f2a900;
            color: #ffffff;
            font-family: Arial, sans-serif;
        }
        h1, h2 {
            text-align: center;
        }
        #sections {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
        }
        .section {
            width: 200px;
            padding: 20px;
            margin: 20px;
            border: 2px solid #ffffff;
            border-radius: 8px;
            text-align: center;
        }
        #qrcode {
            margin: auto;
        }
    </style>
    <script src="https://cdn.rawgit.com/davidshimjs/qrcodejs/gh-pages/qrcode.min.js"></script>
</head>
<body>

<h1>Bitcoin Academy</h1>

<div id="sections">
    <div class="section">
        <h2>Bitcoin</h2>
        <div id="qrcode"></div>
        <p id="btcAddress">bc1qq39uh82x68mw7z34hw5z6xhhkjd9hgxveg8s5p</p>
    </div>
    <div class="section">
        <h2>University</h2>
        <p>Coming soon...</p>
    </div>
    <div class="section">
        <h2>Blockchain</h2>
        <p>Coming soon...</p>
    </div>
    <div class="section">
        <h2>Finance</h2>
        <p>Coming soon...</p>
    </div>
</div>

<script>
    var btcAddress = 'bc1qq39uh82x68mw7z34hw5z6xhhkjd9hgxveg8s5p';
    new QRCode(document.getElementById("qrcode"), btcAddress);
    document.getElementById("btcAddress").textContent = btcAddress;
</script>

</body>
</html>
