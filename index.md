## Hello World

<form action="/my-handling-form-page" method="post">
 <ul>
  <li>
    <label for="name">Name:</label>
    <input type="text" id="name" name="user_name">
  </li>
  <li>
    <label for="mail">E-mail:</label>
    <input type="email" id="mail" name="user_email">
  </li>
  <li>
    <label for="msg">Message:</label>
    <textarea id="msg" name="user_message"></textarea>
  </li>
 </ul>
 <li class="button">
  <button type="submit">Send your message</button>
</li>
 <h1 onclick="changeText(this)">Submit</h1>

<script>
function changeText(id) {
  id.innerHTML = "Ooops!";
}
</script>

</form>
