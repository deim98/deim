<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Application</title>
  </head>
  <body>
      <header>
          <nav>
              <ul>
                  <li><a href="assignment 11.html">Home</a></li>
              </ul>
          </nav>
          <img src="altschool.png" alt="logo" width="100px">
      <p><h1>Application Form</h1>
       Fill in your details</p>
    </header>
    <main id="main">
      <section>
        <form action="assignment 11.html" method="get" aria-label="Form">
          <label for="firstname">Firstname*</label>
          <input type="text" name="firstname" placeholder="Firstname" />
          <label for="lastname">lastname*</label>
          <input type="text" name="lastname" placeholder="Lastname" />
          <br /> <br>
          <label for="Gender">Gender*</label>
            <select name="Gender" place>
              <option value="default" disabled selected>Select Gender</option>
              <option value="male">male</option>
              <option value="Female">Female</option>
            </select>
            <label for="Date of Birth">Date of Birth*</label>
            <input type="date" name="Date of Birth">
            <br><br>
            <label for="Email Address">Email Address*</label>
            <input type="email" name="Email Address" placeholder="Enter Email Address">

            <label for="Education Level">Education Level*
            <select name="Education Level">
              <option value="default" disabled selected>Select level of education</option>
              <option value="Bsc">Bsc</option>
              <option value="Msc">Msc</option>
              <option value="Diploma">Diploma</option>
              <option value="Doctorate(phD)">Doctorate (phD)</option>
              <option value="Post Graduate">Post Graduate</option>
              <option value="Under Graduate">Under Graduate</option>
              <option value="highschool/secondary school">high school/secondary school</option>
              <option value="Junior / Middleschool">Junior / Middleschool</option>
            </select>
            <br><br>
            <label for="country">country*</label>
            <input type="text" name="country" placeholder="Enter your country">
            <label for="state/city of residence">State/city of residence*</label>
            <input type="text" name="state/city of residence" placeholder="Enter State/city of residence">
            <br><br>
            <label for="Employment Status">Employment Status</label>
            <select name="status">
              <option value="default" disabled selected>Select employment status</option>
              <option value="Unemployed">Unemployed</option>
              <option value="employed">Employed</option>
              <option value="Self-employed">Self-employed</option>
              </select>
              <label for="Phone number">Phone Number*</label>
              <input type="text" placeholder="08058964220">
              <br><br>
              <label for="Choose School">Choose School*</label>
            <select name="Choose School">
              <option value="default" disabled selected>Select school</option>
              <option value="Data">School of Data</option>
              <option value="engineering">School of Engineering</option>
              <option value="Product">School of Product</option>
              </select>
              <label for="Choose course of study">Course of Study*</label>
            <select name="course of study">
              <option value="default" disabled selected>Select Course of Study</option>
              <option value="Data">Data Analysis</option>
              <option value="engineering">Backend  Engineering</option>
              <option value="Product">School of Product</option>
              <option value="Fengineering">Backend  Engineering</option>
              <option value="Product">School of Product</option>
              <option value="engineering">Cloud  Engineering</option>
              <option value="Product"> Product Design</option>
              </select>
              <br><br>
              <label for="question">How did you hear about us?*</label>
              <input type="text" name="question" placeholder="eg.twitter">
              <label for="scholarship">Scholarship/Discount Code (optional)</label>
              <input type="text" name="scholarship" placeholder="Scholarship or student ID or discount codes">
        </form>
        <br><br>
        <p>By clicking continue, I agree to  <a href="#">Terms of Use</a> and acknowledge that I have read the  <a href="#">Privacy Policy.</a></p>

        <button>proceed</button>
        <br><br>
        <b>Already have an account?<a href="#">sign in</a></b>
      </section>
    </main>
  </body>
</html>
