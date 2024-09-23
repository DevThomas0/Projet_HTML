/* Change the file type to css*/

body {
    font-family: Arial, sans-serif;
    background-color: #f2f2f2;
}

.login-container {
    width: 400px;
    margin: 100px auto;
    padding: 30px;
    background-color: #ffffff;
    border: 1px solid #ccc;
    border-radius: 4px;
}

.login-form h2 {
    text-align: center;
    margin-bottom: 30px;
}

.form-group {
    margin-bottom: 20px;
}

.form-group label {
    display: block;
    font-weight: bold;
    margin-bottom: 8px;
}

.form-group input[type="text"],
.form-group input[type="email"],
.form-group input[type="password"],
.form-group select {
    width: 100%;
    padding: 12px;
    box-sizing: border-box;
}

.form-group input[type="checkbox"] {
    margin-right: 10px;
}

.radio-group {
    display: flex;
    gap: 20px;
}

.radio-group label {
    display: flex;
    align-items: center;
    font-weight: normal;
}

.radio-group input[type="radio"] {
    margin-right: 5px;
}

.signin-button {
    width: 100%;
    padding: 12px;
    background-color: #008CBA; /* Blue color for Sign In button */
    color: white;
    border: none;
    font-size: 16px;
    cursor: pointer;
    margin-bottom: 10px; /* Space between Sign In and Login buttons */
}

.signin-button:hover {
    background-color: #007bb5;
}

button[type="submit"] {
    width: 100%;
    padding: 12px;
    background-color: #4CAF50; /* Green color for Login button */
    color: white;
    border: none;
    font-size: 16px;
    cursor: pointer;
}

button[type="submit"]:hover {
    background-color: #45a049;
}
