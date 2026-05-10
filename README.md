<!doctype html>
<html lang="en">
<head><meta charset="utf-8"/><meta name="viewport" content="width=device-width,initial-scale=1"/><title>Contact — Lavyn Consulting</title></head>
<body style="font-family:system-ui, sans-serif;max-width:720px;margin:24px auto;padding:16px;">
  <h1>Contact</h1>
  <!-- Replace FORM_ENDPOINT with your Formspree endpoint or use Google Forms action -->
  <form action="https://formspree.io/f/FORM_ENDPOINT" method="POST">
    <label style="display:block;margin-bottom:8px;">Name<br/><input name="name" required style="width:100%"/></label>
    <label style="display:block;margin-bottom:8px;">Email<br/><input name="_replyto" type="email" required style="width:100%"/></label>
    <label style="display:block;margin-bottom:8px;">Message<br/><textarea name="message" required style="width:100%;height:120px"></textarea></label>
    <button type="submit">Send</button>
  </form>
</body>
</html>
