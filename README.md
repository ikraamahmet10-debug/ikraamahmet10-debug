<!DOCTYPE html>
<html lang="so">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ikram | Creative Designer</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,700;1,700&family=Inter:wght@300;400;600&display=swap" rel="stylesheet">
</head>
<body>
    <div class="background-glow"></div>
    
    <main class="hero-con:root {
    --accent: #ff0080; /* Pink/Purple mix */
    --gold: #ffcc33;
    --dark: #0a0a0a;
    --glass: rgba(255, 255, 255, 0.03);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: var(--dark);
    color: white;
    font-family: 'Inter', sans-serif;
    height: 100vh;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
}

/* Background qurux badan oo nuuraya */
.background-glow {
    position: absolute;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, rgba(255, 0, 128, 0.15) 0%, rgba(0, 0, 0, 0) 70%);
    z-index: -1;
    filter: blur(50px);
}

.hero-container {
    width: 90%;
    max-width: 1100px;
    padding: 50px;
    border-radius: 40px;
    background: var(--glass);
    backdrop-filter: blur(20px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 40px 100px rgba(0,0,0,0.5);
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.5rem;
    letter-spacing: 4px;
    margin-bottom: 40px;
}

.logo span { color: var(--accent); }

.greeting {
    text-transform: uppercase;
    letter-spacing: 3px;
    font-size: 0.8rem;
    color: var(--accent);
    font-weight: 600;
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: 5rem;
    margin: 10px 0;
}

.name-gradient {
    background: linear-gradient(to right, #fff, var(--accent), var(--gold));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.role {
    font-size: 1.8rem;
    font-weight: 300;
    color: #ccc;
    margin-bottom: 20px;
}

p {
    max-width: 500px;
    line-height: 1.8;
    color: #999;
    margin-bottom: 40px;
}

/* Button-ka Stylish-ka ah */
.btn-main {
    padding: 18px 40px;
    background: white;
    color: black;
    text-decoration: none;
    border-radius: 100px;
    font-weight: 700;
    transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    display: inline-block;
}

.btn-main:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 30px rgba(255, 0, 128, 0.3);
    background: var(--accent);
    color: white;
}

.social-links {
    margin-top: 30px;
    display: flex;
    gap: 20px;
}

.social-links a {
    color: #666;
    text-decoration: none;
    font-size: 0.8rem;
    transition: 0.3s;
}

.social-links a:hover { color: white; }

/* Responsive for Mobile */
@media (max-width: 768px) {
    h1 { font-size: 3rem; }
    .hero-container { padding: 30px; text-align: center; }
    p { margin: 20px auto; }
    .social-links { justify-content: center; }
}
tainer">
        <header>
            <div class="logo">IK<span>RAM</span></div>
        </header>

        <section class="main-content">
            <span class="greeting">Ku soo dhawaaw dunidada hal-abuurka</span>
            <h1>Hi, I'm <span class="name-gradient">Ikram</span></h1>
            <h2 class="role">Graphic Designer & Web Developer</h2>
            <p>Waxaan isku xiraa quruxda muuqaalka iyo awoodda koodhka si aan u dhiso mustaqbal dhijitaal ah.</p>
            
            <div class="action-area">
                <a href="#" class="btn-main">Arag Shaqadayda</a>
                <div class="social-links">
                    <a href="#">Behance</a>
                    <a href="#">Dribbble</a>
                    <a href="#">LinkedIn</a>
                </div>
            </div>
        </section>
    </main>
</body>
</html>

:root {
    --accent: #ff0080; /* Pink/Purple mix */
    --gold: #ffcc33;
    --dark: #0a0a0a;
    --glass: rgba(255, 255, 255, 0.03);
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    background-color: var(--dark);
    color: white;
    font-family: 'Inter', sans-serif;
    height: 100vh;
    overflow: hidden;
    display: flex;
    align-items: center;
    justify-content: center;
}

/* Background qurux badan oo nuuraya */
.background-glow {
    position: absolute;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, rgba(255, 0, 128, 0.15) 0%, rgba(0, 0, 0, 0) 70%);
    z-index: -1;
    filter: blur(50px);
}

.hero-container {
    width: 90%;
    max-width: 1100px;
    padding: 50px;
    border-radius: 40px;
    background: var(--glass);
    backdrop-filter: blur(20px);
    border: 1px solid rgba(255, 255, 255, 0.1);
    box-shadow: 0 40px 100px rgba(0,0,0,0.5);
}

.logo {
    font-family: 'Playfair Display', serif;
    font-size: 1.5rem;
    letter-spacing: 4px;
    margin-bottom: 40px;
}

.logo span { color: var(--accent); }

.greeting {
    text-transform: uppercase;
    letter-spacing: 3px;
    font-size: 0.8rem;
    color: var(--accent);
    font-weight: 600;
}

h1 {
    font-family: 'Playfair Display', serif;
    font-size: 5rem;
    margin: 10px 0;
}

.name-gradient {
    background: linear-gradient(to right, #fff, var(--accent), var(--gold));
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
}

.role {
    font-size: 1.8rem;
    font-weight: 300;
    color: #ccc;
    margin-bottom: 20px;
}

p {
    max-width: 500px;
    line-height: 1.8;
    color: #999;
    margin-bottom: 40px;
}

/* Button-ka Stylish-ka ah */
.btn-main {
    padding: 18px 40px;
    background: white;
    color: black;
    text-decoration: none;
    border-radius: 100px;
    font-weight: 700;
    transition: 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
    display: inline-block;
}

.btn-main:hover {
    transform: translateY(-5px);
    box-shadow: 0 15px 30px rgba(255, 0, 128, 0.3);
    background: var(--accent);
    color: white;
}

.social-links {
    margin-top: 30px;
    display: flex;
    gap: 20px;
}

.social-links a {
    color: #666;
    text-decoration: none;
    font-size: 0.8rem;
    transition: 0.3s;
}

.social-links a:hover { color: white; }

/* Responsive for Mobile */
@media (max-width: 768px) {
    h1 { font-size: 3rem; }
    .hero-container { padding: 30px; text-align: center; }
    p { margin: 20px auto; }
    .social-links { justify-content: center; }
}
