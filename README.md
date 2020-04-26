<html>
    <head>
        <title>Nuevo Index Mario</title>
        <meta charset="utf-8">
        <meta name="viewport" content="width=device-width, initial-scale=1" />
        
        <style>
            

            :root{
                
                font-family: Arial, Helvetica, sans-serif;

                --color_oscuro:rgba(0, 0, 0, 0.555);
                --color_oscuro_transparente:rgba(199, 57, 235, 0.514);
                --naranja:rgb(233, 103, 17);
                font-size: 1vw;
            }
            strong{background-color::rgba(0, 0, 0, 0.555) ; }
            
            *{  padding:0px;
                margin:0px;
            }
            a{
                text-decoration: none;
            }

            ol, ul {
		        list-style: none;
	        }
            
             
            .centrado_bloque{
               margin-left: auto;
               margin-right: auto; 
            }
            
            header{
                position:fixed;
                top:0px;
                left:0px;
                background-color: var(--color_oscuro);
                min-height: 3.5rem;
                width: 100%;
                z-index: 2000;
            }

                        
                        header div{
                            position: fixed;
                            top: 0.25rem;
                            left:2rem; 
                            color:var(--rojo);
                            font-size: 1.5rem;
                                                       
                        }
                        header nav{
                            position:fixed;
                            top:1rem;
                            right:5rem; 
                            font-size: 1.25rem;
                            font-weight: bold;
                            
                            
                        }
                             
                        header nav ul{
                            text-align: right;
                        }                  
                        header nav ul > li{
                            display: inline-block;
                            vertical-align: top;
                            text-align: left;
                            min-width: 10rem;

                        }

                        header nav ul li > ul{
                            display: none;
                        }

                        header nav ul li:hover ul{
                            display: block;
                            text-align: center;
                        }
                        header nav ul li:hover li{
                            display:block;
                            background-color: var(--color_oscuro);
                        }
                        
                       
                        .submenu:hover ul {
                            display: block;                 
                        }

                        .submenu:hover ul > li{
                            display: block;
                            background-color: var(--color_oscuro);
                        }
                        
                        nav a{
                            color: var(--blanco);
                        }
                        nav a:hover{
                            background-color: var(--blanco);
                            color:var(--color_oscuro);
                        }

            .hero{
                background-image: url(fiesta.jpg);
                background-color: #cccccc;
                height: 800px;
                background-position: center;
                background-repeat: no-repeat;
                background-size: cover;
                position: center;
            }
            .hero div{
                position:relative;
                top:20rem;
                right:50rem;
                background-color: var(--color_oscuro_transparente);
                color:var(--blanco);
                font-size: 1.25rem;
                max-width: 30%;
                padding:3em;
            }
            .hero:hover div{
                left:0;
            }
            .hero div>p{
                padding-top: 3em;
                columns:2;
            }
            
            main{
                position: absolute;
                top: 50rem;
                left:10%;
                min-width: 80%;
                max-width: 80%;
                z-index: 2000;
            }

            main article{
                min-height: 300px;
                min-width:50%;
                background-color: var(--color_oscuro_transparente);
                padding-top: 10px;
                padding-bottom: 10px;
             }

            main article section{
                min-height: 100px;
                margin: 10px;
                /*border-style: solid;*/
                font-size: 1.5rem;
            }
            
            #actividades li{
                display: inline-block;
                background-color: var(--blanco);
                color:var(--color_oscuro);
                margin:2em;

            }
            #actividades li:hover{
                background-color: var(--color_oscuroo);
                color:var(--blanco);
                margin:2em;

            }

            #contenedor-fijo-izquierda{color: cornsilk; font-family: Cambria, Cochin, Georgia, Times, 'Times New Roman', serif;}
            
            
            

        </style>
    </head>
    <body>
       
        
        <header>
            <div class="contendor-fijo-izquierda">
                <h1>TIC2 en cuarentena</h1>
            </div>
            
            <nav class="contendor-fijo-derecha">
                <ul>
                     <li class="submenu"><a href="">Mis trabajos TIc</a>
                        <ul>
                            <li><a href="#ejercicios-1">Ejercicios de introducción a HTML</a></li>
                            <li><a href="#ejercicios-2">Ejercicios de introducción a CSS</a></li>
                            <li><a href="#ejercicios-3">Ejercicios de más etiquetas de CSS</a></li>
                            <li><a href="#ejercicios-4">Ejercicios de la Web Semántica</a></li>
                        </ul>
                    </li>
                    <li><a href="index.html">Mi último index</a></li>
                    <li><a href="#sobre_mi">Sobre mi</a></li>
                </ul>
            </nav>
        </header>  
        
    
           
            <div class="hero">
                <div>
                    <h2>Mi nuevo index Mario de la Mora</h2>
                    <p>Con este nuevo index lo que pretendo es demostrar que he mejorado mi anterior index a una versión que tiene una estética más profesional.</p>
                </div>
                
            </div>
        

        
               
        <main>

            
            <article id="actividades">
                <section id="ejercicios-1">
                    <h2>Ejercicios de introducción a HTML</h2> 
                    <ul>
                     <li><a href="html-ejerc1-intro.html">Ejercicio 1</a></li>
                      <li><a href="html-ejerc2-poema.html">Ejercicio 2</a></li> 
                      <li><a href="html-ejerc3-enfasis.html">Ejercicio 3</a></li> 
                      <li><a href="html-ejerc4-listas.html">Ejercicio 4</a></li> 
                      <li><a href="html-ejerc5-utf-8.html">Ejercicio 5</a></li>
                      <li><a href="html-ejerc6-img.html">Ejercicio 6</a></li>
                      <li><a href="html-ejerc7-viaje.html">Ejercicio 7</a></li>

                    </ul>
                     
                   </section>
                <section id="ejercicios-2">
                    <h2>Ejercicios de introducción a CSS</h2> 
                    <ul>
                        <li><a href="html-ejerc8-color.html">Ejercicio 8</a></li>
                        <li><a href="html-ejerc9-criatura.html">Ejercicio 9</a></li>
                        <li><a href="html-ejerc10-criatura2.html">Ejercicio 10</a></li>
                        <li><a href="html-ejerc11-formato.html">Ejercicio 11</a></li>
                        <li><a href="html-ejerc12-olafs.html">Ejercicio 12</a></li>
                        <li><a href="html-ejerc13-clases.html">Ejercicio 13</a></li>
                        <li><a href="html-ejerc14-desafío-clases.html">Ejercicio 14</a></li>
                        <li><a href="html-ejerc15-selectores.html">Ejercicio 15</a></li>
                        <li><a href="html-ejerc16.html">Ejercicio 16</a></li>

                    </ul>              
                </section>
                <section id="ejercicios-3">
                    <h2>Ejercicios de más etiquetas de CSS</h2> 
                    <ul>
                        <li><a href="html-ejerc18-vinculos.html">Ejercicio 18</a></li> 
                        <li><a href="html-ejerc19-vinculos_internos.html">Ejercicio 19</a></li>
                        <li><a href="html-ejerc20-tabla.html">Ejercicio 20</a></li>
                         <li><a href="html-ejerc21-proyecto_recetas">Ejercicio 21</a> <br></li>

                    </ul>               
                </section>
                <section id="ejercicios-4"> 
                    <h2>Ejercicios de la Web Semántica</h2> 
                    <ul>
                        <li><a href="html-ejerc23-videos">Ejercicio 23</a></li>
                        
                    </ul>             
                 </section>
               
            </article> 
            <article>
                <section>







                </section>
            </article>
            
            <article id="sobre_mi">
                <section> 
                    <h2>Infotmación sobre el autor</h2>

                    <p>Me llamo Mario de la Mora Martínez , voy al IES Doctor Flemin a 2º de bachillerato tecnológico y me gusta hacer deporte y salir de fiesta.
                     Recientemente he cumplido los 18 años y no lo he podido celebrar en condiciones debido a las consecuencias del coronavirus.
                     Mi anterior instituto era las Dominicas y en el futuro me gustaría estudiar algo cercano a la informática.


                    </p>



                </section>

            </article>
        


        </main>
    
        
     <footer>
          
     </footer>

    </body>
</html>
