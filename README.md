<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Kartun Muslimah</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Sofia&display=swap" rel="stylesheet">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Handjet:wght@100..900&display=swap" rel="stylesheet">
    <style>
        /* Reset tampilan dasar */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background-color: #03051A;
            position: relative;
        }
        
        .masjid {
          position: absolute;
          top: 50%;
          left: -4%;
          z-index: 1;
        }
        
        .antena {
          position: absolute;
          border-left: 4px solid transparent; 
          border-right: 4px solid transparent;
          border-bottom: 40px solid #FFD700;
          z-index: -5;
        }
        
        .antenatower {
          position: absolute;
          border-left: 4px solid transparent; 
          border-right: 4px solid transparent;
          border-bottom: 40px solid #FFD700;
          z-index: -5;
        }

        .antenatower-kiri {
          top: 62px;
          left: 270px;
        }
        
        .antenatower-kanan {
          top: 62px;
          left: 785px;
        }
        
        .kubahtower {
          position: absolute;
            height: 90px;
            width: 85px;
            border-radius: 500px 500px 0 0;
            background-color: #FCDB9C;
            
            z-index: -1;
        }
        
        .kubahtower-kanan {
          top: 100px;
          left: 746px;
        }
        
        .kubahtower-kiri {
          top: 100px;
          left: 231px;
        }
        
        .bulantower {
          position: absolute;
          width: 25px;
          height: 35px;
          background-color: transparent;
          border-top: 8px solid #FFD700;
          border-radius: 50%;
          transform: rotate(225deg);
        }
        
        .bulantower-kiri {
          top: 39px;
          left: 269px;
        }
        
        .bulantower-kanan{
          top: 39px;
          left: 784px;
        }

        .l1 {
          height: 200px;
          width: 150px;
          position: absolute;
          background-color: #77EC1E;
          
          border-top-right-radius: 7%;
          border-top-left-radius: 7%;
          
        }
        
        .l1-kanan {
          top: 580px;
          left: 715px;
        }
        
        .l1-kiri {
          top: 580px;
          left: 200px;
        }
        
        .l2 {
          height: 200px;
          width: 120px;
          position: absolute;
          background-color: #77EC1E;
          
          
          border-top-right-radius: 7%;
          border-top-left-radius: 7%;
        }
        
        .l2-kanan {
          top: 382px;
          left: 730px;
        }
        
        .l2-kiri {
          top: 382px;
          left: 215px;
        }
        
        .l3 {
          height: 200px;
          width: 90px;
          position: absolute;
          background-color: #77EC1E;
          
          
          border-top-right-radius: 7%;
          border-top-left-radius: 7%;
        }

        .p1 {
          height: 35px;
          width: 160px;
          position: absolute;
          background-color: #135A13;
         
          border-top-left-radius: 10px;
          border-top-right-radius: 10px;
          border-bottom-left-radius: 10px;
          border-bottom-right-radius: 10px;
          
        }
        
        .p1-kanan {
          top: 580px;
          left: 710px;
        }
        
        .p1-kiri {
          top: 580px;
          left: 195px;
          
        }
        
        .p2 {
          height: 35px;
          width: 130px;
          position: absolute;
          background-color: #135A13;
          
          border-top-left-radius: 10px;
          border-top-right-radius: 10px;
          border-bottom-left-radius: 10px;
          border-bottom-right-radius: 10px;
        }
        
        .p2-kanan {
          top: 380px;
          left: 724px;
        }
        
        .p2-kiri {
          top: 380px;
          left: 209px;
        }

        .p3{
          height: 35px;
          width: 100px;
          position: absolute;
          background-color: #135A13;
          
          border-top-left-radius: 10px;
          border-top-right-radius: 10px;
          border-bottom-left-radius: 10px;
          border-bottom-right-radius: 10px;
        }
        
        .p3-kanan {
          top: 152px;
          left: 740px;
        }
        
        .p3-kiri {
          top: 152px;
          left: 225px;
        }
        
        .bagian-depan {
          height: 390px;
          width: 380px;
          background-color: #4D9715;
          border-top-right-radius: 7%;
          border-top-left-radius: 7%;
          position: absolute;
          top: 390px;
          left: 344px;
        }
        
        .antena {
          position: absolute;
          border-left: 8px solid transparent; 
          border-right: 8px solid transparent;
          border-bottom: 50px solid #FFD700;
          top: 194px;
          left: 528px;
        }

        .kubah-depan {
            position: absolute;
            height: 170px;
            width: 340px;
            border-radius: 5000px 5000px 0 0;
            background-color: #F6C974;
            top: 220px;
            left: 362px;
        }
        
        .plafon {
            position: absolute;
            height: 30px;
            width: 400px;
            border-top-left-radius: 10px;
            border-top-right-radius: 10px;
            border-bottom-left-radius: 10px;
            border-bottom-right-radius: 10px;
            background-color: #114211;
            border-bottom: 6px solid #092C09;
            
        }
        
        .plafon-atas {
            width: 420px;
            top: 376px;
            left: 323px;
        }
        
        .plafon-bawah {
            top: 405px;
            left: 333px;
        }
        
        .pintu {
          position: absolute;
          width: 215px;
          height: 295px;
          background-color: #3E5E2C;
          border-top-right-radius: 500px;
          border-top-left-radius: 500px;
          top: 485px;
          left: 425px;
        }
        
        .bulan {
            position: absolute;
            width: 35px;
            height: 50px;
            background-color: transparent;
            border-top: 10px solid #FFD700;
            border-radius: 50%;
            transform: rotate(225deg);
            top: 158px;
            left: 530px;
            
        }
        
        .muslimah {
            position: absolute;
            left: 42.5%;
            top: 80%;
            z-index: 2;
        }
        
        .sepatu {
          position: absolute;
          height: 30px;
          width: 25px;
          background-color: #634620;
          border-radius: 50%;
        }
        
        .sepatu-kiri{
          top: 280px;
          left: 50px;
        }
        
        .sepatu-kanan {
          top: 280px;
          left: 75px;
        }
        
        .rok {
            position: absolute;
            width: 146px;
            height: 110px; 
            background-color: #449BDC;
            clip-path: polygon(0% 100%, 100% 100%, 80% 0%, 20% 0%); 
            border-radius: 40%;
            top: 192px;
            left: 2px;
        }
        
        .baju {
            position: absolute;
            width: 112px;
            height: 86px;
            background-color: #4682B4;
            border-radius: 16%;
            top: 133px;
            left: 19px;
        }

        /* Hijab */
        .hijab {
            position: absolute;
            width: 100px;
            height: 120px;
            background-color: #62BADC;
            border-radius: 50%;
            top: 20px;
            left: 25px;
        }
        
        .hijab-bawah {
          position: absolute;
          width: 146px;
          height: 110px; 
          background-color: #62BADC;
          clip-path: polygon(0% 100%, 100% 100%, 80% 0%, 20% 0%); 
          border-radius: 50%;
          top: 100px;
          left: 2px;
        }

        /* Wajah */
        .wajah {
            position: absolute;
            width: 70px;
            height: 80px;
            background-color: #F9D9C1;
            border-radius: 50%;
            top: 40px;
            left: 40px;
        }

        /* Mata */
        .mata {
            position: absolute;
            width: 8px;
            height: 12px;
            background-color: black;
            border-radius: 50%;
        }

        .mata-kiri {
            top: 66px;
            left: 55px;
        }

        .mata-kanan {
            top: 66px;
            left: 85px;
        }
        
        .binar {
            position: absolute;
            width: 4.5px;
            height: 6.5px;
            background-color: whitesmoke;
            border-radius: 50%;
        }
        
        .binar-kiri {
            top: 66px;
            left: 55px;
        }
        
        .binar-kanan {
            top: 66px;
            left: 85px;
        }
        
        .binarbwh {
            position: absolute;
            width: 4px;
            height: 4px;
            background-color: white;
            border-radius: 50%;
        }
        
        .binarbwh-kiri {
            top: 72px;
            left: 58px;
        }
        
        .binarbwh-kanan {
            top: 72px;
            left: 88px;
        }
        
        .alis {
            position: absolute;
            width: 13px;
            height: 7.5px;
            background-color: transparent;
            border-top: 1px solid black;
            border-radius: 50%;
            
        }
        
        .alis-kiri {
            transform: rotate(-14deg);
            top: 58px;
            left: 50px;
        }
       
        .alis-kanan {
            transform: rotate(14deg);
            top: 58px;
            left: 84px;
        }
        
        .mulut {
            position: absolute;
            height: 14px;
            width: 24px;
            border-radius: 50px 50px 5px 5px;
            background: indianred;
            transform: rotate(-180deg);
            top: 93.2px;
            left: 63px;
        }
        
        .blush {
            position: absolute;
            width: 14px;
            height: 8px;
            border-radius: 50%;
            background-color: lightpink;
        }
        
        .blush-kanan {
            top: 86px;
            left: 95px;
        }
        
        .blush-kiri {
            top: 86px;
            left: 40.8px;
        }
      
        .lengan {
            position: absolute;
            width: 50px;
            height: 34px;
            border-top-left-radius: 50%;
            border-bottom-left-radius: 50%;
            border-top-right-radius: 25%;
            border-bottom-right-radius: 25%;
            background-color: #4682B4;
        }
        
        .lengan-kiri {
            transform: rotate(-25deg);
            top: 145px;
            left: 16.5px;
        }
        
        .lengan-kanan {
            transform: rotate(-155deg);
            top: 145px;
            left: 86px;
        }
        
        .tangan {
          position: absolute;
          width: 15px;
          height: 40px;
          border-radius: 50%;
          background-color: #F9D9C1;
          
        }
        
        .tangan-kiri {
          top: 126px;
          left: 63px;
          transform: rotate(13deg);
        }
        
        .tangan-kanan {
          top: 126px;
          left: 74px;
          transform: rotate(-13deg);
        }
        
        .batu {
          position: absolute ;
          
          background: linear-gradient(white,  #2F313C); /* Standard syntax */
	        background: -webkit-linear-gradient(grey, #2F313C); /* For Safari 5.1 to 6.0 */
	        background: -o-linear-gradient(grey, #2F313C); /* For Opera 11.1 to 12.0 */
	        background: -moz-linear-gradient(grey, #2F313C); /* For Firefox 3.6 to 15 */
	        border-radius: 500px 500px 150px 150px;
	        z-index: 2;
        }

         .batu1 {
          top: 85.5%;
          left: 12%;
          height: 50px;
          width: 90px;
        }
        
        .batu2 {
          top: 86%;
          left: 17%;
          height: 40px;
          width: 80px;
          
        }
        
        .batu3 {
          top: 88.3%;
          left: 3%;
          height: 40px;
          width: 80px;
        }
        
        .batu4 {
          top: 85.5%;
          left: 69%;
          height: 50px;
          width: 90px;
        }
        
        .batu5 {
          top: 90%;
          left: 85%;
          height: 30px;
          width: 70px;
        }
        
        .grass-container {
          position: absolute;
          top: 82%;
          left: 0%;
          display: flex;
          justify-content: center;
          align-items: flex-end;
          z-index: 1;
         
        }

        .grass-container2 {
          position: absolute;
          top: 82%;
          left: 60%;
          display: flex;
          justify-content: center;
          align-items: flex-end;
          z-index: 1;
         
        }

        .grass-blade {
          width: 20px;
          height: 70px;
          background: linear-gradient(to top, #006400, #32CD32); /* Gradasi hijau daun */
          border-radius: 50%;
          clip-path: polygon(50% 0%, 100% 100%, 0% 100%);
          transform-origin: bottom;
          animation: sway 2s infinite ease-in-out alternate;
          box-shadow: 2px 2px 5px rgba(0, 0, 0, 0.2);
        }

        /* Variasi tinggi dan animasi rumput */
        .grass-blade:nth-child(odd) {
          height: 70px;
          width: 40px;
          animation-duration: 2.5s;
          
        }
        

        .grass-blade:nth-child(even) {
          
          height: 110px;
          width: 50px;
          animation-duration: 2s;
        }

        /* Animasi goyangan rumput */
        @keyframes sway {
          0% { transform: rotate(-20deg); }
            100% { transform: rotate(20deg); }
        }
        
        .jalan {
          width: 1000px;
          height: 500px;
          background: linear-gradient(black,  grey); /* Standard syntax */
	        background: -webkit-linear-gradient(black, #5E5F6B); /* For Safari 5.1 to 6.0 */
	        background: -o-linear-gradient(black, black); /* For Opera 11.1 to 12.0 */
	        background: -moz-linear-gradient(black, black); /* For Firefox 3.6 to 15 */
          position: absolute;
          top: 85%;
        }
        
        .cloud {
            position:absolute;
            width: 120px;
            height: 60px;
            background: ghostwhite; /* Warna kuning emas */
            border-radius: 50px;
            animation: moveCloud 10s linear infinite;
        }

        .cloud1 {
          width: 200px;
          height: 120px;
          border-radius: 100px;
        }

        .cloud3 {
          width: 140px;
          height: 80px;
        }

        .cloud::before,
        .cloud::after {
            content: '';
            position: absolute;
            background: ghostwhite;
            border-radius: 50%;
        }

        .cloud::before {
            width: 80px;
            height: 80px;
            top: -30px;
            left: 20px;
        }

        .cloud::after {
            width: 90px;
            height: 90px;
            top: -20px;
            left: 60px;
        }

        /* Posisi awal awan */
        .cloud1 { top: 40%; left: -350px; animation-delay: 0s; }
        .cloud2 { top: 50%; left: -300px; animation-delay: 8s; }
        .cloud3 { top: 70%; left: -350px; animation-delay: 4s; }

        /* Animasi awan bergerak ke kanan dan kembali ke kiri */
        @keyframes moveCloud {
            0% { transform: translateX(150px); }
            100% { transform: translateX(130vw); }
        }

        .awan {
          opacity: 70%;
        }
          
        .star {
          position: absolute;
          top: 0%;
          left: 10%;
          width: 2px;
          height: 2px;
          background-color: #FCE38A;
          border-radius: 50%;
          animation: twinkle 1.5s infinite ease-in-out;
          opacity: 0; /* Bintang mulai dengan opasitas 0 */
          z-index: -1;
        }   

    /* Membuat animasi untuk efek berkedip */
        @keyframes twinkle {
          0% {
            opacity: 0; /* Bintang mulai tidak terlihat */
          }
          50% {
            opacity: 1; /* Bintang muncul */
          }
          100% {
            opacity: 0; /* Bintang menghilang */
          }
        }

    /* Mengatur posisi acak bintang */
        .star:nth-child(odd) {
          width: 2px;
          height: 2px;
          animation-duration: 2s;
          animation-delay: 0.5s;
        }

        .star:nth-child(even) {
          animation-duration: 2.5s;
          animation-delay: 1s;
        }
        
        .judul {
          position: absolute;
          top: 200px;
          left: 260px;
        }
        
        .judul1 {
          position: absolute;
          top: -50px;
          left: 0px;
          font-family: 'Sofia', cursive;
          font-size: 160px;
          font-weight: bold;
          background: linear-gradient(to right, #AE8625, #F7EF8A , #D2AC47, #EDC967);
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
          background-size: 300% 300%;
          animation: shine 1.5s linear infinite;
          
        }
        
        .judul2 {
          position: absolute;
          font-weight: bold;
          top: 133px;
          left: -110px;
          font-family: 'Sofia', cursive;
          font-size: 120px;
          background: linear-gradient(to right, #AE8625, #F7EF8A, #D2AC47, #EDC967);
          -webkit-background-clip: text;
          -webkit-text-fill-color: transparent;
          animation: shine 1.5s linear infinite;
          background-size: 300% 300%;
        }
        @keyframes shine {
            0% { background-position: 0% 50%; }
            100% { background-position: 100% 50%; }
        }
        
        .dialog {
          position: absolute;
          top: 83.2%;
          left: 62%;
          color: black;
          font-size: 33px;
          z-index: +8;
          font-family: 'Handjet', cursive;
        }
        
        .speech-bubble {
            width: 340px;
            height: 60px;
            background: white; /* Warna latar */
            position: absolute;
            top: 82.3%;
            left: 60%;
            z-index: +7;
        }
          
          /* Panah */
        .speech-bubble::before {
            content: "";
            position: absolute;
            left: -19px; /* Atur posisi panah */
            top: 41px;
            width: 0;
            height: 0;
            border-top: 19px solid transparent;""
            border-bottom: 20px solid transparent;
            border-right: 20px solid white; /* Warna sama dengan latar */
        }
        
        .p {
            position: absolute;
            top: 30%;
            font-family: 'Handjet', cursive;
            font-size: 27px;
             /* Gradasi warna lembut */
            color: white; /* Warna teks yang nyaman dibaca */
            text-align: center;
            padding: 15px 20px; /* Ruang yang lebih nyaman */
            margin: 30px auto; /* Tengah secara horizontal */
            max-width: 620px; /* Lebar maksimal untuk keterbacaan */
            line-height: 1.8; /* Jarak antar baris lebih enak dibaca */
            letter-spacing: 1px; /* Spasi antar huruf agar lebih elegan */
        }
        
        /* Efek hover agar lebih interaktif */
       
        .bintang {
            position: absolute;
            width: 50px;
            height: 50px;
            background: radial-gradient(circle, rgba(255,255,200,0.9) 20%, rgba(255,255,0,0.5) 80%);
            clip-path: polygon(50% 0%, 60% 40%, 100% 50%, 60% 60%, 50% 100%, 40% 60%, 0% 50%, 40% 40%);
            animation: kelapKelip 2s infinite alternate ease-in-out;
            filter: drop-shadow(0 0 10px rgba(255, 255, 100, 0.8));
        }

        @keyframes kelapKelip {
            0% {
                opacity: 0.5;
                transform: scale(0.9);
                filter: drop-shadow(0 0 5px rgba(255, 255, 100, 0.5));
            }
            50% {
                opacity: 1;
                transform: scale(1.2);
                filter: drop-shadow(0 0 15px rgba(255, 255, 100, 1));
            }
            100% {
                opacity: 0.5;
                transform: scale(0.9);
                filter: drop-shadow(0 0 5px rgba(255, 255, 100, 0.5));
            } 
        }

        /* Tambahkan beberap
        a bintang */
        .bintang:nth-child(2) { top: 17%; left: 12%; animation-delay: 0.5s; }
        .bintang:nth-child(3) { top: 20%; left: 7%; animation-delay: 1s; }
        .bintang:nth-child(4) { top: 7%; left: 74%; animation-delay: 1.5s; }
        .bintang:nth-child(5) { top: 19%; left: 85%; animation-delay: 2s; }
        
        .bintang:nth-child(1) { top: 10%; left: 23%; animation-delay: 2s; }
        
        
        
    </style>
</head>
<body>

    <div class="bintang"></div>
    <div class="bintang"></div>
    <div class="bintang"></div>
    <div class="bintang"></div>
    <div class="bintang"></div>

    <div class="p">"Tak ada kata seindah doa, tak ada perbuatan seindah memaafkan. Di hari yang suci ini, saya dan keluarga memohon maaf atas segala salah. Selamat Idul Fitri 1446 H, mohon maaf lahir dan batin."</div>

    <div class="dialog"> .تَقَبَّلَ اللَّهُ مِنَّا وَمِنْكُمْ</div>
  
    <div class="speech-bubble"></div>
  
    <div class="judul">
      <div class="judul1">Happy</div>
      <div class="judul2">Eid&nbsp;Mubarak</div>
    </div>
    
    <div class="muslimah">
        <div class="sepatu sepatu-kiri"></div>
        <div class="sepatu sepatu-kanan"></div>
        <div class="rok"></div>
        <div class="baju"></div>
        <div class="hijab"></div>
        <div class="hijab-bawah"></div>
        <div class="wajah"></div>
        <div class="mata mata-kiri"></div>
        <div class="mata mata-kanan"></div>
        <div class="binar binar-kiri"></div>
        <div class="binar binar-kanan"></div>
        <div class="binarbwh binarbwh-kiri"></div>
        <div class="binarbwh binarbwh-kanan"></div>
        <div class="alis alis-kiri"></div>
        <div class="alis alis-kanan"></div>
        <div class="mulut"></div>
        <div class="blush blush-kiri"></div>
        <div class="blush blush-kanan"></div>
        <div class="tangan tangan-kiri"></div>
        <div class="tangan tangan-kanan"></div>
        <div class="lengan lengan-kanan"></div>
        <div class="lengan lengan-kiri"></div>
        
    </div>
    
    <div class="batu batu1"></div>
    <div class="batu batu2"></div>
    <div class="batu batu3"></div>
    <div class="batu batu4"></div>
    <div class="batu batu5"></div>
    
    <div class="masjid">
      <div class="bagian-depan"></div>
      <div class="antena"></div>
      <div class="kubah-depan"></div>
      <div class="plafon plafon-atas"></div>
      <div class="plafon plafon-bawah"></div>
      <div class="pintu"></div>
      <div class="bulan"></div>
      <div class="l1 l1-kanan"></div>
      <div class="l1 l1-kiri"></div>
      <div class="l2 l2-kanan"></div>
      <div class="l2 l2-kiri"></div>
      <div class="l3 l3-kanan"></div>
      <div class="l3 l3-kiri"></div>
      <div class="p1 p1-kanan"></div>
      <div class="p1 p1-kiri"></div>
      <div class="p2 p2-kanan"></div>
      <div class="p2 p2-kiri"></div>
      <div class="p3 p3-kanan"></div>
      <div class="p3 p3-kiri"></div>
      <div class="kubahtower kubahtower-kanan"></div>
      <div class="kubahtower kubahtower-kiri"></div>
      <div class="antenatower antenatower-kanan"></div>
      <div class="antenatower antenatower-kiri"></div>
      <div class="bulantower bulantower-kanan"></div>
      <div class="bulantower bulantower-kiri"></div>
    </div>
    <div class="grass-container">
  <!-- Menambahkan beberapa bilah rumput -->
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
    </div>
    
    <div class="grass-container2">
  <!-- Menambahkan beberapa bilah rumput -->
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
      <div class="grass-blade"></div>
    </div>
    
    <div class="jalan"></div>
    
    <div class="awan">
      <div class="cloud cloud1"></div>
      <div class="cloud cloud2"></div>
      <div class="cloud cloud3"></div>
    </div>
    
    <div class="star" style="top: 20%; left: 10%"></div>
    <div class="star" style="top: 60%; left: 30%"></div>
    <div class="star" style="top: 10%; left: 70%"></div>
    <div class="star" style="top: 80%; left: 50%"></div>
    <div class="star" style="top: 40%; left: 90%"></div>
    <div class="star" style="top: 90%; left: 15%"></div>
    <div class="star" style="top: 30%; left: 80%"></div>
    <div class="star" style="top: 50%; left: 50%"></div>
    <div class="star" style="top: 70%; left: 40%"></div>
    <div class="star" style="top: 20%; left: 20%"></div>
   
    <script>
    // Membuat banyak bintang secara dinamis
      function createStars(num) {
        for (let i = 0; i < num; i++) {
          let star = document.createElement("div");
          star.classList.add("star");
          star.style.top = `${Math.random() * 100}%`;
          star.style.left = `${Math.random() * 100}%`;
          document.body.appendChild(star);
        }
      }

    // Membuat 100 bintang di latar belakang
      createStars(500);
    </script>
    
</body>
</html>
