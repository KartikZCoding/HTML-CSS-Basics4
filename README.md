# Create Responsive Webpage using HTML & CSS

### Here's Desktop Wireframe of WebPage
![Second Web Development.png](https://github.com/KartikZCoding/HTML-CSS-Basics4/blob/3b2fe62a332b73c5d04eefcf448ea55bb86234b9/My%20Second%20Web%20Page.png)

### Here's Mobile or Tablet Wireframe of WebPage
![Second Web Development.png](https://github.com/KartikZCoding/HTML-CSS-Basics4/blob/3b2fe62a332b73c5d04eefcf448ea55bb86234b9/Responsive%20Design.png)

### HTML Code
```HTML
<!DOCTYPE html>
<html>

<head>
    <title>JOb's OP</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link
        href="https://fonts.googleapis.com/css2?family=Inter:wght@100..900&family=Roboto:ital,wght@0,400;0,500;0,700;0,900;1,400&display=swap"
        rel="stylesheet">
    <link rel="icon" href="./Images/job-logo.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
</head>

<body>
    <!-- Header -->
    <header>
        <div id="navbar">
            <img id="logo" src="./Images/job-logo.png" alt="logo">
            <img id="logo-text" src="./Images/job-logo.png" alt="logo-with-text">
            <span id="logo-name">Job's Op</span>
        </div>
    </header>

    <!-- Banner Image -->
    <div id="banner-image">
        <img id="banner" src="./Images/banner.jpg" alt="Banner Image">
    </div>

    <!-- About -->
    <h1 id="about-head">
        About Job's
    </h1>
    <div id="about">
        <div id="description">
            <p id="texts-desc" style="margin-top: 0;">
                Jobs are evolving with technology and globalization, creating diverseopportunities in remote work, gig
                economy, and automation. Continuous learning, inclusivity, and jobsatisfaction are crucial for thriving
                in the dynamic labor market.</p>
            <p>
                We also offer 2 industry-focused bootcamp:
            <ol>
                <li>
                    <a target="_blank" href="#">FullStack Developer Bootcamp</a>
                </li>
                <li>
                    <a target="_blank" href="#">Data Science Bootcamp</a>
                </li>
            </ol>
            </p>
        </div>
        <div id="team">
            <img id="team-image" src="./Images/team.jpg" alt="Team Working Image">
        </div>
    </div>

    <!-- Jobs Opportunities -->
    <h2>Job Opportunities</h2>
    <div id="jobs">

        <div id="jobs-list">
            <div class="job">
                <div class="job-title">Frontend Developer</div>
                <div class="job-detail">Bengaluru, India</div>
                <div class="job-detail">₹ 12,00,000</div>
                <div class="job-detail">Posted Mar 3, 2023</div>
            </div>
            <div class="job">
                <div class="job-title">Full Stack Developer</div>
                <div class="job-detail">New Delhi, India</div>
                <div class="job-detail">₹ 15,00,000</div>
                <div class="job-detail">Posted Feb 1, 2023</div>
            </div>
            <div class="job">
                <div class="job-title">Data Scientist</div>
                <div class="job-detail">San Francisco, USA</div>
                <div class="job-detail">$175,000</div>
                <div class="job-detail">Posted Dec 22, 2022</div>
            </div>
            <div class="job">
                <div class="job-title">ML Engineer</div>
                <div class="job-detail">Remote</div>
                <div class="job-detail">$80,000</div>
                <div class="job-detail">Posted Sep 19, 2022</div>
            </div>
        </div>

        <table id="jobs-table">
            <tr class="jobs-header-row">
                <th rowspan="2">Job Title</th>
                <th colspan="2">Location</th>
                <th rowspan="2">Salary</th>
                <th rowspan="2">Posted On</th>
            </tr>
            <tr class="jobs-header-row">
                <th>City</th>
                <th>Coutry</th>
            </tr>
            <tr class="jobs-data-row">
                <td>Frontend Develoer</td>
                <td>Bengaluru</td>
                <td>India</td>
                <td>₹12,00,000</td>
                <td>Mar 3, 2023</td>
            </tr>
            <tr class="jobs-data-row">
                <td>Full Stack Developer</td>
                <td>New Delhi</td>
                <td>India</td>
                <td>₹15,00,000</td>
                <td>Feb 1, 2023</td>
            </tr>
            <tr class="jobs-data-row">
                <td>Data Scientist</td>
                <td>San Francisco</td>
                <td>USA</td>
                <td>$175,000</td>
                <td>Dec 22, 2022</td>
            </tr>
            <tr class="jobs-data-row">
                <td>ML Engineer</td>
                <td colspan="2">Remote</td>
                <td>$80,000</td>
                <td>Sep 19, 2022</td>
            </tr>
        </table>
    </div>

    <div id="application">
        <h2>Sumbit Your Application</h2>

        <form id="application-form" action="https://formbold.com/s/oJn7B" method="POST" enctype="multipart/form-data">
            <div class="form-group">
                <label for="name">Name</label><br>
                <input type="text" name="name" id="name" placeholder="Domjoi">
            </div>

            <div class="form-group">
                <label for="email">Email</label><br>
                <input type="tel" name="email" id="email" placeholder="abcd@gmail.com">
            </div>

            <div class="form-group">
                <label for="phone">Phone</label><br>
                <input type="number" name="phone" id="phone" placeholder="+918060583476">
            </div>

            <div class="form-group">
                <label for="dob">Date</label><br>
                <input type="date" name="dob" id="dob">
            </div>

            <div class="form-group">
                <label for="position">Position Applied</label><br>
                <select name="Position Applied" id="position">
                    <option value="">Select Position</option>
                    <option value="frontend">Frontend Developer</option>
                    <option value="fullstack">Full Stack Developer</option>
                    <option value="datascience">Data Science</option>
                    <option value="mlengineer">Ml Engineer</option>
                </select>
            </div>

            <div class="form-group">
                <label for="resume">Resume</label><br>
                <input type="file" name="resume" id="resume" accept=".pdf,.doc,.docx">
            </div>

            <div class="form-group">
                <label for="coverlatter">Cover Latter</label><br>
                <textarea name="coverlatter" id="coverlatter" rows="5"
                    placeholder="Explain what make you suitable for the job.."></textarea>
            </div>

            <div class="form-group">
                <label for="terms">
                    <input type="checkbox" name="terms" id="terms"> I agree to the terms and conditions
                </label>
            </div>

            <div class="form-group">
                <input type="submit" name="" id="" value="Submit">
            </div>
        </form>
    </div>

    <!-- Footer -->
    <div id="footer">
        <ul id="footer-links">
            <li>
                <a target="_blank" href="#">Cources</a>
            </li>
            <li>
                <a target="_blank" href="#">Programs</a>
            </li>
            <li>
                <a target="_blank" href="#">Youtube</a>
            </li>
        </ul>
        <span id="copyright">© 2024, Job's Op</span>
    </div>

</body>

</html>
```
### CSS Code
```CSS
/* Base Style (extra small device) */
html{
  font-size: 14px;
}

body {
  margin: 0;
  padding: 0;
  font-family: 'Roboto', sans-serif;
  font-size: 1rem;
  color: #444444;
}

h1, h2, h3, h4, h5, h6 {
  font-family: 'Inter', sans-serif;
  font-weight: 600;
  color: #222222;
}

h1 { font-size: 2.5rem; }
h2 { font-size: 2rem; }
h3 { font-size: 1.75rem; }
h4 { font-size: 1.5rem; }
h5 { font-size: 1.25rem; }
h6 { font-size: 1rem; }

a {
  text-decoration: none;
  color: #3b82f6;
}

a:hover {
  color: #1D4ED8;
}

#navbar {
  display: flex;
  align-items: center;
  max-width: 100%;
  padding: 8px;
  margin: 0;
  gap: 8px;
}

#navbar img {
  height: 45px;
}

#logo-name {
  font-weight: bold;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
  font-size: 25px;
}

#logo {
  display: block;
}

#logo-text, #logo-name {
  display: none;
}

#banner {
  width: 100%;
  object-fit: cover;
  height: 200px;
}

#about-head {
  text-align: center;
  margin: 12px 0;
}

#about {
  display: flex;
  flex-direction: column;
  max-width: 500px;
  margin: 0 auto;
  padding: 8px;
}

#texts-desc {
  text-align: justify;
}

#description {
  font-size: 1.25rem;
}

#team {
  width: 100%;
}

#team-image {
  border-radius: 5px;
  width: 100%;
}

h2 {
  text-align: center;
  margin: 4px 0px 12px 0px;
}

#jobs {
  max-width: 500px;
  margin: 0 auto;
  padding: 0 8px;
}

#jobs-list {
  display: block;
}

#jobs-table {
  display: none;
}

.job {
  border: 1px solid #dddddd;
  border-radius: 5px;
  margin-top: 8px;
  padding: 8px;
}

.job-title {
  font-size: 1.25rem;
  font-weight: 500;
  color: #222222;
}

.job-detail {
  margin-top: 4px;
  color: #555555;
}

#application {
  max-width: 500px;
  margin: 0 auto;
  padding: 0 8px;
}

#application h2 {
  margin-top: 20px;
}

.form-group {
  margin: 16px 0  ;
}

.form-group label {
  font-weight: 600;
  font-size: 1.15rem;
}

.form-group input, select, textarea {
  width: 90%;
  padding: 4px;
  font-size: 1.25rem;
  margin-top: 4px;
  border-radius: 5px;
  border: 1px solid gray;
}

.form-group textarea {
  font-family: 'Roboto', sans-serif;
}

.form-group input[type="checkbox"] {
  width: 16px;
  height: 16px;
}

.form-group input[type="submit"] {
  background-color: #3b82f6;
  color: white;
  font-weight: 500;
  padding: 12px;
  cursor: pointer;
}

#footer {
  background-color: #E2E8F0;
  padding: 8px;
  padding-bottom: 20px;
  margin-top: 35px;
  text-align: center;
}

#footer-links {
  list-style: none;
  padding: 0;
}

#footer-links li {
  margin: 8px 16px;
}

#copyright {
  color: #6b7280;
}

/* Small Devices (tablets) */
@media screen and (min-width: 576px) {
  html{
    font-size: 16px;
  }

  #logo {
    display: none;
  }
  
  #logo-text, #logo-name {
    display: block;
  }

  #banner {
    height: 250px;
  }

  #about-head {
    margin: 16px 0;
  }

  h2 {
    margin: 4px 0px 16px 0px;
  }

  #application h2 {
    margin-top: 20px;
  }

  .form-group input, select, textarea{
    width: auto;
  }

  .form-group textarea {
    width: 80%;
  }

  #footer-links li {
    display: inline;
  }
}


/* Medium Devices (laptops) */
@media screen and (min-width: 768px) {
  #banner {
    height: 300px;
  }

  #about-head {
    margin: 20px 0;
  }

  #about {
    max-width: 800px;
    flex-direction: row;
  }

  #description {
    width: 50%;
    padding-right: 8px;
  }

  #team {
    width: 50%;
  }
  
  #team-image {
    border-radius: 5px;
    width: 100%;
  }

  h2 {
    margin: 4px 0px 20px 0px;
  }

  #jobs {
    min-width: 800px;
  }

  #jobs-list {
    display: none;
  }

  #jobs-table {
    display: table;
    width: 100%;
    border: 1px solid gray;
    border-collapse: collapse;
  }

  .jobs-header-row th{
    border: 1px solid gray;
    padding: 8px;
    background-color: #bae6fd;
    text-align: center;
    color: #222222;
  }

  .jobs-data-row td {
    border: 1px solid gray;
    padding: 8px;
  }

  #jobs-table tr:nth-child(odd) {
    background-color: #e0f2fe;
  }

  #application {
    max-width: 800px;
  }

  #application h2 {
    margin-top: 30px;
  }
}


/* Large Devices (desktops) */
@media screen and (min-width: 992px) {
  
}

/* Extra Large Devices (large desktops) */
@media screen and (min-width: 1200px) {
  
}
```
### Here's all Images
<a href="https://github.com/KartikZCoding/HTML-CSS-Basics4/tree/3b2fe62a332b73c5d04eefcf448ea55bb86234b9/src/Images">
    <img src="https://github.com/KartikZCoding/Other-Files/blob/29c62f9aa8abe0470d9e2d75c809940a786cf035/image-logo.png" alt="Image Icon" height="90px">
</a>
