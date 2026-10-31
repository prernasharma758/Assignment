# Question 16 : Student registration form.html

<!DOCTYPE html>
<html>
<head>
    <title>Student Registration Form</title>
</head>
<body>
    <h1>Student Registration Form</h1>
    <p>Please fill in the following details.</p>
    <form>
        <h2>Personal Details</h2>
        <label>Full Name:</label>
        <input type="text" name="name" required>
        <br><br>
        <label>Email:</label>
        <input type="email" name="email" required>
        <br><br>
        <label>Phone Number:</label>
        <input type="number" name="phone">
        <br><br>
        <label>Date of Birth:</label>
        <input type="date" name="dob">
        <br><br>
        <label>Gender:</label>
        <input type="radio" name="gender"> Male
        <input type="radio" name="gender"> Female
        <input type="radio" name="gender"> Other
        <br><br>
        <h2>Academic Details</h2>
        <label>Course:</label>
        <select name="course">
            <option>Select Course</option>
            <option>BCA</option>
            <option>BCA (AI)</option>
            <option>BBA</option>
            <option>B.Tech</option>
        </select>
        <br><br>
        <label>College Name:</label>
        <input type="text" name="college">
        <br><br>
        <label>Previous Qualification:</label>
        <input type="text" name="qualification">
        <br><br>
        <h2>Address Details</h2>
        <label>Address:</label>
        <br>
        <textarea name="address" rows="4" cols="30"></textarea>
        <br><br>
        <label>City:</label>
        <input type="text" name="city">
        <br><br>
        <label>State:</label>
        <input type="text" name="state">
        <br><br>
        <h2>Interests</h2>
        <input type="checkbox" name="interest" value="Coding">
        Coding
        <input type="checkbox" name="interest" value="Sports">
        Sports
        <input type="checkbox" name="interest" value="Reading">
        Reading
        <br><br>
        <label>Upload Photo:</label>
        <input type="file" name="photo">
        <br><br>
        <input type="checkbox" required>
        I confirm that all the information is correct.
        <br><br>
        <input type="submit" value="Register">
        <input type="reset" value="Reset">
    </form>
</body>
</html>

# Question 17 : Job application form.html

<!DOCTYPE html>
<html>
<head>
    <title>Job Application Form</title>
</head>
<body>
    <h1>Job Application Form</h1>
    <p>Please fill in your details to apply for the job.</p>
    <form>
        <h2>Personal Information</h2>
        <label>Full Name:</label>
        <input type="text" name="name" required>
        <br><br>
        <label>Email:</label>
        <input type="email" name="email" required>
        <br><br>
        <label>Phone Number:</label>
        <input type="tel" name="phone">
        <br><br>
        <label>Date of Birth:</label>
        <input type="date" name="dob">
        <br><br>
        <label>Gender:</label>
        <input type="radio" name="gender"> Male
        <input type="radio" name="gender"> Female
        <input type="radio" name="gender"> Other
        <br><br>
        <h2>Job Details</h2>
        <label>Position Applied For:</label>
        <select name="position">
            <option>Select Position</option>
            <option>Web Developer</option>
            <option>Data Analyst</option>
            <option>Software Developer</option>
            <option>AI Engineer</option>
        </select>
        <br><br>
        <label>Employment Type:</label>
        <input type="radio" name="employment"> Full Time
        <input type="radio" name="employment"> Part Time
        <input type="radio" name="employment"> Internship
        <br><br>
        <label>Expected Salary:</label>
        <input type="number" name="salary">
        <br><br>
        <h2>Educational Details</h2>
        <label>Highest Qualification:</label>
        <input type="text" name="qualification">
        <br><br>
        <label>College / University:</label>
        <input type="text" name="college">
        <br><br>
        <label>Skills:</label>
        <br>
        <input type="checkbox" name="skills" value="HTML"> HTML
        <input type="checkbox" name="skills" value="CSS"> CSS
        <input type="checkbox" name="skills" value="Java"> Java
        <input type="checkbox" name="skills" value="Python"> Python
        <br><br>
        <h2>Additional Information</h2>
        <label>Work Experience:</label>
        <br>
        <textarea name="experience" rows="4" cols="30"
        placeholder="Describe your experience"></textarea>
        <br><br>
        <label>Upload Resume:</label>
        <input type="file" name="resume">
        <br><br>
        <input type="checkbox" required>
        I confirm that all the information provided is correct.
        <br><br>
        <input type="submit" value="Submit Application">
        <input type="reset" value="Reset">
    </form>
</body>
</html>

# Question 18 : Size chart table.html

<!DOCTYPE html>
<html>
<head>
    <title>Size Chart Table</title>
