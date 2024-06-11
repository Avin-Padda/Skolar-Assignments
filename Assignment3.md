<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HTML Table</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
            border: 1px solid #ddd;
            margin: 20px 0;
        }
        table, th, td {
            border: 1px solid #ddd;
        }
        th, td {
            padding: 12px;
            text-align: center;
            border: 1px solid #ddd;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>
    <table>
        <caption><b>Time Table</b></caption>
        <thead>
            <tr>
                <th>Time/Day</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
                <th>Sunday</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><b>Morning</b></td>
                <td>Eng</td>
                <td>Mat</td>
                <td>Che</td>
                <td>Phy</td>
                <td>Sci</td>
                <td>Evs</td>
                <td>Break</td>
            </tr>
            <tr>
                <td><b>Afternoon</b></td>
                <td>Evs</td>
                <td>Che</td>
                <td>Phy</td>
                <td>Sci</td>
                <td>Mat</td>
                <td>Eng</td>
                <td>Break</td>
            </tr>
            <tr>
                <td><b>Evening</b></td>
                <td>Sci</td>
                <td>Che</td>
                <td>Phy</td>
                <td>Evs</td>
                <td>Eng</td>
                <td>Mat</td>
                <td>Break</td>
            </tr>
        </tbody>
    </table>
</body>
</html>****
