[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-c66648af7eb3fe8bc4f294546bfd86ef473780cde1dea487d3c4ff354943c9ae.svg)](https://classroom.github.com/online_ide?assignment_repo_id=9405835&assignment_repo_type=AssignmentRepo)
<!DOCTYPE html>
<html>
<body>
  <div id="Hour of Code Event">
  <h1>
   Hour of Code Event
  </h1>
  </div>
  <p>On November 15, at 1p.m, we held an <strong>Hour of Code Event</strong>, at Jabrayil district's Sirik village secondary school named after asgar Veysalov, located in Binagadi district.
    <br>We organized this event for an 8th grade class that consisted of 23 students. Nijat Huseynzada gave information about our university, the faculties and teaching staff, and explained some examples from the code.org website(<a href="./index.html"> code.org </a>) Nazrin Muradova gave information about ADA students'successes and the international competitions they participated in, provided information about the code. org website, and explained some. Teymur Aliyev explained the examples after giving information about student life, educational benefits, and career services at the university.</br>
    <br>After informing the students, we divided them into teams, organized a competition, and awarded the winning team with a certificate. In the end, we left school with good impressions of the students. </br>
  </p>
  <strong> Pictures from our event:</strong>
  
  <title>Image slider</title>
  <link rel="stylesheet" href="style.css">
  <!--image slider start-->
    <div class="slider">
      <div  class="slides">
        <!--radio buttons start-->
        <input type="radio" name="radio-btn" id="radio1">
           <input type="radio" name="radio-btn" id="radio2">
              <input type="radio" name="radio-btn" id="radio3">
                 <input type="radio" name="radio-btn" id="radio4">
                   <!--radio buttons end-->
                   <!--slide images start-->
                   <div class="slide first">
        <img src="1.jpg" alt="img1">
          </div>
        <div  class="slide">
        <img src="2.jpg" alt="img2">
          </div>
          <div  class="slide">
        <img src="3.jpg" alt="img3">
          </div>
            <div  class="slide">
        <img src="4.jpg" alt="img4">
    </div>
              <!--slide images end-->
              <!--automatic navigation start-->
              <div class="navigation-auto">
              <div class="auto-btn1"></div>
              <div class="auto-btn2"></div>
              <div class="auto-btn3"></div>
                <div class="auto-btn4"></div>     
  </div>
              <!--automatic navigation end-->
            </div>
            <!--manual navigation start-->
            <div class="navigation-manual">
              <label for="radio1" class="manual-btn"></label>
          </div>
          <!--manual navigation end-->
          </div>
          <!--image slider end-->
          
          <script type="text/javascript">
            var counter= 1;
            setInterval(function(){
            document.getElementById('radio' + counter).ckecked = true;
            counter++;
            if(counter . 4){
            counter = 1;
            }
            }, 5000);
          </script>
  <p>These characteristics of the students motivated us to present our presentation even better:
  <ul>
    <li>Their interest in computer-based majors</li>
    <li>Their respect for each other during the competition</li>
    <li>They listened carefully to our explanations</li>
  </ul>
  </p>
    <a href="https://m.facebook.com/story.php?story_fbid=pfbid033Lub35s8nTkFHTGykBPL1o6xetEBxgTEDc6mLYSXz4jKLzkEsvKCLRCjuzNUzUAkl&id=100010207180693&mibextid=qC1gEa"> Show more</a>
</body>
</html>
