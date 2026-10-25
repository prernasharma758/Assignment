# Assignment
# Question 1 :  What happens between typing a URL and seeing the page ?
When we type a URL into a browser and press Enter, several things happen in the background before the webpage appears on our screen.
First, the browser understands the URL and identifies which website we want to visit. Then, it uses DNS to find the IP address of that website because computers use IP addresses to communicate with each other.
Once the IP address is found, the browser establishes a connection with the server. If we are visiting an HTTPS website, a secure connection is also established to protect the data being exchanged.
After that, the browser sends a request to the server asking for the webpage. The server processes the request and sends back the required content, usually starting with HTML.
The browser then reads the HTML, loads the necessary CSS and JavaScript files, and processes images and other resources. HTML provides the structure, CSS handles the design, and JavaScript adds interactivity.
Finally, the browser puts everything together and displays the webpage on our screen. All these steps happen very quickly, which is why we can open a website within seconds.
# Question 2 : Setup Proof (VS Code, Node.js, Live Server)
**Live server**

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/55867a14-29dd-45d4-b613-6d1a9ee4ccbc" />


# Question 3 : Terminal Navigation Practice Sheet
Objective: Learn how to navigate folders and files using the terminal in VS Code.

Basic Terminal Commands

pwd – Shows the current working directory.

ls – Lists files and folders in Linux/macOS.

dir – Lists files and folders in Windows Command Prompt.

cd foldername – Opens the specified folder.

cd .. – Moves one level up to the parent directory.

mkdir foldername – Creates a new folder with the specified name.

clear – Clears the terminal screen in Linux/macOS.

cls – Clears the terminal screen in Windows Command Prompt.

touch filename – Creates an empty file in Linux/macOS or Git Bash.

# Question 4 : Repository with at least three meaningful commits
**Step 1:** **Configure Git Identity (One-Time Setup)**

git config --global user.name "Prerna Sharma"

git config --global user.email "your-github-email@example.com"

**Step 2: Create a Repository**

mkdir html-css-assignments

cd html-css-assignments

git init

git branch -M main

**Step 3: Create the First Commit**

echo "# HTML CSS Assignments" > README.md

git add README.md

git commit -m "Initial commit: Add README"

**Step 4: Create the Second Commit**

mkdir HTML

echo "<h1>My First Webpage</h1>" > HTML/index.html

git add .

git commit -m "Add initial HTML webpage"

**Step 5: Create the Third Commit**

mkdir CSS

echo "body { font-family: Arial, sans-serif; }" > CSS/style.css

git add .

git commit -m "Add basic CSS styling"
# Question 5 : GitHub repository link
**GitHub Repository Link**

The GitHub repository contains the HTML and CSS assignment files, project documentation, and commit history.

**Repository URL:** `https://github.com/YOUR-USERNAME/html-css-assignments`

**Note:** Replace `YOUR-USERNAME` with your actual GitHub username to create the correct repository link.
# Question 6 : Basic HTML Page
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Webpage</title>
</head>
<body>

    <h1>Welcome to My Webpage</h1>

    <p>Hello! My name is Prerna.</p>
    <p>This is my first basic HTML page.</p>

    <h2>About Me</h2>
    <p>I am a student learning web development.</p>

    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Learning new skills</li>
        <li>Exploring technology</li>
    </ul>

    <h2>Contact</h2>
    <p>Email: example@email.com</p>

</body>
</html>

# Question 7 : resume-text-only.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume</title>
</head>
<body>

    <h1>Prerna Sharma</h1>
    <p>Email: your-email@example.com</p>
    <p>Location: Uttar Pradesh, India</p>
    <p>Career Goal: To build a career in Data Analytics and Artificial Intelligence.</p>

    <hr>

    <h2>Career Objective</h2>
    <p>
        I am a BCA (Artificial Intelligence) student interested in data analytics,
        artificial intelligence, and research. I want to develop my technical skills
        and gain practical experience through projects and learning opportunities.
    </p>

    <h2>Education</h2>
    <ul>
        <li>Bachelor of Computer Applications (Artificial Intelligence) – Invertis University</li>
        <li>Class 12 – 65%</li>
        <li>Class 10 – 80%</li>
    </ul>

    <h2>Technical Skills</h2>
    <ul>
        <li>Python</li>
        <li>HTML and CSS</li>
        <li>Java</li>
        <li>Microsoft Excel</li>
        <li>Power BI</li>
        <li>Data Analytics</li>
    </ul>

    <h2>Projects</h2>
    <ol>
        <li>Healthcare Cost Burden Dashboard using Power BI</li>
        <li>HR Analytics Dashboard</li>
        <li>Banking Customer Analysis</li>
    </ol>

    <h2>Achievements</h2>
    <ul>
        <li>Secured a position in the Top 5 in a college hackathon.</li>
        <li>Won medals in Judo competitions.</li>
    </ul>

    <h2>Certifications</h2>
    <ul>
        <li>Java Basic – HackerRank</li>
        <li>CSS Basic – HackerRank</li>
    </ul>

    <h2>Declaration</h2>
    <p>
        I hereby declare that the information provided above is true
        to the best of my knowledge.
    </p>

    <p><strong>Signature:</strong> Prerna Sharma</p>

