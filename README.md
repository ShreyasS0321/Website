<html>

    
    
    <head>
        
        <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">
<script src="https://code.jquery.com/jquery-3.4.1.slim.min.js" integrity="sha384-J6qa4849blE2+poT4WnyKhv5vZF5SrPo0iEjwBvKU7imGFAV0wwj1yYfoRSJoZ+n" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/popper.js@1.16.0/dist/umd/popper.min.js" integrity="sha384-Q6E9RHvbIyZFJoft+2mJbHaEWldlvI9IOYy5n3zV9zzTtmI3UksdQRVvoxMfooAo" crossorigin="anonymous"></script>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@4.4.1/dist/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
        
<!-- linking bootstrap -->
        

        <script>
            
              const d = new Date();
              let hour = d.getHours();
              t= hour-1;
            //get time in hours
            
            lst=[ "0-1 :  ", "1-2 :  ", "2-3 :  ", "3-4 :  ","4-5:  ","5-6:  ","6-7 :  ","7-8 :  ", "8-9 :  ", "9-10 :  ", "10-11 :  ", "11-12 :  ", "12-13 :  ", "13-14 :  ", "14-15 :  ", "15-16 :  ", "16-17 :  ", "17-18 :  ", "18-19 :  ", "19-20 :  ", "20-21 :  ", "21-22 :  ", "22-23 :  ", "23-24 :  "];
            
            // list containing the schedule
            
            background=0;
            
            // 0 is light theme, 1 is dark
            
            if (hour<6|| hour>18)
                {
                    background=1;
                }
            else
                {
                    background=0;
                }
                 
            
            
        </script>
        
        
        <style>
        
           
            #bd1
            
            {
                
                
                background-color: black;
                
            }
            
            
            #title
            {
                  margin-left: 150px;
        font-family: Arial, Helvetica, sans-serif ;
        font-weight: 700;
        font-size: 35px;
        color:white;
                  margin-top: 30px;
  margin-bottom: 100px;
  margin-right: 150px;
 
            }
            
            
        
        .lst{
          color:#2DD293; 
                       margin-top: 10px;
  
        
        font-size: 20px;
      font-family: BlinkMacSystemFont;
   
     
        }
            
            #list
            {
                
                padding: 50px;
                    width: 400px;
border-style: solid;
            border-color:#338099;
            }
        </style>
        
        
    </head>


    
    
    <body id="bd1">
        
        
         <div id="title">
    
    Daily Schedule 
    
    </div>    
        
 <div id="list">
     
<div class=lst id=l0 >   </div>    
<div id=l1 class=lst >   </div>
<div id=l2 class=lst>  </div>
<div id=l3 class=lst > </div>
<div id=l4 class=lst >  </div>
<div id=l5  class=lst>   </div>
<div id=l6 class=lst>  </div>
<div id=l7 class=lst >  </div>
<div id=l8  class=lst>  </div>
<div id=l9 class=lst >  </div>
<div id=l10 class=lst >  </div>
<div id=l11 class=lst >  </div>
<div id=l12  class=lst>  </div>
<div id=l13 class=lst >  </div>
<div id=l14 class=lst >  </div>
<div id=l15 class=lst>  </div>
<div id=l16 class=lst>   </div>
<div id=l17 class=lst>  </div>
<div id=l18 class=lst>  </div>
<div id=l19 class=lst>  </div>
  <div id=l20 class=lst>  </div>
  <div id=l21 class=lst>  </div>
  <div id=l22 class=lst>  </div>
   <div id=l23 class=lst>  </div>      
     
        </div>
    </body>

    <script>
        
        for (let i = t; i < 23; i++) {
 
            document.getElementById("l"+i).innerHTML=lst[i+1];
}
        
            
    </script>
</html>
