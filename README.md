# EmanSm.github.io
My Portpolio
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Belajar-bootstrap_5</title>

    <!-- bootstrap CSS -->
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-9ndCyUaIbzAi2FUVXJi0CjmCapSmO7SnpJef0486qhLnuZ2cdeRhO02iuK6FUUVM" crossorigin="anonymous" />

    <!-- my CSS -->
    <link rel="stylesheet" href="style/style.css" />
  </head>
  <body>
    <!-- navbar -->
    <nav class="navbar navbar-expand-lg text-bg-primary p-3 shadow-sm p-3 mb-5 rounded">
      <div class="container">
        <a class="navbar-brand" href="#">Navbar</a>
        <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNav">
          <ul class="navbar-nav ms-auto">
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#">Home</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#about">Tentang</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#project">project</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#contact">Kontak</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
    <!-- akhir navbar -->

    <!-- jumbotron -->
    <section class="jumbotron text-center">
      <img src="img/me.jpg" alt="urang" width="200" class="rounded-circle img-thumbnail" />
      <h1 class="display-4">Emn-Sm</h1>
      <p class="lead">MANUSIA BIASA KANG JUALAN NASI KUNING | PROGRAMMER JUGA | KADANG GAMER</p>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320"><path fill="#fff" fill-opacity="1" d="M0,224L288,96L576,128L864,256L1152,128L1440,32L1440,320L1152,320L864,320L576,320L288,320L0,320Z"></path></svg>
    </section>
    <!-- akhir jumbotron -->

    <!-- about -->
    <section class="about" id="about">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Tentang Saya</h2>
          </div>
        </div>
        <div class="row justify-content-center fs-5 text-center">
          <div class="col-md-4">
            <p>Saya lahir di tahun 2000'an, lahir dari keluarga yang sederhana namun mempunyai mimpi yang begitu besar bagi keluarga besar dan keluarga kecil saya!</p>
          </div>
          <div class="col-md-4">
            <p>Walau hanya bersekolah sampai jenjang SMA/sederajat, tapi saya yakin kesuksesan tidak di ukur dari ijazah, jalannya saja yang mungkin tidak akan mudah.</p>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#e2edff" fill-opacity="1" d="M0,160L0,96L288,96L288,128L576,128L576,64L864,64L864,224L1152,224L1152,288L1440,288L1440,320L1152,320L1152,320L864,320L864,320L576,320L576,320L288,320L288,320L0,320L0,320Z"></path>
      </svg>
    </section>
    <!-- akhir about -->

    <!-- project -->
    <section id="project">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Project Saya</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-4 mb-3">
            <div class="card" style="width: 18rem">
              <img src="img/project1.jpg" class="card-img-top" alt="aing" />
              <div class="card-body">
                <p class="card-text text-center">Sampel Project.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" style="width: 18rem">
              <img src="img/project3.jpg" class="card-img-top" alt="aing" />
              <div class="card-body">
                <p class="card-text text-center">Sampel Project.</p>
              </div>
            </div>
          </div>
          <div class="col-md-4 mb-3">
            <div class="card" style="width: 18rem">
              <img src="img/project2.jpg" class="card-img-top" alt="aing" />
              <div class="card-body">
                <p class="card-text text-center">Sampel Project.</p>
              </div>
            </div>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path
          fill="#fff"
          fill-opacity="1"
          d="M0,96L26.7,106.7C53.3,117,107,139,160,170.7C213.3,203,267,245,320,266.7C373.3,288,427,288,480,288C533.3,288,587,288,640,272C693.3,256,747,224,800,224C853.3,224,907,256,960,250.7C1013.3,245,1067,203,1120,202.7C1173.3,203,1227,245,1280,224C1333.3,203,1387,117,1413,74.7L1440,32L1440,320L1413.3,320C1386.7,320,1333,320,1280,320C1226.7,320,1173,320,1120,320C1066.7,320,1013,320,960,320C906.7,320,853,320,800,320C746.7,320,693,320,640,320C586.7,320,533,320,480,320C426.7,320,373,320,320,320C266.7,320,213,320,160,320C106.7,320,53,320,27,320L0,320Z"
        ></path>
      </svg>
    </section>
    <!-- akhir project -->

    <!-- contact -->
    <section id="contact">
      <div class="container">
        <div class="row text-center mb-3">
          <div class="col">
            <h2>Kontak Saya</h2>
          </div>
        </div>
        <div class="row justify-content-center">
          <div class="col-md-6">
            <form>
              <div class="mb-3">
                <label for="name" class="form-label">Nama Lengkap</label>
                <input type="text" class="form-control" id="nama" aria-describedby="name" />
              </div>
              <div class="mb-3">
                <label for="pesan" class="form-label">Pesan</label>
                <textarea class="form-control" id="pesan" rows="3"></textarea>
              </div>
              <div class="mb-3">
                <label for="email" class="form-label">Email</label>
                <input type="email" class="form-control" id="email" aria-describedby="email" />
              </div>
              <button type="submit" class="btn btn-primary mb-5">Submit</button>
            </form>
          </div>
        </div>
      </div>
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 1440 320">
        <path fill="#0d6efd" fill-opacity="1" d="M0,96L0,288L288,288L288,224L576,224L576,192L864,192L864,160L1152,160L1152,128L1440,128L1440,320L1152,320L1152,320L864,320L864,320L576,320L576,320L288,320L288,320L0,320L0,320Z"></path>
      </svg>
    </section>
    <!-- akhir contact -->

    <!-- footer -->
    <footer class="bg-primary text-white text-center">
      <p>Created with love by <a href="https://www.instagram.com/emn.sm/" class="text-white fw-bold">EmnSm</a></p>
    </footer>
    <!-- akhir footer -->
    <!-- script -->
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js" integrity="sha384-geWF76RCwLtnZ8qwWowPQNguL3RmwHVBC9FhGdlKrxdiJJigb/j/68SIy3Te4Bkz" crossorigin="anonymous"></script>
  </body>
</html>
