<!DOCTYPE html>
<html>
    <head>
        <title>Portfolio Website</title>
        <style>
            html{
                scroll-behavior: smooth;
            }
            body{
                margin: 0px;
                font-family: 'Poppins';
            }
            header{
                background:green;
                cursor: pointer;
                display: flex;
                align-items: center;
                justify-content: center;
            }
            header h1{
                height:120px;
                color: white;
                font-size:55px;
                font-family:Arial, Helvetica, sans-serif;
                font-weight: bold;
                letter-spacing: 2px;
                box-sizing: border-box;
            }


            .navigations-links{
                margin-top: -20px;
                font-size:20px;
            }
            .navigations-links ul{
                background: #00E676;
                display: flex;
                gap:20px;
                justify-content: center;
                list-style: none;
            }
            .navigations-links ul li{
                padding:25px;
            }
            .navigations-links ul li a{
                position:relative;
                font-weight: bold;
                color: black;
                text-decoration: none;
                transition: color 0.3s ease-in-out;
            }
            .navigations-links ul li a::after {
                content: "";
                position: absolute;
                left: 0;
                bottom: -5px;
                width: 0;
                height: 3px;
                background: green;
                transition: width 0.3s ease-in-out;
            }
            .navigations-links ul li a:hover {
                color: green;
            }
            .navigations-links ul li a:hover::after {
    width: 100%;
}


            main h1{
                color: white;
                background: black;
                text-align: center;
                padding:15px;
                margin-top: -20px;
                font-size:35px;
                cursor: pointer;
            }
            main p {
                font-size: 20px;
            }

            #hero, #about, #services, #contact {
                padding: 20px;
                border-radius: 10px;
                transition: transform 0.3s ease-in-out ,0.3s ease-in-out;
                box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
            }
            
            #hero:hover, #about:hover, #services:hover, #contact:hover {
                transform: scale(1.02);
                background: #e0e0e0;
            }

            #hero{
                height: 230px;
                margin-top:-10px;
                border: 2px solid black;
                background: lightgray;
            }
            #about{
                height: 230px;
                margin-top:10px;
                border: 2px solid black;
                background: lightgray;
            }
            #services{
                height: 200px;
                margin-top:10px;
                border: 2px solid black;
                background: lightgray;
            }

            #contact{
                height:150px;
                margin-top:10px;
                border: 2px solid black;
                background: lightgray;
            }
            #contact p{
                font-size: 20px;
                letter-spacing: 2px;
            }

            #footer{
                display: flex;
                align-items: center;
                justify-content: center;
                border: 2px solid black;
                margin-top: 10px;
                box-sizing: border-box;
                padding: 20px;
                font-size: 18px;
                font-weight: bold;
                background: #00E676;
                color: black;
                text-align: center;
            }
        </style>
    </head>
        <body>
            <header>
                <h1>SYED SAHIL</h1>
                </header>
                <div class="navigations-links">
                    <ul>
                        <li ><a href="#about">About</a></li>
                        <li><a href="#services">services</a></li>
                        <li><a href="#contact">Contact</a></li>
                        <li><a href="#footer">Footer</a></li>
                    </ul>
                </div>
            
            <main>
            <div id="hero">
                <h1>Welcome to My Portfolio</h1>
                <p>
                Hi, I'm Sahil , a self-taught web developer with 3 years of experience in HTML and CSS. I create 
                clean, responsive websites and offer web development services on Fiverr. Passionate about UI/UX, I'm 
                always learning and improving my skills.
                </p>
                
            </div>

            <div id="about">
                <h1>About Me</h1>
                <p>I have 3 years of self-taught experience in web development, specializing in HTML and CSS to create
                    clean, responsive, and user-friendly websites. I have worked on various projects, focusing on modern
                    designs and efficient layouts. I offer web development services on Fiverr, helping clients build
                    professional and visually appealing websites. My expertise lies in crafting well-structured web
                    pages with a strong emphasis on UI/UX principles, ensuring a smooth user experience. I am 
                    constantly learning and improving my skills to stay updated with the latest trends in web development.
                    </p>
            </div>


            <div id="services">
                <h1>Services</h1>
                <p>I offer professional web development services specializing in HTML and CSS to create clean, 
                    responsive, and user-friendly websites. Whether you need a landing page, business website,
                    or portfolio, I ensure a visually appealing and well-structured design. My focus is on modern
                    UI/UX principles, making websites both attractive and easy to navigate.
                    </p>
            </div>

            <div id="contact">
                <h1>Contact Me</h1>
                <p>Email:syedsahiltanveer@gmail.com</p>
            </div>
            
        </main>

        <footer>
            <div id="footer">© 2025 Syed Sahil. All rights reserved.</div>
        </footer>
        </body>
</html>
