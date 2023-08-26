<!DOCTYPE html>
<html>
<head>
    <title>My Achievements</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            background: linear-gradient(135deg, #fdfcfb, #e2d1c3);
        }
        .container {
            background-color: rgba(255, 255, 255, 0.9);
            border-radius: 20px;
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
            padding: 30px;
            max-width: 800px;
            text-align: center;
        }
        h1 {
            color: #333;
            margin-bottom: 20px;
            font-size: 28px;
            text-transform: uppercase;
            letter-spacing: 2px;
        }
        ul {
            list-style-type: none;
            padding: 0;
            margin: 0;
        }
        li {
            background-color: rgba(255, 255, 255, 0.7);
            padding: 30px;
            margin: 20px 0;
            border-radius: 15px;
            box-shadow: 0 10px 20px rgba(0, 0, 0, 0.1);
            transition: transform 0.3s ease, box-shadow 0.3s ease, background-color 0.3s ease;
            position: relative;
            overflow: hidden;
            cursor: pointer;
            animation: fadeInUp 0.5s ease;
        }
        li:hover {
            transform: translateY(-10px);
            box-shadow: 0 15px 30px rgba(0, 0, 0, 0.2);
            background-color: #66cdaa; /* Medium Aquamarine color */
        }
        .icon {
            font-size: 40px;
            opacity: 0.6;
            position: absolute;
            top: -20px;
            left: 50%;
            transform: translateX(-50%);
        }
        .achievement-details {
            padding-top: 20px;
        }
        .achievement-title {
            font-size: 24px;
            margin-bottom: 5px;
        }
        .description {
            font-size: 18px;
            color: #777;
        }

        @keyframes fadeInUp {
            0% {
                opacity: 0;
                transform: translateY(20px);
            }
            100% {
                opacity: 1;
                transform: translateY(0);
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>My Achievements</h1>
        <ul>
            <li>
                <i class="icon">🏆</i>
                <div class="achievement-details">
                    <div class="achievement-title">First Place in Science Fair</div>
                    <div class="description">Developed a groundbreaking project on renewable energy.</div>
                </div>
            </li>
            <li>
                <i class="icon">🎓</i>
                <div class="achievement-details">
                    <div class="achievement-title">Graduated with Honors</div>
                    <div class="description">Maintained a GPA above 3.8 throughout my academic journey.</div>
                </div>
            </li>
            <li>
                <i class="icon">🌟</i>
                <div class="achievement-details">
                    <div class="achievement-title">Volunteer of the Year</div>
                    <div class="description">Contributed over 200 hours to various community service initiatives.</div>
                </div>
            </li>
        </ul>
    </div>
</body>
</html>