</body>
</html>

# Question 8 : resume semantic.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Resume - Prerna Sharma</title>
</head>
<body>

    <header>
        <h1>Prerna Sharma</h1>
        <p>Student | Aspiring Data Analyst</p>
        <address>
            Email: <a href="mailto:your-email@example.com">your-email@example.com</a><br>
            Location: Uttar Pradesh, India
        </address>
    </header>

    <hr>

    <main>

        <section>
            <h2>Career Objective</h2>
            <p>
                I am a student interested in data analytics, artificial intelligence,
                and web development. My goal is to improve my technical skills
                and gain practical experience through projects and continuous learning.
            </p>
        </section>

        <section>
            <h2>Education</h2>

            <article>
                <h3>Bachelor of Computer Applications</h3>
                <p>Specialization: Artificial Intelligence</p>
                <p>University: Invertis University</p>
            </article>

            <article>
                <h3>Class 12</h3>
                <p>Percentage: 65%</p>
            </article>

            <article>
                <h3>Class 10</h3>
                <p>Percentage: 80%</p>
            </article>
        </section>

        <section>
            <h2>Technical Skills</h2>
            <ul>
                <li>HTML and CSS</li>
                <li>Java</li>
                <li>Python</li>
                <li>Microsoft Excel</li>
                <li>Power BI</li>
                <li>Data Analytics</li>
            </ul>
        </section>

        <section>
            <h2>Projects</h2>

            <article>
                <h3>Healthcare Cost Burden Dashboard</h3>
                <p>
                    Created a dashboard to analyze healthcare costs
                    and present insights using data visualization.
                </p>
            </article>

            <article>
                <h3>HR Analytics Dashboard</h3>
                <p>
                    Analyzed HR data to identify workforce trends
                    and present useful insights.
                </p>
            </article>

            <article>
                <h3>Banking Customer Analysis</h3>
                <p>
                    Explored banking customer data to understand
                    customer behavior and patterns.
                </p>
            </article>
        </section>

        <section>
            <h2>Achievements</h2>
            <ul>
                <li>Secured a position in the top five in a college hackathon.</li>
                <li>Won medals in Judo competitions.</li>
            </ul>
        </section>

        <section>
            <h2>Certifications</h2>
            <ul>
                <li>Java Basic - HackerRank</li>
                <li>CSS Basic - HackerRank</li>
            </ul>
        </section>

        <section>
            <h2>Declaration</h2>
            <p>
                I declare that the information provided above is true
                to the best of my knowledge.
            </p>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 Prerna Sharma. All rights reserved.</p>
    </footer>

</body>
</html>

# Question 9 : Debug buggy html.html

<!DOCTYPE html>
<html>
<head>
    <title>Debug HTML Assignment</title>
    <meta charset="UTF-8">
</head>
<body>

    <h1>Welcome to My Webpage<h1>

    <p>This is my first paragraph.
    <p>This is my second paragraph.</p>

    <h2>My Hobbies</h3>

    <ul>
        <li>Reading
        <li>Learning HTML</li>
        <li>Playing games</li>
    </ol>

    <a href="https://www.google.com">Visit Google</a

    <img src="image.jpg" alt="Sample Image">

    <p><strong>This text is bold.</em></p>

</body>
</html>

# Question 10 : personal-introduction.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Personal Introduction</title>
</head>
<body>

    <header>
        <h1>About Me</h1>
        <p>Welcome to my personal introduction webpage!</p>
    </header>

    <main>
        <section>
            <h2>Introduction</h2>
            <p>
                Hello! My name is Prerna Sharma. I am a student pursuing
                a Bachelor of Computer Applications with a specialization
                in Artificial Intelligence.
            </p>
            <p>
                I am passionate about technology, programming, and learning
                new skills. I enjoy exploring new concepts and applying
                my knowledge to practical projects.
            </p>
        </section>

        <section>
            <h2>My Education</h2>
            <p>
                I am currently studying computer applications and developing
                my knowledge of programming, web development, and data analytics.
            </p>
        </section>

        <section>
            <h2>My Skills</h2>
            <ul>
                <li>HTML and CSS</li>
                <li>Java Programming</li>
                <li>Python Programming</li>
                <li>Data Analytics</li>
                <li>Microsoft Excel and Power BI</li>
            </ul>
        </section>

        <section>
            <h2>My Hobbies</h2>
            <ol>
                <li>Learning new technologies</li>
                <li>Exploring creative ideas</li>
                <li>Reading and studying</li>
                <li>Participating in sports activities</li>
            </ol>
        </section>

        <section>
            <h2>My Career Goal</h2>
            <p>
                My goal is to become a skilled professional in the technology
                field, improve my problem-solving abilities, and contribute
                to meaningful projects.
            </p>
        </section>

        <section>
            <h2>Contact Me</h2>
            <p>
                Email:
                <a href="mailto:your-email@example.com">
                    your-email@example.com
                </a>
            </p>
        </section>
    </main>

    <footer>
        <p>&copy; 2026 Prerna Sharma. All rights reserved.</p>
    </footer>

