# Amazon Landing Project (https://amozonfrombrazil.netlify.app)
![image](https://user-images.githubusercontent.com/62224609/159550753-9174ef56-be50-4edd-8ec0-121886a7e809.png)

Projeto desenvolvido treinar o conhecimento em responsivo. Trabalhado as proporções com o @media. A ideia principal era trabalhar o máximo de proporção. Foi utilizado tambem a biblioteca IONICONS importado por CDN para utilização de seus recuros.

## Treinando Responsivo com @media 
```python
@media screen and (max-width:1200px) {
    /*Normal Screen*/
    .navbar {
        width: 100%;
        height: 100px;
    }
    ul {
        margin-left: 30px;
    }
    ul li {
        margin-left: 60px;
    }
    ul li a {
        font-size: 1.6vw;
    }
    .search {
        margin-top: 3px;
        margin-left: 290px;
    }
    .srch {
        height: 40px;
        width: 190px;
        font-size: 14px;
    }
    .btn {
        height: 40px;
        width: 80px;
    }
    .content {
        width: 100%;
    }
    .content h1,
    .content span {
        font-size: 4.5vw;
    }
    .content .par {
        width: 90%;
        font-size: 1.5vw;
    }
    .content .cn {
        width: 13%;
        height: 3.5vw;
        font-size: 1.8vw;
    }
    .content a {
        font-size: 1.6vw
    }
}

@media screen and (max-width:1170px) {
    /*Login-box*/
    .main {
        padding-left: 20px;
        height: 180vh;
    }
    .form {
        margin-left: -30px;
        width: 250px;
        height: 130px;
        background: linear-gradient(to top, rgba(0, 0, 0, 0.250)50%, rgba(0, 0, 0, 0.250)50%);
        position: absolute;
        top: 420px;
        left: 50px;
        transform: translate(0%, -5%);
        border-radius: 10px;
        padding: 25px;
    }
    .form input {
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid #ff7200;
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    .btnn a {
        font-size: 16px;
    }
    .form .link a {
        font-size: 16px;
    }
}

@media screen and (max-width: 830px) {
    /*For tablet*/
    .content {
        margin-top: 120px;
        width: 80%;
        margin-left: 40px;
    }
    .content h1,
    .content span {
        font-size: 6vw;
    }
    .content .par {
        width: 90%;
        font-size: 1.8vw;
    }
    .content .cn {
        width: 15%;
        height: 4.5vw;
        font-size: 2vw;
    }
    .content a {
        font-size: 2vw
    }
    .logo {
        margin-left: 240px;
        width: 100%;
        margin-top: 15px;
        font-size: 5vw;
    }
    .menu {
        width: 100%;
    }
    ul {
        margin-top: -5px;
        margin-left: 5px;
    }
    ul li {
        margin-left: 60px;
    }
    ul li a {
        font-size: 2vw;
    }
    .search {
        margin-top: -20px;
        margin-left: 60px;
    }
    .srch {
        height: 30px;
        width: 160px;
        font-size: 12px;
    }
    .btn {
        height: 30px;
        width: 70px;
    }
    .main {
        padding-left: 20px;
        height: 180vh;
    }
    .form {
        margin-left: -30px;
        width: 250px;
        height: 370px;
        background: linear-gradient(to top, rgba(0, 0, 0, 0.8)50%, rgba(0, 0, 0, 0.8)50%);
        position: absolute;
        top: 430px;
        left: 50px;
        transform: translate(0%, -5%);
        border-radius: 10px;
        padding: 25px;
    }
    .form input {
        width: 240px;
        height: 35px;
        background: transparent;
        border-bottom: 1px solid hsl(27, 100%, 50%);
        border-top: none;
        border-right: none;
        border-left: none;
        color: #fff;
        font-size: 15px;
        letter-spacing: 1px;
        margin-top: 30px;
        font-family: sans-serif;
    }
    .btnn a {
        font-size: 16px;
    }
    .form .link a {
        font-size: 16px;
    }
}

@media screen and (max-width: 600px) {
    /*IPAD*/
    .content {
        margin-top: 80px;
        margin-left: 20px;
    }
    .search {
        margin-top: -40px;
        margin-left: 42px;
    }
    .logo {
        margin-left: 180px;
        font-size: 4vw;
    }
    ul {
        margin-top: -25px;
        margin-left: -5px;
    }
    ul li {
        margin-left: 50px;
    }
    ul li a {
        font-size: 2vw;
    }
}

@media screen and (max-width: 450px) {
    /*mobile*/
    .logo {
        margin-left: 140px;
        font-size: 4vw;
    }
    ul {
        margin-top: -25px;
    }
    ul li {
        margin-left: 42px;
    }
    ul li a {
        font-size: 2vw;
    }
    .search {
        margin-top: -40px;
        margin-left: 38px;
    }
}
```


