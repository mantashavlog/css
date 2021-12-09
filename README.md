# css
<html>
<head>
<title>html paragraph and style</title>
</head>
<body>
<p style="font-size:25px;font-family:georgia;background-color:lightseagreen;color:white;"><i>A <b>web page </b> (or webpage) is a<u> hypertext document</u> provided by a website and displayed to a user in a web browser. 
A website typically consists of many web pages linked together in a coherent fashion.
 The name<b> "web page" </b> is a metaphor of paper pages bound together into a book.</i>
</p>
<p style="background-color:skyblue;color:white;">The core element of a web page is one or more text files written in the <b><u>Hypertext Markup Language (HTML)</b></u>. Many web pages also make use of JavaScript code for dynamic behavior and Cascading Style Sheets (CSS) code for presentation semantics.[2] WebAssembly executables can also be used for portions of page behavior.
Images, videos, and other multimedia files are often embedded in web pages.
Each web page is identified by a distinct <b>Uniform Resource Locator <u>(URL)</b></u>. When the user inputs a <b>URL </b>into their browser, that page's elements are downloaded from web servers.
 The browser then transforms all of the elements into an interactive visual representation on the user's device.
If the user clicks or taps a link to another page, the browser repeats this process to display the new page, which could be part of the current website or a different one.<br />
</p>
</body>
</html>

<html>
<head>
<link rel="stylesheet" type="text/css" href="style.css">
</head>
<title>how to link a html file to css file</title>
<body>
<h2>cascading style </h2>
</body>
</html>

<html>
<head>
<form>
<body>
<font color="grey">
<label>name</label>
<input type ="textbox" name="fname" required></input><br>
<label>age</label>
<input type ="textbox" name="fname" required></input><br>
<label>address</label>
<input type ="textbox" name="fname" required></input><br>
<label>favorite subject</label>
<input type ="textbox" name="fname" required></input><br>
<label>favorite movie</label>
<input type ="textbox" name="fname" required></input><br>
<label>favorite singer</label>
<input type ="textbox" name="fname" required></input><br>
<label>password</label>
<input type ="password" name="pswd>required></input><br>
<label>submit</label>
<input type ="submit" name="submit"value="submit"></input><br>
</form>
</head>
</body>
</html>

<html>
<head>
<body>
<select>
<font color="brown">
<input type="checkbox" name="chk"><br>
<label>select city</label>
<select name="city"><br>
<option name ="lucknow">lucknow</option><br>
<option name ="delhi">delhi</option><br><br>
<label>submit</label>
<input type ="submit" name="submit"value="submit"></input><br>
</select>
</head>
</body>
</html>

<html>
<head>
<script type ="text/javascript">
function validate(){
var name=document.form.["myform"].["name"].value;
alert(name);
if(name="");
  alert("please enter the name");
   return false;
}
var email=document.form.["myform"].["email"].value;
alert(email);
if(email="");
  alert("please enter the email");
   return false;
}else{
 var re = /\S+@\S+/;
 var x=re.test(email);
 if(){
}else{
alert("email id not in correct format");
return false;
}
}
var mobile=document.form.["myform"].["mobile"].value;
alert(mobile);
if(mobile="");
  alert("please enter the mobile");
   return false;
}else{
   if(isNaN(mobile)){
   alert("mobile number not valid");
}
}
return false;
}
var address=document.form.["myform"].["address"].value;
alert(address);
if(address="");
  alert("please enter the address");
   return false;

}
}



</script>
</head>
<body>
<center>
<h1>validation form</h1>

<h3>sign up form</h3>

<form name="myform" action"form.html" onsubmit="return validate()" method="post">
name ; <input type="text" name="name"/><br>
email : <input type="text" name="email"/><br>
mobile : <input type="text" name="mobile"/><br>
address: <input type="text" name="address"/><br>
<input type="submit" value="submit">
</form>
<center>
</body>
</html>


<html>
<head>
<title>background color</title>
<script language=javascript>
var count=0;
function as()
{
setTimeout("fun1()",5000);
}
function fun1()
{
var a =new 
Array("red","darkblue","sky","yellow","blue","pink","green");
if(count<=6)
{
document.bgColor=a[count++];
setTimeout("fun1()",5000);
}
else
{
count=0;
as();
}
}
</script>
</head>
<body bgcolor=gray onload=as()>
</body>
</html>

