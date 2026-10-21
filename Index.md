HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Job Application Form</title>
</head>
<body>

    <!-- Header Section -->
    <header>
        <h1>Career Application Portal</h1>
        <p>Please complete the application form below to apply for an open position.</p>
    </header>

    <main>
        <!-- Job Application Form -->
        <form action="#" method="POST">
            
            <!-- Full Name -->
            <div>
                <label for="fullname">Full Name:</label><br>
                <input type="text" id="fullname" name="fullname" placeholder="e.g., Alex Johnson" required>
            </div>

            <br>

            <!-- Email -->
            <div>
                <label for="email">Email Address:</label><br>
                <input type="email" id="email" name="email" placeholder="e.g., alex.johnson@example.com" required>
            </div>

            <br>

            <!-- Phone Number -->
            <div>
                <label for="phone">Phone Number:</label><br>
                <input type="tel" id="phone" name="phone" placeholder="e.g., 555-0199" required>
            </div>

            <br>

            <!-- Date of Birth -->
            <div>
                <label for="dob">Date of Birth:</label><br>
                <input type="date" id="dob" name="dob" required>
            </div>

            <br>

            <!-- Portfolio URL -->
            <div>
                <label for="portfolio">Portfolio URL:</label><br>
                <input type="url" id="portfolio" name="portfolio" placeholder="https://example.com">
            </div>

            <br>

            <!-- Radio Buttons for Preferred Shift -->
            <div>
                <label>Preferred Shift:</label><br>
                <input type="radio" id="shift-morning" name="shift" value="morning" checked>
                <label for="shift-morning">Morning Shift</label><br>
                
                <input type="radio" id="shift-evening" name="shift" value="evening">
                <label for="shift-evening">Evening Shift</label>
            </div>

            <br>

            <!-- Checkboxes for Skills -->
            <div>
                <label>Technical Skills:</label><br>
                <input type="checkbox" id="skill-html" name="skills" value="html">
                <label for="skill-html">HTML5</label><br>

                <input type="checkbox" id="skill-css" name="skills" value="css">
                <label for="skill-css">CSS3</label><br>

                <input type="checkbox" id="skill-js" name="skills" value="javascript">
                <label for="skill-js">JavaScript</label>
            </div>

            <br>

            <!-- Dropdown for Job Role -->
            <div>
                <label for="role">Applying for Role:</label><br>
                <select id="role" name="role" required>
                    <option value="" disabled selected>-- Select a Job Role --</option>
                    <option value="frontend">Frontend Developer</option>
                    <option value="backend">Backend Developer</option>
                    <option value="fullstack">Full-Stack Developer</option>
                </select>
            </div>

            <br>

            <!-- Textarea for Cover Letter -->
            <div>
                <label for="coverletter">Cover Letter:</label><br>
                <textarea id="coverletter" name="coverletter" rows="5" cols="40" placeholder="Tell us why you'd be a great fit..."></textarea>
            </div>

            <br>

            <!-- Example of a Disabled Field -->
            <div>
                <label for="status">Application Status:</label><br>
                <input type="text" id="status" name="status" value="Draft (Not Submitted)" disabled>
            </div>

            <br>

            <!-- Submit Button -->
            <div>
                <button type="submit">Submit Application</button>
            </div>

        </form>
    </main>

</body>
</html>