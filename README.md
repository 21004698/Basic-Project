# Basic-Project
Aim :Design a Website like the one given below using CSS.
 Program :
 Home page
 ```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            color: black;
            font-size: 20px;
            padding: 10px;
            text-decoration: none;
        }
            .content {
                position: absolute;
                top: 50%;
                left: 50%;
                transform: translate(-50%,-50%);
                text-align: center;
            }
            .text h2 {
                color: red;
                font-weight: 800;
                font-size: 50px;
                letter-spacing: 3px;
            }
            .text p {
                color: red;
                text-transform: capitalize;
                font-size: 15px;
                margin-bottom: 30px;
                word-spacing: 2px;
                letter-spacing: 1px;
            }
            .login {
                margin: 0px 10px;
                border: 2px solid yellow;
                padding: 13px 35px;
                letter-spacing: 1px;
                color:black;
                border-radius: 30px;
                background-color: yellow;
                text-decoration: none;
            }
            .login:hover {
                border: 2px solid yellow;
                color: yellow;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            } 
            .signup {
                margin: 0px 10px;
                border: 2px solid yellow;
                padding: 13px 35px;
                letter-spacing: 1px;
                color:black;
                border-radius: 30px;
                background-color:  yellow;
                text-decoration: none;
            }
            .signup:hover {
                border: 2px solid gold;
                color: gold;
                background-color: black;
                transition: 0.5s;
                cursor: pointer;
            }
    </style>
</head>
<body>
    <div class="row" style="height: 100px;background-color: rgb(0, 217, 255);">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="page logo.png" style="width: 42%;">
        </div>
        <div class="col-6" style="margin-top: 30px;">
            <a href="">Home</a>
            <a href="">Products</a>
            <a href="">People</a>
            <a href="">Contact</a>
        </div>
        <div class="col-2" style="margin-top: 30px;">
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
        </div>
        <div class="col-1"></div>
        <img src ="software home page.jpg">
    </div>
    <div class="content">
        <div class="text">
            <h2>C M R Solutions </h2>
            <br>
            <p> Transforming Ideas into Impartful Reality through Precision Coding and Innovation </p>
            <br>
            <div>
                <a href="#" class="login"> Log In </a>
                <a href="#" class="signup"> Sign Up </a>
            </div>
        </div>
    </div>  
    </div>
</body>
</html>
```
People.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            color: black;
            font-size: 20px;
            padding: 10px;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <div class="row" style="height: 100px;background-color:rgb(0, 255, 251);">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="page logo.png" style="width: 42%;">
        </div>
        <div class="col-6" style="margin-top: 30px;">
            <a href="">Home</a>
            <a href="">Products</a>
            <a href="">People</a>
            <a href="">Contact</a>
        </div>
        <div class="col-2" style="margin-top: 30px;">
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
        </div>
        <div class="col-1"></div>
    </div>

    <div class="row my-5">
        <div class="col-2 mx-5">
            <div class="card" style="width: 18rem;">
                <img src="ambani.jpeg" class="card-img-top" style="height: 15rem;">
                <div class="card-body">
                    <h4>mukesh ambani  <br> (Founder) </h4>
                </div>
            </div>
        </div>


    <div class="col-2 mx-5">
        <div class="card" style="width: 18rem;">
            <img src="elon musk.jpeg" class="card-img-top" style="height: 15rem;">
            <div class="card-body">
                <h4>elon musk <br> (Founder) </h4>
            </div>
        </div>
    </div>

    <div class="col-2 mx-5">
        <div class="card" style="width: 18rem;">
            <img src="satya nadella.jpeg" class="card-img-top" style="height: 15rem;">
            <div class="card-body">
                <h4>Satya Nadella <br> (CEO & Chairman)</h4>
            </div>
        </div>
    </div>

    <div class="col-2 mx-5">
        <div class="card" style="width: 18rem;">
            <img src="modi.jpeg" class="card-img-top" style="height: 15rem;">
            <div class="card-body">
                <h4>Narendra modi <br> (Prime minister of India)</h4>
            </div>
        </div>
    </div>
