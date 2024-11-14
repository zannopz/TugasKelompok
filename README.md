<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="Style.css">
    <link rel="stylesheet" href="css/all.css">
    <title>my profile</title>
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css"/>
</head>
<body onload="loader()">
    <div id="Loading"></div>
     <!-----start Hearder section----->
     <div id="hearder"  data-aos="fade-up"
     data-aos-anchor-placement="top-bottom">
        <div class="contenier">
            <nav >
                <img src="img/Lgo.png" alt="logo" class="logo" data-aos="zoom-in">
                <ul id="sidmenu" data-aos="zoom-in">
                    <li><a href="#hearder" >Home</a></li>
                    <li><a href="#about" >Tentang</a></li>
                    <li><a href="#portfolio" >Proses Desain</a></li>
                    <li><a href="#produk">Produk</a></li>
                    <li><a href="#contact">Kontak</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                 </ul>
                 <i class="fa-solid fa-bars" onclick="openmenu()"></i>
              </nav> 
              <div class="hearder-text"  data-aos="fade-right"
              data-aos-offset="300"
              data-aos-easing="ease-in-sine">
                <p>Please Wellcome</p>
                <h5>To Manula</h5>
                <h1>"MANULA"<span>manusia pelupa & pemula</span> <br> Kelompok 4</h1>
              </div>       
            </div>
        </div>
     </div>
      <!-----End Hearder section----->
     
      <!-----start About section----->
      <div id="about"data-aos="fade-up"
      data-aos-anchor-placement="center-bottom">
        <div class="contenier">
            <div class="row">
                <div class="about-col-1">
                  <img src="img/dp.jpeg" data-aos="zoom-in" >  
                </div>
                <div class="about-col-2" data-aos="zoom-in">
                    <h1 class="sub-title">Tentang MANULA</h1>
                    <p>"manula merupakan manusia pelupa dan pemula"</p><p>mungkin berasal dari sudut pandang yang melihat bahwa manula (manusia lanjut usia)</p><p>sering mengalami beberapa perubahan dalam kemampuan kognitif,</p><p>terutama terkait memori atau daya ingat.</p><p>Mereka juga memiliki kemampuan dan wawasan yang sangat berharga</p><p>dan sering menjadi pembimbing bagi generasi yang lebih muda.</p>
                   <div class="tab-titles" data-aos="fade-left">
                    <p class="tab-links active-link " onclick="opentab('skills')">Skills</p>
                    <p class="tab-links" onclick="opentab('experience')">Experience</p>
                    <p class="tab-links" onclick="opentab('education')">Education</p>
                   </div>
                   <div class="tab-contents active-tab" id="skills" data-aos="zoom-in">
                    <ul>
                        <li><span>Komunikasi dan Empati</span><br>Lansia sering memiliki keterampilan komunikasi yang baik dan empati tinggi.</li></p>
                        <li><span>Keterampilan Teknis dan Manual</span><br>Banyak manula yang menguasai keterampilan praktis, seperti kerajinan, pertukangan,<p>memasak, atau berkebun, yang memerlukan ketelitian dan kesabaran.</li></p>
                        <li><span>Kemampuan Mengelola Konflik</span><br>Pengalaman hidup sering membuat manula lebih sabar dan bijak dalam menyelesaikan<p>konflik, baik dalam kehidupan pribadi maupun profesional.</li></p>
                        <li><span>Keterampilan Konsultatif atau Pembimbingan</span><br>Banyak manula memiliki pengalaman sebagai mentor atau pembimbing.</li></p>
                   </div>
                   <div class="tab-contents" id="experience" >
                    <ul>
                        <li><span>Pengalaman Karier dan Kehidupan</span><br>Pengalaman hidup mereka yang luas mencakup berbagai bidang,mulai dari karier,keluarga.</li>
                        <li><span>Pengambilan Keputusan</span><br>Melalui berbagai pengalaman hidup, manula cenderung lebih matang.</li>
                        <li><span>Pengetahuan Budaya dan Tradisi</span><br>Manula sering memiliki pengetahuan mendalam tentang budaya,sejarah,tradisi.</li>
                    </ul>
                   </div>
                   <div class="tab-contents" id="education">
                    <ul>
                        <li><span>Pendidikan Formal dan Non-Formal</span><br>Banyak manula memiliki latar belakang pendidikan yang baik.</li>
                        <li><span>Kesediaan untuk Terus Belajar</span><br>Meskipun mungkin lebih lambat dalam mengadopsi teknologi baru.</li>
                        <li><span>Penguasaan Nilai dan Etika</span><br>Pendidikan yang mereka peroleh tentang etika, moral, dan tata krama.</li>
                    </ul>
                   </div>
                </div>
            </div>
        </div>
      </div>
      <!-----End About section----->

        <!----portfolio section Start ----->

        <div id="portfolio">
            <div class="contenier">
                <h1 class="sub-title">PROSES DESAIN</h1>
                <p>Proses desain adalah fondasi yang menjadi dasar setiap produk.</p>
                <div class="work-list" >
                    <div class="work" data-aos="zoom-in">
                        <img src="img/cat1.jpeg" >
                        <div class="layer">
                            <h3>kucing</h3>
                            <p>KUCING LUCU DAN MENGGEMASKAN</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                        
                    </div>
                    <div class="work" data-aos="zoom-in">
                        <img src="img/cat3.jpeg" >
                        <div class="layer">
                            <h3>kucing</h3>
                            <p>KUCING LUCU DAN MENGGEMASKAN</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                        
                    </div>
                    <div class="work" data-aos="zoom-in">
                        <img src="img/cat2.jpeg" >
                        <div class="layer">
                            <h3>kucing</h3>
                            <p>KUCING LUCU DAN MENGGEMASKAN</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                    </div>         
                </div>                
            </div>
        </div>
        <div id="portfolio">
            <div class="contenier">
                <div class="work-list">
                    <div class="work" data-aos="zoom-in">
                        <img src="img/cat4.jpeg" >
                        <div class="layer">
                            <h3>kucing</h3>
                            <p>KUCING LUCU DAN MENGGEMASKAN</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                        
                    </div>
                    <div class="work" data-aos="zoom-in">
                        <img src="img/cat5.jpeg" >
                        <div class="layer">
                            <h3>kucing</h3>
                            <p>KUCING LUCU DAN MENGGEMASKAN</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                        
                    </div>
                    <div class="work" data-aos="zoom-in">
                        <img src="img/cat6.jpeg" >
                        <div class="layer">
                            <h3>kucing</h3>
                            <p>KUCING LUCU DAN MENGGEMASKAN</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>             
                    </div>                   
                </div>
                <a href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327" class="btn">Random Aja</a>
            </div>
        </div>
         <!----portfolio section End ----->
       
         <div id="produk"></div>
            <div class="contenier">
                <h1 class="sub-title">PRODUK</h1>
                <p>Usaha kreatif akan mengungkap bakat dan komitmen seseorang.</p>
                <div class="work-list">
                    <div class="work" data-aos="zoom-in">
                        <img src="img/produk1.jpeg" >
                        <div class="layer">
                            <h3>MINUMAN</h3>
                            <p>Seger dan enak banget pokoknya</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                        
                    </div>
                    <div class="work" data-aos="zoom-in">
                        <img src="img/produk3.jpeg" >
                        <div class="layer">
                            <h3>MINUMAN</h3>
                            <p>Seger dan enak banget pokoknya</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>
                        
                    </div>
                    <div class="work" data-aos="zoom-in">
                        <img src="img/produk2.jpeg" >
                        <div class="layer">
                            <h3>MINUMAN</h3>
                            <p>Seger dan enak banget pokoknya</p>
                            <a target="_blank"  href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-solid fa-up-right-from-square"></i></a>
                        </div>             
                    </div>                   
                </div>
                <a href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327" class="btn">Random Aja</a>

            </div>
        </div>

         
          <!----Contact section Start ----->
          <div id="contact"  >
            <div class="contenier">
                <div class="row">
                    <div class="contact-left"  data-aos="fade-up-right">
                        <h1 class="sub-title">Kontak Kami</h1>
                        <p><i class="fa-solid fa-paper-plane"></i>MANULA@gmail.com</p>
                        <p><i class="fa-solid fa-square-phone-flip"></i>08888888889*</p>
                        <div class="social-icons" data-aos="zoom-in">
            
                            <a target="_blank" class="instagram" href="https://www.instagram.com/shanazalf/"><i class="fa-brands fa-square-instagram"></i></a>
                            <a target="_blank" class="tiktok" href="https://www.tiktok.com/@chloenfreya/video/7435280128327896327"><i class="fa-brands fa-tiktok"></i></a>
                            <a target="_blank" class="github" href="https://github.com/zannopz?tab=repositories"><i class="fa-brands fa-github"></i></a>
                            <a target="_blank" class="linkedin" href=""><i class="fa-brands fa-linkedin"></i></a>
                        </div>
                        <a href="" class="btn btn2">Lihat Resume</a>

                    </div>
                    <div class="contact-right" data-aos="fade-up-left">
                        <form >
                            <input type="text" name="Name" placeholder="Nama" required>
                            <input type="Email" name="Email" placeholder="Gmail" required>
                            <textarea name="massage" rows="6" placeholder="Pesan"></textarea>
                            <button type="submit" class="btn btn2">Kirim</button>
                        </form>
                    </div>
                </div>
            </div>
            <div class="copyright">
                <p>Copyright@ KELOMPOK 4 <i class="fa-solid fa-heart"></i> TUGAS website PROJECT kelompok kami</p>
                <p>💓THANK YOU AND NAMA KELOMPOK KAMI🌻</p>
            </div>
          </div>
          <!----Contact section End ----->
          <script>
            var preloader = document.getElementById("Loading");
            function loader(){
              preloader.style.display = 'none';
            }
          </script>

      <script>
        var tablinks = document.getElementsByClassName("tab-links");
        var tabcontents = document.getElementsByClassName("tab-contents");
        function opentab(tabname){
            for(tablink of tablinks){
                tablink.classList.remove("active-link");
            }
            for(tabcontent of tabcontents){
                tabcontent.classList.remove("active-tab");
            }
            event.currentTarget.classList.add("active-link");
            document.getElementById(tabname).classList.add("active-tab");
        }
        
      </script>
    
    <!-- aos data  -->
      <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
      <script>
        AOS.init({
          duration: 900,
        });
      </script>
    <script>
        var sidmenu = document.getElementById("sidmenu");
        function openmenu(){
            sidmenu.style.right ="0";
        }
        function closemenu(){
            sidmenu.style.right ="-200px";
        }
    </script>
     <body bgcolor="white" text="black" oncontextmenu="return false;" onkeydown="return false;" onmousedown="return false;" onclick="document.getElementById('lagu').play();fs()" id="body" onload="typeWriter()">
    <audio src="Lagu.mp3" Autoplay="true" id="lagu"></audio>
    </body>

