# LIC-Policy-website
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>LIC POLICY Website</title>
    <script src="https://cdn.emailjs.com/dist/email.min.js"></script>
    <script type="text/javascript" src="https://cdn.jsdelivr.net/npm/@emailjs/browser@4/dist/email.min.js"></script>
    <script type="text/javascript">
        (function () {
            emailjs.init("TW4DHJiWlCyTxYlAH");
        })();
    </script>
    <script type="text/javascript">

        document.getElementById('contactForm').addEventListener('submit', function (event) {
            event.preventDefault(); // Prevent default form submission
            console.log("first");
            // Get form data
            var formData = {
                name: document.querySelector('input[name="Your Name"]').value,
                email: document.querySelector('input[name="Your Email"]').value,
                address: document.querySelector('input[name="Your Address"]').value,
                phone: document.querySelector('input[name="Phone Number"]').value,
                message: document.querySelector('textarea[name="Your Message"]').value
            };
            console.log("second");

            // Send email
            emailjs.send("service_f44bwf5", "template_xke1cpb", formData)
                .then(function (response) {
                    console.log("third");

                    console.log('Email sent successfully!', response);
                    alert('Your message has been sent successfully!');
                }, function (error) {
                    console.error('Email sending failed:', error);
                    alert('Oops! Something went wrong, please try again later.');
                });
        });
    </script>
    <link rel="stylesheet" href="try.css">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>

</head>

