html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Plagiarism Checker</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f9f9f9;
            margin: 0;
            padding: 0;
        }
        .container {
            max-width: 800px;
            margin: 0 auto;
            padding: 20px;
            background-color: #ffffff;
            border-radius: 5px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
            color: #333;
        }
        textarea {
            width: 100%;
            height: 200px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 3px;
            resize: vertical;
        }
        button {
            display: block;
            margin: 20px auto;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            border: none;
            border-radius: 3px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Plagiarism Checker</h1>
        <textarea id="textToCheck" placeholder="Paste your text here..."></textarea>
        <button onclick="checkPlagiarism()">Check Plagiarism</button>
        <div id="result"></div>
    </div>

    <script>
        function checkPlagiarism() {
            const text = document.getElementById('textToCheck').value;
            // Implement your plagiarism checking logic here
            // You can use APIs or algorithms to compare the text against other sources.
            // Display the result in the 'result' div.
            const resultDiv = document.getElementById('result');
            resultDiv.innerHTML = 'Plagiarism percentage: 5%'; // Example result
        }
    </script>
</body>
</html>