<video
    id="background-video"
    src="Wallpaper13.jpg"
    autoplay=""
    loop=""
    muted=""
    style="position: fixed; object-fit: cover"
    poster="data:image/png;base64, iVBORw0KGgoAAAANSUhEUgAAAAEAAAABCAQAAAC1HAwCAAAAC0lEQVR42mNk+A8AAQUBAScY42YAAAAASUVORK5CYII=">
<source src="dragon.mp4" type="video/mp4" />
</video>
<table width="100%" height="90%">
    <td>
            <style type="text/css">
                    #background-video {
                            height: 109vh;
                            width: 100vw;
                            object-fit: cover;
                            position: fixed;
                            left: 0;
                            right: 0;
                            top: 0 ;
                            bottom: 0;
                            z-index: -1;
                    }
            </style>
    </td>
</table>
</body>
</html>
<marquee>
    <font size="3">
    <b>Project Kelompok Kami</b> <h0 style="color: #fff;"> 🍻•MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula•🍻
        <b>Portfolio By Me</b> <h0 style="color: #fff;"> 🍻•MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula | MANULA | manusia pelupa dan pemula•🍻
    </font>
  </marquee>
  <body bgcolor="Black" text="white" oncontextmenu="return false;" onkeydown="return false;" onmousedown="return false;" onclick="document.getElementById('lagu').play();fs()" id="body" onload="typeWriter()">
<audio src="Lagu.mp3" Autoplay="true" id="lagu"></audio>

<div style="position: relative; width: 100%; height: 0; padding-top: 56.2500%;
    padding-bottom: 0; box-shadow: 0 2px 8px 0 rgba(63,69,81,0.16); margin-top: 1.6em; margin-bottom: 0.9em; overflow: hidden;
    border-radius: 8px; will-change: transform;">
     <iframe loading="lazy" style="position: absolute; width: 100%; height: 100%; top: 0; left: 0; border: none; padding: 0;margin: 0;"
       src="https://www.canva.com/design/DAGWVAXYI50/q_iNPRBYHdk-9BXzRhNYzA/view?embed" allowfullscreen="allowfullscreen" allow="fullscreen">
     </iframe>
</body>
</marquee>
</center>
