<h1>Peliculas Marvel</h1>

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


<h2>Pautas:</h2>
<h4>Register(nombre (unico),email,password,rol)</h4>
<h4>Login(nombre,password)</h4>
<h4>Si el rol es admin: el cliente no puede ver la vista del admin. El admin puede añadir o eliminar una pelicula.</h4>
<h4>Si el rol es cliente: puede ver todas las peliculas, guardarlas en favoritos y buscar por nombre en un buscador</h4>
