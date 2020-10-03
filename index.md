<!DOCTYPE html>
<html>
	<head>
		<title>Input Form</title>
	</head>
	<body>
		<form action="http://localhost:5000/api/v1/resources/books/all" name="myForm" method="post">
			<label for="order_id">Order Id</label><br>
			<input type="text" id="order_id" name="order_id"><br>
			<label for="root_order_id">Root Order ID</label><br>
			<input type="text" id="root_order_id" name="root_order_id"><br>
			<label for="customer_account_mnemonic">Customer Mnemonic</label><br>
			<input type="text" id="customer_account_mnemonic" name="customer_account_mnemonic"><br>
			<label for="ticker_symbol">Security Code</label><br>
			<input type="text" id="ticker_symbol" name="ticker_symbol"><br>
			<label for="side">Side</label><br>
			<input type="text" id="side" name="side"><br>
			<label for="trade_date">Trade Date</label>
			<input type="date" id="start_trade_date" name="start_trade_date" value="2020-10-03" min="2018-01-01" max="2025-12-31"><br>
			<input type="date" id="start_trade_date" name="start_trade_date" value="2020-10-03" min="2018-01-01" max="2025-12-31"><br><br>
			<input type="submit" value="SubmitForm">
		</form>
	</body>
</html>
