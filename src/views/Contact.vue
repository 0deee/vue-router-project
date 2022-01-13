<template>
  <div class="contact">
    <div class="contact-heading">
      <h1 id="contact-heading">Contact me</h1>
      <p>I will be glad to hear from you!</p>
    </div>
    <div class="contact-body">
        <label>Your name: </label>
        <input type="text" id="name-input" value="Firstname Lastname"><br><br>
        <label id="message-label">Your message to me:</label><br>
        <input type="text" id="message-input" value="Content"><br>
        <input type="submit" value="Send Message" id="send-btn">
    </div>
  </div>
</template>
<style scoped>
.contact {
  display:grid;
  grid-template-columns: auto 700px auto;
  align-items: center;
}
.contact-heading {
  grid-column: 1/4;
  text-align: center;
}
.contact-body {
  grid-column:2/3;
  text-align: left;
}
p {
    font-size: 16px;
    font-weight: 400;
}
#message-input {
    height:150px;
    width:500px;
}
#send-btn {
    border:none;
    color: black;
    background-color:#E1E1E1;
    padding: 15px;
    margin-top: 5px;
}
</style>

