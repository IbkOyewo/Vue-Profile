<template>
  <form action="">
  <h1>Contact Us!</h1>
<p>Say Hello! Or whatever you want!</p>
  <input name="name" type="text"
placeholder="Name"/>
  
  <input name="email" type="email"
placeholder="Email"/>
  
  <textarea name="text" placeholder="Message"></textarea>
  
  <div> <lable><input type="checkbox"/>Yes, I'm Human!</lable></div>
 
   <input type="submit"/>
</form>
</template>

<script>
export default {
name: "Form"
}
</script>

<style>
form {
  width: 30%;
  height: 100%;
  background: #f1f1f1;
  margin: 5% 33%;
  padding: 2%;
 
  border-radius: 2px;
  box-shadow: 1px 1px 3px rgba(0,0,0,0.2);
  display: block;
  margin-top: 2em;
}



h1 {
  text-align: center;
  margin-top: 5px;
}

p {
  text-align: center;
  margin-bottom: 1em;
}

#logo {
  font-size: 50px;
  text-align: center;
  color: #4889f0;
}

form input, textarea {
   border-radius: 2px;
  width: 90%;
display: block;
  font-size: 16px;
  font-weight: 300;
  margin-left: 5%;
  margin-right: 5%;
  margin-top: 10px;
  border: 1px solid #eceff1;
  padding: 15px;
  z-index: 1;
position: relative;
box-sizing: border-box;
background: #fff;
border: 1px solid #d9d9d9;
border-top: 1px solid #c0c0c0;
}

[type="submit"] {
  border: 1px solid #2f5bb7;
color: #fff;
 padding: 10px;
text-shadow: 0 1px rgba(0,0,0,0.3);
background-color: #357ae8;
  margin-top: 12px;
  font-weight: 500;
}

[type="submit"]:hover {
border-color: #c6c6c6;
color: #fff;
cursor: pointer;
background-color: #4c8ffc;
-moz-box-shadow: 0 1px 1px rgba(0,0,0,0.1);
-webkit-box-shadow: 0 1px 1px rgba(0,0,0,0.1);
box-shadow: 0 1px 1px rgba(0,0,0,0.1);
  }
</style>