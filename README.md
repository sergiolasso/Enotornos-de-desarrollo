# Enotornos-de-desarrollo

1ºTrimestre Creacion de una pagina web

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>¡Independizate ya!</title>
    <link rel="stylesheet" href="estilos/normalize.css">
    <link rel="stylesheet" href="estilos/estilos.css">
</head>
<body>

    <section class = solo_fondo></section>
    
    <img class="manzana" src="/Imagenes/imagen_entrada.png" alt="Logotipo">

    <div class = link >
        <a href="principal_modo_oscuro.html">Modo oscuro</a>
        <a href="index.html">Inicio</a>
        <a href="como_independizarte.html">Como Independizarse</a>
        <a href="orden_limpieza.html">Orden y limpieza</a>
        <a href="economia.html">Economia</a>
        <a href="en_pareja.html">En pareja</a>
        <a href="consejos.html">Consejos</a>
        <a href="productos.html">Productos recomendados</a>
        <a href="cestaCompra.html">Cesta de la compra</a>
        <a href="burocracia.html">Burocracia</a>
        <a href="formulariio.html"> Nuestra newsletter</a>
    </div>   

    <hr>

    <main>

        <section>
            <article class = base>
                <h1>Independizate ya</h1>
                <p>En independizate ya, os vamos a ayudar con consejos y soluciones utiles para aquellas personas que esteis pensando en indendizaros o que ya hayas comenzado este arduo proceso que es vivir solo. La circusntancias por las que desees independizaros pueden ser varias, pero seguro que encuentras algo que te sea de utilidad en este sitio web. ¿Estas preparado? Pues empecemos.</p>
            </article>
        </section>
        
        <section>
            <article class = base>
                <h2>Antes de empezar</h2>

                <p>Independizarse es algo que debe de hacerse con cabeza. Puede que tengamos el respaldo de papa y mama o puede que en verdad lo estes haciendo para huir de casa de tus padres. En cualquier caso, seria recomendable que se haga con unas cuantas cosas puestas sobre seguro.</p>
            </article>
            <article class = base>
                <h2>Dinero</h2>

                <p>Aunque tengamos una pagina completa destinada a este apartado. Te adelantaremos un poco por aquí. Debes de tener al menos 6 meses de tu gasto habitual en efectivo. Este colchón sera suficiente si las cosas no salen como tenias pensado y darte tiempo a buscar otro plan.</p>
            </article>
            
            <article class = base>
                <h2>¿Donde esta tu limite?</h2>

                <p>Cuando salimos de casa, hay algunas cosas que siempre papa y mama nos han protegido e incluso que no hemos llegado a verlo, ya que son cosas que bien puede ser importante, pero a lo mejor solo se hacen en muy contadas ocasiones. Desde reuniones con los vecinos, problemas con seguros o soluciones con las becas. Para todo esto hay servicios que se pueden ser utiles. Puedes contratar a alguien para que te ayude con la limpieza del hogar, puedes contratar a un abogado para hacer la declaración de la renta ... Lo más importante es que vayas haciendo las cosas por ti mismo, que poco a poco te vayas acostumbrando y al fin y al cabo el dinero no es infinito y mucho menos cuando te acabas de mudar. </p>
            </article>
            <article class = base>
                <h2>¿Y como me mudo?</h2>

                <p>A excepción de que tengas que llevarte muebles o cosas así, tus cosas no deberian de ocupar más que unas pocas cajas. Si tus padres o algun amigo tiene coche, lo más comodo es hacerte un par de viajes y quitartelo del medio. Contratar un servicio de mudanzas, puede llegar a resultar caro, pero si no tienes ayuda, puede que sea tu mejor opción. No te recomiendo servicios como correo postal, ya que los paquetes pueden llegar a perderse y tarda demasiado, además que en algunos sitios, dependiendo de la distancia o cosas así, puede llegar a ser hasta más caro. Si la distancia es corta, como dentro de una ciudad, puedes hacerlo con cun carro de la compra, aunque en algunos aspectos, puede resultar incomodo y es posible que se rompan cosas por el camino.  </p>
            </article>    

        </section>
    
    </main>
    <footer>
    
        Contacto: sergio.lasso@cesjuanpablosegundo.es

        <br>

        Entornos de desarrollo. Todos los derechos reservados. 
        
    </footer>
</body>
</html> 


El CSS

h1{

    padding-left: 10px;
    border-radius: 30px;
    background-color: cornflowerblue;

}
h2{

    padding-left: 10px;
    border-radius: 30px;
    

}
p {

    background-color:salmon ;
    padding: 10px; 
    margin: 20px; 
    border-radius: 30px;

}
img{

    height: 400px;
    width: 400px;
    margin-left: auto;
    margin-right: auto;

}

body{

    background-color: beige;
    margin: 0%;
    

}
footer{

    background-color: gray;
    padding-top: 10px;
    margin-top: 15px;
    padding: 10px;


}

header{


    display: inline-block;

}

div.iniciales{

    margin-left: auto;
    margin-right: auto;

}

section.solo_fondo{

    background-color: mediumaquamarine;
    height: 10px;
    width: 100%;
    margin-bottom: 8px;

}

article.base{

    margin-right: 20%;
    margin-left: 20%;

}
a{

    padding: 5px;

}
div.link{

    margin-left: 20%;
    margin-right: 20%;

}
div.centrar{

    margin-left: auto;
    margin-right: auto;

}
main{

    padding-bottom: 50px;

}
.manzana{

    display: flex;
    justify-content: center;
    align-items: center;
}
.formulario{
    width: 400px; 
    background-color: aquamarine;
    padding: 30px; 
    margin:auto; 
    margin-top: 100px; 

}




2º Trimestre 

Código de powershell

#Etiqueta
$Label1=New-Object System.Windows.Forms.Label
$Label1.Text="Nombre"
$Label1.AutoSize=$True
$Label1.Location=New-Object System.Drawing.Size(100,120)

#CAJADETEXTO
$TextBox1 = New-Object System.Windows.Forms.TextBox
$TextBox1.Location = New-Object System.Drawing.Size(120,140)
$TextBox1.Size = New-Object System.Drawing.Size(260,20)

#Etiqueta
$Label2=New-Object System.Windows.Forms.Label
$Label2.Text="E-mail"
$Label2.AutoSize=$True
$Label2.Location=New-Object System.Drawing.Size(100,160)

#Etiqueta
$Label=New-Object System.Windows.Forms.Label
$Label.Text="Subcribete a nuestra Newsletter. Gratis"
$Label.AutoSize=$True
$Label.Location=New-Object System.Drawing.Size(100,90)

#Etiqueta
$Label3=New-Object System.Windows.Forms.Label
$Label3.Text="Se te notificara de todas nuestras actualizaciones."
$Label3.AutoSize=$True
$Label3.Location=New-Object System.Drawing.Size(100,260)

$Button1.Add_Click(
    {
        $Var=$TextBox.Text;
        $Var >> guardar.txt
        $TextBox.Text = ""
        
   
    }
)

$Button2.Add_Click({$Form.Close()})

$Form.Controls.Add($Button1)
$Form.Controls.Add($Button2)
$Form.Controls.Add($Label)
$Form.Controls.Add($TextBox)
$Form.Controls.Add($Label1)
$Form.Controls.Add($TextBox1)
$Form.Controls.Add($Label2)
$Form.Controls.Add($Label3)

$Form.ShowDialog()



            
            
            
            
