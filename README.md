<%@ Page Language="C#" Title="Login" AutoEventWireup="true" CodeBehind="WebForm1.aspx.cs" Inherits="Test.WebForm1" %>

<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
    font-family: Arial, Helvetica, sans-serif;  
}
form {
    border: 3px solid #f1f1f1;
}

select#soflow, select#soflow-color {
   -webkit-appearance: button;
   -webkit-border-radius: 2px;
   -webkit-box-shadow: 0px 1px 3px rgba(0, 0, 0, 0.1);
   -webkit-padding-start: 2px;
   -webkit-user-select: none;
   background-image: url(http://i62.tinypic.com/15xvbd5.png), -webkit-linear-gradient(#FAFAFA, #F4F4F4 40%, #E5E5E5);
   background-position: 97% center;
   background-repeat: no-repeat;
   border: 1px solid #AAA;
   color: #555;
   font-size: inherit;
   margin: 20px;
   overflow: hidden;
   padding: 5px 20px;
   text-overflow: ellipsis;
   white-space: nowrap;
   width: 570px;
   align-self:center;
}

input[type=text], input[type=password] {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  box-sizing: border-box;
}

button {
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  cursor: pointer;
  width: 100%;
}

button:hover {
  opacity: 0.8;
}

.cancelbtn {
  width: auto;
  padding: 10px 18px;
  background-color: #f44336;
}

.imgcontainer {
  text-align: center;
  margin: 24px 0 12px 0;
}

.textHeader {
    font-family:'Comic Sans MS';
    text-align:center;
}

.formDiv {
    padding-left:400px;
    padding-right:400px;
}

img.avatar {
  width: 40%;
  border-radius: 50%;
}


span.psw {
  float: right;
  padding-top: 16px;
}

</style>
</head>
<body>
    <div class="formDiv">
<div class="textHeader">
    <h1>Login</h1>
</div>


<form>
  <div class="imgcontainer">
    <img src="Images/loginImage.jpg" alt="Avatar" class="avatar">
  </div>

  <div class="container">
    <label for="uname"><b>Username</b></label>
      <br />
    <input type="text" placeholder="Enter Username" name="uname" required>

    <label for="psw"><b>Password</b></label>
      <br />
    <input type="password" placeholder="Enter Password" name="psw" required>
      <br />
    <label for="userType"><b>User Type</b></label>
      <br />
    <select id="soflow">
    <option selected="selected">Admin</option>
    <option>User</option>
    </select>
    <button type="submit">Login</button>
  </div>
</form>
</div>
</body>
</html>
