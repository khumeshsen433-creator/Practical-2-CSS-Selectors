# Practical-2-CSS-Selectors
<!DOCTYPE html>
<html>
<head>
    <title>College Information</title>

    <style>
        /* Universal selector */
        * {
            font-family: Arial, sans-serif;
        }

        /* Element selector */
        h1 {
            color: navy;
            text-align: center;
        }

        /* Class selector */
        .info {
            background-color: lightyellow;
            padding: 10px;
        }

        /* ID selector */
        #college {
            color: red;
        }

        /* Grouping selector */
        h2, p {
            margin: 10px;
        }

        /* Descendant selector */
        div p {
            color: green;
        }
    </style>
</head>
<body>

    <h1 id="college">ABC College</h1>

    <h2>College Information</h2>

    <p class="info">Welcome to ABC College.</p>

    <div>
        <p>Courses: BCA, B.Tech, B.Sc.</p>
        <p>Facilities: Library, Labs and Sports.</p>
    </div>

</body>
</html>