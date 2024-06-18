<body>
    <img class="title" src="/title.png" alt="Rat Economy">

    <p class="content" >
        Our website is currently under construction.
        <br>
        Please visit our temporary website below!
        <br>
        <img class="arrow" src="/arrow.png" alt="Arrow">
    </p>


    <div class="buttons">
        <a href="https://rat-economy.notion.site" target="_blank" class="button roboto-condensed-medium-italic">website</a>
        <a href="https://rat-economy.itch.io" target="_blank" class="button roboto-condensed-medium-italic">itch.io</a>
        <a href="   https://www.youtube.com/@rat-economy" target="_blank" class="button roboto-condensed-medium-italic">youtube</a>
    </div>
</body>

<style>
    .arrow{
        width: 80px;
        transform: rotate(45deg);
        padding-top: 50px;
    }

    .title{
        width: 50vw;
        max-width: 800px;
        min-width: 500px;
    }
    
    body {
        margin: 0;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
        text-align: center;
        gap: 32px;
        height: 100vh; /* Adjust as needed */
    }

    .content {
        font-size: 26px;
        color: black;
        line-height: 2;
    }

    .buttons {
        display: flex;
        gap: 36px;
        margin: 16px;
    }

    .button {
        text-decoration: none;
        padding: 16px 36px;
        border-radius: 10px;
        border: 0;
        background-color: rgb(255, 56, 86);
        letter-spacing: 1.5px;
        font-size: 20px;
        transition: all 0.15s ease;
        box-shadow: rgb(201, 46, 70) 0px 10px 0px 0px;
        color: hwb(0 100% 0%);
        cursor: pointer;
    }
    .button:hover {
        box-shadow: rgb(201, 46, 70) 0px 7px 0px 0px;
    }
    .button:active {
        background-color: rgb(255, 56, 86);
        box-shadow: rgb(201, 46, 70) 0px 0px 0px 0px;
        transform: translateY(5px);
        transition: 300ms;
    }

    @media (max-width: 600px) {
        body {
            gap: 16px;
        }
        .title {
            width: 90vw; /* Use more of the viewport width */
            min-width: initial; /* Remove the minimum width */
        }

        .content {
            font-size: 4.25vw; /* Slightly smaller font size */
        }

        .buttons {
            flex-direction: column; /* Stack buttons vertically */
            gap: 20px; /* Adjust gap for vertical layout */
            width: 90%; /* Full width */
            margin: 0;
            padding: 10px 0px;
        }

        .arrow {
            padding-top: 24px; /* Adjust padding */
        }
    }
</style>

