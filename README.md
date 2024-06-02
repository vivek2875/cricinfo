# cricinfo
// html code 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <!-- favicon -->
    <link rel="apple-touch-icon" sizes="180x180" href="images/favicon/apple-touch-icon.png">
    <link rel="icon" type="image/png" sizes="32x32" href="images/favicon/favicon-32x32.png">
    <link rel="icon" type="image/png" sizes="16x16" href="images/favicon/favicon-16x16.png">
    <link rel="manifest" href="/site.webmanifest">
    <link rel="mask-icon" href="/safari-pinned-tab.svg" color="#5bbad5">
    <meta name="msapplication-TileColor" content="#da532c">
    <meta name="theme-color" content="#ffffff">

    <title>Cricinfo</title>
    <link rel="stylesheet" href="CSS/style.css">
</head>
<body>
    <header>
        <h1>India vs Sri Lanka World Cup Final 2011</h1>
    </header>
    <main>
        <section class="teams">
            <div class="team">
                <img src="images/indian flag.jpg" alt="India Flag">
                <h2>India</h2>
            </div>
            <div class="team">
                <img src="images/srilankan flag.jpg" alt="Sri Lanka Flag">
                <h2>Sri Lanka</h2>
            </div>
        </section>
        <section class="match-details">
            <h3>Match Details</h3>
            <p>Date: April 2, 2011</p>
            <p>Venue: Wankhede Stadium, Mumbai</p>
            <p>Result: India won by 6 wickets</p>
        </section>
        <section class="scorecard">
            <h3>Scorecard</h3>
            <div class="innings">
                <h4>Sri Lanka Innings</h4>
                <table>
                    <tr>
                        <th>Batsman</th>
                        <th>Runs</th>
                        <th>Balls</th>
                        <th>4s</th>
                        <th>6s</th>
                    </tr>
                    <tr>
                        <td>Mahela Jayawardene</td>
                        <td>103</td>
                        <td>88</td>
                        <td>13</td>
                        <td>0</td>
                    </tr>
                    <!-- Add more player rows as needed -->
                </table>
                <p>Total: 274/6 (50 overs)</p>
            </div>
            <div class="innings">
                <h4>India Innings</h4>
                <table>
                    <tr>
                        <th>Batsman</th>
                        <th>Runs</th>
                        <th>Balls</th>
                        <th>4s</th>
                        <th>6s</th>
                    </tr>
                    <tr>
                        <td>Gautam Gambhir</td>
                        <td>97</td>
                        <td>122</td>
                        <td>9</td>
                        <td>0</td>
                    </tr>
                    <tr>
                        <td>MS Dhoni</td>
                        <td>91*</td>
                        <td>79</td>
                        <td>8</td>
                        <td>2</td>
                    </tr>
                    <!-- Add more player rows as needed -->
                </table>
                <p>Total: 277/4 (48.2 overs)</p>
            </div>
        </section>
        <section class="player-of-the-match">
            <h3>Player of the Match</h3>
            <div class="player">
                <img src="images/dhoni.jpg" alt="MS Dhoni">
                <h4>MS Dhoni</h4>
                <p>For his match-winning 91* off 79 balls</p>
            </div>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Cricinfo Simulation. All rights reserved.</p>
    </footer>
</body>
</html>


// CSS code
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f8f9fa;
}

header {
    background-color: #343a40;
    color: white;
    text-align: center;
    padding: 0px 0;
}

main {
    padding: 20px;
}

.teams {
    display: flex;
    justify-content: space-around;
    margin-bottom: 20px;
}

.team {
    text-align: center;
}

.team img {
    width: 100px;
    height: auto;
    border: 1px solid #ccc;
}

.match-details {
    text-align: center;
    margin-bottom: 20px;
}

.scorecard {
    text-align: center;
    margin-bottom: 20px;
}

.scorecard .innings {
    margin-bottom: 20px;
}

.scorecard table {
    width: 100%;
    border-collapse: collapse;
    margin: 0 auto;
}

.scorecard th, .scorecard td {
    border: 1px solid #ccc;
    padding: 8px;
    text-align: center;
}

.scorecard th {
    background-color: #f2f2f2;
}

.player-of-the-match {
    text-align: center;
    margin-bottom: 20px;
}

.player {
    display: inline-block;
    text-align: center;
}

.player img {
    width: 150px;
    height: auto;
    border: 1px solid #ccc;
    border-radius: 50%;
}

footer {
    background-color: #343a40;
    color: white;
    text-align: center;
    padding: 10px 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

