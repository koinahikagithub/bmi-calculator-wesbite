<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>BMI Calculator</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>BMI Calculator</h1>
    </header>
    <main>
        <form id="bmi-form">
            <label for="height">Height (cm):</label>
            <input type="number" id="height" name="height" required>
            
            <label for="weight">Weight (kg):</label>
            <input type="number" id="weight" name="weight" required>
            
            <button type="submit">Calculate BMI</button>
        </form>
        <div id="result"></div>
    </main>
    <footer>
        <p>&copy; 2024 BMI Calculator</p>
    </footer>
    <script src="script.js"></script>
</body>
</html>
