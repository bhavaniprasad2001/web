<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>welcome </title>
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="ex.css" >
    
</head>
<body>
    <header class="header">
        <a href="#" class="logo">Portfolio</a>
        <nav class="bar">
            <a href="#home" style="--i:1;" class="active">Home</a>
            <a href="#education" style="--i:2;">Education</a>
            <a href="#skills" style="--i:3;">Skills</a>
            <a href="#contact" style="--i:4;">Contact</a>
        </nav> 
    </header>
    <section class="home" id="home">
        <div class="home-tab">
            <h3>Hello</h3>
            <h2 class="name">This is Bhavani Prasad</h2>
            <h3>I'm a <span id="running">  </span></h3>
            

            <div class="social">
                <a href="https://instagram.com/rules_breaker_bp?igshid=NTc4MTIwNjQ2YQ==" target="_blank" title="insta_profile"><i class='bx bxl-instagram'></i></a>
                <a href="https://www.linkedin.com/in/bhavani-prasad-undefined-58209923b" target="_blank" title="linkedin_profile"><i class='bx bxl-linkedin-square' ></i></a>
                <a href="https://www.facebook.com/bhavaniprasad.bhavaniprasad.54" target="_blank" title="facebook profile"><i class='bx bxl-facebook' ></i></a>
            </div>
            <section class="resume">
                <a href="#" class="res">Download Resume</a>
            </section>
        

        </div>
    </section>
    <!-- about section-->
    <section class="education" id="education">
        <h2 class="headp">My <span class="jour">Journey</span></h2>
        <div class="edu-col">
            <h4 class="tit">Education</h4>
            <div class="edu-box">
                <div class="contentedu">
                    <div class="year"><i class='bx bxs-calendar' ></i>&nbsp;2020 - 2023</div>
                    <h3>Bachelor Degree</h3>
                    <p>I have completed b.Tech Electrical and Electronics Engineering in Pragati Engineering college with 8.2 CGPA</p>
                </div>
            </div>
            <div class="edu-box">
                <div class="contentedu">
                    <div class="year"><i class='bx bxs-calendar' ></i>&nbsp;2017 - 2020</div>
                    <h3>Diploma</h3>
                    <p>I have completed Diploma Electrical and Electronics Engineering in Andhra Polytechnic college,kakinada with 86% </p>
                </div>
            </div>
            <div class="edu-box">
                <div class="contentedu">
                    <div class="year"><i class='bx bxs-calendar' ></i>&nbsp;2014- 2017</div>
                    <h3>High School</h3>
                    <p>I have studied 7th class to 10th class in Sri Adharsha High School, pithapuram.</p>
                    
                </div>
            </div>            
        </div>
    </section>

    <!--skills-->
    <section class="skills" id="skills">
        <h2 class="headp">My <span class="jour">Skills</span></h2>
        <div class="skillrow">
            <div class="skillcol">
                <h3 class="titlee">Programming Skills</h3>

                <div class="skillbox">
                    <div class="contents">
                        <div class="skillcon">
                            <h3>Python <span class="jour">75%</span></h3>
                            <div class="bara"><span></span></div>
                        </div>
    
                        <div class="skillcon">
                            <h3>HTML <span class="jour">85%</span></h3>
                            <div class="barb"><span></span></div>
                        </div>
    
                        <div class="skillcon">
                            <h3>CSS <span class="jour">70%</span></h3>
                            <div class="barc"><span></span></div>
                        </div>
    
                        <div class="skillcon">
                            <h3>Java Script <span class="jour">55%</span></h3>
                            <div class="bard"><span></span></div>
                        </div>
                    </div>
                    

                </div>
            </div>


            <div class="skillcol">
                <h3 class="titlee">Professional Skills</h3>

                <div class="skillbox">
                    <div class="contents">
                        <div class="skillcon">
                            <h3>Electrical Design <span class="jour">90%</span></h3>
                            <div class="bare"><span></span></div>
                        </div>
    
                        <div class="skillcon">
                            <h3>Web-Design <span class="jour">80%</span></h3>
                            <div class="barf"><span></span></div>
                        </div>
    
                        <div class="skillcon">
                            <h3>Automation (PLC, SCADA)  <span class="jour">87%</span></h3>
                            <div class="barg"><span></span></div>
                        </div>
                    </div>
                    

                </div>
            </div>

        </div>
    </section>


    <section class="contact" id="contact">
        <h2 class="headp"> Contact <span class="jour"> Me!</span></h2>
        <form action="">
            <div class="big">
                <div class="fill">
                    <input type="text" placeholder="enter name" required>
                    <span class="fom"></span>
                </div>

                <div class="fill">
                    <input type="text" placeholder="Email id">
                    <span class="form"></span>
                </div>

                <div class="fill">
                    <input type="number" placeholder="mobile number" required>
                    <span class="fom"></span>
                </div>
            </div>
            <div class="textare">
                <textarea class="pest" rows="10" cols="30" placeholder="Message..."required ></textarea>
                <span class="fom"></span>
            </div>

            <div class="btn-box ">
                <input type="submit" style="background-color: aqua;" class="btn">
            </div>
        </form>
    </section>
    <script src="https://unpkg.com/typed.js@2.0.16/dist/typed.umd.js"></script>
    
  <!-- Setup and start animation! -->
  <script>
    var typed = new Typed('#running', {
      strings: ['   Electrical Engineer', ' Web-Development',"Automation"],
      typeSpeed: 50,
      backSpeed:50,
      backDelay:100,
      loop:true
    })
  </script>


    
    
    
</body>
</html>
