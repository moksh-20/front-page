<!DOCTYPE html>
<html>

<head>
    <link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css" integrity="sha384-JcKb8q3iqJ61gNV9KGb8thSsNjpSL0n8PARn9HuZOnIxN0hoP+VmmDGMN5t9UJ0Z" crossorigin="anonymous" />
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.1/dist/umd/popper.min.js" integrity="sha384-9/reFTGAW83EW2RDu2S0VKaIzap3H66lZH81PoYlFhbGU+6BZp6G7niu735Sk7lN" crossorigin="anonymous"></script>
    <script src="https://stackpath.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js" integrity="sha384-B4gt1jrGC7Jh4AgTPSdUtOBvfO8shuf57BaghqFfPlYxofvL8/KUEfYiJOMMV+rV" crossorigin="anonymous"></script>
</head>


<body>
    <style>
        .bg-container-1 {
            background-image: url("https://assets-global.website-files.com/663b1a24e3e50e7f3975727a/6642d5aa286595708e6ff3fc_Dark%20Full.png");
            color: #191936;
            height: 100vh;
            width: 100vw;
            background-size: cover;
        }

        .heading-1 {
            font-family: cursive;
            text-align: center;
            font-weight: bold;
            padding: 40px;
            font-size: 70px;
            color: #0d2930;
        }

        .p-2 {
            text-align: center;
            font-size: 30px;
        }

        .btn-1 {
            text-align: center;
            padding: 10px;
            height: 100px;
        }

        .bg-2 {
            background-color: transparent;
            border-radius: 10px;
            border: 1px solid black;
            height: 100vh;
            color: #0d2930;
        }

        .image {
            height: 30vh;
            margin-left: auto;
            margin-right: auto;
        }

        .im {
            display: flex;
            justify-content: center;
            align-items: center;
        }
    </style>

    <div>
        <h1 class="heading-1">ARTIGENZ</h1>
        <div class=" bg-2 fixed-center">
            <div class="im">
                <img src="https://img.freepik.com/premium-vector/ai-logo-template-vector-with-white-background_1023984-15069.jpg" class="image" />
            </div>
            <p class="p-2">Welcome to <br>ARTIGENZ <br>click on below button <br> to login</p>
            <div class=" btn-1">
                <button id="myButton">Login</button>
                <button>Sign Up</button>
            </div>
        </div>
    </div>
    <script>
        document.getElementById("myButton").addEventListener("click", function() {
            alert("you don't have a account please click on sign up");
        });
    </script>
</body>

</html>
