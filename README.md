<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>MBC LABORATORY</title>
    <link rel="stylesheet" href="tugasmbc.css">
</head>
<!--feather icons-->
<script src="https://unpkg.com/feather-icons"></script>
<body>
    <nav class="navbar">
        <a href="#" class="logo"><img src="coba.png" alt="Logo"></a>
    
        <div class="navbar-nav">
            <a href="#home">Home</a>
            <a href="#divisi">Divisi</a>
            <a href="#contact">Contact</a>
            <a href="#developer">Developer</a>
        </div>
    
        <div class="navbar-extra">
            <a href="#" id="search"><i data-feather="search"></i></a>
            <a href="#" id="menu"><i data-feather="menu"></i></a>
        </div>
    </nav>

    <!--Hero Section-->
    <div class="hero">
        <section id="home">
            <div class="kolom">
                <h1>Pusat Riset Teknologi dan Konsultan <span>Cybersecurity, Big Data, dan Multimedia Application</span></h1>
                <p>MBC Laboratory didirikan pada tanggal 4 Oktober 2019. MBC merupakan salah satu entitas penelitian yang beroperasi di bawah Kementrian Komunikasi dan Multimedia (KK NCM)</p>
            </div>
        </section>
    </div>

    <div class="container">
        <div class="division">
            <img src="cyber.png" alt="Cybersecurity Logo" class="logo">
            <h2>Cyber security</h2>
            <p>Menangani keamanan sistem dan jaringan untuk melindungi data dan informasi dari ancaman siber.</p>
        </div>
        <div class="division">
            <img src="data.png" alt="Big Data Logo" class="logo">
            <h2>Big Data</h2>
            <p>Memproses dan menganalisis data dalam skala besar untuk menghasilkan wawasan yang penting bagi keputusan strategis bisnis.</p>
        </div>
        <div class="division">
            <img src="game.png" alt="Game Technology Logo" class="logo">
            <h2>Game Technology</h2>
            <p>Mengembangkan dan memodifikasi teknologi game untuk menawarkan pengalaman bermain yang berbeda dan inovatif.</p>
        </div>
        <div class="division">
            <img src="GIS.png" alt="Geographical Information System Logo" class="logo">
            <h2>Geographical Information System</h2>
            <p>Mengolah dan menganalisis data geografis untuk menghasilkan peta serta informasi spasial yang bermanfaat.<p>
        </div>

    </div>
    <section id="kontak" class="kontak-section">
        <h2>More Info</h2>
        <div class="kontak-container">
            <div class="kontak-item">
                <h3>Address</h3>
                <p>TULT 13.04</p>
            </div>
            <div class="kontak-item">
                <h3>Contact</h3>
                <p>(+62) 123-456-789</p>
            </div>
            <div class="kontak-item">
                <h3>Email</h3>
                <p>mbclab@telkomuniv.com</p>
            </div>
            <div class="kontak-item">
                <h3>Instagram</h3>
                <p>@mbclab</p>
            </div>

 
            <section class="profile-section">
                <div class="profile-container">
                    <img src="profil.jpg" alt="Profile Photo" class="profile-photo">
                    <div class="profile-info">
                        <h1>Web Developer</h1>
                        <p>Hallo! Perkenalkan saya Gusti Ayu Adindha Jyothi. Mahasiswi Telkom University dari jurusan S1 Teknik Telekomunikasi, memiliki minat pada bidang Cyber Security.</p>
                        <div class="contact-info">
                            <h2>Contact Information</h2>
                            <p><strong>Email:</strong> <a href="mailto:email@example.com">gustiayu@gmail.com</a></p>
                            <p><strong>Phone:</strong> +62 8194-4966</p>
                            <p><strong>Address:</strong> Bandung, Bojongsoang</p>
                        </div>
                    </div>
                </div>
            </section>
        

    <!--Feather Icons-->
    <script>
        feather.replace();
    </script>
</body>
</html>

*{
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    outline: none;
    text-decoration: none;
}

body{
    font-family: 'Poppins', sans-serif;
    background-color: #000;
    color:#fff;

}

.navbar {
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding: 1.4rem 7%;
    background-color: rgba(1, 1, 1, 0.8);
    border-bottom: 1px solid black;
    position: fixed;
    top: 0;
    left: 0;
    right: 0;
    z-index: 9999;
}

.navbar-nav {
    display: flex;
    align-items: center;
    margin: 0;
}

.navbar-nav .logo img {
    height: 30px; 
}

