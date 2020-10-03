<head>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
</head>
## Hello World

<form action="http://localhost:5000/" method="post" name="myForm">
 <ul>
  <li>
    <label for="name">Order_ID:</label>
    <input type="text" id="name" name="user_name">
  </li>
  <li>
    <label for="mail">Root_Order_id:</label>
    <input type="email" id="mail" name="user_email">
  </li>
  <li>
    <label for="msg">Trade_Date:</label>
    <textarea id="msg" name="user_message"></textarea>
  </li>
 </ul>
 <li class="button">
  <button onclick="changeText()">Send Message-10</button>
  <!--<button type="submit">Send your message</button> -->
</li>
 <h1 onclick="changeText(this)">SubmitForLocalhost</h1>

<script>
function changeText() {
  <!-- id.innerHTML = "Ooops!"; -->
 <!-- window.location.href="http://www.google.com"; -->
 window.location.href="http://127.0.0.1:5000/api/v1/resources/books/all";
}

 function demo() { 
  var formData = JSON.stringify($("#myForm").serializeArray());
  $.ajax({ 
     type: "GET", 
     url: "http://127.0.0.1:5000/api/v1/resources/books/all", 
     data: formdata, 
     datatype: "json", 
     contentType : "application/json"
     success: function(){ 
        alert("AJAX request successfully completed");
       // Do operation what you want to do 
     } 
  }); 
} 
</script> 
<input type="submit" onclick="demo()" value="SubmitAJAX"> 

</form>
