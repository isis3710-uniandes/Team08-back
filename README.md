# Team08-back
<img src="https://ssaenz11.github.io/images/donu.jpg">
<h1>Descripción del proyecto Donu</h1>
<p>Donu es una plataforma web que pretender facilitar el proceso de donaciones entre las personas y las ONG En esta plataforma pretendemos que tanto los usuario y las ong puedan decir los elementos que pueden donar y los que realmente necesitan. Existen también empresas que patrocinan las ONG y empresas de transporte que estarán encargadas de facilitar la transacción. Finalmente pueden observarse las evicencias de que se han hecho con las donaciones que se han dado.</p>
<br>
<img src="https://api.genmymodel.com/projects/_K1b0oD05EemQWcstM2zleA/diagrams/_K1b0oz05EemQWcstM2zleA/svg">

<h1>Instrucciones para correr el proyecto</h1>
<ol>
  <li >Descargar el proyecto </li>
  <li >hacer sudo npm install </li>
  <li >hacer sudo npm install nodemon </li>
  <li >hacer npm start </li>
  <li >abrir en un navegador con la url http://localhost:3000/</li>
  <li >las pruebas de postman se encuentran en las carpeta "pruebas de postman"</li>
</ol>
<h1>Puntos a tener en cuenta</h1>
<ul>
  <li value="20"><strong>AL CORRER LAS PRUEBAS DE POSTMAN ASEGURESE DE COLOCAR UN DELAY DE 500 MS PUES ESTO DISMINUYE QUE REBOTE LA SOLICITUD. ESTO OCURRE PORQUE ESTAMOS ESCRIBIENDO SOBRE UN DOC TIPOS JSON Y HACE QUE LAS PETICIONES NECESITEN DE MÁS TIEMPO. CUANDO LA PETICIÓN REBOTE SE VERÁ QUE A PESAR DE QUE EL STATUS ES 200 EL RETORNO VA A SER 0</strong></li>
  <li value="20">RECUERDE QUE PARA LAS PRUEBAS DE DELETE CORRERAN CORRECTAMENTE SOLO UNA VEZ, PUESTO QUE LUEGO ESTARÁN BORRADOS LOS ELEMENTOS</li>
</ul>

<h2>Rutas de peticiones ejemplos</h2>
<ul>
  <li > GET: http://localhost:3000/solicitud</li>
   <li >GET: http://localhost:3000/ong </li>
   <li >GET: http://localhost:3000/sponsor </li>
   <li >GET: http://localhost:3000/beneficiarios </li>
   <li >GET: http://localhost:3000/donantes </li>
   <li >GET: http://localhost:3000/articulos </li>
   <li >GET: http://localhost:3000/benefit </li>
   <li >GET: http://localhost:3000/transportationCompany </li>
   <li >GET: http://localhost:3000/evidence </li>
   <li >POST: http://localhost:3000/solicitud </li>
   <li >POST: http://localhost:3000/ong </li>
   <li >POST: http://localhost:3000/sponsor </li>
   <li >POST: http://localhost:3000/beneficiarios </li>
   <li >POST: http://localhost:3000/donantes </li>
  <li >POST: http://localhost:3000/articulos </li>
   <li >POST: http://localhost:3000/benfit </li>
   <li >POST: http://localhost:3000/transportationCompany </li>
   <li >POST: http://localhost:3000/evidence </li>
   <li >PUT: http://localhost:3000/solicitud/17 </li>
   <li >PUT: http://localhost:3000/ong/17 </li>
   <li >PUT:http://localhost:3000/sponsor/17 </li>
   <li >PUT: http://localhost:3000/beneficiarios/15 </li>
   <li >PUT: http://localhost:3000/donantes/15 </li>
   <li >PUT: http://localhost:3000/articulos/13 </li>
   <li >PUT: http://localhost:3000/benefit/5c7b3dd2006bf3210b17262f</li>
   <li >PUT: http://localhost:3000/transportationCompany/5c7b3fc1ae475c2b34130e07 </li>
   <li >PUT: http://localhost:3000/evidence/5c7b3aeef03b0526b19463cd</li>
   <li >DELETE:http://localhost:3000/solicitud/17 </li>
   <li >DELETE:http://localhost:3000/ong/17 </li>
   <li >DELETE:http://localhost:3000/sponsor/17 </li>
   <li >DELETE: http://localhost:3000/beneficiarios/998 </li>
   <li >DELETE: http://localhost:3000/donantes/998 </li>
   <li >DELETE: http://localhost:3000/articulos/998 </li>
   <li >DELETE: http://localhost:3000/benefit/5c7b3dd2006bf3210b17262f</li>
   <li >DELETE: http://localhost:3000/transportationCompany/5c7b3fc1ae475c2b34130e07 </li>
   <li >DELETE: http://localhost:3000/evidence/5c7b3aeef03b0526b19463cd</li>
 </ul>


