<head>
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link href="https://fonts.googleapis.com/css2?family=Roboto+Condensed:ital,wght@0,100..900;1,100..900&amp;family=Roboto:ital,wght@0,100;0,300;0,400;0,500;0,700;0,900;1,100;1,300;1,400;1,500;1,700;1,900&amp;display=swap" rel="stylesheet" />
</head>
<slot/>

<style>
    :global(.roboto-condensed-medium-italic) {
        font-family: "Roboto Condensed", sans-serif;
        font-weight: 500;
        font-style: italic;
    }
    :global(.roboto-regular) {
        font-family: "Roboto", sans-serif;
        font-weight: 400;
        letter-spacing: 0.25px;
    }
    :global(body) {
        font-family: "Roboto", sans-serif;
        font-weight: 500;
        letter-spacing: 0.4px;
        font-style: italic;
        background-color: #CFD4C5;
    }
</style>
