body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

nav ul {
    list-style-type: none;
    margin: 0;
    padding: 0;
    background-color: #004080;
}

nav ul li {
    display: inline;
    padding: 10px;
}

nav ul li a {
    text-decoration: none;
    color: white;
    padding: 10px 15px;
    display: inline-block;
}

h1 {
    color: #333;
}

table {
    width: 100%;
    border-collapse: collapse;
    margin: 20px 0;
    font-size: 18px;
}

table th, table td {
    text-align: left;
    padding: 12px;
}

table tr:nth-child(even) {
    background-color: #f2f2f2;
}

button {
    background-color: #004080;
    color: white;
    border: none;
    padding: 10px 20px;
    cursor: pointer;
}

button:hover {
    background-color: #0066cc;
}
<%@ include file="header.html" %>
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Reservaciones</title>
</head>
<body>
    <h1>Reservaciones</h1>
    <table>
        <thead>
            <tr>
                <th>N° Mesa</th>
                <th>Capacidad</th>
                <th>Reservación</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td><img src="img/mesa1.png" alt="Mesa 1"> (1)</td>
                <td>4</td>
                <td><button>Reservación</button></td>
            </tr>
            <tr>
                <td><img src="img/mesa2.png" alt="Mesa 2"> (2)</td>
                <td>2</td>
                <td><button>Reservación</button></td>
            </tr>
            <!-- Repite según los datos -->
        </tbody>
    </table>
</body>
</html>
<%@ include file="header.html" %>
<!DOCTYPE html>
<html>
<head>
    <link rel="stylesheet" type="text/css" href="style.css">
    <title>Inicio</title>
</head>
<body>
    <h1>Hola Equipo: <span>Buenos días</span></h1>
</body>
</html>