.navbar-nav a {
    color: white;
    display: inline-block;
    font-size: 1.4rem;
    text-decoration: none;
    margin: 0 1rem;
}

.navbar .navbar-nav a:hover {
    color: #A0153E;
}

.navbar .navbar-nav a::after{
    content: '';
    display: block;
    padding-bottom: 0.5rem;
    border-bottom: 0.1rem solid #A0153E ;
    transform: scaleX(0)
    
}

.navbar .navbar-nav a:hover::after{
    transform: scaleX(1);
}


.navbar .navbar-extra a {
    color: white;
    margin: 0 0.5rem;
    text-decoration: none;
}

/* Hero section */
.hero {
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    background-image: url('coba bg.jpg');
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
}

.hero p {
    color: white;
}

.kolom {
    text-align: center;
    color: #fff;
}

.kolom p {
    color: white; 
}
h1 {
    font-size: 2.5rem;
    margin-bottom: 1rem;
}


h1 span {
    display: block;
    font-size: 1.5rem;
}

p {
    font-size: 1rem;
    max-width: 800px;
    margin: 0 auto;
}

a.tbl-pink {
    background: #0C1844;
    border-radius: 20px;
    margin-top: 20px;
    padding: 15px 20px;
    color: #fff;
    cursor: pointer;
    font-weight: bold;
}

.container {
    display: flex;
    justify-content: space-around;
    flex-wrap: wrap;
    padding: 20px;
}

.division {
    background: #fff;
    border-radius: 8px;
    box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    width: 23%;
    margin: 10px;
    text-align: center;
    padding: 20px;
    box-sizing: border-box;
}

.logo {
    width: 80px;
    height: auto;
    margin-bottom: 10px;
}

h2 {
    color: #333;
    font-size: 1.5em;
    margin: 10px 0;
}

.division p {
    color: #000; /* Ini membuat teks dalam elemen <p> di dalam .division berwarna hitam */
}

/*halaman contact*/
.kontak-section {
    padding: 4rem 7%;
    background-color: #222;
    color: #ffffff; 
}

.kontak-section h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    text-align: center;
}

.kontak-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px; 
}

.kontak-item {
    display: flex;
    flex-direction: column;
    align-items: center;
    text-align: center;
    background-color: #222; 
    padding: 2rem;
    border-radius: 10px;
    border: 1px solid #444; 
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.3); 
    width: 250px; 
    transition: transform 0.3s ease, box-shadow 0.3s ease; 
}

.kontak-item:hover {
    transform: scale(1.05); 
    box-shadow: 0 6px 12px rgba(0, 0, 0, 0.5); 
}
.kontak-section h2 {
    font-size: 2.5rem;
    margin-bottom: 2rem;
    text-align: center;
    color: #fff; 
}
.kontak-item h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
}

.kontak-item p {
    font-size: 1rem;
    color: #ccc; 
}

/*developer*/
.profile-section {
    background-color: #ffffff; 
    padding: 40px;
    border-radius: 10px;
    max-width: 800px;
    margin: 20px auto;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}

.profile-container {
    display: flex;
    align-items: center;
}

.profile-photo {
    border-radius: 50%;
    width: 150px;
    height: 150px;
    margin-right: 20px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
}

.profile-info {
    max-width: 600px;
}

.profile-info h1 {
    margin-top: 0;
    color: #003366; 
}

.profile-info p {
    font-size: 16px;
    line-height: 1.5;
    color: #333333; 
}

.profile-info a {
    color:#003366; 
    text-decoration: none;
}

.profile-info a:hover {
    text-decoration: underline;
}

.contact-info h2 {
    margin-bottom: 10px;
    font-size: 20px;
    color: #003366; 
}

.contact-info p {
    margin: 5px 0;
    color: #333333; 
}

/*Media*/
@media (max-width: 1366px) {
    html {
        font-size: 75%;
    }
    
}

@media (max-width: 768px) {
    html {
        font-size: 62.5%;
    }

    .division {
        width: calc(50% - 20px); 
    }
}

@media (max-width: 450px) {
    html {
        font-size: 55%;
    }

    .division {
        width: 100%; 
    }
}

/*open laptop*/
@media (max-width: 1366px){
    html{
        font-size: 75%
    }
}

/*open tablet*/
@media (max-width: 768px){
    html{
        font-size: 62.5%
    }
}

/*open phone*/
@media (max-width: 450px){
    html{
        font-size: 55%}
}
