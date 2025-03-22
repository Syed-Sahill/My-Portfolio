<!DOCTYPE html>
<html>
    <head>
        <title>Landing Page for a Productivity App</title>
        <style>
            body{
                background:lightgray;
                font-family: Arial, Helvetica, sans-serif;
                margin: 0;
                padding: 0;
                font-weight: bold;
                scroll-behavior: smooth;
            }
            header{
                display: flex;
                align-items: center;
                justify-content: center;
                color: white;
                background:rgb(103, 1, 1);
                height:300px;
            }
            header h1{
                font-size: 40px;
            }
            header h2{
                font-size:20px;
                text-align: center;
            }
            header button{
                border: 0;
                padding:15px;
                margin-top: 10px;
                margin-left:35%;
                color: black;
                background: linear-gradient(to right, #f9c559, #ff7e5f);
                border-radius: 30px;
                font-size:17px;
                font-weight: bold;
                cursor: pointer;
                transition: all 0.3s ease-in-out;
            }
            header button:hover{
                transform: scale(1.02);
                background: linear-gradient(to right, #ff7e5f, #f9c559);
            }
            /* #box1 , #box2 , #box3 {
                display: flex;
                flex-direction: row;
            } */

            main h1{
                text-align: center;
                font-weight: 900;
                font-size: 40px;
                letter-spacing: 1px;
                background:; 
            }

            #feature h2{
                font-size:30px;
                text-align: center;
            }
            #feature p{
                font-size:18px;
                text-align: center;
            }

            #boxes{
                display:flex;
                justify-content:space-evenly;
                gap:20px;
                margin: 10px;
            }
            .box1{
                border:4px solid rgb(103, 1, 1);
                border-radius: 30px;
                background:wheat;
                height: 200px;
                display: flex;
                flex-direction: column;
                letter-spacing:2px;
                padding:20px;
                transition: transform 0.3s ease-in-out ,0.3s ease-in-out;
            }
            .box1:hover{
                transform: scale(1.02);
            }
            .box2{
                border:4px solid rgb(103, 1, 1);
                border-radius: 30px;
                background:wheat;
                height: 200px;
                display: flex;
                flex-direction: column;
                letter-spacing:2px;
                padding:20px;
                transition: transform 0.3s ease-in-out ,0.3s ease-in-out;
            }
            .box2:hover{
                transform: scale(1.02);
            }
            .box3{
                border:4px solid rgb(103, 1, 1);
                border-radius: 30px;
                background:wheat;
                height: 200px;
                display: flex;
                flex-direction: column;
                letter-spacing:2px;
                padding:20px;
                transition: transform 0.3s ease-in-out ,0.3s ease-in-out;
            }
            .box3:hover{
                transform: scale(1.02);
            }

            #user-section .para{
                height: 200px;
                margin: 10px;
                background:wheat;
                display: flex;
                flex-direction: column;
                justify-content: center;
                align-items: center;
                border:5px solid rgb(103, 1, 1);  
                border-radius: 30px;
                /* box-shadow: 5px 5px 7px #f9c559; */
                letter-spacing:1px;
                font-size:18px;
                transition: transform 0.3s ease-in-out ,0.3s ease-in-out;
            }
            #user-section .para:hover{
                transform: scale(1.02);
            }

            .p-section{
                margin: 10px;
                display: flex;
                flex-direction: column;
                justify-content:space-evenly;
                align-items: center;
                letter-spacing:3px;
                font-size:25px;
                border: 5px solid rgb(103, 1, 1);
                border-radius: 30px;
                background:wheat;
                height:250px;
                transition: transform 0.3s ease-in-out ,0.3s ease-in-out;
            }
            .p-section:hover{
                transform: scale(1.02);
            }
            .p-section a{
                color:maroon;
                list-style: none;
                text-decoration: none;
            }

            footer{
                color: white;
                background: rgb(103, 1, 1) ;
                height:80px;
                font-size:20px;
                display: flex;
                align-items: center;
                justify-content: center;
                letter-spacing: 2px;
            }
        </style>
    </head>
    <body>
        <header>
            <div id="hero">
                <h1>Boost Your Productivity with Ease</h1>
                <h2>Organize tasks, set goals, and achieve more—effortlessly!</h2>
                <button>Get Started for Free</button>
            </div>
        </header>

        <main>
            <div id="feature">
                <h1>Features</h1>
            <div id="boxes">
                <div class="box1">
                <h2>Smart Task Management</h2>
                <p>Plan and track tasks effectively</p>
                </div>

                <div class="box2">
                <h2>Seamless Integration</h2>
                <p>Connect with your favorite apps smoothly.</p>
                </div>

                <div class="box3">
                <h2>Analytics & Reports</h2>
                <p>Gain insights into your productivity.</p>
                </div>
            </div>
            </div>

            <div id="user-section">
                <h1>What Our Users Say</h1>
            <div class="para">
                <p>This app transformed the way I work! - Alex</p>
                <p>Highly recommend for teams and individuals. - Sarah</p>
            </div>
            </div>

            <div id="pricing">
                <h1>Choose Your Plan</h1>
            <div class="p-section">
                <div class="sec1"><a href="">Free Plan - Basic Features</a></div>
                <div class="sec2"><a href="">Pro Plan - Advanced tools</a></div>
                <div class="sec3"><a href="">Business Plan - Full suite</a></div>
            </div>
            </div>
        </main>

        <footer>
            <div id="social-media-links"></div>
            <div id="contact information">syedsahiltanveer@gmail.com</div>
            <div id="Copyright">© 2025 Syed Sahil. All rights reserved.</div>
        </footer>
    </body>
</html>
