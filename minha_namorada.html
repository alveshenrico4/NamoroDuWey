<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Você quer ser minha namorada?</title>
<link href="https://fonts.googleapis.com/css2?family=Cinzel+Decorative:wght@400;700&family=Playfair+Display:ital,wght@0,400;0,600;1,400;1,600&family=Cormorant+Garamond:ital,wght@0,300;0,400;1,300;1,400&display=swap" rel="stylesheet">
<style>
*{margin:0;padding:0;box-sizing:border-box}
html,body{width:100%;min-height:100%;font-family:'Cormorant Garamond',serif;background:#06030a;color:#f0e6d3;overflow-x:hidden}

/* ── FUNDO PRINCIPAL ── */
.scene{position:fixed;inset:0;z-index:0}
.scene svg{width:100%;height:100%;object-fit:cover}

/* Overlay de névoa */
.fog{position:fixed;inset:0;z-index:1;background:
  radial-gradient(ellipse 70% 50% at 50% 100%,rgba(90,0,20,.7) 0%,transparent 60%),
  radial-gradient(ellipse 100% 40% at 50% 0%,rgba(5,0,10,.8) 0%,transparent 60%);
  pointer-events:none}

/* ── PÉTALAS ── */
.petals{position:fixed;inset:0;z-index:2;pointer-events:none;overflow:hidden}
.petal{position:absolute;top:-20px;font-size:13px;animation:cair linear infinite;opacity:0;user-select:none}
@keyframes cair{0%{transform:translateY(0) rotate(0deg);opacity:0}10%{opacity:.8}90%{opacity:.4}100%{transform:translateY(105vh) rotate(520deg) translateX(40px);opacity:0}}

/* Partículas douradas */
.sparks{position:fixed;inset:0;z-index:2;pointer-events:none}
.spark{position:absolute;border-radius:50%;background:#c9a84c;animation:subir linear infinite;opacity:0}
@keyframes subir{0%{transform:translateY(0) scale(1);opacity:0}20%{opacity:.5}80%{opacity:.2}100%{transform:translateY(-70vh) scale(.2);opacity:0}}

/* ── LAYOUT ── */
.wrapper{position:relative;z-index:10;min-height:100vh;display:flex;flex-direction:column;align-items:center;justify-content:center;padding:40px 20px}

/* Card central */
.card{position:relative;max-width:660px;width:100%;padding:56px 48px;background:rgba(6,2,10,.82);border:1px solid rgba(180,130,50,.28);backdrop-filter:blur(14px);animation:surgir 1.4s cubic-bezier(.16,1,.3,1) both}
@keyframes surgir{from{opacity:0;transform:translateY(50px) scale(.97)}to{opacity:1;transform:translateY(0) scale(1)}}

/* Borda dourada animada */
.card::before{content:'';position:absolute;inset:-1px;background:linear-gradient(135deg,rgba(201,168,76,.5),transparent 35%,rgba(140,0,20,.45),transparent 65%,rgba(201,168,76,.4)) border-box;-webkit-mask:linear-gradient(#fff 0 0) padding-box,linear-gradient(#fff 0 0);mask:linear-gradient(#fff 0 0) padding-box,linear-gradient(#fff 0 0);-webkit-mask-composite:destination-out;mask-composite:exclude;pointer-events:none}

/* Cantos ornamentados */
.c{position:absolute;width:26px;height:26px}
.c svg{width:100%;height:100%}
.c.tl{top:9px;left:9px}.c.tr{top:9px;right:9px;transform:scaleX(-1)}.c.bl{bottom:9px;left:9px;transform:scaleY(-1)}.c.br{bottom:9px;right:9px;transform:scale(-1)}

/* ── TEXTOS ── */
.olho{font-family:'Cinzel Decorative',cursive;font-size:.58rem;letter-spacing:.38em;color:#c9a84c;text-transform:uppercase;margin-bottom:20px;opacity:0;animation:subiu 1s .3s ease both}
.titulo{font-family:'Cinzel Decorative',cursive;font-size:clamp(1.5rem,4.5vw,2.5rem);font-weight:700;line-height:1.22;color:#f5e8d5;text-shadow:0 0 50px rgba(180,0,30,.9),0 2px 6px rgba(0,0,0,.8);margin-bottom:8px;opacity:0;animation:subiu 1s .5s ease both}
.titulo span{color:#e8475f}
.sep{display:flex;align-items:center;gap:10px;margin:22px auto;width:fit-content;opacity:0;animation:subiu 1s .7s ease both}
.sep-l{width:55px;height:1px;background:linear-gradient(90deg,transparent,#c9a84c)}.sep-r{width:55px;height:1px;background:linear-gradient(270deg,transparent,#c9a84c)}
.texto{font-family:'Playfair Display',serif;font-style:italic;font-size:clamp(.98rem,2.4vw,1.18rem);line-height:1.95;color:#c4a882;margin-bottom:28px;opacity:0;animation:subiu 1s .9s ease both}
.texto strong{color:#f0e6d3;font-style:normal;font-weight:600}
.citacao{font-family:'Cormorant Garamond',serif;font-size:1.04rem;font-style:italic;color:rgba(201,168,76,.85);border-left:2px solid #8b0000;padding:12px 0 12px 18px;text-align:left;margin:26px 0;opacity:0;animation:subiu 1s 1.1s ease both}

@keyframes subiu{from{opacity:0;transform:translateY(18px)}to{opacity:1;transform:translateY(0)}}

/* ── BOTÕES ── */
.btns{display:flex;gap:16px;justify-content:center;flex-wrap:wrap;margin-top:36px;opacity:0;animation:subiu 1s 1.3s ease both}
.btn{font-family:'Cinzel Decorative',cursive;font-size:.68rem;letter-spacing:.1em;padding:15px 34px;border:none;cursor:pointer;position:relative;overflow:hidden;transition:all .35s ease;text-transform:uppercase}
.btn-sim{background:linear-gradient(135deg,#7a0000,#b01c28);color:#fff;box-shadow:0 0 28px rgba(130,0,0,.5)}
.btn-sim::after{content:'';position:absolute;inset:0;background:linear-gradient(135deg,#b01c28,#e8475f);opacity:0;transition:opacity .35s}
.btn-sim:hover::after{opacity:1}.btn-sim:hover{transform:translateY(-3px);box-shadow:0 10px 38px rgba(200,50,70,.6)}
.btn-sim span{position:relative;z-index:1}
.btn-nao{background:transparent;color:#c4a882;border:1px solid rgba(201,168,76,.3);transition:all .3s}
.btn-nao:hover{border-color:#c9a84c;color:#c9a84c}

/* ── TELA SIM ── */
#sim{display:none;position:fixed;inset:0;z-index:200;background:rgba(4,0,8,.96);align-items:center;justify-content:center;flex-direction:column;animation:fade .7s ease both}
#sim.show{display:flex}
.sim-box{text-align:center;padding:40px;animation:surgir 1s ease both}
.coracao{font-size:5.5rem;display:block;margin-bottom:18px;animation:bater 1.1s ease infinite}
@keyframes bater{0%,100%{transform:scale(1)}50%{transform:scale(1.18)}}
.sim-tit{font-family:'Cinzel Decorative',cursive;font-size:clamp(1.8rem,5vw,3rem);color:#e8475f;text-shadow:0 0 60px rgba(232,71,95,.9);margin-bottom:14px}
.sim-sub{font-family:'Playfair Display',serif;font-style:italic;font-size:1.18rem;color:#c4a882;max-width:460px;line-height:1.8}
.sim-icons{margin-top:22px;font-size:2.2rem;letter-spacing:10px;animation:bater 1.1s ease infinite}

/* ── BOTÃO ÁUDIO ── */
#audio-btn{position:fixed;bottom:26px;right:26px;z-index:300;width:50px;height:50px;border-radius:50%;background:rgba(120,0,0,.88);border:1px solid #c9a84c;color:#c9a84c;font-size:1.2rem;cursor:pointer;transition:all .3s;display:flex;align-items:center;justify-content:center;box-shadow:0 0 18px rgba(120,0,0,.5)}
#audio-btn:hover{background:#8b0000;transform:scale(1.1)}

/* Anéis de brilho */
.ring{position:absolute;border-radius:50%;border:1px solid rgba(130,0,0,.12);top:50%;left:50%;transform:translate(-50%,-50%);animation:anel 4s ease infinite;pointer-events:none}
.ring:nth-child(1){width:420px;height:420px}.ring:nth-child(2){width:640px;height:640px;animation-delay:2s}
@keyframes anel{0%,100%{opacity:.5;transform:translate(-50%,-50%) scale(1)}50%{opacity:0;transform:translate(-50%,-50%) scale(1.07)}}

@keyframes fade{from{opacity:0}to{opacity:1}}

@media(max-width:520px){.card{padding:38px 22px}.btns{flex-direction:column;align-items:center}.btn{width:100%}}
</style>
</head>
<body>

<!-- MÚSICA -->
<audio id="musica" loop>
  <source src="https://www.soundhelix.com/examples/mp3/SoundHelix-Song-1.mp3" type="audio/mp3">
</audio>

<!-- ═══════════════════════════════════════════
     CENA DE FUNDO: Damon & Elena (arte SVG)
     ═══════════════════════════════════════════ -->
<div class="scene">
<svg viewBox="0 0 1200 800" preserveAspectRatio="xMidYMid slice" xmlns="http://www.w3.org/2000/svg">
  <defs>
    <radialGradient id="ceu" cx="50%" cy="30%" r="70%">
      <stop offset="0%" stop-color="#1a0830"/>
      <stop offset="40%" stop-color="#0d041a"/>
      <stop offset="100%" stop-color="#040008"/>
    </radialGradient>
    <radialGradient id="lua-brilho" cx="50%" cy="50%" r="50%">
      <stop offset="0%" stop-color="#fffbe0" stop-opacity="1"/>
      <stop offset="60%" stop-color="#f5d87a" stop-opacity=".6"/>
      <stop offset="100%" stop-color="#c9a84c" stop-opacity="0"/>
    </radialGradient>
    <radialGradient id="chao" cx="50%" cy="0%" r="100%">
      <stop offset="0%" stop-color="#2a0010"/>
      <stop offset="100%" stop-color="#06010d"/>
    </radialGradient>
    <filter id="glow-lua">
      <feGaussianBlur stdDeviation="14" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <filter id="glow-fig">
      <feGaussianBlur stdDeviation="5" result="blur"/>
      <feMerge><feMergeNode in="blur"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
    <clipPath id="clip-cena">
      <rect width="1200" height="800"/>
    </clipPath>
  </defs>

  <g clip-path="url(#clip-cena)">

  <!-- Céu -->
  <rect width="1200" height="800" fill="url(#ceu)"/>

  <!-- Estrelas -->
  <g opacity=".9">
    <circle cx="80" cy="60" r="1.2" fill="#fff" opacity=".9"/>
    <circle cx="160" cy="35" r=".8" fill="#fff" opacity=".7"/>
    <circle cx="240" cy="90" r="1.4" fill="#fff"/>
    <circle cx="320" cy="45" r=".9" fill="#fff" opacity=".8"/>
    <circle cx="420" cy="20" r="1.1" fill="#fff" opacity=".85"/>
    <circle cx="500" cy="70" r=".7" fill="#fff" opacity=".6"/>
    <circle cx="580" cy="30" r="1.3" fill="#fff"/>
    <circle cx="660" cy="55" r=".8" fill="#fff" opacity=".75"/>
    <circle cx="750" cy="25" r="1.0" fill="#fff" opacity=".9"/>
    <circle cx="840" cy="80" r=".9" fill="#fff" opacity=".7"/>
    <circle cx="920" cy="40" r="1.2" fill="#fff"/>
    <circle cx="1000" cy="65" r=".7" fill="#fff" opacity=".65"/>
    <circle cx="1080" cy="30" r="1.1" fill="#fff" opacity=".85"/>
    <circle cx="1150" cy="55" r=".8" fill="#fff" opacity=".7"/>
    <circle cx="130" cy="130" r=".7" fill="#fff" opacity=".5"/>
    <circle cx="350" cy="110" r="1.0" fill="#fff" opacity=".6"/>
    <circle cx="700" cy="100" r=".9" fill="#fff" opacity=".55"/>
    <circle cx="950" cy="115" r=".8" fill="#fff" opacity=".6"/>
    <circle cx="1100" cy="95" r="1.1" fill="#fff" opacity=".7"/>
    <circle cx="50"  cy="160" r=".6" fill="#fff" opacity=".4"/>
    <circle cx="200" cy="175" r=".8" fill="#fff" opacity=".5"/>
    <circle cx="460" cy="155" r=".7" fill="#fff" opacity=".45"/>
    <circle cx="800" cy="145" r=".9" fill="#fff" opacity=".5"/>
    <circle cx="1030" cy="170" r=".6" fill="#fff" opacity=".4"/>
  </g>

  <!-- Lua cheia com brilho -->
  <circle cx="600" cy="160" r="90" fill="url(#lua-brilho)" filter="url(#glow-lua)" opacity=".85"/>
  <circle cx="600" cy="160" r="65" fill="#fff9e0" opacity=".92"/>
  <!-- Crateras suaves -->
  <circle cx="575" cy="145" r="10" fill="#ede4b0" opacity=".35"/>
  <circle cx="618" cy="170" r="7" fill="#ede4b0" opacity=".3"/>
  <circle cx="598" cy="188" r="5" fill="#ede4b0" opacity=".25"/>

  <!-- Reflexo da lua no chão -->
  <ellipse cx="600" cy="760" rx="120" ry="18" fill="#c9a84c" opacity=".08"/>

  <!-- Floresta / árvores góticas (fundo) -->
  <!-- Árvore 1 -->
  <g fill="#0f0418" opacity=".85">
    <path d="M60 800 L70 680 L55 660 L75 640 L62 615 L80 595 L68 570 L90 550 L78 525 L98 505 L110 505 L120 525 L108 550 L128 570 L116 595 L134 615 L120 640 L137 660 L122 680 L130 800 Z"/>
    <!-- Galhos esquerda -->
    <path d="M78 600 Q40 580 20 560 Q45 570 68 588 Z"/>
    <path d="M72 635 Q25 615 5 595 Q35 610 65 628 Z"/>
    <path d="M88 565 Q60 540 45 515 Q68 535 85 558 Z"/>
    <!-- Galhos direita -->
    <path d="M118 600 Q156 580 176 560 Q151 570 128 588 Z"/>
    <path d="M124 635 Q171 615 191 595 Q161 610 131 628 Z"/>
    <path d="M108 565 Q136 540 151 515 Q128 535 111 558 Z"/>
  </g>

  <!-- Árvore 2 esq -->
  <g fill="#0d0316" opacity=".75">
    <path d="M0 800 L8 700 L-2 685 L10 668 L2 648 L16 630 L8 610 L24 592 L16 572 L32 554 L44 554 L54 572 L44 592 L60 610 L50 630 L65 648 L55 668 L68 685 L56 700 L62 800 Z"/>
    <path d="M16 640 Q-20 620 -40 600 Q-10 618 10 635 Z" opacity=".7"/>
    <path d="M52 640 Q80 618 100 600 Q72 618 58 635 Z" opacity=".7"/>
  </g>

  <!-- Árvore 3 direita -->
  <g fill="#0e0318" opacity=".8">
    <path d="M1100 800 L1108 695 L1096 678 L1112 660 L1100 638 L1118 618 L1106 596 L1126 576 L1114 554 L1134 534 L1148 534 L1158 554 L1146 576 L1162 596 L1150 618 L1168 638 L1154 660 L1170 678 L1156 695 L1164 800 Z"/>
    <path d="M1108 640 Q1068 618 1048 598 Q1078 616 1102 636 Z" opacity=".7"/>
    <path d="M1154 640 Q1192 618 1212 598 Q1184 616 1160 636 Z" opacity=".7"/>
  </g>

  <!-- Árvore 4 extrema direita -->
  <g fill="#0a0212" opacity=".7">
    <path d="M1170 800 L1176 720 L1168 706 L1178 692 L1170 675 L1182 660 L1174 644 L1188 628 L1180 612 L1194 597 L1204 597 L1212 612 L1204 628 L1218 644 L1208 660 L1222 675 L1212 692 L1224 706 L1212 720 L1218 800 Z"/>
  </g>

  <!-- Névoa no chão -->
  <ellipse cx="600" cy="800" rx="700" ry="80" fill="#1a0828" opacity=".7"/>
  <ellipse cx="200" cy="790" rx="300" ry="50" fill="#200530" opacity=".5"/>
  <ellipse cx="1000" cy="790" rx="300" ry="50" fill="#200530" opacity=".5"/>

  <!-- CHÃO -->
  <path d="M0 750 Q300 740 600 755 Q900 770 1200 748 L1200 800 L0 800 Z" fill="url(#chao)"/>

  <!-- ══════════════════════════════════
       FIGURAS: DAMON e ELENA
       Silhuetas detalhadas e românticas
       ══════════════════════════════════ -->

  <!-- Sombra das figuras -->
  <ellipse cx="580" cy="756" rx="120" ry="12" fill="#000" opacity=".45"/>

  <!-- ── ELENA (esquerda) – silhueta feminina elegante ── -->
  <g filter="url(#glow-fig)" opacity=".95">
    <!-- Vestido longo com fluência -->
    <path d="
      M460 758
      Q445 720 438 680 Q432 640 440 600
      Q448 560 452 520
      L458 480 L462 450
      Q466 430 468 410
      Q478 390 490 390
      Q505 388 516 398
      Q522 410 524 430
      Q526 452 524 475
      L520 505 L518 530
      Q522 565 525 600
      Q530 642 522 685
      Q515 722 508 758
      Z
    " fill="#1a0520"/>
    <!-- Detalhes do corpo -->
    <path d="
      M462 450 Q468 430 490 425 Q510 422 520 438 L518 475
      Q510 465 490 462 Q470 460 462 470 Z
    " fill="#250830"/>
    <!-- Saia esvoaçante esquerda -->
    <path d="
      M440 600 Q420 630 400 660 Q385 690 375 725
      Q395 730 415 720 Q435 700 448 670
      Q455 645 452 620 Z
    " fill="#1a0520"/>
    <!-- Saia esvoaçante direita -->
    <path d="
      M525 600 Q542 630 558 660 Q570 692 575 728
      Q555 730 538 718 Q520 698 512 668
      Q505 645 510 620 Z
    " fill="#1a0520"/>
    <!-- Corpo superior / blusa -->
    <path d="
      M468 395 Q475 378 490 372 Q506 368 516 378
      Q524 390 524 408 L516 410
      Q508 395 490 392 Q472 390 468 405 Z
    " fill="#2a0a38"/>
    <!-- Pescoço -->
    <rect x="484" y="355" width="14" height="22" rx="6" fill="#5c2840"/>
    <!-- Rosto / cabeça (oval feminino delicado) -->
    <ellipse cx="491" cy="330" rx="26" ry="32" fill="#5c2840"/>
    <!-- Cabelo longo oscilando -->
    <path d="
      M465 320 Q450 280 445 240 Q442 200 448 165
      Q455 140 465 130 Q450 155 448 190
      Q445 225 452 265 Q460 300 470 325 Z
    " fill="#1a0520"/>
    <path d="
      M517 320 Q530 285 533 248 Q536 210 528 175
      Q520 148 510 135 Q524 158 528 192
      Q532 228 528 265 Q522 298 516 322 Z
    " fill="#1a0520"/>
    <!-- Topo do cabelo -->
    <path d="M466 302 Q472 270 491 260 Q510 268 516 300 Q508 288 491 285 Q474 288 466 302 Z" fill="#1a0520"/>
    <!-- Braço esquerdo em direção a Damon -->
    <path d="
      M468 420 Q450 430 438 448 Q428 466 432 485
      Q440 496 452 490 Q462 476 466 460
      Q468 445 468 432 Z
    " fill="#5c2840"/>
    <!-- Mão esquerda -->
    <ellipse cx="434" cy="488" rx="10" ry="8" fill="#5c2840"/>
    <!-- Braço direito caído gentilmente -->
    <path d="
      M522 420 Q540 440 545 465 Q548 485 540 498
      Q528 505 520 496 Q515 480 516 460
      Q518 440 520 425 Z
    " fill="#5c2840"/>
    <!-- Detalhe colar / decote -->
    <ellipse cx="491" cy="388" rx="16" ry="5" fill="#3a1248" opacity=".6"/>
  </g>

  <!-- ── DAMON (direita) – silhueta masculina dramática ── -->
  <g filter="url(#glow-fig)" opacity=".95">
    <!-- Casaco / corpo -->
    <path d="
      M610 758
      Q615 718 616 680 Q616 642 612 605
      Q608 565 604 528
      L600 495 L598 465
      Q596 438 596 415
      Q604 395 618 390
      Q634 386 648 395
      Q660 408 660 430
      Q660 455 654 480
      L650 510 L648 540
      Q650 578 648 615
      Q645 655 648 695
      Q650 728 652 758
      Z
    " fill="#0d0218"/>
    <!-- Ombros largos / jaqueta -->
    <path d="
      M585 420 Q570 408 562 420 Q558 435 565 450
      Q575 460 588 455 Q598 448 600 435 Z
    " fill="#150325"/>
    <path d="
      M665 420 Q680 408 688 420 Q692 435 685 450
      Q675 460 662 455 Q652 448 650 435 Z
    " fill="#150325"/>
    <!-- Lapelas do casaco -->
    <path d="M598 415 L610 435 L618 420 L626 435 L634 415 Q628 400 618 395 Q608 393 598 415 Z" fill="#1e0430"/>
    <!-- Gola alta -->
    <rect x="609" y="376" width="30" height="20" rx="5" fill="#1e0430"/>
    <!-- Pescoço -->
    <rect x="614" y="356" width="20" height="24" rx="7" fill="#4a2035"/>
    <!-- Cabeça (oval masculino firme) -->
    <ellipse cx="624" cy="328" rx="28" ry="34" fill="#4a2035"/>
    <!-- Cabelo curto estruturado -->
    <path d="M596 312 Q600 288 610 272 Q618 260 624 258 Q618 262 612 278 Q606 296 600 318 Z" fill="#0d0218"/>
    <path d="M652 312 Q648 288 638 272 Q630 260 624 258 Q630 262 636 278 Q642 296 648 318 Z" fill="#0d0218"/>
    <path d="M600 295 Q610 278 624 274 Q638 278 648 295 Q638 283 624 280 Q610 283 600 295 Z" fill="#0d0218"/>
    <!-- Sobrancelha marcante (detalhe) -->
    <path d="M605 310 Q614 305 622 308" stroke="#0d0218" stroke-width="2.5" fill="none" stroke-linecap="round"/>
    <path d="M626 308 Q634 305 643 310" stroke="#0d0218" stroke-width="2.5" fill="none" stroke-linecap="round"/>
    <!-- Olhos (profundos) -->
    <ellipse cx="612" cy="318" rx="5" ry="4" fill="#0d0218"/>
    <ellipse cx="636" cy="318" rx="5" ry="4" fill="#0d0218"/>
    <!-- Braço esquerdo (alcançando Elena) -->
    <path d="
      M598 430 Q578 445 562 462 Q548 480 546 500
      Q550 514 560 512 Q572 504 580 488
      Q590 468 597 448 Z
    " fill="#4a2035"/>
    <!-- Mão esquerda perto de Elena -->
    <ellipse cx="548" cy="507" rx="11" ry="9" fill="#4a2035"/>
    <!-- Braço direito -->
    <path d="
      M658 430 Q676 452 682 475 Q686 496 678 510
      Q668 518 660 508 Q654 492 652 470 Q651 450 654 435 Z
    " fill="#4a2035"/>
    <!-- Calça / pernas -->
    <path d="M600 640 Q595 695 592 758 L613 758 L618 640 Z" fill="#0d0218"/>
    <path d="M648 640 Q652 695 655 758 L634 758 L630 640 Z" fill="#0d0218"/>
  </g>

  <!-- Mãos se tocando / entrelaçadas -->
  <g opacity=".9">
    <ellipse cx="540" cy="505" rx="15" ry="10" fill="#5c2840" transform="rotate(-12,540,505)"/>
    <ellipse cx="555" cy="500" rx="15" ry="10" fill="#4a2035" transform="rotate(8,555,500)"/>
    <!-- Detalhe dos dedos -->
    <path d="M530 500 Q538 494 548 497" stroke="#4a2035" stroke-width="2.5" fill="none" stroke-linecap="round"/>
    <path d="M560 496 Q568 490 574 494" stroke="#5c2840" stroke-width="2.5" fill="none" stroke-linecap="round"/>
  </g>

  <!-- Rosa negra no chão -->
  <g transform="translate(490,720)" opacity=".7">
    <circle cx="0" cy="0" r="12" fill="#3a0015"/>
    <circle cx="0" cy="0" r="8" fill="#5a0020"/>
    <circle cx="0" cy="0" r="4" fill="#8b0030"/>
    <path d="M0 12 L-2 35" stroke="#2a0010" stroke-width="2"/>
    <!-- espinhos -->
    <path d="M-2 20 L-8 17" stroke="#2a0010" stroke-width="1.5"/>
    <path d="M-2 26 L6 23" stroke="#2a0010" stroke-width="1.5"/>
  </g>

  <!-- Pétalas de rosa no chão -->
  <ellipse cx="460" cy="745" rx="6" ry="3" fill="#5a0020" opacity=".5" transform="rotate(-25,460,745)"/>
  <ellipse cx="530" cy="750" rx="5" ry="2.5" fill="#5a0020" opacity=".4" transform="rotate(15,530,750)"/>
  <ellipse cx="625" cy="748" rx="4" ry="2" fill="#5a0020" opacity=".45" transform="rotate(-10,625,748)"/>

  <!-- Velas (decoração) -->
  <g opacity=".6">
    <!-- Vela esquerda -->
    <rect x="340" y="700" width="8" height="45" fill="#ede4c0" rx="2"/>
    <ellipse cx="344" cy="698" rx="5" ry="8" fill="#f5c842" opacity=".8"/>
    <ellipse cx="344" cy="695" rx="2" ry="4" fill="#fff" opacity=".9"/>
    <!-- Reflexo chão vela esq -->
    <ellipse cx="344" cy="746" rx="12" ry="3" fill="#f5c842" opacity=".12"/>
    <!-- Vela direita -->
    <rect x="850" y="705" width="8" height="40" fill="#ede4c0" rx="2"/>
    <ellipse cx="854" cy="703" rx="5" ry="8" fill="#f5c842" opacity=".8"/>
    <ellipse cx="854" cy="700" rx="2" ry="4" fill="#fff" opacity=".9"/>
    <ellipse cx="854" cy="746" rx="12" ry="3" fill="#f5c842" opacity=".12"/>
  </g>

  <!-- Névoa rasteira final -->
  <ellipse cx="600" cy="780" rx="650" ry="45" fill="#12022a" opacity=".55"/>

  </g><!-- fim clip -->
</svg>
</div>

<!-- Névoa overlay -->
<div class="fog"></div>

<!-- Pétalas flutuantes -->
<div class="petals" id="petals"></div>
<div class="sparks" id="sparks"></div>

<!-- ═══════════════════
     CARD CENTRAL
     ═══════════════════ -->
<div class="wrapper" id="mainPage">
  <div class="ring"></div>
  <div class="ring"></div>

  <div class="card">

    <!-- Cantos -->
    <div class="c tl"><svg viewBox="0 0 26 26" fill="none"><path d="M1 25V1h24" stroke="#c9a84c" stroke-width="1.4"/><circle cx="1" cy="1" r="2" fill="#c9a84c"/></svg></div>
    <div class="c tr"><svg viewBox="0 0 26 26" fill="none"><path d="M1 25V1h24" stroke="#c9a84c" stroke-width="1.4"/><circle cx="1" cy="1" r="2" fill="#c9a84c"/></svg></div>
    <div class="c bl"><svg viewBox="0 0 26 26" fill="none"><path d="M1 25V1h24" stroke="#c9a84c" stroke-width="1.4"/><circle cx="1" cy="1" r="2" fill="#c9a84c"/></svg></div>
    <div class="c br"><svg viewBox="0 0 26 26" fill="none"><path d="M1 25V1h24" stroke="#c9a84c" stroke-width="1.4"/><circle cx="1" cy="1" r="2" fill="#c9a84c"/></svg></div>

    <p class="olho">❧ Uma mensagem do coração ❧</p>

    <h1 class="titulo">Você quer ser<br><span>minha namorada?</span></h1>

    <div class="sep">
      <div class="sep-l"></div>
      <span style="color:#c9a84c;font-size:.95rem">🌹</span>
      <div class="sep-r"></div>
    </div>

    <p class="texto">
      Desde o primeiro momento em que te vi,<br>
      soube que algo havia mudado para sempre.<br><br>
      Como Damon olhava para Elena — com uma intensidade<br>
      que transcende o tempo — <strong>é exatamente assim que eu te vejo.</strong><br><br>
      Você torna cada dia mais bonito só por existir nele.
    </p>

    <blockquote class="citacao">
      "Não importa o que aconteça, eu estarei aqui.<br>
      Porque você é a única coisa que faz sentido para mim."
    </blockquote>

    <p class="texto" style="animation-delay:1.1s;font-size:1.08rem;margin-bottom:0">
      Quero ser o teu eterno, o teu lar, o teu ponto seguro.<br>
      <strong>Você me dá essa honra?</strong>
    </p>

    <div class="btns">
      <button class="btn btn-sim" onclick="dizerSim()"><span>🌹 Sim, quero!</span></button>
      <button class="btn btn-nao" id="btnNao" onmouseover="fugir(this)" onclick="tentouNao()">Não</button>
    </div>

  </div>
</div>

<!-- ═══════════════════
     TELA DO SIM
     ═══════════════════ -->
<div id="sim">
  <div class="sim-box">
    <span class="coracao">❤️</span>
    <h2 class="sim-tit">Eu sabia!</h2>
    <p class="sim-sub">
      Como Damon e Elena — duas almas que o destino insistiu em unir —<br><br>
      <em>nós fomos feitos um para o outro.</em><br><br>
      Te amo demais! 🌹🥀
    </p>
    <div class="sim-icons">❤️ 🌹 ❤️ 🌹 ❤️</div>
  </div>
</div>

<!-- Botão Áudio -->
<button id="audio-btn" onclick="alternarAudio()" title="Música">🎵</button>

<script>
// ── PÉTALAS ──
const pc = document.getElementById('petals');
['🌹','🥀','❤️','✨','🌸'].forEach((s,i)=>{
  for(let j=0;j<5;j++){
    const el=document.createElement('div');
    el.className='petal';el.textContent=s;
    el.style.cssText=`left:${Math.random()*100}vw;animation-duration:${8+Math.random()*10}s;animation-delay:${Math.random()*14}s;font-size:${10+Math.random()*12}px`;
    pc.appendChild(el);
  }
});

// ── PARTÍCULAS ──
const sc=document.getElementById('sparks');
for(let i=0;i<28;i++){
  const el=document.createElement('div');
  el.className='spark';const sz=2+Math.random()*3;
  el.style.cssText=`width:${sz}px;height:${sz}px;left:${Math.random()*100}vw;bottom:${Math.random()*25}vh;animation-duration:${5+Math.random()*8}s;animation-delay:${Math.random()*8}s`;
  sc.appendChild(el);
}

// ── ÁUDIO ──
const mus=document.getElementById('musica');let tocando=false;
window.addEventListener('click',function ini(){if(!tocando){mus.play().then(()=>{tocando=true;document.getElementById('audio-btn').textContent='🔊'}).catch(()=>{})}window.removeEventListener('click',ini)},{once:true});
function alternarAudio(){if(tocando){mus.pause();tocando=false;document.getElementById('audio-btn').textContent='🎵'}else{mus.play();tocando=true;document.getElementById('audio-btn').textContent='🔊'}}

// ── BOTÃO NÃO FOGE ──
let fugas=0;
function fugir(btn){
  fugas++;
  if(fugas>6){btn.style.opacity='0.1';btn.style.fontSize='.35rem';return}
  const vw=window.innerWidth,vh=window.innerHeight;
  btn.style.position='fixed';btn.style.zIndex=9999;btn.style.transition='left .2s ease,top .2s ease';
  btn.style.left=Math.random()*(vw-120)+'px';btn.style.top=Math.random()*(vh-60)+'px';
}
function tentouNao(){fugir(document.getElementById('btnNao'))}

// ── SIM ──
function dizerSim(){
  for(let i=0;i<50;i++)setTimeout(explodir,i*70);
  setTimeout(()=>document.getElementById('sim').classList.add('show'),700);
}
function explodir(){
  const h=document.createElement('div');
  h.textContent=['❤️','🌹','✨','💕','🥀'][Math.floor(Math.random()*5)];
  h.style.cssText=`position:fixed;font-size:${1.4+Math.random()*2}rem;pointer-events:none;z-index:9999;left:${Math.random()*100}vw;top:${Math.random()*100}vh;animation:fup 1.8s ease both`;
  document.body.appendChild(h);setTimeout(()=>h.remove(),1800);
}
const stl=document.createElement('style');
stl.textContent='@keyframes fup{from{opacity:1;transform:translateY(0)}to{opacity:0;transform:translateY(-90px)}}';
document.head.appendChild(stl);
</script>
</body>
</html>
