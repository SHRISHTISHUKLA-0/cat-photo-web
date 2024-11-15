<!DOCTYPE html>
<html lang="en">
  <head>
    <title>CatPhotoApp</title>
  </head>
  <body>
<h2>CatPhotoApp</h2>
<main>
  <h3>Cat Photos</h3>
  <!--ToDO: add link to cat photos -->
  <p>Click here to view more <a href="#"  target="_blank">cat photos</a>.</p>
  <a href="#"><img src="c:\Users\ADMIN\Downloads\cats.jpg" alt="A cute orange cat lying
    on its back."></a>
    <h3>Cat Lists</h3>
    <div class="lists">
      <p>Things cats <em>love</em>:</p>
      <ul>
        <li>cat nip</li>
        <li>laser pointers</li>
        <li>lasagna</li>

      </ul>
      <img src="c:\Users\ADMIN\Downloads\lasagna.jpg" alt="lasagna">
      <p>Things cats <strong>hate</strong>:</p>
      <ol>
        <li>flea treatment</li>
        <li>thunder</li>
        <li>other cats</li>
      </ol>
    </div>
    <img src="cats.jpg" alt="cats">
    <form action="/submit-cat-photo">
      <label for="indoor"><input id="indoor" type="radio" name="indoor-outdoor"
        checked> Indoor</label>label><br>

        <label for="loving"><input id="loving" type="checkbox" name="personality" checked> Loving</label><br>
        <label for="lazy"><input id="lazy" type="checkbox" name="personality"> Lazy</label><br>
        <label for="energetic"><input id="energetic" type="checkbox" name="personality"> Energetic</label><br>

        <input type="text" placeholder="cat photo URL" required><br>
        <button type="submit">submit</button>
      </form>
    </main>
   <footer>
    <p><small>No Copyright - <a href="https://shrishtishukla-art.blogspot.com</a></small></p>
  </footer>
</body>
</html>
