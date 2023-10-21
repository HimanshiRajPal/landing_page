# landing_page
landing.css
@import url('https://fonts.googleapis.com/css2?family=Ubuntu:wght@300&display=swap');

*{
    margin: 0;
    padding: 0;
}

.container{
    max-width: 80vw;
    font-family: 'Ubuntu', sans-serif;
}

.navbar{
    display: flex;
    height: 67px;
}
.navbar li{
    list-style: none;
    margin: 0 12px;
}

.topleft{
    width: 50%;
}

.topright{ 
    width: 50%;
}

.section1{
   max-height: 100vh; 
   color: #000000;
}

.section1 h1{
    color: #d9642e;
    font-size: 2rem;
}

.logo{
    font-size: 1.3rem;
}

.dumbellimg{
    width: 289px;
}

.topright .gymimg{
    width: 466px;
}

.section2{
    padding: 73px;
}

.section2 h1{
    font-size: 2.3rem;
}

.section2 p{
    padding: 0 8vw;
    text-align: center;
}

.box{
    padding: 8px 0;
    margin: 12px 22px;
    min-width: 20vw;
    border: 2px solid rgb(141, 80, 33);
    border-radius: 8px;
    text-align: center;
}

.box h2{
    font-size: 2rem;
    padding: 15px 0;
}

.highlighted{
    font-size: 1.2rem;
    font-weight: bolder;
}

.box ul{
    list-style-type: none;
}

.box ul li{
   margin: 12px 2px;
}

.plantable{
    display: flex;
    justify-content: center;
    align-items: center;
}

.section3 table{
    width: 100%;
    margin-bottom: 140px;
    margin-top: 20px;
    border-collapse: collapse;
}

.section3 table th{ 
    width: 23vw; 
    border-bottom: 2px solid black;
    padding: 15px 0;
} 

.section3 table td{   
    border-bottom: 2px solid black; 
} 
 

.section3 h1{
    font-size: 2.3rem;
}

.section3{
    padding: 73px;
}

footer{
    padding: 23px;
    text-align: center;
}
.buttons{
    display: flex;
    justify-content: center;
    align-items: center;
    margin: 12px;
}

.deal{
    font-size: 1.2rem;
    font-weight: bolder;
    margin: 12px 0;
}
