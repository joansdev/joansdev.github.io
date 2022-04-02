<!DOCTYPE html>

<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="niewport" content="width=device-width" , initial-scale="1.0">
    <title>JavaScript</title>
</head>

<body>

    <script>
        // 남자이고 군필자여야 하는데, JS개발 경험이 있거나 / 자격증이 있어야 통과 
        const gender = prompt('성별?', "F / M");
        const name = prompt('이름?');
        const age = Number(prompt("나이?"));
        const isAdult = age > 19;

        if (gender == "M" && (name == "Yohan" || isAdult)){
            alert('통과')
        }
        else {
            alert('돌아가')
        }
    </script>

</body>

</html>