<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Bhagyesh's Portfolio</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;700&display=swap" rel="stylesheet">
<link rel="stylesheet" href="https://github.com/Bhagyeshredde/wt/blob/main/html/portfolio/styles.css">
<link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <nav>
            <!-- We took two div for left and right section oof navbar -->
            <div class = "left">Bhagyesh's Portfolio</div>
            <div class = "right">
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#service">Services</a></li>
                <li><a href="#projects">Projects</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
            </div>
        </nav>
    </header>
    <main>
        <section class="home">
            <section class ="firstSection">
                <div class="leftSection">
                    Hey, My Name is 
                    <div><span class="text-purple">Bhagyesh Reddy</span>
                    and I am a<br><span id="element"></span></div>
                    <br>
                    <a href=""><button class="button1">Download Resume</button></a>
                    <a href="https://www.linkedin.com/in/bhagyesh-reddy-4241492b4/"><button class="button1">Linkdin</button></a>
                    <a href="https://github.com/Bhagyeshredde"><button class="button1">Github</button></a>
                </div>
                <div class="rightSection">
                    <img  src="education.jpg" alt="">
                </div>
            </section>
        </section>
        <hr>
        <Section class="secondSection">
            <div id="about"> 
                <div class="abt">
                <h1>About</h1>
                <span class="text-purple">Know more about me</span>
                <br>
                <br>
            </div>
            <section>
                <div>
                    <!--Description-->
                    <p class="description">
                        Greetings! I'm <b>Bhagyesh Reddy</b>, a cybersecurity enthusiast with a genuine passion for programming and securing digital landscapes🌐. Armed with an insatiable curiosity and a knack for problem-solving, I've delved into the dynamic world of cybersecurity, and I'm navigating through the complexities with a blend of excitement and determination.
                    </p> 
                </div>
                <div class="boxes">
                    <div class="exp">
                            <img  style="width: 80px; height: 80px;" src="experience.jpg" alt="Experoence icon">
                            <p class="icon-text"><b>Experience</b></p>
                            <br>
                            <p class="icon-text2">Entry level</p>
                            <p class="icon-text2">Cybersecurity Anaylst</p>
                    </div>               
                    <div class="edu">
                            <img style="width: 80px; height: 80px;" src="education.jpg" alt="Education icon">
                            <p class="icon-text"><b>Education</b></p>
                            <br>
                            <p class="icon-text2">Bachlor's in Technology</p>
                            <p class="icon-text2">CSE-Cybersecurity</p>
                    </div>
                </div>
            </section>
        </section>
        <hr>
        <Section class="thirdSection">
            <div id="service"> <h1>Service</h1>
                <span class="text-purple">I can work on</span>
            </div>
            <br>
            <br>
            <p class="description" >As an Engineer of Computer Science my knowledge and skills is good in the domain of computer science and I have learn algorithm, data structure, computer programming, computer architecture and organisation, discrete mathematics, data management system. Along with my specialisation in Cyber security and Digital Forensics lead me to have insight in the field of security. I bring expertise in securing digital landscapes. Additionally, my proficiency extends to web development, where I leverage skills in creating secure and dynamic online solutions.
            </p>      
            <div class="content">
                <div class="card reveal active">
                  <div class="service-icon">
                    <i class="fas fa-graduation-cap"></i>
                  </div>
                  <div class="info">
                    <h3>Digital Forensics</h3>
                    <p class="desc" >Experienced in digital investigations, I specialize in extracting and analyzing electronic evidence. Skilled in uncovering insights that contribute to cybercrime investigations.</p>
                  </div>
                </div>
                <div class="card reveal active">
                  <div class="service-icon">
                    <i class="fas fa-file-code"></i>
                  </div>
                  <div class="info">
                    <h3>Web Developer</h3>
                    <p class="desc">With a keen interest in Front-end Development, skills in HTML, CSS, Javascript and a thorough understand of a user point of view leads me to be involved in Web Development.</p>
                  </div>
                </div>
                <div class="card reveal active">
                  <div class="service-icon">
                    <i class="fas fa-bug"></i>
                  </div>
                  <div class="info">
                    <h3>Cyber security analyst</h3>
                    <p class="desc">I as a Security analysts can monitor, prevent, and stop attacks on private data. These digital professionals create and implement firewalls and software systems to protect data and network infrastructures.</p>
                  </div>
                </div>
              </div>
        </Section>
        <hr>
        <Section class="forthSection">
            <div id="projects"> <h1>Projects</h1>
                <span class="text-purple">What I have done</span>
            </div>
        </Section>
        <hr>
        <Section class="fifthSection">
            <div id="contact"> <h1>Contact Me</h1>
                <span class="text-purple">Get in touch</span>
            </div><br><br>         
            <form action="">
                <fieldset>
                    <div>
                        <br><br>
                        <h2 style="font-size: 1.5rem; font-family: poppins , sans-serif; text-align: center;">Send us a message</h2>
                        <br>
                        <hr class="hr2">
            </div><br>
                <div class="form-details">
                    <div class="form-left">
                        <div class="formhead">
                            <label for="name">Your Name:</label>
                            <input type="text" id="username" placeholder="Enter Your Name" required>
                        </div>
                        <div class="formhead">
                            <label for="number">Phone Number:</label>
                        <input type="text" id="number" placeholder="Enter Your Number" required>
                        </div>
                    </div>                  
                    <div class="form-right">
                        <div class="formhead">
                            <label for="password">Your Email:</label>
                            <input type="text" id="text" placeholder="Enter Your Email">
                        </div>
                        <div class="formhead">
                            <label for="password">Company Name:</label>
                            <input type="text" id="password" placeholder="Enter Your Company Name" required>
                        </div>
                    </div>                    
                </div>
                <div>
                    <br>
                <button class="btn" type="submit">Send Message</button>
                <br><br>
                </div>
                <hr class="hr2"><br>
                <div>
                <p class="cmt"><b>Comment</b></p>
                <div>
                    <textarea name="comment" id="cmt"></textarea>
                </div><br>
            </fieldset>
            </form>
        </Section>
        <br>
        <section class="sixthSection">
            <div >             
            </div>
        </section>
    </main>   
    <script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>
        <!-- Setup and start animation! -->
    <script>
    var typed = new Typed('#element', {
        strings: ['Cybersecurity student.'],
        typeSpeed: 50,
    });
  </script>

</body>
<footer>
    <p>&copy; 2024 Bhagyesh Reddy</p>
</footer>
</html>
