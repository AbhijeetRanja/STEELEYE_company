<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Orders Dashboard</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="dashboard">
        <div class="left">
            <h2>1. Select Order Details</h2>
            <ul>
                <li>buySellIndicator</li>
                <li>orderStatus</li>
                <li>orderType</li>
            </ul>
        </div>
        <div class="right">
            <h2>*Select Order Timestamps*</h2>
            <ul>
                <li>orderRecived 2022-11-04 T15:29:00Z</li>
                <li>orderStatusUpdated 2022-11-04 T15:29:00Z</li>
                <li>orderSubmitted 2022-11-04 T15:29:00Z</li>
            </ul>
        </div>
    </div>
    <div class="order-table">
        <table>
            <tr>
                <th>Order Id</th>
                <th>Buy/Sell</th>
                <th>Country</th>
                <th>Order Submitted</th>
                <th>Order Volume/USD</th>
            </tr>
            <tr>
                <td>1</td>
                <td>BUY</td>
                <td>USA</td>
                <td>2022-11-04 T15:29:00Z</td>
                <td>$1000</td>
            </tr>
            <tr>
                <td>2</td>
                <td>SELL</td>
                <td>Canada</td>
                <td>2022-11-04 T15:30:00Z</td>
                <td>$500</td>
            </tr>
            <!-- Add more rows if needed -->
        </table>
    </div>
</body>
</html>
