# FP-Website
<!DOCTYPE html>
<html>
    <head>
        <style>
            body{
                background-color: lightgoldenrodyellow;
            }
            h1{
                background-color: lightslategray;
            }
            h2{
                background-color: lightslategray;
            }
        </style>
    </head>
 
  <body>
  <h1>The Final Project</h1>
  <h2>Introduction</h2>
    <p>This is created for my Final project for the class of INFOTC 1000 <p/>
    <h1>Introducing Myself</h1>
    <p>Hi! My name is Claudia Fuentes but my full name goes like this: Claudia Y. S. Fuentes. </p>
    <h3><b>A little bit about me.</b></h3>
    <p><b>Personal Life</b></p>
    <p>I live with my mom and dad and my little sister. I also have an older sister who is married and with a child. My family is actually really big if you count all of the relatives from the other states like:</p>
  <ul>
      <li>Texas</li>
      <li>Tennesssee</li>
      <li>Virginia</li>
      <li>Maryland</li>
  </ul>
  <p>Theres also a possibility that there are some <i>Unknown Relatives</i>as well because I only know some relatives from Texas and from Tennessee.</p>
  <h2><b>Pets</b></h2>
  <p>For pets I have in total 6 dogs and 1 guinea pig. </p>
  <p>There are 3 female dogs and 3 male dogs and the guinea pig is a female as well. </p>
  <p>Their names are:</p>
  <ul>
      <li><a href=https://s3.amazonaws.com/cdn-origin-etr.akc.org/wp-content/uploads/2017/11/16105011/English-Cocker-Spaniel-Slide03.jpg>Fee Fee</a></li>
      <li><a href=https://imagesvc.meredithcorp.io/v3/mm/image?url=https%3A%2F%2Fstatic.onecms.io%2Fwp-content%2Fuploads%2Fsites%2F47%2F2021%2F03%2F09%2Fchihuahua-laying-down-wooden-floor-1675701502-2000.jpg>Justin</a></li>
      <li>Luna</li>
      <li>Jesse <i>Male</i></li>
      <li>Blu</li>
      <li>Mar</li>
      <li>LeLe <i>Guinea Pig</i></li>
      <img src="https://petsvills.com/wp-content/uploads/2020/08/male-black-guinea-pig-names-a.webp" width="500" height="300"/>
      </ul>
<h1><b>Education</b></h1>
      <p>Currently I am a freshman in the <i><a href=https://missouri.edu> University of Missouri-Columbia</i> </a>and I am pursing a <b>Bachelors Degree</b>
    in IT with the pathway of Engineering</p>

<h1><b>Code Projects</b></h1>

    <p>  from math import pi</p>
      <p>import math</p>
      <p>#Surface area is2(pi)rh + 2(pi)r^2</p>
     
     <p>def get_radius():</p>
         <p>while True:</p>
             <p>try:</p>
                 <p>radius = float(input("Enter the Radius "))</p>
                 <p> (radius < 0):</p>
                    <p>print("No Negative numbers")</p>
                    <p>continue</p>
             <p>except ValueError:</p>
                     <p>print("Only Numerical Values are allowed.")</p>
             <p>else:</p>
                <p>break</p>
         <p>return radius</p>
     <p>def get_height():</p>
         <p>while True:</p>
             <p>try:</p>
                <p>height = float(input("Enter the Height "))</p>
                 <p>if (height < 0):</p>
                    <p>print("No Negative Numbers")</p>
                     <p>continue</p>
             <p>except ValueError:</p>
                     <p>print("Only Numerical Values are allowed.")</p>
             <p>else:</p>
                 <p>break</p>
         <p>return height</p>
     <p>def get_pint():</p>
         <p>while True:</p>
             <p>try:</p>
                 <p>pint = float(input("What is the cost of Pints? "))</p>
                 <p>if(pint < 0):</p>
                     <p>print("No Negative Numbers")</p>
                     <p>continue</p>
             <p>except ValueError:</p>
                 <p>print("Only Numerical Values are allowed.")</p>
             <p>else:</p>
                 <p>break</p>
         <p>return pint</p>
     <p>def calculate_cylinder_sa(radius, height):</p>
         <p>sa = 2 * pi * radius * height + 2 * pi * radius ** 2</p>
         <p>return sa</p>
     <p> pint_total(sa):</p>
         <p>p = math.ceil(sa / 50)</p>
         <p>return sa</p>
     <p>def pint_report(p):</p>
         <p>print("Total Pints is ",math.ceil(p))</p>
     <p>def pint_cost(pint,p):</p>
         <p>cost = p * pint</p>
         <p>print("The Cost will be $",format(cost,",.2f" ))</p>
     <p>def generate_report(radius, height, sa):</p>
        <p>print("A Cylinder with a radius of ",radius, "and height of ",height,"has a surface area of ",sa)</p>
     <p>def main():</p>
        <p>print("Welcome to the Cylinder Coatings Estimator.")</p>
         <p>print(" ")</p>
    <p>do_calculation = True</p>
        <p>while (do_calculation):</p>
            <p>radius = get_radius()</p>
            <p>height = get_height()</p>
             <p>pint = get_pint()</p>
             <p>sa = calculate_cylinder_sa(radius, height)</p>
             <p>generate_report(radius, height, sa)</p>
             <p>p = pint_total(sa)</p>
             <p>pint_report(p)</p>
             <p>p= pint_cost(pint,p)</p>
             <p>another_calculation = input("Do you want to continue? (Y/N): "
                                         )</p>
             <p>if (another_calculation != "Y"):</p>
                <p> do_calculation = False</p>
                 <p>break</p>
     <p>main()</p>

</body>
 
 </html>
