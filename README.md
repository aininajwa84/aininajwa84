<!DOCTYPE html>
<html lang="en">

<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
  <style>
    h1 {
      font-family: Gothic Medium;
    }

    h2 {
      font-family: Verdana;
    }

    /* h3{ 
        font-family: Verdana;
       background-color: #a6acc1; 
        border: 2px solid rgb(0, 0, 0);
        padding: 15px;
      }*/

      h5{
          font-family: Verdana;
       background-color: #a6acc1; 
        border: 2px solid rgb(0, 0, 0);
        padding: 15px;
      }
  </style>

  <meta charset="UTF-8" />
  <meta http-equiv="X-UA-Compatible" content="IE=edge" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />

  <link rel="stylesheet" href="CSS/navbar.css">
  <link rel="stylesheet" href="CSS/footer.css">
  <link rel="stylesheet" href="CSS/main.css">
  <link rel="stylesheet" href="CSS/index.css">
  <script src="https://code.jquery.com/jquery-3.6.0.min.js"></script>
  <link rel="stylesheet" href="CSS/sliderImage.css">
  <script src="JS/index.js"></script>
  <script src="JS/imageSlider.js"></script>

  <title>ACE SKILL TECH </title>
  <link rel="icon" type="image/x-icon" href="Asset/Icon/logo.png">
</head>

