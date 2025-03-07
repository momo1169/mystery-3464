<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>3464 - 사라진 음원</title>
    <style>
        body {
            background-color: black;
            color: white;
            text-align: center;
            font-family: Arial, sans-serif;
            padding: 50px;
        }
        .hidden {
            opacity: 0;
            transition: opacity 3s ease-in;
        }
        .reveal {
            opacity: 1 !important;
        }
        a {
            color: #00bfff;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <h1>3464 - 사라진 음원</h1>
    <p>이 음원을 찾고 있나요?</p>
    <p>하지만 조심하세요. 듣는 순간, 당신도 영향을 받을 수 있습니다.</p>
    <p>누군가 이 음원을 숨기려 하고 있습니다.</p>
    
    <h2 id="hiddenText" class="hidden">당신은 이미 연결되었습니다.</h2>
    
    <script>
        setTimeout(() => {
            document.getElementById("hiddenText").classList.add("reveal");
        }, 5000); // 5초 후 메시지 나타남
    </script>
</body>
</html>
