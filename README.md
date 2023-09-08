<style>
    .title-container section{
    height: 100vh;
    background: #000;
    }
    .title-container section:before{
        content: '';
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        background: linear-gradient(to right, #f00, #f00, #0f0, #0ff, #ff0, #0ff);
        mix-blend-mode: color;
        pointer-events: none;

    }
    .title-container h1{
        margin: 0;
        padding: 0;
        position: absolute;
        top: 50%;
        transform: translateY(-50%);
        width: 100%;
        text-align: center;
        color: #ddd;
        font-size: 5em;
        font-family: sans-serif;
        letter-spacing: 0.2em;
    }

    .title-container .titulo1{
        margin: 0;
        padding: 0;
        position: absolute;
        top: 20%;
        transform: translateY(-50%);
        width: 100%;
        text-align: center;
        color: #dddddd6c;
        font-size: 2em;
        font-family: sans-serif;
        letter-spacing: 0.2em;
        opacity: 0;
        animation: animacionTitulos 1s linear forwards;
    }

    .title-container .titulo2{
        margin: 0;
        padding: 0;
        position: absolute;
        top: 75%;
        transform: translateY(-50%);
        width: 100%;
        text-align: center;
        color: #dddddd6c;
        font-size: 2em;
        font-family: sans-serif;
        letter-spacing: 0.2em;
        opacity: 0;
        animation: animacionTitulos 1s linear forwards;
    }
    .title-container h1 span{
        opacity: 0;
        display:inline-block;
        animation: animacion 1s linear forwards;
    }

    /* SISTEMAS */

    .title-container h1 span:nth-child(1){
        animation-delay: 1s;
    }
    .title-container h1 span:nth-child(2){
        animation-delay: 1.5s;
    }
    .title-container h1 span:nth-child(3){
        animation-delay: 2.5s;
    }
    .title-container h1 span:nth-child(4){
        animation-delay: 3s;
    }
    .title-container h1 span:nth-child(5){
        animation-delay: 3.5s;
    }
    .title-container h1 span:nth-child(6){
        animation-delay: 3.75s;
    }
    .title-container h1 span:nth-child(7){
        animation-delay: 3.80s;
    }
    .title-container h1 span:nth-child(8){
        animation-delay: 4s;
    }
    /* UDENAR */
    .title-container h1 span:nth-child(9){
        animation-delay: 1s;
    }
    .title-container h1 span:nth-child(10){
        animation-delay: 1.5s;
    }
    .title-container h1 span:nth-child(11){
        animation-delay: 2s;
    }
    .title-container h1 span:nth-child(12){
        animation-delay: 2.5s;
    }
    .title-container h1 span:nth-child(13){
        animation-delay: 3s;
    }
    .title-container h1 span:nth-child(14){
        animation-delay: 3.5s;
    }
    .title-container h1 span:nth-child(15){
        animation-delay: 4s;
    }

    .title-container video{
        object-fit: cover;
        width: 100%;
        height: 100%;
    }

    @keyframes animacion{
        0%{
            opacity: 0;
            transform:rotateY(90deg);
            filter:blur(10px);
        }
        100%{
            opacity: 1;
            transform:rotateY(0deg);
            filter:blur(0);
        }
    }

    @keyframes animacionTitulos {
        0% {
        opacity: 0;
        transform: translateY(-20px);
        }
        100% {
        opacity: 1;
        transform: translateY(0);
        }
    }
</style>
<div  class="title-container">
        <section>
            <video src="https://github.com/SegundoPaladines/SegundoPaladines/assets/99047308/c91b5ff9-6e84-412d-9581-87fdf110c958" autoplay muted></video>
            <h2 class="titulo1">Hi There</h2>
            <h1>
                <span>S</span>
                <span>E</span>
                <span>G</span>
                <span>U</span>
                <span>N</span>
                <span>D</span>
                <span>O</span>
                <br>
                <span>P</span>
                <span>A</span>
                <span>L</span>
                <span>A</span>
                <span>D</span>
                <span>I</span>
                <span>N</span>
                <span>E</span>
                <span>S</span>
            </h1>
            <h2 class="titulo2">Welcome to My Repo</h2>
        </section>
    </div>