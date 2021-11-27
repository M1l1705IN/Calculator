<!DOCTYPE html>
<html> 
   <head> 
<meta name="viewport" content=" width=devices-width, initial-scale=1"/>
      <script> 

         //function that display value 

         function dis(val) 

         { 

             document.getElementById("result").value+=val 

         } 

           

         //function that evaluates the digit and return result 

         function solve() 

         { 

             let x = document.getElementById("result").value 

             let y = eval(x) 

             document.getElementById("result").value = y 

         } 

           

         //function that clear the display 

         function clr() 

         { 

             document.getElementById("result").value = "" 

         } 

      </script> 

      

      <style> 

         .title{ 

         margin-bottom: 10px; 

         text-align:center; 

         width: 500px; 

         color:teal; 

         border: 5px solid            green; 
             border-radius:40px;
padding:25px;
margin-left:70px;
font-size:30px;


         } 

  

         input[type="button"] 

         { 

         background-color:lightgrey; 
         color: red; 

         border: solid dodgerblue  2px; 

         width:100% 
border-radius: 40px;
padding:60px;
font-size:25px;
            

         } 

  

         input[type="text"] 

         { 

         background-color:white; 

         border: solid olive 2px; 

         width:100% 
         height:50px;
         color: dodgerblue;
      font-weight:bold;
      padding:30px;
       border-radius:20px;
margin-left:10px;
border:2px solid orange;
  font-size:30px;
         } 
div 
    {

height:700px;
width:100%;
background: black;
border-radius:40x;
item-align:center;
padding-bottom:30px;
padding:70px;
padding-left:70px;
}
table
     {

padding:15px;
border-radius:40px;
border:2px solid fuchsia;
font-size:70px;
}


      </style> 

   </head> 

   

   <body>

      <p class = title >Project WRLD Calculator</p> 
</center>
      <table border="5"> 

         <tr> 

            <td colspan="3"><input type="text" id="result"/></td> 

            

            <td><input type="button" value="c" onclick="clr()"/> </td> 

         </tr> 

         <tr> 

           
            <td><input type="button" value="1" onclick="dis('1')"/> </td> 

            <td><input type="button" value="2" onclick="dis('2')"/> </td> 

            <td><input type="button" value="3" onclick="dis('3')"/> </td> 

            <td><input type="button" value="/" onclick="dis('/')"/> </td> 

         </tr> 

         <tr> 

            <td><input type="button" value="4" onclick="dis('4')"/> </td> 

            <td><input type="button" value="5" onclick="dis('5')"/> </td> 

            <td><input type="button" value="6" onclick="dis('6')"/> </td> 

            <td><input type="button" value="-" onclick="dis('-')"/> </td> 

         </tr> 

         <tr> 

            <td><input type="button" value="7" onclick="dis('7')"/> </td> 

            <td><input type="button" value="8" onclick="dis('8')"/> </td> 

            <td><input type="button" value="9" onclick="dis('9')"/> </td> 

            <td><input type="button" value="+" onclick="dis('+')"/> </td> 

         </tr> 

         <tr> 

            <td><input type="button" value="." onclick="dis('.')"/> </td> 

            <td><input type="button" value="0" onclick="dis('0')"/> </td> 

           
            <td><input type="button" value="=" onclick="solve()"/> </td> 

            <td><input type="button" value="*" onclick="dis('*')"/> </td> 

         </tr> 

      </table> 
</center>

   </body> 

</
