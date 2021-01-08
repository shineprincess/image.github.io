<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Overlay Image</title>

    <style>
        *{
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        .parent_div {
            width: 100vw;
            height: 100vh;
            background: cyan;
            display: flex;
            justify-content: center;
            align-items: center;

        }
        .child_div {
            width: 60vw;
            height: 60vh;
            /* background: lawngreen; */
            background-image: linear-gradient(120deg, rgba(0,0,0,0.5)50%,transparent 50%) , url(https://media.tacdn.com/media/attractions-splice-spp-674x446/0a/dc/a3/40.jpg);
            background-size: 100% 100%;
            box-shadow: 0 10px 20px -6px #000;
        }

        @media (max-width: 768px) {
            .child_div {
                background-image: linear-gradient(120deg, rgba(0,0,0,0.7),rgba(0,0,0,0.7) ) , url(https://media.tacdn.com/media/attractions-splice-spp-674x446/0a/dc/a3/40.jpg);
                
            }
        }

    </style>


</head>


<body>
    <div class="parent_div">
        <div class="child_div">

        </div>
    </div>
</body>
</html>
