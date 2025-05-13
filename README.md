# Cristiano-amakk
<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كريستيانو عمك</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #d40000;
            font-size: 2.5em;
        }
        button {
            background-color: #d40000;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.2em;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #b30000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>كريستيانو عمك</h1>
        <button onclick="playSound()">اضغط لسماع الصوت</button>
    </div>

    <audio id="audio" src="https://www.myinstants.com/media/sounds/adel-imam-3amo.mp3"></audio>

    <script>
        function playSound() {
            const audio = document.getElementById('audio');
            audio.play();
        }
        
        // تشغيل الصوت تلقائياً عند فتح الصفحة (اختياري)
        window.onload = function() {
            // يمكنك إلغاء التعليق من السطر التالي إذا كنت تريد تشغيل الصوت تلقائياً
            // playSound();
        };
    </script>
</body>
</html><!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>كريستيانو عمك</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
        }
        h1 {
            color: #d40000;
            font-size: 2.5em;
        }
        button {
            background-color: #d40000;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 1.2em;
            border-radius: 5px;
            cursor: pointer;
            margin-top: 20px;
        }
        button:hover {
            background-color: #b30000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>كريستيانو عمك</h1>
        <button onclick="playSound()">اضغط لسماع الصوت</button>
    </div>

    <audio id="audio" src="https://www.myinstants.com/media/sounds/adel-imam-3amo.mp3"></audio>

    <script>
        function playSound() {
            const audio = document.getElementById('audio');
            audio.play();
        }
        
        // تشغيل الصوت تلقائياً عند فتح الصفحة (اختياري)
        window.onload = function() {
            // يمكنك إلغاء التعليق من السطر التالي إذا كنت تريد تشغيل الصوت تلقائياً
            // playSound();
        };
    </script>
</body>
</html>