</body>
</html>

# Question 11 : portfolio-navigation.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Portfolio</title>
</head>
<body>

    <header id="home">
        <h1>Prerna Sharma</h1>
        <p>Student | Aspiring Data Analyst | Web Development Learner</p>

        <nav>
            <a href="#home">Home</a> |
            <a href="#about">About</a> |
            <a href="#skills">Skills</a> |
            <a href="#projects">Projects</a> |
            <a href="#education">Education</a> |
            <a href="#contact">Contact</a>
        </nav>
    </header>

    <hr>

    <main>

        <section id="about">
            <h2>About Me</h2>
            <p>
                Hello! My name is Prerna Sharma. I am a student interested
                in technology, programming, artificial intelligence,
                and data analytics.
            </p>
            <p>
                I enjoy learning new technologies and building projects
                that help me improve my technical and problem-solving skills.
            </p>
            <a href="#home">Back to Home</a>
        </section>

        <hr>

        <section id="skills">
            <h2>My Skills</h2>
            <ul>
                <li>HTML and CSS</li>
                <li>Java Programming</li>
                <li>Python Programming</li>
                <li>Data Analytics</li>
                <li>Microsoft Excel</li>
                <li>Power BI</li>
            </ul>
            <a href="#home">Back to Home</a>
        </section>

        <hr>

        <section id="projects">
            <h2>My Projects</h2>

            <article>
                <h3>Healthcare Cost Burden Dashboard</h3>
                <p>
                    A data visualization project designed to analyze
                    healthcare costs and present useful insights.
                </p>
            </article>

            <article>
                <h3>HR Analytics Dashboard</h3>
                <p>
                    A dashboard project focused on understanding workforce
                    data and identifying important HR trends.
                </p>
            </article>

            <article>
                <h3>Banking Customer Analysis</h3>
                <p>
                    A project that explores customer data to identify
                    patterns and support data-driven decisions.
                </p>
            </article>

            <a href="#home">Back to Home</a>
        </section>

        <hr>

        <section id="education">
            <h2>Education</h2>
            <p>
                Bachelor of Computer Applications (BCA)
                with a specialization in Artificial Intelligence.
            </p>
            <p>University: Invertis University</p>
            <a href="#home">Back to Home</a>
        </section>

        <hr>

        <section id="contact">
            <h2>Contact Me</h2>
            <p>
                Email:
                <a href="mailto:your-email@example.com">
                    your-email@example.com
                </a>
            </p>

            <p>
                GitHub:
                <a href="https://github.com/" target="_blank" rel="noopener noreferrer">
                    Visit GitHub
                </a>
            </p>

            <a href="#home">Back to Home</a>
        </section>

    </main>

    <hr>

    <footer>
        <p>&copy; 2026 Prerna Sharma. All rights reserved.</p>
        <p>Thank you for visiting my portfolio!</p>
    </footer>

</body>
</html>

# Question 12 : images-with-alt.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Images with Alt Text</title>
</head>
<body>

    <header>
        <h1>Working with Images in HTML</h1>
        <p>This webpage demonstrates how to add images using HTML.</p>
    </header>

    <main>

        <section>
            <h2>Image 1: Nature</h2>
            <img
                src="images/nature.jpg"
                alt="A beautiful green landscape surrounded by mountains"
                width="400"
                height="250">
            <p>This image represents the beauty of nature.</p>
        </section>

        <hr>

        <section>
            <h2>Image 2: Technology</h2>
            <img
                src="images/technology.jpg"
                alt="A laptop displaying programming code on its screen"
                width="400"
                height="250">
            <p>This image represents technology and programming.</p>
        </section>

        <hr>

        <section>
            <h2>Image 3: Education</h2>
            <img
                src="images/education.jpg"
                alt="Books and a notebook arranged on a study table"
                width="400"
                height="250">
            <p>This image represents education and learning.</p>
        </section>

        <hr>

        <section>
            <h2>Example of an Image That Cannot Load</h2>
            <img
                src="images/unavailable-image.jpg"
                alt="An image that is currently unavailable"
                width="400"
                height="250">
            <p>
                If the image cannot load, the browser may display
                the alternative text.
            </p>
        </section>

    </main>

    <footer>
        <p>&copy; 2026 HTML Practice Assignment</p>
    </footer>

</body>
</html>



