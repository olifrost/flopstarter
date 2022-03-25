---
layout: page
title: Submit
---
<form action="https://formspree.io/f/xeqnlqyk" method="POST">

  <label for="Title">Title:</label>
  <input type="text" name="name" placeholder="Flopstarter" required>

  <label for="Message">Description:</label>
  <input type="text" name="description" rows="20" cols="20" id="Message" placeholder="A platform for bad ideas" required>

  <label for="Email">Contact (Optional):</label>
  <input type="email" name="replyto"  id="Email" placeholder="If you would like to be credited or raise funds">
  <input type="hidden" name="_next" value="http://flopstarter.com/thanks/" />

    <input type="submit" value="Submit" class="submit-button">
</form>
