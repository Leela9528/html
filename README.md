<html>
    <head>
       
        <style>
            *{
font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
}
h1{
    text-align: center;
    margin-top: 100px;
     
}
.menu{
    
    margin-left: 0px 80px 100px 80px;
   
}
span{
 
    border: 1px solid black; 
    margin-top: 50px;
    margin-left: 50px;
    float: left;
   margin-bottom: 20px;
}
.chicken{
    position: relative;
    background-color: gray;
    box-shadow: 15px 10px 15px black;
}
.beef{
    position: relative;
    background-color: gray;
    box-shadow: 15px 10px 15px black;
}
.sushi{
    position: relative;
    background-color: gray;
    box-shadow: 15px 10px 15px black;
}
.exp{
    padding:25px;
}
.c1{
    border: 1px solid black;
    position: absolute;
    top:-21px;
    left: 50%;
    height: 30px;
    width: 149px;
    text-align: center;
    font-size: 20px;
    background-color: pink;
}
.b1{
    border: 1px solid black;
    position: absolute;
    top:-21px;
    left: 50%;
    height: 30px;
    width: 149px;
    text-align: center;
    font-size: 20px;
    background-color: red;
}
.s1{
    border: 1px solid black;
    position: absolute;
    top:-21px;
    left: 50%;
    height: 30px;
    width: 149px;
    text-align: center;
    font-size: 20px;
    background-color: yellowgreen;
}
@media (min-width:992px)
{
    .chicken{
        width:25%;
        height: 55%;
       
    }
    .c1{
        width:50%;
    }
    .beef{
        width: 25%;
        height: 55%;
    }
    .b1{
        width:50%;
    }
    .sushi{
        width:25%;
       height: 55%;
    }
    .s1{
        width:50%;
    }
}

@media (min-width: 768px) and (max-width: 991px)
{
    .chicken{
        width:40%;
        height: 50%;
    }
    .c1{
        width:50%;
    }
    .beef{
        width: 40%;
        height:50%;
    }
    .b1{
        width:50%;
    }
    .sushi{
        width:90%;
        height: 30%;
    }
    .s1{
        width:50%;
    }
    
}
@media (max-width:767px)
{
    .chicken{
        width:100%;
        height: 30%;
    }
    .c1{
        width: 50%;
    }
    .beef{
        width: 100%;
        height: 30%;
    }
    .b1{
        width: 50%;
    }
    .sushi{
        width:100%;
        height: 30%;
    }
    .s1{
        width: 50%;
    }
}

        </style>
    </head>
    <body>
        <h1> Our Menu</h1>
        <div class="menu">
            <span class="chicken">
            <p class="exp">Chickens were domesticated in Southern China around 
                8,000 years ago in 6000 B.C. The color of the egg depends on the chickens earlobes.
                Red ear lobed chickens lay brown eggs.  
                </p>
            <p class="c1"><b>chicken</b></p>
            </span>
            
            <span class="beef">
            <p class="exp">Beef is mainly composed of saturated and monounsaturated fat, present in approximately equal amounts. 
            The major fatty acids are stearic acid, oleic acid, and palmitic acid.</p>
            <p class="b1"><b>Beef</b></p>
            </span>
            <span class="sushi">
                <p class="exp">Sushi is the most famous Japanese dish outside of Japan,
                     and one of the most popular dishes among the Japanese.
                     In Japan, sushi is usually enjoyed on special occasions, such as a celebration</p>
            <p class="s1"><b>Sushi</b></p>
            </span>
        </div>
    </body>
</html>
