<!DOCTYPE html>
<html>
<head>
    <title>Hospital Token System</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <h1>🏥 City Hospital Appointment</h1>
    </header>

    <div class="container">

        <!-- Booking Section -->
        <div class="card">
            <h2>Book Appointment Token</h2>
            <input type="text" id="patientName" placeholder="Enter Patient Name">
            <button onclick="bookToken()">Book Token</button>
            <p id="tokenMessage"></p>
        </div>

        <!-- Display Section -->
        <div class="card">
            <h2>Current Ongoing Token</h2>
            <h1 id="currentToken">0</h1>
            <button onclick="nextToken()">Next Token (Admin)</button>
        </div>

    </div>

    <script src="script.js"></script>
</body>
</html>
