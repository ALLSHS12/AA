<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Website</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: Arial, sans-serif;
            text-align: center;
        }

        .navbar {
            display: flex;
            justify-content: flex-end;
            background-color: #f8f8f8;
            padding: 10px 20px;
        }

        .navbar a {
            text-decoration: none;
            color: black;
            margin: 0 15px;
            font-size: 18px;
        }

        .navbar a:hover {
            text-decoration: underline;
        }

        .image-container {
            text-align: center;
            margin-top: 20px;
        }

        .image-container img {
            width: 1350px;
            height: 290px;
        }

        #apps-list {
            display: none;
            margin-top: 20px;
        }

        #apps-list a {
            display: block;
            margin: 10px 0;
            font-size: 18px;
            color: blue;
            text-decoration: none;
        }

        #apps-list a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <div class="navbar">
        <a href="home.html">Home</a>
        <a href="about us.html">About Us</a>
        <a href="contact us.html">Contact Us</a>
        <a href="Animation NC II.html">ANIMATION NC II</a>
    </div>

    <hr>

    <div class="image-container">
        <img src="ANI-HUB.png" alt="ANI-HUB">
    </div>

    <a href="https://www.animeoutline.com/#:~:text=AnimeOutline%20is%20one%20of%20the,anime%20related%20tips%20and%20advice!">
        <img src="kawaii.jpg" width="200" height="200" alt="html">
       
    </a>

    <h4>Tutorials Step by Step</h4>

   
    </a>
    <a href="https://www.youtube.com/@DrawlikeaSir">
    <video controls loop src="video.mp4" width="500"></video>
    </a>
    <h4>Video Tutorial</h4>
    <a href="https://www.imagidraw.com/"></a>

    <button onclick="showApps()">Show Free Apps</button>

    <div id="apps-list">
        <h2>Free Apps</h2>
        <a href="https://ibispaint.com/?lang=en-US " target="_blank">ibispaint</a>
        <a href="https://apps.apple.com/us/app/artstudio-pro/id1244142051 " target="_blank">artstudio-pro</a>
        <a href="https://www.tayasui.com/sketches/" target="_blank">tayasui</a>
        <a href="https://concepts.app/en/" target="_blank">Concepts</a>
        <a href="https://www.google.com/url?sa=t&source=web&rct=j&opi=89978449&url=https://play.google.com/store/apps/details%3Fid%3Dcom.adsk.sketchbook%26hl%3Den_IN%26referrer%3Dutm_source%253Dgoogle%2526utm_medium%253Dorganic%2526utm_term%253Dpencil%2Bapp%26pcampaignid%3DAPPU_1_j_qjZ7rhJJqYnesPr5_o8AM&ved=2ahUKEwj65Ibw3a2LAxUaTGcHHa8PGj4Q8oQBegQIDxAB&usg=AOvVaw3SSpWeAhoDWVrRev7cfvF1" target="_blank">Sketchbook</a>
        <a href="https://flipaclip.com/ " target="_blank">Flipaclip</a>
        <a href="https://play.google.com/store/apps/details?id=com.drawing.pad.desk.app.coloring.book.paint.sketch&hl=en_IN" target="_blank">Sketch Pad</a>
    </div>
    <script>
        function showApps() {
            document.getElementById("apps-list").style.display = "block";
        }
    </script>

</body>
</html>
