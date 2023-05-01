# <!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Javascript</title>
    <script>
        function add() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 + num2;
            myForm.sum3.value = num3;
        }

        function sub() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 - num2;
            myForm.sum3.value = num3;
        }

        function mod() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 % num2;
            myForm.sum3.value = num3;
        }

        function multi() {
            let num1 = parseInt(document.getElementById('num1').value);
            let num2 = parseInt(document.getElementById('num2').value);
            let num3 = num1 * num2;
            myForm.sum3.value = num3;
        }

        function reset() {
            document.getElementById('num1').reset();
            document.getElementById('num2').reset();
            document.getElementById('num3').reset();
        }
        function ageCalc() {
            let age = parseInt(document.getElementById('age').value)
            if (age >= 18) {
                alert('Your eligible');
            } else {
                alert('Your not elgible');
            }
        }
    </script>
</head>

<body>
    <fieldset>
        <div style=" border: 1px solid rgb(255, 47, 54);text-align:center;">
            <h1 style="color: blueviolet;">BASIC CALCULATOR</h1><background-color
            <form id="myForm">
                <input type="number" id="num1" placeholder="Enter first no."><br><br>
                <input type="number" id="num2" placeholder="Enter second no."><br><br>
                <input type="number" id="sum3" placeholder="Your sum"><br><br>
                <input type="button" value="Add" onclick="add()"><br><br>
                <input type="button" value="Substract" onclick="sub()"><br><br>
                <input type="button" value="Modulus" onclick="mod()"><br><br>
                <input type="button" value="Multiply" onclick="multi()"><br><br>
                <input type="button" value="Reset" onclick="reset()"><br><br>
            </form>
        </div>
    </fieldset><div>
<fieldset>
    <form>
                    <div>
                        <fieldset>
                            <h1>Eligibility check</h1>
                            <input type="number" id="age" placeholder="Enter your age"><br><br>
                            <input type="button" value="Click here " onclick="ageCalc()"><br><br>
                        </fieldset>
                    </div>
                </form>

</fielddset>

</form>

</body>

</html>-