</div>
</body>
</html>
```
Product.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            color: black;
            font-size: 20px;
            padding: 10px;
            text-decoration: none;
        }
        footer {
                background-color: gold;
                margin-top: auto;
            }
    </style>
</head>
<body>
    <div class="row" style="height: 100px;background-color:rgb(0, 255, 225);">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="page logo.png" style="width: 42%;">
        </div>
        <div class="col-6" style="margin-top: 30px;">
            <a href="">Home</a>
            <a href="">Products</a>
            <a href="">People</a>
            <a href="">Contact</a>
        </div>
        <div class="col-2" style="margin-top: 30px;">
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
        </div>
        <div class="col-1"></div>
    </div>

    <div class="row my-5">
        <div class="col-2 mx-5">
            <div class="card" style="width: 18rem;">
                <img src="artificial.webp" class="card-img-top" style="height: 15rem;">
                <div class="card-body">
                    <h4>Artificial Intelligence</h4>
                </div>
            </div>
        </div>


    <div class="col-2 mx-5">
        <div class="card" style="width: 18rem;">
            <img src="Cloud-Solutions.png" class="card-img-top" style="height: 15rem;">
            <div class="card-body">
                <h4>Cloud Solutions</h4>
            </div>
        </div>
    </div>

    <div class="col-2 mx-5">
        <div class="card" style="width: 18rem;">
            <img src="Mobile-Application-Software.jpg" class="card-img-top" style="height: 15rem;">
            <div class="card-body">
                <h4>Mobile Applications</h4>
            </div>
        </div>
    </div>

    <div class="col-2 mx-5">
        <div class="card" style="width: 18rem;">
            <img src="machine learning.jpeg" class="card-img-top" style="height: 15rem;">
            <div class="card-body">
                <h4>Machine Learning</h4>
            </div>
        </div>
    </div>
</div>
</body>
</html>
```
Contact.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.11.3/font/bootstrap-icons.min.css">
    <style>
        a{
            color: black;
            font-size: 20px;
            padding: 10px;
            text-decoration: none;
        }
        .box {
                display: flex;
                column-gap: 40px;
                background: transparent;
                position: relative;
                top: 50px;
            }
            .box-1 {
                height: 400px;
                width: 400px;
                border: 3px solid black;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 250px;
            }
            .box-2 {
                height: 400px;
                width: 400px;
                border: 3px solid black;
                border-radius: 20px;
                background: transparent;
                position: relative;
                left: 300px;
            }
            .box-1 form {
                display: flex;
                color: black;
                background: transparent;
                padding: 10px;
                font-size: 15px;
                position: relative;
                top: 15px;
            }
            .box-1 form input {
                background: transparent;
                display: flex;
                border: 1px solid rgb(30, 4, 4);
                border-radius: 10px;
                padding: 15px 30px;
                font-size: 18px;
                color: black;
                position: relative;
                top: 30px;
            }
            .box-1 form textarea {
                background: transparent;
                color: rgb(32, 7, 7);
                padding: 15px 10px;
                position: relative;
                top: 30px;
                left: 30px;
                border: 1px solid black;
                border-radius: 10px;
            }
            .box-1 form button {
                border: 0;
                outline: none;
                padding: 15px 20px;
                color: black;
                border-radius: 30px;
                background: rgb(10, 236, 236);
                cursor: pointer;
                position: relative;
                top: 50px;
            }
            .box-2 h2 {
                color: rgb(0, 0, 0);
                position: relative;
                top: 25px;
                left: 50px;
                font-size: 30px;
            }
            .box-2 p {
                color: black;
                position: relative;
                top: 50px;
                padding: 10px 80px;
            }
            .box-2 span {
                color: rgb(35, 6, 6);
                font-size: 20px;
            }
            
    </style>
</head>
<body>
    <div class="row" style="height: 100px;background-color: rgb(0, 255, 238);">
        <div class="col-1"></div>
        <div class="col-2">
            <img src="page logo.png" style="width: 42%;">
        </div>
        <div class="col-6" style="margin-top: 30px;">
            <a href="">Home</a>
            <a href="">Products</a>
            <a href="">People</a>
            <a href="">Contact</a>
        </div>
        <div class="col-2" style="margin-top: 30px;">
            <a href=""><i class="bi bi-facebook"></i></a>
            <a href=""><i class="bi bi-twitter"></i></a>
            <a href=""><i class="bi bi-instagram"></i></a>
            <a href=""><i class="bi bi-youtube"></i></a>
        </div>
        <div class="col-1"></div>
        <div class="box">
            <div class="box-1">
                <form>
                    <center>
                        <h1>For any queries</h1>
                        <input type="text" placeholder="Enter your name">
                        <br>
                        <input type="email" placeholder="Enter your email">
                        <br>
                        <textarea rows="4" cols="30" placeholder="Any comments"> </textarea>
                        <br>
                        <button type="submit"> Submit </button>
                    </center>
                </form>
            </div>
            <div class="box-2"> 
                <h2> For details contact</h2>
                <p> <span><b>Address</b> </span> :Challa bazaar,pathuru,vinjamuru,nellore d.t,AP</p>
                <p> <span><b>Email</b></span> :challamaheswar62@gmail.com</p>
                <p> <span><b>Phone</b> </span> :8247863304</p>
            </div>
        </div>
    </div>
```

Out put :
![Training HP-ot 1](https://github.com/user-attachments/assets/9465574d-1a31-4840-ad38-8db0f7e5534f)
![TR product -1](https://github.com/user-attachments/assets/aca7c3ad-4f31-4d30-a97b-6a9148dd2c11)
![TR product-2](https://github.com/user-attachments/assets/22a94d6f-7339-49d6-be5a-07c6cd3f7fcf)
![TR contact-3](https://github.com/user-attachments/assets/421d4c08-f54d-45fd-940d-afff946deecb)

Result :Design a Website like the one given below using CSS was successfully executed.



