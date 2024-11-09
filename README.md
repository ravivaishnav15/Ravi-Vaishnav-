# Ravi-Vaishnav-
I'm a Web Designer &amp; Web Developer 
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ravi Vaishnav Portfolio</title>
    <link rel="stylesheet" href="style.css">
    <link rel="shortcut icon" href="images/img3.png" type="banner_image">
    <script src="https://kit.fontawesome.com/b1c2de8876.js" crossorigin="anonymous"></script>
</head>
<body>
    <div id="header">
        <div class="container">
            <nav>
                <img src="images/logo.png" class="logo">
                <ul id="sidemenu">
                    <li><a href="#header">HOME</a></li>
                    <li><a href="#about">ABOUT</a></li>
                    <li><a href="#SERVICES">SERVICES</a></li>
                    <li><a href="#work">WORK</a></li>
                    <li><a href="#contact">CONTACT</a></li>
                    <i class="fa-solid fa-xmark" onclick="closemenu()"></i>
                </ul>
                <i class="fa-solid fa-bars" onclick="openmenu()"></i>
            </nav>
            <div class="header-text"><p>Software Engineer</p>
                <h1>Hello,I'm <span>Ravi</span><br>Vaishnav From Jaipur </h1>
            </div>
            </div>
            </div>
    <div id="about">
        <div class="container">
            <div class="row"><div class="about-col-1">
                <img src="images/img.jpg">
            </div>
        <div class="about-col-2">
            <h1 class="sub-title">About Me</h1><br>
            <p>"I am a dedicated Computer Science Engineering student with a strong passion for software development, data science, and AI. With a solid foundation in programming and problem-solving, I am eager to apply my skills to innovative projects and contribute to cutting-edge technological advancements. I am constantly exploring new technologies and seeking opportunities to learn and grow in the field of computer science."</p>
            <div class="tab-title">
                <p class="tab-links active-link" onclick="opentab('Skill')" >Skill</p>
                <p class="tab-links" onclick="opentab('Experience')">Experience</p>
                <p class="tab-links" onclick="opentab('Education')">Education</p>
            </div>
            <div class="tab-contents active-tab" id="Skill">
                <ul>
                    <li><span>Data science</span><br>AI & ML</li>
                    <li><span>Web Development </span><br>Web Developer</li>
                    <li><span>Programming Language</span><br>C , C++ , Python</li>
                </ul>
            </div>

            <div class="tab-contents" id="Experience">
                <ul>
                    <li><span>Frontent Web Development</span><br>Upflairs PVT LTD Build an E-Commerce website using HTML , CSS and Javascript</li> <br>
                    <li><span>Data Science AI & ML Training</span><br>Upflairs PVT LTD Got Conceptual knowledge about Python , Numpy , Pandas , Matplotlib , Seaborn , Sklearn , Machine</li>
                </ul>
            </div>

            <div class="tab-contents" id="Education">
                <ul>
                    <li><span>2024-2028</span><br>Bachelor of Technology</li>
                    <li><span>2023-2024</span><br>Senior Secondary Examination</li>
                    <li><span>2021-2022</span><br>Secondary Examination</li>
                </ul>
            </div>


        </div></div>
        </div>
    </div>

    <!---------services------->
    <div id="SERVICES">
        <div class="container">
            <h1 class="">My SERVICES</h1>
            <div class="services-list">
                <div>
                    <i class="fa-solid fa-laptop-code"></i>
                    <h2>Data Science</h2>
                    <p>Data science is an academic field that uses scientific methods, statistics, and other tools to analyze data to extract insights that can help businesses make decisions.</p>
                    <a href="https://en.wikipedia.org/wiki/Data_science" target="_blank">Learn more</a>
                </div>

                <div>
                    <i class="fa-solid fa-crop-simple"></i>
                    <h2>Web Developer</h2>
                    <p>Web developers design, maintain, and optimize websites and other web-based applications for consumer use. They rely on insights from computer programming, software development, and graphic design, often working alongside professionals in each field.</p>
                    <a href="https://en.wikipedia.org/wiki/Web_developer" target="_blank">Learn more</a>
                </div>

                <div>
                    <i class="fa-solid fa-mobile-screen"></i>
                    <h2>AI & ML</h2>
                    <p>Artificial intelligence and Machine learning can be applied in many ways, allowing organizations to automate repetitive or manual processes that help drive informed decision-making.</p>
                    <a href="https://en.wikipedia.org/wiki/Artificial_intelligence" target="_blank">Learn more</a>
                </div>



            </div>
        </div>
    </div>

