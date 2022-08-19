# A Very Serious Business Notes Taking App 

<h2>User Story</h2>

<p>
AS A small business owner
I WANT to be able to write and save notes
SO THAT I can organize my thoughts and keep track of tasks I need to complete
</p>

<h2>Getting Up & Running</h2>
<p>
The application has a db.json file on the back end that is used to store and retrieve notes using the fs module.

The following HTML routes was created:
<ul>
    <li>GET /notes returns the notes.html file.</li>
    <li>GET * returns the index.html file.</li>
</ul>

The following API routes was created:
<ul>
<li>GET /api/notes reads the db.json file and returns all saved notes as JSON.</li>
<li>POST /api/notes receives a new note to save on the request body, adds it to the db.json file, and then returns the new note to the client. Each note has a unique ID.</li>
</ul>
</p>