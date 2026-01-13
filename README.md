# CSS-Day-3
<!DOCTYPE html>
<html>
<head>
    <title>Color Formats and Background Demo</title>
    <style>
        /* Header with named color */
        header {
            background-color: green;
            color: white;
            padding: 15px;
            text-align: center;
        }

        /* Section with HEX color */
        section {
            background-color: #ffcc99;
            padding: 15px;
            margin: 10px;
        }

        /* Div with RGB text and HSL background */
        div {
            color: rgb(255, 255, 255);
            background-color: hsl(210, 60%, 40%);
            padding: 15px;
            margin: 10px;
        }

        /* Footer with background image */
        footer {
            background-image: url("https://via.placeholder.com/900x200");
            background-size: cover;
            background-repeat: no-repeat;
            color: white;
            padding: 30px;
            text-align: center;
        }
    </style>
</head>
<body>

    <header>
        <h1>Named Color Header</h1>
    </header>

    <section>
        <h2>HEX Color Section</h2>
        <p>This section uses HEX background color.</p>
    </section>

    <div>
        <h2>RGB Text & HSL Backgro
