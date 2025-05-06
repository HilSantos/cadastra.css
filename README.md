# cadastra.css
Criação do layout de cadastracliente.php

/* Reset básico */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-color: #031220;
    padding: 30px;
}

h1 {
    text-align: center;
    margin-bottom: 20px;
    color: #3bdb49;
}

form {
    max-width: 600px;
    margin: 0 auto;
    background-color: #dfd0d0;
    padding: 30px;
    border-radius: 12px;
    box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
}

label {
    display: block;
    margin-top: 15px;
    font-weight: bold;
    color: #444;
}

input[type="text"],
input[type="email"],
input[type="date"],
input[type="password"],
select {
    width: 100%;
    padding: 10px;
    margin-top: 5px;
    border: 1px solid #ccc;
    border-radius: 8px;
    font-size: 16px;
    transition: border-color 0.3s;
}

input[type="text"]:focus,
input[type="email"]:focus,
input[type="date"]:focus,
input[type="password"]:focus,
select:focus {
    border-color: #0077cc;
    outline: none;
}

input[type="submit"] {
    margin-top: 25px;
    width: 30%;
    padding: 12px;
    background-color: #e0d96bda;
    color: rgb(20, 20, 20);
    border: none;
    border-radius: 8px;
    font-size: 17px;
    cursor: pointer;
    transition: background-color 0.3s;
}

input[type="submit"]:hover {
    background-color: #dbd59d;
}

/* Responsividade */
@media (max-width: 600px) {
    body {
        padding: 15px;
    }

  form {
        padding: 20px;
    }

  input,
    select {
        font-size: 14px;
    }

  h1 {
        font-size: 22px;
    }
}
