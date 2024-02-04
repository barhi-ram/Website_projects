# Website_projects
In this repository, you will find some small website development projects.

___________________________________________________________________________ 
<br>

  <h1>Author : Ram Pujan Barhi </h1>
<br>
The first project is for gym website .


<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ram Fitness center</title>

</head>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Baloo+Da+2:wght@500&display=swap" rel="stylesheet">


<link rel="stylesheet" href="/CSS/style.css">
<style>
    /* CSS Reset */
    body {
        font-family: 'Baloo Da 2', sans-serif;
        color: white;
        margin: 0px;
        padding: 0px;
        /* background: url(gym.jpg); */
        background: url(imageweb.jpg);
        background-size: 1500px;
        /* background-repeat: no-repeat; */
      
    }
 

    .left {
        display: inline-block;
        position: absolute;
        left: 20px;
        top: 20px;


        /* border: 2px solid red; */
    }

    .mid {
        display: block;
        width: 58%;
         
        margin: 38px auto;
        /* border: 2px solid green; */
    }

    .right {
        position: absolute;
        right: 10px;
        top: 20px;
        display: inline-block;
        /* border: 2px solid yellow; */
    }

    .navbar {
        display: inline-block;
    }

    .navbar li {

        display: inline-block;

    }

    .navbar li a {
        color: white;
        text-decoration: none;
        padding: 50px 12px 0px 12px;
        font-size: 30px;
    }


    .navbar li a:hover,
    .navbar li a.active {
        color: rgb(216, 200, 231);
        text-decoration: underline;

    }

    .left img {
        width: 75px;
    }

    .left div {

        text-align: center;
    }

    .btn {
        font-family: 'Baloo Da 2', sans-serif;
        box-shadow: 3px 3px 3px rgb(115, 179, 173);
        margin: 0px 9px;
        background-color: black;
        color: white;
        padding: 4px 10px;
        border: 2px solid gray;
        border-radius: 10px;
        font-size: 12px;
        cursor: pointer;
    }


.container h1{

    text-align:  center;
}

.container button{
    display: block;
    width: 45%;
    padding: 7px 0px;
    margin: 12px auto;
    font-size: 20px;
    letter-spacing: 5px;
}
    .form-group input {    
        font-family: 'Baloo Da 2', sans-serif;
        box-shadow: 3px 3px 3px rgb(115, 179, 173);
        margin: 4px auto;
        background-color: white;
        color: blue;
        padding: auto;
        border: 2px solid gray;
        border-radius: 10px;
        font-size: 12px;
        cursor: pointer;
        width: 340px;
        text-align: center;
        display: block;
        font-size: 18px;
       
    }



 






    .btn:hover {
        background-color: gray;
        box-shadow: 3px 3px 3px rgb(209, 145, 73);

    }



    /* div style  */
    .container {

        border: 2px solid yellow;
        margin: 40px 29px;
        padding: 2px 45px 15px 45px;
        width: 41%;
        border-radius: 15px;

    }

    .container h1 {
        /* white-space: nowrap; */
        text-shadow: 1px 12px 10px rgb(45, 217, 230);
    }
</style>

<body>
    <header class="header">
        <!-- Left box for logo -->
        <div class="left">
            <div>


                <img src="logo.png" alt="error">
                <div>

                    Ram Fitness Center

                </div>


            </div>

        </div>
        <!-- Mid box for navbar -->
        <div class="mid">
            <ul class="navbar">
                <li><a href="#" class="active">Home</a></li>
                <li><a href="#">About Us</a></li>
                <li><a href="#">Fitness Calculator </a></li>
                <li><a href="#">Contact Us</a></li>


            </ul>

        </div>
        <!-- Right box for button -->

        <div class="right">
            <button class="btn">Call us now </button>

            <button class="btn">Email Us</button>
        </div>
    </header>










    <div class="container">
        <h1>Join the best Gym of Kathmandu Now</h1>
        <form action="noaction.php"></form>
        


        <div>

            <div class="form-group">

                <input type="text" name="" placeholder="Enter Your Name">
    
            </div>
    


             
            <div class="form-group">

                <input type="text" name="" placeholder="Enter Your Age">

            </div>
            <div class="form-group">

                <input type="text" name="" placeholder="Enter Your Gender">

            </div>
            <div class="form-group">

                <input type="text" name="" placeholder="Enter Your Location">

            </div>
            <div class="form-group">

                <input type="text" name="" placeholder="Enter Your mobile No">

            </div>
            <button class="btn">Submit</button>

        </div>
    </div>
</body>

</html>
