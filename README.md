<strong>Project Title:</strong> TODO App

<strong>Description:</strong>

I created a TODO app to practice JavaScript and its paradigms, focusing on DOM manipulation and functionality. The application allowed me to add TODO items, track the total number of TODOs, and keep count of unchecked TODOs.

<strong>Technologies Used:</strong>

<ul>
  <li><strong>HTML:</strong> For the structure of the web pages.</li>
  <li><strong>CSS:</strong> For styling the TODO app, utilizing pre-written styles.</li>
  <li><strong>JavaScript:</strong> For implementing dynamic functionalities and interactions within the TODO app.</li>
</ul>
<strong>Features:</strong>

<strong>Adding TODOs:</strong>

<ul>
  <li>I implemented the functionality to create new TODO items when a button was clicked. Each TODO item included a checkbox and a label.</li>
  <li>The <code>addTodo()</code> function was responsible for adding TODOs to the list and updating the count of total and unchecked TODOs.</li>
</ul>
<strong>Updating TODO Counts:</strong>

<ul>
  <li>I created a function to update the count of total TODOs and unchecked TODOs dynamically. This count was displayed on the page and updated whenever a TODO item was added or its checkbox was checked or unchecked.</li>
</ul>
<strong>Delete Functionality:</strong>

<ul>
  <li>As an additional challenge, I added a delete button to each TODO item. Clicking this button removed the TODO item from the list and updated the counts accordingly.</li>
</ul>
Setup Instructions and Running the Code in a Browser
Download and Setup
Download the project from this link and unzip it.

Navigate to Project Directory
Open a terminal, navigate (cd) to the mail directory: cd CS50-project-6-javascript-mail

Apply Migrations
Run the following commands to set up the database:

bash
Copy code
python manage.py makemigrations mail
python manage.py migrate
Start the Web Server
Run:

bash
Copy code
python manage.py runserver
Open the server in your browser (usually http://127.0.0.1:8000/).

Register an Account
Register with any email and password (they don’t need to be real).

Using the Email Client
After logging in, navigate through Inbox, Sent, and Archive using the buttons. Use the "Compose" button to create new emails. All interactions happen dynamically without reloading the page.
