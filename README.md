<h1 align="center">Hi 👋, I'm DANE</h1>
<h3 align="center">C#, JS and WEB Developer from Germany, EUROPE</h3>

- 🔭 I’m currently working on [ELITE ROLEPLAY PROJECT](https://elite-projects.de)

- 🌱 I’m currently optimizing my skills on **OpenSoure/Code beautify**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://dev.to/elite-dane" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/dev-dot-to.svg" alt="elite-dane" height="30" width="40" /></a>
<a href="https://stackoverflow.com/users/0" target="blank"><img align="center" src="https://cdn.jsdelivr.net/npm/simple-icons@3.0.1/icons/stackoverflow.svg" alt="0" height="30" width="40" /></a>
</p>

<div class="ghost-canvas">
            <div class="ghost-body">
                <div class="ghost-body-copy">
                    
                </div>
                <div class="ghost-head">
                    <div class="eye-left"></div>
                    <div class="eye-right"></div>
                    <div class="mouth"></div>
                </div>
                <div class="down-bubble">
                    <div class="bubble-1"></div>
                    <div class="bubble-2"></div>
                    <div class="bubble-3"></div>
                    <div class="bubble-4"></div>
                </div>
            </div>
        </div>
        
        <style>
        /*
Simple animated ghost from @MirkoWD

Setup:
-Remove .body 
-To remove the animation simply delete the code inside the ANIMATION tags
-The image is fully responsive, simple change the height and width of .ghost-canvas 
*/

body{
    background-color: #0E0735;
}
/*Canvas that contains the ghost, change this values to move around ar resize the ghost*/
.ghost-canvas{
    position: relative;
    width: 600px;
    height: 400px;
    margin: 100px auto 0 auto;
}

.ghost-body{
    position: absolute;
    height: 28%;
    width: 22%;
    background-color: white;
    left: 40%;
    top:  33%;
  /*ANIMATION START*/
    animation-name: floating;
    animation-duration: 10s;
    animation-timing-function:linear;
    animation-iteration-count: infinite;
  /*ANIMATION END*/
}
.ghost-body-copy{
    position: absolute;
    height: 28%;
    width: 22%;
    background-color: white;
    left: 40%;
    top:  33%;
    z-index: 1;
}

.ghost-head{
    position: absolute;
    height: 100%;
    width: 100%;
    top: -50%;
    background-color: white;
    border-radius: 90px;
    
}
.eye-right{
    position: absolute;
    height: 22%;
    width: 20%;
    right: 22%;
    top: 40%;
    background-color: black;
    border-radius: 50%;
}
.eye-left{
    position: absolute;
    height: 22%;
    width: 20%;
    left: 22%;
    top: 40%;
    background-color: black;
    border-radius: 50%;
}
.mouth{
    position: absolute;
    height: 26%;
    width: 24%;
    left: 38%;
    top: 70%;
    background-color: black;
    border-radius: 50%;
    z-index: 2
}
.down-bubble{
    position: absolute;
    height: 55%;
    width: 100%;
    top:70%;
}

.bubble-1{
    position: absolute;
    height: 100%;
    width:25%;
    background-color: white;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  /*ANIMATION START*/
    animation-name: bubble;
    animation-duration: 2.8s;
    animation-iteration-count: infinite;
    animation-timing-function:ease-in-out;
  /*ANIMATION END*/
}
.bubble-2{
    position: absolute;
    height: 100%;
    width:25%;
    left: 25%;
    background-color: white;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  /*ANIMATION START*/
    animation-name: bubble;
    animation-duration: 3.2s;
    animation-iteration-count: infinite;
    animation-timing-function:ease-in-out;
  /*ANIMATION END*/
}
.bubble-3{
    position: absolute;
    height: 100%;
    width:25%;
    right: 25%;
    background-color: white;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  /*ANIMATION START*/
    animation-name: bubble;
    animation-duration: 3.4s;
    animation-iteration-count: infinite;
    animation-timing-function:ease-in-out;
  /*ANIMATION END*/
}
.bubble-4{
    position: absolute;
    height: 100%;
    width:25%;
    right: 0;
    background-color: white;
    border-bottom-left-radius: 50px;
    border-bottom-right-radius: 50px;
  /*ANIMATION START*/
    animation-name: bubble;
    animation-duration: 3s;
    animation-iteration-count: infinite;
    animation-timing-function:ease-in-out;
  /*ANIMATION END*/
}

/*ANIMATION START*/
@keyframes bubble{
    0%{
        top: 0;
    }
    50%{
        top:20%;
    }
     100%{
        top: 0;
    }
}
@keyframes floating{
    0%{top: 33%;}
    30%{top: 40%;}
    50%{top:33%;}
    70%{top:25%;}
    100%{top:33%;}
}
/*ANIMATION END*/
</style>
