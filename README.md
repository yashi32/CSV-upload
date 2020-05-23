# CSV-Manager

<p>
CSV-Manager is used to work with external data, as in 'csv' files and view or show the data present in it.
</p>
<h3>Prerequisites</h3>
<h2>Backend</h2>
<ul>
  <li>Node.js </li>
  <li> Express</li>
  <li>MongoDB </li>
  
 </ul>
 <h2>Frontend</h2>
 <li>HTML </li>
 <li>CSS </li>
 <li>Javascript </li>
 <li>EJS </li>
 <h2>Install Dependencies</h2>
 <ul>
  <li>npm install express</li>
  <li>npm install mongoose</li>
  <li>npm install ejs</li>
  <li>npm install csv-parser</li>
  <li>npm install multer</li>
  <li>npm install express-ejs-layouts</li>
  </ul>
  
  <h3>Start the  App</h3>
  <p>node index.js</p>

<h3>API Endpoints</h3>
<ul>
  <li>[GET] localhost:8000/files --> Display a list of all uploaded files</li>
  <li>[POST] localhost:8000/files/new --> To upload a file</li>
  <li>[GET] localhost:8000/files/:id --> Display the contents of the file</li>
</ul>
