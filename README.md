# codsoft_taskno1
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>JavaScript Calculator</title>
    <link rel="stylesheet" href="style.css">
    <script src="script.js" defer></script>
</head>
<body>
    <table class="tbl">
        <tr>
            <td colspan="3"><input type="text" id="result"></td>
            <td><input type="button" value="C" onclick="clr()" id="clear"></td>
        </tr>
        <tr>
            <td><input type="button" value="1" onclick="Num('1')"></td>
            <td><input type="button" value="2" onclick="Num('2')"></td>
            <td><input type="button" value="3" onclick="Num('3')"></td>
            <td><input type="button" value="/" onclick="Num('/')"></td>
        </tr>
        <tr>
            <td><input type="button" value="4" onclick="Num('4')"></td>
            <td><input type="button" value="5" onclick="Num('5')"></td>
            <td><input type="button" value="6" onclick="Num('6')"></td>
            <td><input type="button" value="-" onclick="Num('-')"></td>
        </tr>
        <tr>
            <td><input type="button" value="7" onclick="Num('7')"></td>
            <td><input type="button" value="8" onclick="Num('8')"></td>
            <td><input type="button" value="9" onclick="Num('9')"></td>
            <td><input type="button" value="+" onclick="Num('+')"></td>
        </tr>
        <tr>
            <td><input type="button" value="." onclick="Num('.')"></td>
            <td><input type="button" value="0" onclick="Num('0')"></td>
            <td><input type="button" value="=" onclick="equal()"></td>
            <td><input type="button" value="*" onclick="Num('*')"></td>
        </tr>
    </table>
</body>
</html>
