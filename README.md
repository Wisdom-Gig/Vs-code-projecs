# my_first_project
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="author" content="Wisdom Aderinto">
    <meta name="description" content="THIS THE OFFICIAL WEBSITE FOR LITTLE TACO SHOP wa">
    <title>LITTLE TACO SHOP</title>
    <link rel ="icon" href="images/css logo.png">
    <link href="sytle main css.css" rel="stylesheet"></link>
</head>
<body>
    <header class="header">
    <h1 class="header__h1"> LITTLE TACO SHOP </h1>
    <nav class="header__nav">
        <ul class="header__ul">
            <li>
               <a href="#menu">Menu</a>
            </li>
            <li>
                <a href="hours.html">STORE HOURS</a>
            </li>
            <li>
                <a href="contact.html">Contact</a> 
            </li>
            <li> 
                <a href="about  .html">ABOUT LTS</a>
                </a>
            </li>
        </ul>  
        </nav> 
</header>

<section class="hero">
    <h2 class="hero__h2">Bienvenidos</h2>
<figure>
<img src="images/tacos and a drink.jpeg" alt="TACOS AND A DRINK" width="1000" height="667">
<figcaption class="offscreen">
TACOS AND A DRINK
</figcaption>
</figure>  
</section>
<hr>
<main class="main">
    <article id="menu" class="main__article">
    <h2>OUR MENU</h2>
    <section>
        <figure>
    <img src="images/tasty tacos.jpeg" alt="SOME TASTY TACOS" width="500" height="400">
    <figcaption>
    Sweet tasty tacos
    </figcaption>
    </figure>
    </section>
        <table>
        <caption><u><b><i>OUR TACOS</i></b></u></caption>
            <thead> 
            <tr>
            <th scope="col">Tacos</th>
            <th scope="col"><abbr title="QUANTITY">Qty</abbr></th>
            <th scope="col">Price</th>
            </tr>
            </thead>
        <tbody>
        <tr>
        <th scope="row"rowspan="3">
            CRUNCHY</th>
         <td>1</td>
         <td>$1.50</td>
         </tr>
         <tr>
         <td>2</td>
         <td>$2.50</td>
         </tr>
         <tr>
         <td>3</td>
         <td>$3.25</td>
         </tr>

        <tr>
        <th scope="row"rowspan="3">
            SOFT</th>
         <td>1</td>
         <td>$2.00</td>
         </tr>
         <tr>
         <td>2</td>
         <td>$3.50</td>
         </tr>
         <tr>
         <td>3</td>
         <td>$4.50</td>
         </tr>
        </tbody>
        <tfoot>
            <tr>
            <td colspan="3">
                chips&amp; salsa $2
            </td>
            </tr>
            </tfoot> 
        </table>
        <a href="#">back to top</a>
    </article>
        <hr> 
    <a href="#">BACK TO TOP</a> 
</main>
        <footer class="footer">
            
            <p>
                <span class="nowrap">Copyright &copy;</span>
                 <span class="nowrap">  LITTLE TACO SHOP </span></p>
        </footer>
</body>
</html>
