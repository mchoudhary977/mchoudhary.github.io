## Hello World

<form action="/my-handling-form-page" method="post">
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
  <button type="submit" onclick="changeText(this)">Send your message</button>
  <!--<button type="submit">Send your message</button> -->
</li>
 <!--<h1 onclick="changeText(this)">Submit</h1> -->

<script>
function changeText(id) {
  <!-- id.innerHTML = "Ooops!"; -->
 window.location.href="http://www.google.com";
}
</script>

</form>
