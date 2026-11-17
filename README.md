<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Portfolio | Manchester United</title>

<style>
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background: #f5f5f5;
    color: #222;
}

/* HEADER */
header {
    background: #c8102e;
    color: white;
    padding: 22px 9%;
    display: flex;
    justify-content: space-between;
    align-items: center;
    box-shadow: 0 3px 12px #00000018;
}

.logo {
    font-size: 21px;
    font-weight: bold;
    letter-spacing: 1px;
}

.logo span {
    color: #f5c451;
}

nav a {
    text-decoration: none;
    color: white;
    margin-left: 25px;
    font-size: 14px;
}

nav a:hover {
    color: #f5c451;
}

/* HERO */
.container {
    max-width: 1050px;
    margin: auto;
    padding: 70px 25px;
}

.hero {
    background: #c8102e;
    color: white;
    padding: 55px 45px;
    border-radius: 16px;
    margin-bottom: 55px;
    position: relative;
    overflow: hidden;
}

.hero::after {
    content: "MU";
    position: absolute;
    right: 35px;
    bottom: -35px;
    font-size: 160px;
    font-weight: bold;
    color: #ffffff10;
}

.tag {
    display: inline-block;
    background: #a30c25;
    color: #f5c451;
    padding: 9px 16px;
    border-radius: 30px;
    font-size: 12px;
    margin-bottom: 22px;
    letter-spacing: 1px;
}

.hero h1 {
    font-size: clamp(34px, 5vw, 48px);
    margin-bottom: 15px;
    position: relative;
    z-index: 1;
}

.hero h1 span {
    color: #f5c451;
}

.hero p {
    max-width: 550px;
    line-height: 1.8;
    font-size: 15px;
    color: #f5e9e9;
    position: relative;
    z-index: 1;
}

/* DOCUMENTS */
.section-heading {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-bottom: 25px;
}

.section-heading h2 {
    font-size: 24px;
    border-left: 5px solid #c8102e;
    padding-left: 13px;
}

.section-heading span {
    color: #999;
    font-size: 13px;
}

.documents {
    display: grid;
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
    gap: 22px;
}

.card {
    background: white;
    border-radius: 13px;
    padding: 28px;
    border: 1px solid #e8e8e8;
    border-top: 4px solid #c8102e;
    text-decoration: none;
    color: #222;
    display: block;
    transition: .3s;
}

.card:hover {
    transform: translateY(-7px);
    box-shadow: 0 10px 25px #c8102e18;
    border-top-color: #e6b747;
}

.icon {
    width: 50px;
    height: 50px;
    background: #fae9ec;
    border-radius: 12px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-size: 24px;
    margin-bottom: 22px;
}

.number {
    color: #c8102e;
    font-size: 12px;
    font-weight: bold;
    margin-bottom: 10px;
    letter-spacing: 1px;
}

.card h3 {
    font-size: 19px;
    margin-bottom: 12px;
}

.card p {
    color: #777;
    font-size: 13px;
    line-height: 1.8;
    margin-bottom: 22px;
}

.open {
    color: #c8102e;
    font-size: 13px;
    font-weight: bold;
}

/* ABOUT */
.info {
    margin-top: 65px;
    padding: 30px;
    background: white;
    border-radius: 13px;
    border-left: 5px solid #c8102e;
    display: flex;
    justify-content: space-between;
    align-items: center;
    gap: 20px;
}

.info h3 {
    margin-bottom: 8px;
}

.info p {
    font-size: 13px;
    color: #777;
    line-height: 1.7;
}

.info-icon {
    font-size: 38px;
    color: #c8102e;
}

/* FOOTER */
footer {
    background: #202020;
    color: white;
    text-align: center;
    padding: 28px;
    font-size: 12px;
}

footer span {
    color: #e6b747;
}

/* MOBILE */
@media(max-width:600px) {
    header {
        flex-direction: column;
        gap: 15px;
        padding: 20px;
    }

    nav a {
        margin: 0 7px;
        font-size: 12px;
    }

    .container {
        padding: 45px 18px;
    }

    .hero {
        padding: 40px 25px;
    }

    .hero::after {
        font-size: 100px;
        right: 15px;
    }

    .info {
        align-items: flex-start;
    }
}
</style>
</head>

<body>

<header>
    <div class="logo">MY<span>PORTFOLIO.</span> 🔴</div>

    <nav>
        <a href="#">Home</a>
        <a href="#documents">Documents</a>
        <a href="#about">About</a>
    </nav>
</header>

<main class="container">

    <!-- HERO -->
    <section class="hero">

        <div class="tag">
            THE RED DEVILS • EST. 1878
        </div>

        <h1>My Personal <span>Documents.</span></h1>

        <p>
            Selamat datang di halaman portofolio saya.
            Di sini terdapat beberapa dokumen dan hasil
            karya yang dapat kamu lihat melalui pilihan
            di bawah ini.
        </p>

    </section>

    <!-- DOCUMENTS -->
    <section id="documents">

        <div class="section-heading">
            <h2>My Documents</h2>
            <span>01 — 03 / FILES</span>
        </div>

        <div class="documents">

            <!-- SURAT LAMARAN -->
            <a class="card"
               href="https://canva.link/sxgoa7z2l4yg8zn"
               target="_blank"
               rel="noopener noreferrer">

                <div class="icon">📄</div>
                <div class="number">DOCUMENT 01</div>

                <h3>Surat Lamaran Kerja</h3>

                <p>
                    Dokumen surat lamaran pekerjaan
                    yang berisi informasi dan pengajuan
                    diri untuk posisi pekerjaan.
                </p>

                <div class="open">Buka Dokumen ↗</div>
            </a>

            <!-- CV WEBSITE -->
            <a class="card"
               href="https://rivaldoanugrah095-wq.github.io/Cv-rivaldo-aminnnn/"
               target="_blank"
               rel="noopener noreferrer">

                <div class="icon">🌐</div>
                <div class="number">DOCUMENT 02</div>

                <h3>CV Website</h3>

                <p>
                    Curriculum Vitae dalam bentuk
                    website yang menampilkan profil,
                    pengalaman, dan kemampuan.
                </p>

                <div class="open">Buka Website ↗</div>
            </a>

            <!-- CV PPT -->
            <a class="card"
               href="https://canva.link/v1rw74c0jfjn1bo"
               target="_blank"
               rel="noopener noreferrer">

                <div class="icon">📊</div>
                <div class="number">DOCUMENT 03</div>

                <h3>CV PowerPoint</h3>

                <p>
                    Curriculum Vitae dalam format
                    presentasi yang berisi informasi
                    mengenai diri saya.
                </p>

                <div class="open">Buka Presentasi ↗</div>
            </a>

        </div>

    </section>

    <!-- ABOUT -->
    <section class="info" id="about">

        <div>
            <h3>About This Page</h3>

            <p>
                Halaman pribadi untuk mengumpulkan
                dokumen dan portofolio saya.
                <br>
                Glory Glory Man United!
            </p>
        </div>

        <div class="info-icon">⚽</div>

    </section>

</main>

<footer>
    © 2026 MY PORTFOLIO.
    <span>GLORY GLORY MAN UNITED!</span>
</footer>

</body>
</html>
