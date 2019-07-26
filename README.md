# project

<html>
<head>

<title>Ride Share</title>

<style>



body {
  display: flex;
  justify-content: center;
}

.vldform {
    box-sizing: border-box;
    width: 375px;input[type=text], input[type=password] {
  width: 100%;
  padding: 15px;
  margin: 5px 0 22px 0;
  display: inline-block;
  border: none;
  background: #f1f1f1;
}

input[type=text]:focus, input[type=password]:focus {
  background-color: #ddd;
  outline: none;
}
hr {
  border: 1px solid #f1f1f1;
  margin-bottom: 25px;
}

/* Set a style for all buttons */
button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
  opacity: 0.9;
}

button:hover {
  opacity:1;
}

/* Extra styles for the cancel button */
.cancelbtn {
  padding: 14px 20px;
  background-color: #f44336;
}

/* Float cancel and signup buttons and add an equal width */
.cancelbtn, .signupbtn {
  float: left;
  width: 50%;
}

/* Add padding to container elements */
.container {
  padding: 16px;
}

/* Clear floats */
.clearfix::after {
  content: "";
  clear: both;
  display: table;
}

/* Change styles for cancel button and signup button on extra small screens */
@media screen and (max-width: 300px) {
  .cancelbtn, .signupbtn {
    width: 100%;
  }
}
    display: flex;
    flex-direction: column;
    padding: 35px 55px;
    font-family: "Nunito Sans";
    animation: a .5s;
    animation-fill-mode: forwards;
    border: #d4d4d4 1px solid;
    border-radius: 10px;
    box-shadow: 0 2px 6px 0 hsla(0, 0%, 0%, 0.2);
}

.vldform a {
    text-decoration: none;
}

.vldform h1 {
    font-size: 40px;
    color: skyblue;
    margin: 0px 0px 26px 0px;
}

.vldform__textbox {
    border: 0;
    outline: 0;
    border-bottom: 2px skyblue solid;
    font-size: 18px;
    margin-top: 36px;
    padding-bottom: 9px;
    font-family: "Nunito Sans";
}

.vldform__textbox[type="password"]::after {
    content: " ";
    display: block;
    width: 10px;
    height: 10px;
    background-color: skyblue;
    
}

.vldform__recoverypassword{
    align-self: flex-end;
    margin: 10px 0px;
    font-size: 16px;
    color: skyblue;
}

.vldform__button {
    margin-top: 42px;
    height: 50px;
    border: 0;
    color: black;
    border-radius: 10px;
    font-size: 22px;
    font-weight: 600;
    font-family: "Nunito Sans";
    cursor: pointer;
}

.vldform__signup {
    align-self: center;
    margin-top: 50px;
    margin-bottom: 0px;
}

.vldform__signup a {
    color: skyblue;
    font-weight: 600;
    margin-left: 4px;
}

.vldreg {
    display: none;
}

.vldrecpass {
    display: none;
}

</style>

</head>
</html>
