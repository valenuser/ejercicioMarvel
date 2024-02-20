

<h1>Peliculas Marvel</h1>
<img src='[https://upload.wikimedia.org/wikipedia/commons/b/b9/Marvel_Logo.svg](https://38.media.tumblr.com/c3a315a0812b91696068ad95f1c3b8d0/tumblr_nmulilJVEs1sogfsmo1_1280.gif)'>
<h2>Node dependencias:</h2>
<ul>
  <li>express</li>
  <li>express-validator</li>
  <li>mongoose/mysql2</li>
  <li>uuid(si no se usa mongo)</li>
  <li>bcryptjs</li>
  <li>jsonwebtoken</li>
  <li>express-session</li>
  <li>morgan</li>
  <li>nodemon</li>
  <li>ejs/pug</li>
</ul>

<img src='https://i.pinimg.com/originals/07/0a/4b/070a4b09f4fac7795aac0ff95c48c687.gif'>
<h2>Pautas:</h2>
<h4>Register(nombre (unico),email,password,rol,token)</h4>
<h4>Login(nombre,password)</h4>
<h4>El usuario tendra vista general donde se vean todas las peliculas y otra donde sea su perfil y se vean todas sus peliculas favoritas</h4>
<h4>Las peliculas deben tener: titulo,picture</h4>
<h4>Si el rol es admin: el usuario no puede ver la vista del admin. El admin puede añadir o eliminar una pelicula.</h4>
<h4>Si el rol es usuario: puede ver todas las peliculas, guardarlas en favoritos y buscar por nombre en un buscador</h4>
<h4>Debe haber una tabla en la db con todas las peliculas</h4>