<body>
    <header>
        <div class="logo"><span>Life</span>Insurance.</div>
        <ul class="navlist">
            <li><a href="#home" style="--i:1;">Home</a></li>
            <li><a href="#about" style="--i:2;">About</a></li>
            <li><a href="#services" style="--i:3;">Work </a></li>
            <li><a href="#skills" style="--i:4;">Buy</a></li>
            <li><a href="#portfolio" style="--i:5;">Plans</a></li>
            <li><a href="#contact" style="--i:6;">Contact</a></li>
        </ul>
        <div id="menu-icon" class="bx bx-menu"></div>
    </header>

    <!---------------------------home section------------------------------------------------------------>

    <section id="home" class="home">
        <div class="home-content .scroll-scale">
            <h1>Hi! Buddy</h1>
            <div class="change-text">
                <h3>I'm</h3>
                <h3>
                    <span class="word">LIC&nbsp;Policy. </span>
                    <span class="word">Your&nbsp;Guide</span>
                    <span class="word">Your&nbsp;Friend</span>
                    <span class="word">To&nbsp;Choose</span>
                    <span class="word">A&nbsp;Best</span>
                </h3>
            </div>

            <p>Life Insurance Corporation (LIC) policies provide financial security to policyholders and their families
                through various insurance plans, including term insurance, endowment plans, and ULIPs (Unit Linked
                Insurance Plans).
            </p>

            <div class="info-box">
                <div class="email-info">
                    <h5>Features:</h5>
                    <span>Protection,more.</span>
                </div>

                <div class="behance-info">
                    <h5>Details:</h5>
                    <span>LIC Premium,more.</span>
                </div>
            </div>

            <div class="btn-box">
                <a href="https://www.policybazaar.com/lic-of-india/articles/how-lic-works/" class="btn">
                    How we work
                </a>
                <a href="https://www.forbes.com/advisor/in/life-insurance/lic-policy/" class="btn">
                    Best LIC Policies
                </a>
            </div>

            <div class="social-icons">
                <a href="#"><i class='bx bxl-facebook'></i></a>
                <a href="#"><i class='bx bxl-instagram'></i></a>
                <a href="#"><i class='bx bxl-twitter'></i></a>
                <a href="#"><i class='bx bxl-dribbble'></i></a>
            </div>
        </div>

        <div class="home-image .scroll-scale">
            <div class="img-box">
                <img src="/lic_agent.png" alt="">
            </div>

            <div class="liquid-shape">
                <svg viewBox="0 0 500 500" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink"
                    width="100%" id="blobSvg">
                    <path fill="#12f7ff">
                        <animate attributeName="d" dur="10000ms" repeatCount="indefinite" values="
                        M429,358Q375,466,254,459.5Q133,453,89,351.5Q45,250,92,154Q139,58,256.5,47Q374,36,428.5,143Q483,250,429,358Z;
                        
                        M413,351Q367,452,256.5,441Q146,430,91.5,340Q37,250,85.5,150Q134,50,243.5,60.5Q353,71,406,160.5Q459,250,413,351Z;

                        M386.5,329Q341,408,243.5,419Q146,430,73.5,340Q1,250,75,163Q149,76,258.5,61Q368,46,400,148Q432,250,386.5,329Z;

                        M392.5,326.5Q338,403,241.5,417.5Q145,432,105,341Q65,250,111,169Q157,88,260.5,70Q364,52,405.5,151Q447,250,392.5,326.5Z;

                        M427.5,351.5Q367,453,246,459.5Q125,466,67,358Q9,250,78.5,162Q148,74,251,72Q354,70,421,160Q488,250,427.5,351.5Z;

                        M425,339.5Q353,429,247,434.5Q141,440,81.5,345Q22,250,81,155Q140,60,239,78.5Q338,97,417.5,173.5Q497,250,425,339.5Z;

                        M394.5,334.5Q348,419,248.5,421.5Q149,424,111.5,337Q74,250,107.5,155.5Q141,61,245,70Q349,79,395,164.5Q441,250,394.5,334.5Z;

                        M429,358Q375,466,254,459.5Q133,453,89,351.5Q45,250,92,154Q139,58,256.5,47Q374,36,428.5,143Q483,250,429,358Z;
                        "></animate>
                    </path>
                </svg>
            </div>
        </div>
    </section>


    <!------------------------------about section--------------------------------------------------------->

    <section id="about" class="about">
        <div class="img-about .scroll-scale">
            <img src="/WhatsApp Image 2024-05-08 at 8.31.35 PM-fotor-bg-remover-20240509153552.png" alt="">
            <div class="info-about1">
                <span>50+</span>
                <p>Insurers</p>
            </div>
            <div class="info-about2">
                <span>Over 9 million</span>
                <p>Customers Trust</p>
            </div>
            <div class="info-about3">
                <span>100%</span>
                <p>Reliable</p>
            </div>
        </div>

        <div class="about-content">
            <span>Let us introduce Ourself</span>
            <h2>About us</h2>
            <h3>A story of Best</h3>
            <p>Every day we wake up to the fact that more than 250 million lives are part of our family called Life
                Insurance Corporation.

                We are humbled by the magnitude of the responsibility we carry and realise the lives that are associated
                with us are very valuable indeed.

                Though this journey started over six decades ago, we are still conscious of the fact that, while
                insurance may be a business for us, being part of millions of lives every day for the past 65 years has
                been a process called TRUST.</p>

            <div class="btn-box">
                <a href="https://licindia.in/know-your-life-insurance" class="btn">Read More</a>
            </div>
        </div>
    </section>

    <!------------------------------service section--------------------------------------------------------->

    <section id="services" class="services">
        <div class="main-text">
            <span>
                What we will do for you
            </span>
            <h2>Our Work</h2>
        </div>

        <div class="section-services .scroll-bottom">
            <div class="service-box">
                <i class='bx bxs-layer service-icon'></i>
                <h3>Discovery and Planning</h3>
                <p>1.1 Requirement Gathering and Analysis
                    <br><br>

                    1.2 Content Strategy
                    <br><br>

                    1.3 Technical Specifications
                    <br><br>
                </p>
                <div class="btn-box service-btn">
                    <a href="https://wayfinancial.com/services/life-insurance-planning/" class="btn">Read More</a>
                </div>
            </div>

            <div class="service-box">
                <i class='bx bx-code-alt service-icon'></i>
                <h3>Design and Development</h3>
                <p>2.1 Wireframing and Prototyping
                    <br><br>

                    2.2 Visual Design
                    <br><br>

                    2.3 Front-end and Back-end Development
                    <br><br>
                </p>
                <div class="btn-box service-btn">
                    <a href="https://licindia.in/request-for-proposal-for-design-development-implementation-and-maintenance-of-hrms-system-for-life-insurance-corporation-of-india" class="btn">Read More</a>
                </div>
            </div>

            <div class="service-box">
                <i class='bx bx-desktop service-icon'></i>
                <h3>Testing and Deployment</h3>
                <p>3.1 Quality Assurance Testing
                    <br><br>

                    3.2 User Acceptance Testing (UAT)
                    <br><br>

                    3.3 Deployment and Launch Methods
                    <br><br>
                </p>
                <div class="btn-box service-btn">
                    <a href="https://katalon.com/resources-center/blog/insurance-application-testing" class="btn">Read More</a>
                </div>
            </div>
        </div>
    </section>

    <!------------------------------buy section--------------------------------------------------------->

    <section id="skills" class="skills">
        <div class="main-text">
            <span>insure and secure</span>
            <h2>A True Saga Of Trust</h2>
        </div>

        <div class="skill-main">
            <div class="skill-left">
                <h3>Purchase Skills</h3>
                <div class="skill-bar">
                    <div class="info">
                        <p>Research and Compare Policies</p>
                        <p>72%</p>
                    </div>
                    <div class="bar">
                        <span class="html"></span>
                    </div>
                </div>

                <div class="skill-bar">
                    <div class="info">
                        <p>Get Quotes and Calculate Premiums</p>
                        <p>90%</p>
                    </div>
                    <div class="bar">
                        <span class="figma"></span>
                    </div>
                </div>

                <div class="skill-bar">
                    <div class="info">
                        <p>Apply for the Policy</p>
                        <p>80%</p>
                    </div>
                    <div class="bar">
                        <span class="javascript"></span>
                    </div>
                </div>

                <div class="skill-bar">
                    <div class="info">
                        <p>Review and Finalize the Purchase</p>
                        <p>62%</p>
                    </div>
                    <div class="bar">
                        <span class="css"></span>
                    </div>
                </div>

            </div>
            <div class="skill-right">
                <h3>Secure Skills</h3>
                <div class="porfessional">
                    <div class="box">
                        <div class="circle" data-dots="80" data-percent="90"></div>
                        <div class="text">
                            <h2>90%</h2>
                            <small>Secure Website & Data Transmission</small>
                        </div>
                    </div>

                    <div class="box">
                        <div class="circle" data-dots="80" data-percent="90"></div>
                        <div class="text">
                            <h2>80%</h2>
                            <small>User Authentication & Authorization</small>
                        </div>
                    </div>

                    <div class="box">
                        <div class="circle" data-dots="80" data-percent="90"></div>
                        <div class="text">
                            <h2>55%</h2>
                            <small>Data Protection & Storage</small>
                        </div>
                    </div>

                    <div class="box">
                        <div class="circle" data-dots="80" data-percent="90"></div>
                        <div class="text">
                            <h2>70%</h2>
                            <small>Monitoring & Compliance</small>
                        </div>
                    </div>
                </div>
            </div>
    </section>

    <!------------------------------Plans section--------------------------------------------------------->


    <section id="portfolio" class="portfolio">
        <div class="main-text">
            <span>What we will do for you</span>
            <h2>Latest Plans</h2>
        </div>

        <div class="container">
            <div class="fillter-buttons">
                <button class="button" data-filter="all">All</button>
                <button class="button" data-filter=".product">Pension</button>
                <button class="button" data-filter=".inter">Health</button>
                <button class="button" data-filter=".web">Insurance</button>
            </div>

            <div class="portfolio-gallery">
                <div class="port-box mix product">
                    <div class="port-image">
                        <img src="/WhatsApp Image 2024-05-08 at 8.31.37 PM (1).jpeg" alt="">
                    </div>
                    <div class="port-content">
                        <h3>Endowment Plans</h3>
                        <p>
                            The LIC has a huge range of endowment plans to offer. Most of its endowment plans are
                            designed to participate in the company’s profits and others deal in wealth creation through
                            investment in equity markets.
                        </p>
                        <a href="https://www.kotaklife.com/insurance-guide/savingstax/what-is-endowment-plan#:~:text=What%20is%20Endowment%20Insurance%20Plan,period%20called%20the%20maturity%20period."><i class='bx bx-link-external'></i></a>
                    </div>
                </div>

                <div class="port-box mix product">
                    <div class="port-image">
                        <img src="/WhatsApp Image 2024-05-08 at 8.31.35 PM (1).jpeg" alt="">
                    </div>
                    <div class="port-content">
                        <h3>Term Insurance</h3>
                        <p>
                            Term insurance provides coverage for a specified period, paying a death benefit if the
                            insured passes away during that term. It is typically more affordable than permanent life
                            insurance, with no cash value accumulation.
                        </p>
                        <a href="https://www.kotaklife.com/term-insurance"><i class='bx bx-link-external'></i></a>
                    </div>
                </div>

                <div class="port-box mix inter">
                    <div class="port-image">
                        <img src="/WhatsApp Image 2024-05-08 at 8.31.37 PM.jpeg" alt="">
                    </div>
                    <div class="port-content">
                        <h3>Pension plans</h3>
                        <p>
                            Pension insurance provides a steady income stream to individuals after retirement, ensuring
                            financial stability in their later years. It involves regular contributions during the
                            working years, which are then converted into periodic payments upon retirement.
                        </p>
                        <a href="https://www.iciciprulife.com/retirement-pension-plans.html#:~:text=Pension%20plans%20let%20you%20accumulate,and%20your%20future%20is%20secure."><i class='bx bx-link-external'></i></a>
                    </div>
                </div>

                <div class="port-box mix inter">
                    <div class="port-image">
                        <img src="/WhatsApp Image 2024-05-08 at 8.31.36 PM (1).jpeg" alt="">
                    </div>
                    <div class="port-content">
                        <h3>Unit-linked plans</h3>
                        <p>
                            Unit Linked Insurance Plans (ULIPs) offer a combination of life insurance and investment,
                            with premiums partially funding insurance and the rest invested in equity or debt funds.
                            They provide both financial protection
                        </p>
                        <a href="https://www.iciciprulife.com/insurance-library/ulips/what-are-ulips.html#:~:text=The%20full%20form%20of%20ULIP,is%20divided%20into%20two%20parts."><i class='bx bx-link-external'></i></a>
                    </div>
                </div>

                <div class="port-box mix inter">
                    <div class="port-image">
                        <img src="/WhatsApp Image 2024-05-08 at 8.31.36 PM.jpeg" alt="">
                    </div>
                    <div class="port-content">
                        <h3>Micro insurance plans</h3>
                        <p>
                            Microinsurance provides affordable and accessible insurance coverage to low-income
                            individuals, protecting them against specific risks like health issues, accidents, or
                            property loss.
                        </p>
                        <a href="https://www.investopedia.com/terms/m/microinsurance.asp"><i class='bx bx-link-external'></i></a>
                    </div>
                </div>

                <div class="port-box mix web">
                    <div class="port-image">
                        <img src="/WhatsApp Image 2024-05-08 at 8.31.35 PM (2).jpeg" alt="">
                    </div>
                    <div class="port-content">
                        <h3>Health plans</h3>
                        <p>
                            Health plans offer coverage for medical expenses, including hospitalization, treatments, and
                            preventive care, ensuring financial protection against health-related costs. They can be
                            tailored to individual or family needs
                        </p>
                        <a href="https://www.iciciprulife.com/health-insurance/health-insurance-plans.html"><i class='bx bx-link-external'></i></a>
                    </div>
                </div>
                <div>
                    <head>
                        <meta charset="UTF-8">
                        <meta name="viewport" content="width=device-width, initial-scale=1.0">
                        <title>LIC Chatbot</title>
                        <link rel="stylesheet" href="cg.css">
                    </head>
                    <body>
                        <div class="chat-container">
                            <div class="chat-header">
                                <h1>LIC Chatbot</h1>
                            </div>
                            <div class="chat-messages" id="chat-messages"></div>
                            <div class="chat-input-container">
                                <input type="text" id="user-input" placeholder="Type your message...">
                                <button id="send-button">Send</button>
                            </div>
                        </div>
                        <script src="cg.js"></script>
                    </body>
                    </div>
            </div>
        </div>
    </section>

    <!------------------------------Contact section--------------------------------------------------------->


    <section id="contact" class="contact">
        <div class="main-text ">
            <span>Ask me a question</span>
            <h2>Contact Me</h2>
        </div>
        <form id="my_form" onsubmit="submitForm(); return false;">
            <p><input  id="n"  placeholder="Name" required></p>
            <p><input  id="e"  placeholder="Email Address" type="email" required></p>
            
            <textarea  id="m"  rows="10" placeholder="write your Message here" required></textarea>
            
                <p><input type="submit" id="mybtn" value="Submit Form" > <span id="status"></span></p>
            
        </form>

        <script>

            function _(id){return document.getElementById(id);}
            
            function submitForm(){
            
            _("mybtn").disabled = true;
            
            _("status").innerHTML = 'please wait...';
             var formdata = new FormData();
            
            formdata.append("n", _("n").value);
            
            formdata.append("e", _("e").value);
            
            formdata.append("m", _("m").value);
            
            var ajax =new XMLHttpRequest();
            ajax.open("POST", "example_parser.php");
            
            ajax.onreadystatechange =function(){
            
            if(ajax.readyState == 4 && ajax.status == 200) {

                if(ajax.responseText == "success"){
            
            ("my_form").innerHTML='<h2>Thanks'+_("n"). value+', your message has been sent.<h2>'
            
                 } else {
            
            _("status").innerHTML = ajax. responseText;
            
            _("mybtn").disabled = false;
                 }
                }
            }

            ajax.send(formdata ) ;
        }
            
            </script>
    </section>


    <!-- footer website-->

    <footer>
        <p>Copyright &copy; 2023 by Life Insurance || All Right Reserved.</p>
        <a href="#home"><i class='bx bx-up-arrow-alt'></i></a>
    </footer>
    <script src="/mixitup.min.js"></script>
    <script src="try.js"></script>
</body>

</html>
