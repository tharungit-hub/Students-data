# Students-data

## AIM
develop a responsive website to display students data

# ALGORITHM
### STEP 1
create a simple html page using heading tag
### STEP 2
Add a table tags to display students data
### STEP 3
To make responsive use media attribute in css
### STEP 4
Execute the program

# CODE
~~~
<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<style>
* {
  box-sizing: border-box;
  color: black;
}


table, th, td {
  border:1px solid black;
}

.menu {
  float: left;
  width: 20%;
  text-align: center;
}

.menu a {
  background-color: #e5e5e5;
  padding: 8px;
  margin-top: 7px;
  display: block;
  width: 100%;
  color: black;
}

.main {
  float: left;
  width: 60%;
  padding: 0 20px;
}

.right {
  background-color: #e5e5e5;
  float: left;
  width: 20%;
  padding: 15px;
  margin-top: 7px;
  text-align: center;
}

@media only screen and (max-width: 620px) {
  /* For mobile phones: */
  .menu, .main, .right {
    width: 100%;
  }
}
</style>
</head>
<body style="font-family:Verdana;color:#aaaaaa;">

<div style="background-color:#e5e5e5;padding:15px;text-align:center;">
  <h1>VIT Institute and technology</h1>
</div>

<div style="overflow:auto">
  <div class="menu">
    <a href="#">Home</a>
    <a href="#">Contact Us</a>
    <a href="#">Acadamecis</a>
    <a href="#">Admissions</a>
  </div>

  <div class="main">
    <h2>Student Data</h2>
    <table style="width:100%">
      <tr>
        <th>NAME</th>
        <th>ID.NO</th>
        <th>DEPT</th>
      </tr>
      <tr>
        <td>A</td>
        <td>01</td>
        <td>CSE</td>
      </tr>
      <tr>
        <td>B</td>
        <td>02</td>
        <td>ECE</td>
      </tr>
      <tr>
        <td>C</td>
        <td>03</td>
        <td>AI&DS</td>
      </tr>
      <tr>
        <td>D</td>
        <td>04</td>
        <td>MEC</td>
      </tr>
      <tr>
        <td>E</td>
        <td>05</td>
        <td>CSE</td>
      </tr>
      <tr>
    </table>
  </div>

  <div class="right">
    <h2>About</h2>
    <p>VIT was established with the aim of providing quality higher education on par with international standards. It persistently seeks and adopts innovative methods to improve the quality of higher education on a consistent basis</p>
  </div>
</div>

<div style="background-color:#e5e5e5;text-align:center;padding:10px;margin-top:7px;">Thanks for visiting</div>

</body>
</html>
~~~
# OUPUT
![SEC](t1.png)
![SEC](t2.png)
![SEC](t3.png)

# RESULT
responsive website to display students data was successfully executed.