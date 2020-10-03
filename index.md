<!DOCTYPE html>
<html>
    <head>
        <title>Basic Web Page</title>
		<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    </head>
    <body>
		<form action="http://localhost:5000/api/v1/resources/books/all" name="myForm" method="post">
			<label for="orderid">Order ID: </label><br>
			<input type="text" id="orderid" name="orderid"><br>
			<label for="rootorderid">Root Order ID: </label><br>
			<input type="text" id="rootorderid" name="rootorderid"><br>
			<label for="custmnemonicaccount">CustomerMnemonicAccount: </label><br>
			<input type="text" id="custmnemonicaccount" name="custmnemonicaccount"><br>
			
			<input type="submit" onclick="demo()" value="SubmitForm">
		</form>
	</body>
	
