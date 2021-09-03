<html> 

   <head> 

      <script> 

         function dis(val) 

         { 

             document.getElementById("result").value+=val 

         }
         
         function solve() 

         { 

             let x = document.getElementById("result").value 

             let y = eval(x) 

             document.getElementById("result").value = y 

         }
         
         function clr() 

         { 

             document.getElementById("result").value = "" 

         } 

      </script> 

      <style> 

         .title{ 

         margin-bottom: 10px; 

         text-align:center; 
          display: inline-block; 
         width: 210px; 
         heigth:400px;
         background-color:lite yellow;
         color:red; 

         border: solid black 2px; 

         } 

  

         input[type="button"] 

         { 
            text-align:center;
         background-color:blue	; 

         color: black;
         display: inline-block;
         border: solid black 2px;
         width:450%;
         height:230%;

         } 

  

         input[type="text"] 

         { 
          text-align:center;
         background-color:white;
         display: inline-block;  

         border: solid black 2px; 

         width:100%;
         height:300%;
         
         } 
         body
         {
          text-align:center;
          background-color: pink;
          width: 300px; 
          heigth:400px;
          }
          table
          {
        text-align:center;
          margin: auto;
          background-color: #9dd2ea;
          width: 300px;
          height: 325px;
          text-align: center;
          border-radius: 4px;
          }
          td
          {
          text-align:center;
            height:10%;
            width:15%;
            padding:10%;
          
          
          }
          tr
          {
          text-align:center;
           padding:100%;
           height:100%;
           width:150%;
          }

      </style> 

   </head> 

   <body> 

      <div class = title >Shantanu's Calculator😁😎</div> 

      <table border="1"> 

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
            
            <td><input type="button" value="*" onclick="dis('*')"/> </td> 

            <td><input type="button" value="=" onclick="solve()"/> </td> 

         </tr> 

      </table> 

   </body> 
   <div class = title > ❤️😍This is for you😍❤️   </div> 

</html>