</head>
<body>
    <h1>Clothing Size Chart</h1>
    <p>Find your correct clothing size using the table below.</p>
    <table border="1">
        <tr>
            <th>Size</th>
            <th>Chest (inches)</th>
            <th>Waist (inches)</th>
            <th>Hip (inches)</th>
        </tr>
        <tr>
            <td>XS</td>
            <td>32</td>
            <td>26</td>
            <td>34</td>
        </tr>
        <tr>
            <td>S</td>
            <td>34</td>
            <td>28</td>
            <td>36</td>
        </tr>
        <tr>
            <td>M</td>
            <td>36</td>
            <td>30</td>
            <td>38</td>
        </tr>
        <tr>
            <td>L</td>
            <td>38</td>
            <td>32</td>
            <td>40</td>
        </tr>
        <tr>
            <td>XL</td>
            <td>40</td>
            <td>34</td>
            <td>42</td>
        </tr>
        <tr>
            <td>XXL</td>
            <td>42</td>
            <td>36</td>
            <td>44</td>
        </tr>
    </table>
    <br>
    <h2>Size Guide</h2>
    <p>XS - Extra Small</p>
    <p>S - Small</p>
    <p>M - Medium</p>
    <p>L - Large</p>
    <p>XL - Extra Large</p>
    <p>XXL - Double Extra Large</p>
</body>
</html>

# Question 19 : Meta tags audit.html

<!DOCTYPE html>
<html>
<head>
    <title>Meta Tags Audit</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="This is my personal webpage created using HTML.">
    <meta name="keywords" content="HTML, Web Development, Programming, Student">
    <meta name="author" content="Prerna Sharma">
    <meta http-equiv="refresh" content="300">
</head>
<body>
    <h1>HTML Meta Tags Audit</h1>
    <p>Welcome to my webpage.</p>
    <h2>About This Page</h2>
    <p>
        This webpage demonstrates different HTML meta tags
        used to provide information about a website.
    </p>
    <h2>Meta Tags Used</h2>
    <ul>
        <li>Charset Meta Tag</li>
        <li>Viewport Meta Tag</li>
        <li>Description Meta Tag</li>
        <li>Keywords Meta Tag</li>
        <li>Author Meta Tag</li>
        <li>Refresh Meta Tag</li>
    </ul>
</body>
</html>

# Question 20 : Multipage project.html

<!DOCTYPE html>
<html>
<head>
    <title>My Personal Website</title>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        body {
            font-family: Arial;
            margin: 30px;
            line-height: 1.6;
        }
        nav a {
            margin-right: 20px;
            text-decoration: none;
            color: blue;
        }
        .page {
            display: none;
        }
        .page:target {
            display: block;
        }
        body:not(:has(.page:target)) #home {
            display: block;
        }
        img {
            width: 200px;
        }
        table {
            border-collapse: collapse;
            width: 50%;
        }
        th, td {
            border: 1px solid black;
            padding: 8px;
        }
    </style>
</head>
<body>
    <header>
        <h1>My Personal Website</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About Me</a>
            <a href="#registration">Registration</a>
            <a href="#contact">Contact</a>
        </nav>
    </header>
    <hr>
    <main>
        <!--Home Section -->
        <section id="home" class="page">
            <h2>Welcome to My Website</h2>
            <p>
                Hello! Welcome to my personal website.
                This website contains information about me,
                my education and my contact details.
            </p>
            <img src="https://picsum.photos/300/200" alt="Sample image">
            <h3>Website Sections</h3>
            <ul>
                <li><a href="#about">Know About Me</a></li>
                <li><a href="#registration">Registration Form</a></li>
                <li><a href="#contact">Contact Me</a></li>
            </ul>
        </section>
        <!-- About Me Section -->
        <section id="about" class="page">
            <h2>About Me</h2>
            <p>
                My name is Prerna Sharma. I am a BCA (AI) student.
                I am interested in learning technology, artificial
                intelligence and web development.
            </p>
            <h3>My Education Details</h3>
            <table>
                <tr>
                    <th>Details</th>
                    <th>Information</th>
                </tr>
                <tr>
                    <td>Name</td>
                    <td>Prerna Sharma</td>
                </tr>
                <tr>
                    <td>Course</td>
                    <td>BCA (AI)</td>
                </tr>
                <tr>
                    <td>University</td>
                    <td>Invertis University</td>
                </tr>
                <tr>
                    <td>Interest</td>
                    <td>AI and Data Analytics</td>
                </tr>
            </table>
        </section>
        <!-- Registration Section -->
        <section id="registration" class="page">
            <h2>Student Registration Form</h2>
            <form>
                <label>Full Name:</label><br>
                <input type="text" name="name" required>
                <br><br>
                <label>Email:</label><br>
                <input type="email" name="email" required>
                <br><br>
                <label>Date of Birth:</label><br>
                <input type="date" name="dob">
                <br><br>
                <label>Select Course:</label><br>
                <select name="course">
                    <option>BCA</option>
                    <option>BCA (AI)</option>
                    <option>BBA</option>
                    <option>B.Tech</option>
                </select>
                <br><br>
                <input type="submit" value="Register">
            </form>
        </section>
        <!-- Contact Section -->
        <section id="contact" class="page">
            <h2>Contact Me</h2>
            <p>You can contact me using the form below.</p>
            <form action="mailto:your-email@example.com" method="post" enctype="text/plain">
                <label>Your Name:</label><br>
                <input type="text" name="name" required>
                <br><br>
                <label>Your Email:</label><br>
                <input type="email" name="email" required>
                <br><br>
                <label>Your Message:</label><br>
                <textarea name="message" rows="5" cols="30"></textarea>
                <br><br>
                <input type="submit" value="Send Message">
            </form>
        </section>
    </main>
    <hr>
    <footer>
        <p>© 2026 My Personal Website. All Rights Reserved.</p>
        <a href="#home">Back to Home</a>
    </footer>
</body>
</html>
