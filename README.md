<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
<body>
    <h1>Todo Flask Project</h1>
    <p>Welcome to the Todo Flask Project! This is a simple web application that allows users to manage their todo list. Users can add, update, delete, and search todos by their title. The project is built using HTML, Python (Flask), and Bootstrap.</p>

<h2>Features</h2>
    <ul>
        <li><strong>Add Todo</strong>: Users can add new todos to their list.</li>
        <li><strong>Update Todo</strong>: Users can update the details of existing todos.</li>
        <li><strong>Delete Todo</strong>: Users can delete todos from their list.</li>
        <li><strong>Search Todo</strong>: Users can search for todos by their title.</li>
    </ul>

<h2>Technologies Used</h2>
    <ul>
        <li><strong>HTML</strong>: For structuring the web pages.</li>
        <li><strong>Python (Flask)</strong>: For the backend server and application logic.</li>
        <li><strong>Bootstrap</strong>: For styling the web pages and making them responsive.</li>
    </ul>

<h2>Installation</h2>
    <ol>
        <li><strong>Clone the repository</strong>:
            <pre><code>(https://github.com/Basil-raza-khan/Python-Flask-TodoApp.git)
cd todo-flask-project</code></pre>
        </li>
        <li><strong>Create a virtual environment</strong>:
            <pre><code>python -m venv venv</code></pre>
        </li>
        <li><strong>Activate the virtual environment</strong>:
            <ul>
                <li><em>On Windows</em>:
                    <pre><code>venv\Scripts\activate</code></pre>
                </li>
                <li><em>On macOS/Linux</em>:
                    <pre><code>source venv/bin/activate</code></pre>
                </li>
            </ul>
        </li>
        <li><strong>Install the required packages</strong>:
            <pre><code>pip install -r requirements.txt</code></pre>
        </li>
        <li><strong>Run the application</strong>:
            <pre><code>flask run</code></pre>
        </li>
        <li>Open your web browser and go to <a href="http://127.0.0.1:5000">http://127.0.0.1:5000</a> to see the application in action.</li>
    </ol>

<h2>Project Structure</h2>
    <pre><code>todo-flask-project/
│
├── app.py                # Main application file
├── requirements.txt      # List of dependencies
├── static/
├── templates/
│   ├── index.html        # Homepage template in-line JavaScript
│   ├── update.html      # Template for updating an existing todo
└── README.md             # Project README file</code></pre>

<h2>Usage</h2>

<h3>Adding a Todo</h3>
    <ol>
        <li>Go to the homepage.</li>
        <li>Click on the "Add Todo" button.</li>
        <li>Fill in the details of the todo and submit the form.</li>
    </ol>

<h3>Updating a Todo</h3>
    <ol>
        <li>Find the todo you want to update.</li>
        <li>Click the "Edit" button next to the todo.</li>
        <li>Update the details and submit the form.</li>
    </ol>

   <h3>Deleting a Todo</h3>
    <ol>
        <li>Find the todo you want to delete.</li>
        <li>Click the "Delete" button next to the todo.</li>
        <li>Confirm the deletion.</li>
    </ol>

<h3>Searching for a Todo</h3>
    <ol>
        <li>Use the search bar at the top of the homepage.</li>
        <li>Enter the title of the todo you are looking for.</li>
        <li>View the search results.</li>
    </ol>

<h2>Contributing</h2>
    <p>If you would like to contribute to this project, please fork the repository and submit a pull request. We welcome all contributions that improve the functionality and user experience of the application.</p>

<p>Thank you for using the Todo Flask Project! If you have any questions or feedback, feel free to open an issue or contact us. Happy coding!</p>
</body>
</html>
