#index.html<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Expense Tracker</title>
    <link rel="stylesheet" href="styles.css"><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Expense Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Register</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="login.html">Login</a></li>
        </ul>
    </nav>
    <section>
        <form action="#" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Register</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 Expense Tracker</p>
    </footer>
</body>
</html>

2. register.html
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register - Expense Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Register</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="login.html">Login</a></li>
        </ul>
    </nav>
    <section>
        <form action="#" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Register</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 Expense Tracker</p>
    </footer>
</body>
</html>

3.login.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login - Expense Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Login</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="register.html">Register</a></li>
        </ul>
    </nav>
    <section>
        <form action="#" method="post">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Login</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 Expense Tracker</p>
    </footer>
</body>
</html>

4. add_expense.html 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Add Expense - Expense Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Add Expense</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="view_expense.html">View Expenses</a></li>
        </ul>
    </nav>
    <section>
        <form action="#" method="post">
            <label for="expense_name">Expense Name:</label>
            <input type="text" id="expense_name" name="expense_name" required>
            <label for="amount">Amount:</label>
            <input type="number" id="amount" name="amount" required>
            <label for="date">Date:</label>
            <input type="date" id="date" name="date" required>
            <button type="submit">Add Expense</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 Expense Tracker</p>
    </footer>
</body>
</html>

5. edit_expense.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Edit Expense - Expense Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Edit Expense</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="view_expense.html">View Expenses</a></li>
        </ul>
    </nav>
    <section>
        <form action="#" method="post">
            <label for="expense_name">Expense Name:</label>
            <input type="text" id="expense_name" name="expense_name" required>
            <label for="amount">Amount:</label>
            <input type="number" id="amount" name="amount" required>
            <label for="date">Date:</label>
            <input type="date" id="date" name="date" required>
            <button type="submit">Edit Expense</button>
        </form>
    </section>
    <footer>
        <p>&copy; 2023 Expense Tracker</p>
    </footer>
</body>
</html>

6. view_expense.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>View Expenses - Expense Tracker</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>View Expenses</h1>
    </header>
    <nav>
        <ul>
            <li><a href="index.html">Home</a></li>
            <li><a href="add_expense.html">Add Expense</a></li>
        </ul>
    </nav>
    <section>
        <table>
            <thead>
                <tr>
                    <th>Expense Name</th>
                    <th>Amount</th>
                    <th>Date</th>
                    <th>Actions</th>
                </tr>
            </thead>
            <tbody>
                <tr>
                    <td>Sample Expense</td>
                    <td>$100</td>
                    <td>2023-06-22</td>
                    <td>
                        <a href="edit_expense.html">Edit</a>
                    </td>
                </tr>
            </tbody>
        </table>
    </section>
    <footer>
        <p>&copy; 2023 Expense Tracker</p>
    </footer>
</body>
</html>

styles.css
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 10px 0;
    text-align: center;
}

nav ul {
    background-color: #444;
    list-style-type: none;
    padding: 0;
    text-align: center;
    margin: 0;
}

nav ul li {
    display: inline;
}

nav ul li a {
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    display: inline-block;
}

nav ul li a:hover {
    background-color: #555;
}

section {
    padding: 20px;
}

form {
    max-width: 600px;
    margin: 0 auto;
    background: #fff;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 0 10px rgba(0,0,0,0.1);
}

form label {
    display: block;
    margin-bottom: 10px;
}

form input {
    width: 100%;
    padding: 10px;
    margin-bottom: 20px;
    border: 1px solid #ddd;
    border-radius: 5px;
}

form button {
    width: 100%;
    padding: 10px;
    background: #333;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

form button:hover {
    background: #555;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin-top: 20px;
}

table th, table td {
    padding: 10px;
    border: 1px solid #ddd;
    text-align: left;
}

table th {
    background-color: #333;
    color: #fff;
}

table tr:nth-child(even) {
    background-color: #f4f4f4;
}

footer {
    text-align: center;
    padding: 20px;
    background-color: #333;
    color: #fff;
    position: fixed;
    bottom: 0;
    width: 100%;
}

@media (max-width: 600px) {
    nav ul {
        display: block;
    }

    nav ul li {
        display: block;
        text-align: left;
    }
}

