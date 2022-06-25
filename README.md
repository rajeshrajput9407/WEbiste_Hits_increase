# WEbiste_Hits_increase
WEbiste Hits increase

<!DOCTYPE html>
  
<html>
<head>
    <style>
        body{
            text-align:center;
        }
    </style>
</head>
  
<body>
  
    <h2 style="color:green">Website hits count</h2>
    <h4 style="color:purple" id="count"></h4>
  
     
  
    <script>
	 var WindowObj;
	  
   
   function sleep(ms) {
      return new Promise(resolve => setTimeout(resolve, ms));
   }
   
   async function Tutor() {
    
      for (let i = 1; i <100000 ; i++) { 
	 document.getElementById("count").innerHTML = i;
          openWin();	  
         await sleep(50);
         closeWin();
      }
   }

   
  function openWin() {
            WindowObj = window
                     .open("https://karanpackersandmovers.com/", "_blank", "width=200, height=200");
        }
  
  function closeWin() {
            WindowObj.close();
			WindowObj= null;
        }  
        
		 Tutor();
    </script>
  
</body>
  
</html>