<body>
  

  <div class="nav-wrapper">
    <div class="grad-bar"></div>
    <nav class="navbar">
      <img src="Asset/skimLogoPNG.png" alt="Logo Perantisan">
      <div class="menu-toggle" id="mobile-menu">
        <span class="bar"></span>
        <span class="bar"></span>
        <span class="bar"></span>
      </div>
      <ul class="nav no-search">
        <li><a href="index.html" class="nav-links">UTAMA</a></li>
          <li><a href="career.html" class="nav-links">KERJAYA</a></li>
          <li><a href="programme.html" class="nav-links">GALERI</a></li>
          <li><a href="about.html" class="nav-links">TENTANG KAMI</a></li>
          <li><a href="contactUs.html" class="nav-links">HUBUNGI KAMI</a></li>
      </ul>
    </nav>
    </div>

  

  <div class="slideshow-container">
    <div class="mySlides fade">
      <img src="Asset/slideBanner01.jpg" style="width: 100%;">
    </div>

    <div class="mySlides fade">
      <img src="Asset/slideBanner02.jpg" style="width: 100%;">
    </div>

    <div class="mySlides fade">
      <img src="Asset/slideBanner03.jpg" style="width: 100%;">
    </div>

    <a class="prev" onclick="plusSlides(-1)">❮</a>
    <a class="next" onclick="plusSlides(1)">❯</a>
  </div>
  <br>

  <div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span>
    <span class="dot" onclick="currentSlide(2)"></span>
    <span class="dot" onclick="currentSlide(3)"></span>
  </div>


  <div class="bodyItem">
    <div class="MVOtitle">
      <center>
        <h1>MISI, VISI DAN OBJEKTIF</h1>
      </center>
    </div>
    <div class="MVO grid">
      <div class="misi">
        <img src="Asset/missionIcon.png" alt="Icon Misi" class="mvoIcon" />
        <div class="mvopad">MISI AND VISI</div>
        Menyediakan platform kemahiran dan akademik sejajar....
        <br />
        <a href="about.html"> Baca lagi </a>
      </div>
      <div class="visi">
        <img src="Asset/vissionIcon.png" alt="Icon Visi" class="mvoIcon" />
        <div class="mvopad">VISI</div>
        Untuk menjadi pendidikan yang unggul, tenaga profesional....
        <br />
        <a href="about.html">Baca lagi</a>
      </div>
      <div class="objektif">
        <img src="Asset/objectiveIcon.png" alt="Icon Objektif" class="mvoIcon" />
        <br />
        <div class="mvopad">OBJEKTIF</div>
        Memberi pendedahan kepada program akademik dan.....
        <br />
        <a href="about.html"> Baca lagi </a>
      </div>
    </div>

    <div class="tentangKami">
      <div class="tentangImg"><img src="Asset/talkPic.jpg" alt=""></div>
      <div class="tentangText">
        <h1>TENTANG KAMI</h1>
        <h3 style="margin: auto;">
          Kami adalah syarikat yang berkomitmen untuk membantu pelajar
          mencapai cita-cita akademik mereka dengan memudahkan akses mereka
          ke pendidikan tinggi. Dengan kepakaran kami dalam bidang
          pendidikan, kami menyediakan perkhidmatan sokongan yang berkualiti
          tinggi untuk membantu pelajar mengenal pasti kolej yang sesuai
          dengan minat, keperluan dan matlamat mereka.
        </h3>

        <br />
        <a href="about.html"><button class="buttonReadMore">Sejarah Kami</button></a>
      </div>
    </div>
    <br>
    <div class="skm">
      <h2>PROGRAM SKIM BELIA PERANTISAN KEMAHIRAN</h2>

      <!-- <div class="container1"> 
            <img src="Asset/Card/Card-01.jpg" style="max-width:100%;cursor:pointer"
          onclick="onClick(this)" class="modal-hover-opacity">
          </div>
          <div class="container1">
            <img src="Asset/aircond.png" style="max-width:100%;cursor:pointer" 
            onclick="onClick(this)" class="modal-hover-opacity">
          </div>
          <div class="container1">
            <img src="Asset/automatif.png" style="max-width:100%;cursor:pointer" 
            onclick="onClick(this)" class="modal-hover-opacity">
          </div>
          <div class="container1">
            <img src="Asset/acc.png" style="max-width:100%;cursor:pointer" onclick="onClick(this)" class="modal-hover-opacity">
          </div>
        
        
        <div id="modal01" class="modal" onclick="this.style.display='none'">
          <span class="close">&times;&nbsp;&nbsp;&nbsp;&nbsp;</span>
          <div class="modal-content">
            <img id="img01" style="max-width:100%">
          </div>
        </div> -->

        
        <div class="grid skmCard"> 
          <!-- <a href="Asset/elektrikal.png" > -->
            <div><img src="Asset/Card-01.jpg" alt="" />
            <b>  
              <center>
                  <a href="#" onclick="openLightbox('Asset/elektrikal.png')">Lihat Poster</a>
              </center>
            </b>
            </div>

            <div><img src="Asset/Card-02.jpg" alt="" />
              <b>  
                <center>
                    <a href="#" onclick="openLightbox('Asset/pengurusan pejabat.png')">Lihat Poster</a>
                </center>
              </b>
            </div>
              
            <div><img src="Asset/Card-03.jpg" alt="" />
              <b>  
                <center>
                    <a href="#" onclick="openLightbox('Asset/sistem komputer.png')">Lihat Poster</a>
                </center>
              </b>
            </div>


            <div><img src="Asset/Card-04.jpg" alt="" />
              <b>  
                <center>
                    <a href="#" onclick="openLightbox('Asset/mekatronik.png')">Lihat Poster</a>
                </center>
              </b>
              </div>

              <div><img src="Asset/Card-05.jpg" alt="" />
                <b>  
                  <center>
                      <a href="#" onclick="openLightbox('Asset/pelancongan.png')">Lihat Poster</a>
                  </center>
                </b>
                </div>

                <div><img src="Asset/Card-06.jpg" alt="" />
                  <b>  
                    <center>
                        <a href="#" onclick="openLightbox('Asset/kimpalan.png')">Lihat Poster</a>
                    </center>
                  </b>
                  </div>

                  <div><img src="Asset/Card-07.jpg" alt="" />
                    <b>  
                      <center>
                          <a href="#" onclick="openLightbox('Asset/automatif.png')">Lihat Poster</a>
                      </center>
                    </b>
                    </div>

                    <div><img src="Asset/Card-08.jpg" alt="" />
                      <b>  
                        <center>
                            <a href="#" onclick="openLightbox('Asset/tadika.png')">Lihat Poster</a>
                        </center>
                      </b>
                      </div>

                      <div><img src="Asset/Card-09.png" alt="" />
                        <b>  
                          <center>
                              <a href="#" onclick="openLightbox('Asset/reka bentuk grafik.png')">Lihat Poster</a>
                          </center>
                        </b>
                        </div>

                        <div><img src="Asset/Card-10.png" alt="" />
                          <b>  
                            <center>
                                <a href="#" onclick="openLightbox('Asset/maritim.png')">Lihat Poster</a>
                            </center>
                          </b>
                          </div>


                          <div><img src="Asset/Card-11.png" alt="" />
                            <b>  
                              <center>
                                  <a href="#" onclick="openLightbox('Asset/kecantikan.png')">Lihat Poster</a>
                              </center>
                            </b>
                            </div>

                            <div><img src="Asset/Card -10.png" alt="" />
                              <b>  
                                <center>
                                    <a href="#" onclick="openLightbox('Asset/kulinari.png')">Lihat Poster</a>
                                </center>
                              </b>
                              </div>

                              <div><img src="Asset/Card-13.png" alt="" />
                                <b>  
                                  <center>
                                      <a href="#" onclick="openLightbox('Asset/multimedia.png')">Lihat Poster</a>
                                  </center>
                                </b>
                                </div>

                                <div><img src="Asset/Card - 12.png" alt="" />
                                  <b>  
                                    <center>
                                        <a href="#" onclick="openLightbox('Asset/filem.png')">Lihat Poster</a>
                                    </center>
                                  </b>
                                  </div>

                                  <div><img src="Asset/card-14.png" alt="" />
                                    <b>  
                                      <center>
                                          <a href="#" onclick="openLightbox('Asset/pra sekolah.png')">Lihat Poster</a>
                                      </center>
                                    </b>
                                    </div>

                                    <div><img src="Asset/card-15.png" alt="" />
                                      <b>  
                                        <center>
                                            <a href="#" onclick="openLightbox('Asset/pastri.png')">Lihat Poster</a>
                                        </center>
                                      </b>
                                      </div>

                                      <div><img src="Asset/card-17.png" alt="" />
                                        <b>  
                                          <center>
                                              <a href="#" onclick="openLightbox('Asset/ukur tanah.png')">Lihat Poster</a>
                                          </center>
                                        </b>
                                        </div>

                                        <div><img src="Asset/card-18.png" alt="" />
                                          <b>  
                                            <center>
                                                <a href="#" onclick="openLightbox('Asset/mekanikal.png')">Lihat Poster</a>
                                            </center>
                                          </b>
                                          </div>

                                          <div><img src="Asset/card-19.png" alt="" />
                                            <b>  
                                              <center>
                                                  <a href="#" onclick="openLightbox('Asset/it.png')">Lihat Poster</a>
                                              </center>
                                            </b>
                                            </div>

                                            <div><img src="Asset/card-20.png" alt="" />
                                              <b>  
                                                <center>
                                                    <a href="#" onclick="openLightbox('Asset/acc.png')">Lihat Poster</a>
                                                </center>
                                              </b>
                                              </div>

                                              <div><img src="Asset/card-21.png" alt="" />
                                                <b>  
                                                  <center>
                                                      <a href="#" onclick="openLightbox('Asset/aircond.png')">Lihat Poster</a>
                                                  </center>
                                                </b>
                                                </div>
                                              </div>

              <div id="lightbox" class="lightbox">
                <span class="close-button" onclick="closeLightbox()">&times;</span>
                <img src="" id="lightbox-image" alt="Popup Image">
            </div>
        
            <script>
                function openLightbox(imageSrc) {
                    var lightbox = document.getElementById("lightbox");
                    var lightboxImage = document.getElementById("lightbox-image");
        
                    lightboxImage.src = imageSrc;
                    lightbox.style.display = "block";
                }
        
                function closeLightbox() {
                    var lightbox = document.getElementById("lightbox");
                    lightbox.style.display = "none";
                }
            </script>

      <!-- <a href="Asset/pengurusan pejabat.png" >
                      <div><img src="Asset/Card-02.jpg" alt="" />
                       <b> <center><a href="Asset/pengurusan pejabat.png" target="_blank" onclick="window.open('Asset/pengurusan pejabat.png', 'popup', 'height=600, width=700'); return false;">Lihat Poster</a>
                          </div
                    ></a></b>

       <a href="Asset/sistem komputer.png"> 
                      <div><img src="Asset/Card-03.jpg" alt="" />
                     <b>   <center><a href="Asset/sistem komputer.png" target="_blank" onclick="window.open('Asset/sistem komputer.png', 'popup', 'height=600, width=700'); return false;">Lihat Poster</a>
                          </div
                    ></a></b>

        <a href="Asset/mekatronik.png">
          <div><img src="Asset/Card-04.jpg" alt="" /></div>
        </a>

        <a href="Asset/pelancongan.png">
          <div><img src="Asset/IconWebsite-08.png" alt="" /></div>
        </a>
        <a href="Asset/kimpalan.png">
          <div><img src="Asset/Card-06.jpg" alt="" /></div>
        </a>
        <a href="Asset/automatif.png">
          <div><img src="Asset/Card-07.jpg" alt="" /></div>
        </a>

        <a href="Asset/tadika.png">
          <div><img src="Asset/Card-08.jpg" alt="" /></div>
        </a>

        <a href="Asset/reka bentuk grafik.png">
          <div><img src="Asset/Card-09.png" alt="" /></div>
        </a>

        <a href="Asset/maritim.png">
          <div><img src="Asset/Card-10.png" alt="" /></div>
        </a>

        <a href="Asset/kecantikan.png">
          <div><img src="Asset/Card-11.png" alt="" /></div>
        </a>

        <a href="Asset/kulinari.png">
          <div><img src="Asset/Card -10.png" alt="" /></div>
        </a>

        <a href="Asset/multimedia.png">
          <div><img src="Asset/Card-13.png" alt="" /></div>
        </a>

        <a href="Asset/filem.png">
          <div><img src="Asset/Card - 12.png" alt="" /></div>
        </a>

        <a href="Asset/pra sekolah.png">
          <div><img src="Asset/card-14.png" alt="" /></div>
        </a>

        <a href="Asset/pastri.png">
          <div><img src="Asset/card-15.png" alt="" /></div>
        </a>

        <a href="Asset/ukur tanah.png">
          <div><img src="Asset/card-17.png" alt="" /></div>
        </a>

        <a href="Asset/office.png">
          <div><img src="Asset/card-16.png" alt="" /></div>
        </a>

        <a href="Asset/mekanikal.png">
          <div><img src="Asset/card-18.png" alt="" /></div>
        </a>

        <a href="Asset/it.png">
          <div><img src="Asset/card-19.png" alt="" /></div>
        </a>

        <a href="Asset/acc.png">
          <div><img src="Asset/card-20.png" alt="" /></div>
        </a>

        <a href="Asset/aircond.png">
          <div><img src="Asset/card-21.png" alt="" /></div>
        </a>


         <a href="aircond.png" 
              ><div><img src="card-22.png" alt="" /></div
            ></a> 
                    </div>-->

    </div>
    <br><br><br><br><br><br><br><br>
    <div class="grid sijil">
      <div class="sijilText">
        <h2><b>APA KELEBIHAN SIJIL KEMAHIRAN MALAYSIA (SKM) ?</b></h2>
        <br />

        <h5>Sijil Berkualiti Dan Diiktiraf</h5>
        <p>
          Sijil latihan kemahiran Malaysia diperakui oleh Jabatan
          Pembangunan Kemahiran dan boleh diguna pakai untuk memohon kerja
          di sektor kerajaan mahupun swasta
        </p>

        <br />
        <h5>Peluang Kerja Selepas Tamat Latihan</h5>
        <p>
          Pelajar diberi peluang bekerja di industri yang menjalinkan
          kerjasama (MOU) dengan pusat latihan kemahiran.
        </p>

        <br />
        <h5>Peluang Sambung Ke Ijazah</h5>
        <p>
          Peluang untuk sambung ke peringkat ijazah sangat luas melalui MTUN
          (Malaysian Technical University Network).
        </p>

        <br />
        <h5>Elaun bulanan (Sara Hidup)</h5>
        <p>
          Elaun sara hidup RM400/RM600 sebulan dapat membantu meringankan
          beban kewangan pelajar untuk makan dan minum.
        </p>

        <br />
        <h5>
          Pinjaman Penuh 100% Dari Perbadanan Tabung Pembangunan Kemahiran
          (PTPK).
        </h5>
        <p>
          Pinjaman pelajaran untuk pelatih menyambung belajar disediakan dan
          diuruskan oleh pihak kolej.
        </p>
      </div>
      <div class="sijilImg">
        <img src="Asset/CONTOH SIJIL SKM.jpg" alt="Contoh Sijil SKM" />
      </div>
    </div>

    <div class="officePicBanner grid">
      <div class="textOfficeBanner">
        <h1>PROGRAM PERANTISAN BELIA KEMAHIRAN</h1>
        <p>CIK AZRA - <b>014-8431401</b></p>
        <p>ENCIK NAZMI MOHD NOR - <b>017-9955713</b></p>
      </div>
      <div class="buttonOfficeBanner">
        <a href="contactUs.html">
          <div class="buttonOnBanner">
            <h3>HUBUNGI KAMI</h3>
          </div>
        </a>
      </div>
    </div>


    <!----
        <div class="diploma">
   
          <h2>SKIM PERANTISAN BELIA KEMAHIRAN & PENGAJIAN TINGGI</h2>
          <div class="grid diplomaCard">
            <a
              href="programme.html"
              onmouseenter="showOverlay1()"
              onmouseleave="closeOverlay1()"
              ><div id="dCard1" class="ease">
                <img src="dCard1.jpg" alt="" />
                <div id="cardOverlay1" class="overlay hidden posa"></div>
                <p id="cardText1" class="posa hidden dpCardText">
                  Diploma Syariah Islamiah
                </p>
              </div></a
            >
            <a
              href="programme.html"
              onmouseenter="showOverlay2()"
              onmouseleave="closeOverlay2()"
              ><div id="dCard2" class="ease">
                <img src="dCard2.jpg" alt="" />
                <div id="cardOverlay2" class="overlay hidden posa"></div>
                <p id="cardText2" class="posa hidden dpCardText">
                  Diploma Usuludin
                </p>
              </div></a
            >
            <a
              href="programme.html"
              onmouseenter="showOverlay3()"
              onmouseleave="closeOverlay3()"
              ><div id="dCard3" class="ease">
                <img src="dCard3.jpeg" alt="" />
                <div id="cardOverlay3" class="overlay hidden posa"></div>
                <p id="cardText3" class="posa hidden dpCardText">
                  Diploma Al-Quran Qiraat
                </p>
              </div></a
            >
            <a
              href="programme.html"
              onmouseenter="showOverlay4()"
              onmouseleave="closeOverlay4()"
              ><div id="dCard4" class="ease">
                <img src="dCard4.jpg" alt="" />
                <div id="cardOverlay4" class="overlay hidden posa"></div>
                <p id="cardText4" class="posa hidden dpCardText">
                  Diploma Pengurusan Perniagaan
                </p>
              </div></a
            >
            <a
              href="programme.html"
              onmouseenter="showOverlay5()"
              onmouseleave="closeOverlay5()"
              ><div id="dCard5" class="ease">
                <img src="dCard5.jpg" alt="" />
                <div id="cardOverlay5" class="overlay hidden posa"></div>
                <p id="cardText5" class="posa hidden dpCardText">
                  Diploma Hotel
                </p>
              </div></a
            >
            <a
              href="programme.html"
              onmouseenter="showOverlay6()"
              onmouseleave="closeOverlay6()"
              ><div id="dCard6" class="ease">
                <img src="dCard6.jpg" alt="" />
                <div id="cardOverlay6" class="overlay hidden posa"></div>
                <p id="cardText6" class="posa hidden dpCardText">
                  Diploma Perakaunan
                </p>
              </div></a
            >
          </div>
          <a href="programme.html"
            ><div class="moreButton">
              <button class="buttonLanjut" style="vertical-align:middle"><span>LANJUT </span></button></div
          ></a>
        </div>
      </div> -->

    <div class="footer">
      <div class="footer1 grid">
        <span class="grid1 pad10">
          <h4>PAUTAN LAIN TAJAAN PENDIDIKAN</h4>
          <ul>
            <a href="https://myperkasatvet.ptpk.gov.my/portal/" target="_blank" class="linkTajaan">
              <li>Perbadanan Tabung Pembangunan Kemahiran (PTPK)</li>
            </a>
            <a href="https://www.dsd.gov.my/" target="_blank" class="linkTajaan">
              <li>Jabatan Pembangunan Kemahiran (JPK)</li>
            </a>
            <a href="https://www.ptptn.gov.my/" target="_blank" class="linkTajaan">
              <li>Perbadanan Tabung Pendidikan Tinggi Nasional (PTPTN)</li>
            </a>
            <a href="https://www.mara.gov.my/en/index/" target="_blank" class="linkTajaan">
              <li>Majlis Amanah Rakyat (MARA)</li>
            </a>
          </ul>
        </span>
        

        <span class="grid2 pad10">
          <br>
          <br>
          <a href="index.html" class="nav">Home</a><br />
          <a href="about.html" class="nav">About Us</a><br />
          <a href="contactUs.html" class="nav">Contact Us</a><br />
          <a href="career.html" class="nav">Career</a><br />
          <a href="programme.html" class="nav">Programme</a>
        </span>
      </div>
      <br>
      <div class="footer2">
        Ace Skill Tech © 2023. All Rights Reserved
      </div>
    </div>

    <script>
      var slideIndex = 0;
      var slides, dots;
      showSlides();
    </script>
</body>

</html>
