# Profolio-Kevin2023

Hi! I'm Kevin

I am a bachelor's student in video game production and digital entertainment

* {
    margin: 0;
    padding: 0;
}
.article {
    padding: 60px;
}
.margen {
    padding: 60px;
    color: white;
}
.grid {
    width: 300px;
    height: 300px;
    display: flex;
    flex-wrap: wrap;
    border-style: solid;
  }
  
  
  .grid div {
    width: 30px;
    height: 30px;
  }
  .controlgrid {
    width: 300px;
    height: 300px;
    display: flex;
    flex-wrap: wrap;
  }
  .controlgrid div {
    width: 100px;
    height: 100px;
  }
  
  .snake {
    background-image: radial-gradient(circle, rgb(73, 211, 96), rgb(69, 148, 67));
    border-radius: 10px;
   
  }
  
  .apple {
    background-image: radial-gradient(circle, rgb(255, 93, 93), rgb(207, 13, 13));
    border-radius: 10px;
  }
.boton {
    padding: 20px 0px;
}
.btnc {
    border: 0px solid black;
    background-color: black;
    padding: 5px 10px;
    color: white;
    outline: none;
    font-family: 'Montserrat';
    font-weight: 500;
    font-size: 50px;
    text-align: center;
    vertical-align: center;
  }
  .btnc:hover {
    background-color: #333;
  }
.btn {
    border: 0px solid black;
    background-color: black;
    padding: 5px 10px;
    color: white;
    outline: none;
    font-family: 'Montserrat';
    font-weight: 500;
    font-size: 20px;
  }
  
  .btn:hover {
    background-color: #333;
  }
/* topnav*/

.topnav {
    overflow: hidden;
    background-color: #333;
    font-family: 'Montserrat';
    font-weight: 500;
    font-size: 40px;
    
  }
  
  .topnav a {
    float: left;
    display: block;
    color: #f2f2f2;
    text-align: center;
    padding: 14px 16px;
    text-decoration: none;
    font-size: 17px;
  }
  
  .topnav a:hover {
    background-color: #ddd;
    color: black;
  }
  
  .topnav a.active {
    background-color: rgb(255, 255, 255);
    color: rgb(0, 0, 0);
  }
  
  .topnav .icon {
    display: none;
  }

  @media screen and (max-width: 768px) {
    .topnav a:not(.active) {display: none;}
    .topnav a.icon {
        font-family: 'Montserrat';
      float: right;
      display: block;
      font-size: 17px;
    }
  }
  
  @media screen and (max-width: 768px) {
    .topnav.responsive {position: relative;}
    .topnav.responsive .icon {
      position: absolute;
      right: 0;
      top: 0;
    }
    .topnav.responsive a {
      float: none;
      display: block;
      text-align: left;
    }
  }
  * {
    margin: 0;
    padding: 0;
}

.img-bannerbig {
    display: none;
}

.img-bannersmall {
    width: 100%;
    vertical-align: bottom;
}

.wrapper{
    width: 100%;
    font-family: 'Open Sans';
}
.wrapper h2{
    padding: 30px 30px 20px;
    font-family: 'Montserrat';
    font-weight: 500;
    font-size: 40px;
    color: #111111;
    line-height: 44px;
}

/*estilo del footer*/
.contact-info {
    color: lightgray;
    font-family: 'Open Sans';
    font-size: 18px;
    font-style: italic;
    text-align: center;
    padding: 20px;
    position: fixed;
    width: 100%;
    bottom: 0;
}
/*cambio con pantalla de tablet*/
@media only screen and (min-width:768px){
    .img-bannerbig {
        display: block;
        width: 100%;
        
    }
    .img-bannersmall {
        display: none;
    }
    .wrapper {
        width: 700px;
        margin: 0 auto;
    }
    .wrapper h2{
        padding: 30px 0px 0px;
        font-size: 50px;
        line-height: 54px;
    }
}


/*sticky footer*/
.page-wrap {
    min-height: 100%;
    margin-bottom: 30px; 
  }
  .page-wrap:after {
    content: "";
    display: block;
  }
  .contact-info, .page-wrap:after {
    height: 30px; 
  }
  .contact-info {
    background: black;
  }

/*estilo del link de contacto*/
a:link {
      color: lightgray;
}
a:hover {
      color: white;
}
a:active {
    color: black;
    background-color: lightgray;
}