<!------work-------->

<div id="work">
    <div class="container">
        <h1 class="sub-title">My Work</h1>
        <div class="Work-list">
            <div class="Work">
                <img src="images/mywork1.jpg" >
                <div class="layer">
                    <h3>Breast Cancer Detection Prediction</h3><br>
                    <p>Reiteration of the relevance of the analysis for Breast Cancer Diagnosis.
                       <br><br> Used technology such as Python , numpy , pandas , matploylib , Sklearn , flask and pickle.</p>
                    <a href="https://github.com/ravivaishnav15/Breast-Cancer-Detection-Prediction" target="_blank"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="Work">
                <img src="images/mywork2.png" >
                <div class="layer">
                    <h3>Resume Screening</h3><br>
                    <p>This Project helps in making resume ATS friendly and help in  pick out profession as per your Resume details.
                       <br><br> Used technology such as Python , streamlit , pickle , nltk , numpy and pandas.</p>
                    <a href="https://github.com/ravivaishnav15/Resume-Screening-with-Python" target="_blank"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
            <div class="Work">
                <img src="images/mywork3.jpg" >
                <div class="layer">
                    <h3>E-Commerce Website</h3><br>
                    <p>An E commerce website using HTML , CSS and Javascript.</p>
                    <a href="https://github.com/ravivaishnav15/E-Commerce-Website" target="_blank"><i class="fa-solid fa-arrow-up-right-from-square"></i></a>
                </div>
            </div>
        </div>
        <a href="#" class="btn">See More</a>
    </div>
</div>

<!-------contact------->

<div id="contact">
    <div class="container">
        <div class="row">
            <div class="contact-left">
                <h1 class="sub-title">Contact Me</h1>
                <p><i class="fa-regular fa-paper-plane"></i>ravivashnav2006@gmail.com</p>
                <p><i class="fa-solid fa-square-phone"></i>7615805541</p>
                <div class="social-icons">
                <a href="https://x.com/ravi_pandit_15" target="_blank"><i class="fa-brands fa-x-twitter"></i></i></a>
                <a href="https://www.instagram.com/ravi_pandit_15?igsh=Y2toMTBpeDdqMnB6" target="_blank"><i class="fa-brands fa-instagram"></i></a>
                <a href="https://www.linkedin.com/in/ravi_pandit_15" target="_blank"><i class="fa-brands fa-linkedin"></i></a>
                <a href="https://www.facebook.com/ravivaishnav?mibextid=ZbWKwL" target="_blank"><i class="fa-brands fa-facebook"></i></a>
                </div>
                <a href="images/Resume.pdf" download class="btn btn2">Download CV</a>
            </div>
            <div class="contact-right">
                <form name="submit-to-google-sheet">
                    <input type="text" Name="Name" placeholder="Your Name" required>
                    <input type="email" name="email" placeholder="Your Email" required>
                    <textarea name="Message" rows="6" placeholder="Your Message"></textarea>
                    
                    <BUtton type="submit" class="btn btn2" >submit</BUtton>
                    
                </form>
                <span id="msg"></span>
                
            </div>
        </div>
    </div>
    <div class="copyright">
        <p></i>  Copyright <i class="fa-regular fa-copyright"></i>  Ravi Vaishnav. </p>
    </div>
</div>

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
    <script>
        const scriptURL = 'https://script.google.com/macros/s/AKfycbzyvtkVcnFjYy1a7Zq_KugtO4XQcSiiGX0M1sIlWUcc7wtiTfhyVRA09Og184f0xeL_/exec'
        const form = document.forms['submit-to-google-sheet']
        const msg = document.getElementById("msg")
      
        form.addEventListener('submit', e => {
          e.preventDefault()
          fetch(scriptURL, { method: 'POST', body: new FormData(form)})
            .then(response => {
                msg.innerHTML = "Thank For Message !!! "
                setTimeout(function(){
                    msg.innerHTML = ""
                },5000)
                form.reset()
            })
            .catch(error => console.error('Error!', error.message))
        })
      </script>
      <script>
        var sidemen = document.getElementById("sidemenu");
        function openmenu(){
            sidemen.style.right ="0";
        }
        function closemenu(){
            sidemen.style.right ="-200px";
        }
      </script>
    
</body>
</html><!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Page title</title>
</head>
<body>
    
</body>
</html>
