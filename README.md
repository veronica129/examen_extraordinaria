<!doctype html>
<html lang="en">


<head>
   

	<meta charset="UTF-8">
    
	<title>YOUR LOGO</title>
    <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700,900&display=swap" rel="stylesheet">
     <style type="text/css">
         
        
        *{
            padding: 0;
            margin: 0;
           
        }
                 body{
             font-family: 'Roboto', sans-serif;
            background:url(background.png)no-repeat center center fixed;
            background-size:100% 100%;
            
        }
         
        .boton_learn_more{
    text-decoration: none;
    padding: 3px;
    padding-left: 10px;
    padding-right: 10px;
    font-family: helvetica;
    font-weight: 300;
    font-size: 25px;
    font-style: italic;
    color: #006505;
    background-color: #82b085;
    border-radius: 15px;
    border: 3px double #006505;
  }
  .boton_1:hover{
    opacity: 0.6;
    text-decoration: none;
  }
     
     
        a{
            text-decoration: none;
        }

        /*NAV*/
        
        nav{
            width: 50%;
            padding: 50px 50px;
            white-space:nowrap;
            display: inline;
        }
        
        nav h1{
            color: black;
            font-size: 15pt;
            margin:160px -100px 0 140px;

        }
    
         main h2{
             font-size: 24pt;
            font-weight: 700;
         }
         main h3{
             font-weight: lighter;
             font-size:28pt;
         }
         main p_1{
             font-weight: bold;
         }
      
    
      .menu_inicio a{
          
           font-size: 10pt;

            color: black;
            margin:150px -450px 0 530px;
          
          /*añadimos las caracteristicas del cirulo que tenemos al lado del titulo*/
          
        }
         .circulo {
        position: absolute;
             top: 165px;
             left: 120px;
     width: 15px;
     height: 15px;
     border-radius: 50%;
     border-radius: 50%;
     border-radius: 50%;
     background: #000000;
}
         
         /* añadimos como debe ser el boton del learn more para tenerlo como queremos, los padding son los margenes y position donde queremos ponerlo*/
        .boton {
            position: absolute;
            right: 960px;
            top:620px;
text-decoration:none;
font-weight:bold;
font-size: 20px;
color:#333333;
padding-top:10px;
padding-bottom:10px;
padding-left:20px;
padding-right:20px;
background-color:#ce663d;
border-width: 3px;
border-radius:35px;
         }
        
            nav a{
        
             float:left;
             font-size: 1em;
             font-weight: 900;
          }
        
         p_boton{
              color: white;

         }
    
      
        
       
        
       
    
        
        
   /* Aqui ponemo el main que tendremos la parte blanca que queremos poner por encima del background del propio navegador*/    
     
 main{
            background-color:#FFFFFF;
     padding-top: 200px;
     padding-bottom: 180px;
     border-radius: 20px;
         
     margin-left: 100px;
     margin-right: 100px;
     margin-top: 100px;
     

     
            
        }
         .foto_escritorio{
             
             margin-right: 80px;
             position: relative;
             top: -250px;
          }        
         .container{
             
            margin-left: 40px;

        
        
    </style>
    
</head>
<body>
    
     <nav>
         <!-- aqui incluimos la class circulo para poder hacer la llamada en el body, ya que lo queremos tener al lado del titulo h1-->
         <div class="circulo ">
        </div>
         
         <div_1 class="navigation"> 
               
               
                 <a href="#" >
                  

                <h1>YOUR LOGO</h1>
                
                </a>
                
        </div_1>
        <div class="menu_inicio" >

                       
                <a href="#">HOME</a>
                <a href="#">OUR TEAM</a>
                <a href="#">SERVICES</a>
                <a href="#">CONTACT</a>
        

                 </div>
    

                 
    </nav>


    <main>
       
        <!-- aqui incluiremos todo el texto que queremos introduccir en la pagina, ademas de diferenciar cada p por si queremos cambiar una parte del texto en concreto, de ahi que tengamos p_1, h2, h3, etc-->
         <div class="container">
             

            <h2>APPOINTMENT</h2>
        <h3>BOOKING</h3>
             <br>
             <br>
             <br>
        <p_1>Lorem ipsum dolor</p_1>
             <br>
             <br>
        <p> Sit amet, consectetuer adipiscing elit, sed diam nonummy<br>nibh euismod tincidunt ut laoreet dolore magna aliquam <br> erat volutpat. Ut wisi enum ad minim veniam, quis nostrud<br> exerci tation ullamcorper suscipit lobortis nisl utv.v</p>

             <div class="foto_escritorio">
                  <img src="chico_escritorio.png"align="right" >

             </div>
  
                      </div>

    </main>
    <!-- creamos un footer para poder meter le boton ya que lo tenemos que tener debajo de todo y no puede ir en el main-->
    <!-- Metemos el p_boton porque tenemos que poder editar el texto de algun modo entonces hacemos eso para tener la referencia-->
    <footer>
                
        <div class= "boton">
             <a href="#" ><p_boton>LEARN MORE ></p_boton> </a>
       
            
        </div>
    </footer>
</body>
   
    </html>
