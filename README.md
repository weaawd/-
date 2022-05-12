# -<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" />
    <link href="https://fonts.googleapis.com/css2?family=Kanit&display=swap" rel="stylesheet" />
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/css/bootstrap.min.css" rel="stylesheet" />
    <link href="https://ianlunn.github.io/Hover/css/hover.css" rel="stylesheet" />
    <script src="https://cdnjs.cloudflare.com/ajax/libs/animejs/2.0.2/anime.min.js"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.1.0/dist/js/bootstrap.bundle.min.js"></script>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.3.0/font/bootstrap-icons.css">
    <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <title>Hadesx</title>
    <style>
        body {
            margin: 0;
            font-family: Arial;
            font-size: 17px;
            background-color: black;
            font-family: "Kanit", sans-serif;
        }
        
        #myVideo {
            position: fixed;
            min-width: 100%;
            min-height: 100%;
            -webkit-filter: blur(5px);
            -moz-filter: blur(5px);
            -o-filter: blur(5px);
            -ms-filter: blur(5px);
            filter: blur(5px);
        }
        
        .img-content {
            color: #fff;
            position: absolute !important;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        
        .ml13 {
            font-size: 3em;
            text-transform: uppercase;
            letter-spacing: 0.1em;
            font-weight: 600;
            color: rgb(255, 255, 255);
        }
        
        .ml13 .letter {
            display: inline-block;
            line-height: 1em;
        }
        
        .content-social {
            position: fixed;
            bottom: 0;
            color: #f1f1f1;
            width: 100%;
            padding: 20px;
        }
        
        .btn-check:focus+.btn,
        .btn:focus {
            outline: 0;
            box-shadow: none;
        }
    </style>
</head>

<body id="body" data-aos-easing="ease" data-aos-duration="400" data-aos-delay="0">
    <div class="content">
        <img id="myVideo" src="https://cdn.discordapp.com/attachments/934719315675082753/934753723681505280/903575.png">
        <div class="text-center img-content">
            <img style="
        width: 200px;
        border-radius: 100%;
        -webkit-animation-name: hvr-bob-float, hvr-bob;
        animation-name: hvr-bob-float, hvr-bob;
        -webkit-animation-duration: .3s, 1.5s;
        animation-duration: .3s, 1.5s;
        -webkit-animation-delay: 0s, .3s;
        animation-delay: 0s, .3s;
        -webkit-animation-timing-function: ease-out, ease-in-out;
        animation-timing-function: ease-out, ease-in-out;
        -webkit-animation-iteration-count: 1, infinite;
        animation-iteration-count: 1, infinite;
        -webkit-animation-fill-mode: forwards;
        animation-fill-mode: forwards;
        -webkit-animation-direction: normal, alternate;
        animation-direction: normal, alternate;" src="https://cdn.discordapp.com/attachments/934719315675082753/934750758950281306/2-12-2021PNG.png" alt="Artist">
            <div>
                <h1 class="ml13"><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">S</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">p</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">e</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">c</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">t</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">o</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">r</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);">X</span><span class="letter" style="opacity: 1; transform: translateY(0px) translateZ(0px);"></span></h1>
            </div>

            <div>
                <center data-aos="fade-up" data-aos-delay="800" data-aos-duration="500" class="aos-init aos-animate">
                    <hr style="width: 14%; height: 5px; margin-top: 10px;">
                </center>
                <div data-aos="fade-up" data-aos-delay="1000" data-aos-duration="500" class="aos-init aos-animate">
                    <span class="txt-rotate" data-period="2000" data-rotate="[&quot;SPECTOR#2004&quot;,&quot;Hadesx&quot;, &quot;https://discord.gg/spectorshop&quot;]" '=""><span class="wrap">http</span></span>
            </div>
        </div>
    </div>


    <div class="content-social">
        <div>
            <a href="https://github.com/Hadesx2004" target="_blank" class="btn hvr-buzz"><i class="bi bi-github" style="color:white;font-size:2rem;"></i></a>
				<a href="https://www.facebook.com/highdes2004" target="_blank" class="btn hvr-buzz"><i class="bi bi-facebook" style="color:white;font-size:2rem;"></i></a>
				<a href="https://discord.gg/spectorshop" target="_blank" class="btn hvr-buzz"><i class="bi bi-discord" style="color:white;font-size:2rem;"></i></a>
				<a href="https://youtube.com/channel/UCP2Xzbw-FiYF81jI6wyX_Gw" target="_blank" class="btn hvr-buzz"><i class="bi bi-youtube" style="color:white;font-size:2rem;"></i></a>
        </div>
    </div>
    </div>

    <script>
        var audio = new Audio("https://files.catbox.moe/wl2r68.mp3");
        $("#body").click(function() {
            audio.play();
            audio.volume = 0.05
        })
        AOS.init();
        var textWrapper = document.querySelector('.ml13 ');
        textWrapper.innerHTML = textWrapper.textContent.replace(/\S/g, "<span class='letter '>$&</span>");

        anime.timeline({
                loop: false
            })
            .add({
                targets: '.ml13 .letter ',
                translateY: [100, 0],
                translateZ: 0,
                opacity: [0, 1],
                easing: "easeOutExpo",
                duration: 1400,
                delay: (el, i) => 300 + 30 * i
            })
        var TxtRotate = function(el, toRotate, period) {
            this.toRotate = toRotate;
            this.el = el;
            this.loopNum = 0;
            this.period = parseInt(period, 10) || 2000;
            this.txt = ' ';
            this.tick();
            this.isDeleting = false;

        };

        TxtRotate.prototype.tick = function() {
            var i = this.loopNum % this.toRotate.length;
            var fullTxt = this.toRotate[i];


            if (this.isDeleting) {
                this.txt = fullTxt.substring(0, this.txt.length - 1);

            } else {
                this.txt = fullTxt.substring(0, this.txt.length + 1);

            }

            this.el.innerHTML = '<span class="wrap">' + this.txt + '</span>'; var that = this; var delta = 300 - Math.random() * 100; if (this.isDeleting) { delta /= 2; } if (!this.isDeleting && this.txt === fullTxt) { delta = this.period;
                    this.isDeleting = true; } else if (this.isDeleting && this.txt === '') { this.isDeleting = false; this.loopNum++; delta = 500; } setTimeout(function() { that.tick(); }, delta); }; window.onload = function() { var elements = document.getElementsByClassName('txt-rotate');
                    for (var i = 0; i
                    < elements.length; i++) { var toRotate=elements[i].getAttribute( 'data-rotate'); var period=elements[i].getAttribute( 'data-period'); if (toRotate) { new TxtRotate(elements[i], JSON.parse(toRotate), period); } } var css=document.createElement( "style");
                        css.type="text/css" ; css.innerHTML=".txt-rotate > .wrap { border-right: 0.08em solid #666 }" ; document.body.appendChild(css); }; </script>


                        <style type="text/css">
                            .txt-rotate>.wrap {
                                border-right: 0.08em solid #666
                            }
                        </style>
</body>
