<!DOCTYPE html>
<html>
<head>
    <title>Sigma Academy</title>
    <style>
        body {
            font-family: Arial;
            text-align: center;
            background: #f2f2f2;
        }
        .box {
            margin-top: 100px;
            padding: 20px;
            background: white;
            width: 300px;
            margin-left: auto;
            margin-right: auto;
            border-radius: 10px;
            box-shadow: 0 0 10px gray;
        }
        input {
            padding: 10px;
            width: 80%;
            margin-top: 10px;
        }
        button {
            padding: 10px 20px;
            background: green;
            color: white;
            border: none;
            margin-top: 10px;
        }
        #content {
            display: none;
            margin-top: 20px;
        }
    </style>
</head>

<body>

<div class="box">
    <h2>Enter Secret Code</h2>
    <input type="password" id="code" placeholder="Enter Code">
    <br>
    <button onclick="checkCode()">Submit</button>

    <div id="content">
        <h3>Welcome Student 🎉</h3>
        
        <!-- IMAGE -->
        <img src="your-image.jpg" width="200"><br><br>

        <!-- PDF -->
        <a href="your-file.pdf" download>Download PDF</a>
    </div>
</div>

<script>
    function checkCode() {
        var code = document.getElementById("code").value;

        if(code === "SIGMA1234") {
            document.getElementById("content").style.display = "block";
        } else {
            alert("Wrong Code ❌");
        }
    }
</script>

</body>
</html># Sigma-academy-
