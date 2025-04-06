<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thiện Đẹp trai</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            margin: 0;
            padding: 0;
            background: #4c030c;
            text-align: center;
            color: #1a2802;
        }
        .header {
            background: #ff4d6d;
            color: white;
            padding: 20px;
            font-size: 28px;
            font-weight: bold;
            text-transform: uppercase;
        }
        .container {
            max-width: 600px;
            margin: 30px auto;
            padding: 20px;
            background: #fff0f3;
            box-shadow: 0 4px 10px rgba(255, 77, 109, 0.2);
            border-radius: 15px;
        }
        .button {
            display: inline-block;
            padding: 12px 25px;
            margin: 10px;
            font-size: 16px;
            background: #ff4d6d;
            color: white;
            border: none;
            border-radius: 25px;
            cursor: pointer;
            transition: all 0.3s;
        }
        .button:hover {
            background: #ff1f4b;
            transform: scale(1.1);
        }
        .message {
            display: none;
            margin-top: 20px;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>
<body>
    <div class="header">Bóc Phốt Ngọc Thùy 💖</div>
    <div class="container">
        <h1>Mọi người có biết?</h1>
        <p>Mình là nạn nhân của BLGD ( bạo lực gia đình )</p>
        
        <button class="button" onclick="showMessage('message1')">Ngọc Thùy</button>
        <button class="button" onclick="showMessage('message2')">Điểm xấu của cổ</button>
        <button class="button" onclick="showMessage('message3')">Lưu ý, phòng tránh về cổ</button>
        
        <p id="message1" class="message">"Ngọc Thùy tên đầy đủ là TRẦN THỊ NGỌC THÙY , là 1 sát thủ máu lạnh,cổ chỉ măm me cắn người, đánh người. Tôi là nạn nhân của cổ, mỗi lần gặp là tan toác: 10 cái cắn,4-5 cái vả, 1000+ câu chửi." 💕</p>
        <p id="message2" class="message">"Điểm xấu là ngủ sớm,dậy sớm,ăn nhiều,chăm làm việc nhà, chăm học :(((" 💖</p>
        <p id="message3" class="message">"không có biện pháp phòng tránh hay cách khắc phục nào, chúc bạn cẩn trọng và gặp may mắn" 💘</p>
    </div>
    
    <script>
        function showMessage(id) {
            document.querySelectorAll('.message').forEach(msg => msg.style.display = 'none');
            document.getElementById(id).style.display = 'block';
        }
    </script>
</body>
</html>
