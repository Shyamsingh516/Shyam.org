<!DOCTYPE html>
<html lang="en-IN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>SJMAT Joining Fee</title>
    <style>
        body, html {
            margin: 0;
            padding: 0;
            height: 100%;
            font-family: 'Arial', sans-serif;
            color: white;
            text-align: center;
            overflow: auto; /* Allow scrolling */
        }

        /* Video Background */
        .video-background {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            object-fit: cover;
            animation: videoPlay 1s infinite linear;
        }

        @keyframes videoPlay {
            0% { transform: scale(1); }
            100% { transform: scale(1); }
        }

        .header {
            background-color: rgba(0, 0, 0, 0.8);
            padding: 20px;
            font-size: 1.5em;
            text-transform: uppercase;
            letter-spacing: 3px;
            color: #FFD700;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.6);
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .header img {
            width: 80px;
            height: 80px;
            margin-right: 15px;
        }

        .header-text {
            color: #FFD700;
            font-size: 1.5em;
            text-transform: uppercase;
        }

        .container {
            margin: 50px auto;
            padding: 20px;
            background: rgba(0, 0, 0, 0.8);
            border-radius: 12px;
            width: 80%;
            max-width: 1000px;
            max-height: calc(100vh - 100px);
            overflow-y: auto; /* Enable vertical scroll */
        }

        .qr-code {
            margin-top: 30px;
            border: 3px solid #FFD700;
            display: inline-block;
            padding: 20px;
            border-radius: 10px;
        }

        .qr-code img {
            width: 200px;
            height: 200px;
        }

        .pay-now-button {
            background-color: #4CAF50;
            color: white;
            padding: 15px 30px;
            font-size: 1.8em;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            transition: all 0.3s ease;
            margin-top: 20px;
        }

        .pay-now-button:hover {
            background-color: #45a049;
        }

        .whatsapp-btn {
            background-color: #25D366;
            color: white;
            padding: 15px 30px;
            font-size: 1.5em;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 20px;
        }

        .whatsapp-btn:hover {
            background-color: #128C7E;
        }

        /* Course List */
        .course-list {
            margin-top: 30px;
            text-align: left;
            font-size: 1.2em;
        }

        .course-list ul {
            list-style-type: none;
            padding-left: 0;
        }

        .course-list li {
            margin: 10px 0;
        }

        .course-list a {
            color: #FFD700;
            text-decoration: none;
        }

        .course-list a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>

    <!-- Video Background -->
    <video class="video-background" autoplay muted loop>
        <source src="https://media-hosting.imagekit.io//712e4e3f23c14905/3141208-uhd_3840_2160_25fps.mp4?Expires=1735212158&Key-Pair-Id=K2ZIVPTIP2VGHC&Signature=cxqf1qMDurGmmYyq46vwlPZuq3DQeoKM3naYBw7EaueJuMGb-6ple8AtfThswv7jiEx~kFiWKP-l7bDYzBoxlI4-B~h2It04XugjPGrVarOX5WEbFbCvvJKnn6bL7lS1TUA3UqGsOhb5H~D0BQ43dMiQ0OzBabIAvAa6o8sCTST40TJIjo0H2u3qofJdHpFJiwqrGQWpzGOZH1d4UxDVPC26sQTU-nbs0bVZWlMG0YhPu7X5exP4rH1lSOOCjZwEYmWL90k4x4zgfhd2t9k1FIEMgnSJ4O836tyL9vdcd9sRAg9GZO6oeIMMAbdxzwEcX82nW8Zs-Nl5Aps2a5RulA__" type="video/mp4">
        Your browser does not support the video tag.
    </video>

    <div class="header">
        <img src="https://assets.onecompiler.app/42z6psaqg/433yv63mt/Screenshot_2024-05-16-08-54-54-321_com.miui.gallery.png" alt="Logo">
        <span class="header-text">SJMAT Joining Fee</span>
    </div>

    <div class="container">
        <h2>Pay Using UPI</h2>
        <p>Join SJMAT today and unlock exclusive benefits!</p>

        <!-- QR Code Section -->
        <div class="qr-code">
            <h3>Scan & Pay</h3>
            <img src="https://assets.onecompiler.app/42z6psaqg/433yvddps/Screenshot_2024-12-24-13-20-06-492_com.phonepe.app.png" alt="QR Code">
            <p>Scan this QR code using your payment app to pay ₹500 or more to <strong>sjmat516@axl</strong>.</p>
        </div>

        <!-- Pay Now Button -->
        <button class="pay-now-button" onclick="window.location.href='upi://pay?pa=sjmat516@axl&pn=SJMAT&mc=0000&tid=1234567890&tr=unique-id&tn=Joining+Fee&am=500&cu=INR'">
            Pay Now
        </button>

        <!-- WhatsApp Contact Button -->
        <a href="https://wa.me/9199968850" target="_blank">
            <button class="whatsapp-btn">Contact Us on WhatsApp</button>
        </a>

        <!-- Course List Section -->
        <div class="course-list">
            <h3>Courses Offered</h3>
            <ul>
                <li><a href="#">Financial Business Management</a></li>
                <li><a href="#">Stock Market Trading Strategies</a></li>
                <li><a href="#">Investment Analysis & Research</a></li>
                <li><a href="#">Freelancing Mastery</a></li>
                <li><a href="#">Digital Marketing for Beginners</a></li>
                <li><a href="#">E-Commerce Business Setup</a></li>
                <li><a href="#">Personal Finance & Wealth Management</a></li>
                <li><a href="#">Cryptocurrency & Blockchain</a></li>
                <li><a href="#">Risk Management in Trading</a></li>
                <li><a href="#">Entrepreneurship and Business Growth</a></li>
            </ul>
        </div>
    </div>

</body>
</html>
