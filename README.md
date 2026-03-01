<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>VG Nexus AI - Pioneering the Future</title>
    <style>
        /* ————————————————
           मुख्य डिज़ाइन (Styles)
           ———————————————— */
        body {
            margin: 0;
            padding: 0;
            background: radial-gradient(circle, #0a1128 0%, #010101 100%); /* गहरा नीला-काला बैकग्राउंड */
            color: #ffffff; /* सफेद टेक्स्ट */
            font-family: 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif; /* आधुनिक फोंट */
            overflow-x: hidden;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            text-align: center;
        }

        /* चमकता हुआ ग्लोब (Glowing AI Globe) */
        .globe-container {
            position: absolute;
            width: 300px;
            height: 300px;
            border-radius: 50%;
            background: radial-gradient(circle, rgba(0, 255, 255, 0.3) 0%, rgba(0, 0, 0, 0) 70%); /* एआई ग्लोब का चमकदार असर */
            box-shadow: 0 0 50px rgba(0, 255, 255, 0.5), 0 0 100px rgba(128, 0, 128, 0.3); /* नीली और बैंगनी चमक */
            animation: pulseGlobe 4s infinite alternate; /* पल्स एनीमेशन */
            z-index: 1;
        }

        @keyframes pulseGlobe {
            0% { transform: scale(1); box-shadow: 0 0 50px rgba(0, 255, 255, 0.5), 0 0 100px rgba(128, 0, 128, 0.3); }
            100% { transform: scale(1.05); box-shadow: 0 0 70px rgba(0, 255, 255, 0.7), 0 0 130px rgba(128, 0, 128, 0.5); }
        }

        /* टेक्स्ट कंटेंट (Text Content) */
        .content {
            position: relative;
            z-index: 2; /* टेक्स्ट ग्लोब के ऊपर दिखे */
            max-width: 800px;
            padding: 20px;
        }

        h1 {
            font-size: 3rem; /* बड़ा हेडर */
            font-weight: 700;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        .highlight {
            color: #00ffff; /* नियॉन नीला रंग (VG) */
            text-shadow: 0 0 10px #00ffff; /* नियॉन चमक */
        }

        h2 {
            font-size: 1.5rem; /* छोटा हेडर */
            font-weight: 400;
            color: #cccccc; /* हल्का ग्रे टेक्स्ट */
            margin-bottom: 30px;
            letter-spacing: 0.5px;
        }

        /* "Explore" बटन */
        .btn-explore {
            display: inline-block;
            padding: 12px 30px;
            font-size: 1rem;
            font-weight: 600;
            color: #010101; /* काला टेक्स्ट */
            background-color: #00ffff; /* नियॉन नीला बैकग्राउंड */
            border: none;
            border-radius: 25px;
            text-decoration: none;
            transition: all 0.3s ease;
            box-shadow: 0 4px 15px rgba(0, 255, 255, 0.4);
            cursor: pointer;
        }

        .btn-explore:hover {
            background-color: #ffffff; /* होवर करने पर सफेद */
            color: #010101;
            transform: translateY(-2px); /* थोड़ा ऊपर उठे */
            box-shadow: 0 6px 20px rgba(255, 255, 255, 0.6);
        }

        /* बैकग्राउंड डेटा लाइन्स (Background Data Lines) */
        .data-lines {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background-image: 
                linear-gradient(rgba(0, 255, 255, 0.05) 1px, transparent 1px),
                linear-gradient(90deg, rgba(0, 255, 255, 0.05) 1px, transparent 1px); /* डेटा ग्रिड */
            background-size: 50px 50px;
            z-index: 0;
            opacity: 0.3;
        }

    </style>
</head>
<body>

    <div class="data-lines"></div>

    <div class="globe-container"></div>

    <div class="content">
        <h1><span class="highlight">VG</span> Nexus AI</h1>
        <h2>Pioneering the Future of Artificial Intelligence</h2>
        <a href="#" class="btn-explore">Explore Solutions</a>
    </div>

</body>
</html>
