# practice
my practice repo in github
charx sa ni
kapoy
<!Doctype html>
<head>
<style>
input[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

input[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}

input[type=submit]:hover {
  background-color: #45a049;
}

div {
  border-radius: 5px;
  background-color: #f2f2f2;
  padding: 20px;
}
button[type=submit]:hover {
  background-color: green;
}
button[type=text], select {
  width: 100%;
  padding: 12px 20px;
  margin: 8px 0;
  display: inline-block;
  border: 1px solid #ccc;
  border-radius: 4px;
  box-sizing: border-box;
}

button[type=submit] {
  width: 100%;
  background-color: #4CAF50;
  color: white;
  padding: 14px 20px;
  margin: 8px 0;
  border: none;
  border-radius: 4px;
  cursor: pointer;
}
h1{
    text-align: center;
}

</style>
</head>
<form method="post">        
<h1>Enter a name:</h1> <input type="text" name="String"/><br>  
<button type="submit" colo>Check</button>  
</form>

<?php

    if($_POST)  
    {  
        //get the value from form  
        $String = $_POST["String"];  
        //reversing the string  
        $reverse = strrev($String);  
          
        //checking if the string and reverse is equal  
        if($String == $reverse){  
            echo "The name $String is Palindrome";     
        }else{  
            echo "The name $String is not a Palindrome";   
        }  
}     
      ?>  
    </html>
