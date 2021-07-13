<!DOCTYPE html>
<html>
    <head>
        <title>My Blog</title>
<style>
html {
    margin: 0;
    padding: 0;
}
body {
    font-family: 'Handlee', cursive;
    font-size: 13pt;
    background-color: #efefef;
    padding: 10px;
    margin: 0;
}
h1 {
    font-size: 15pt;
    color: #20bcd5;
    text-align: center;
    padding: 18px 0 18px 0;
    margin: 0 0 10px 0;
}
h1 span {
    border: 4px dashed #20bcd5;
    padding: 10px;
}
p {
    padding: 0;
    margin: 0;
}
.img-circle {
    border: 3px solid white;
    border-radius: 50%;
}
.section {
    background-color: #fff;
    padding: 15px;
    margin-bottom: 10px;
    border-radius: 10px;
}
#header {
    background-image: url("https://cdn.pixabay.com/photo/2019/05/27/14/46/background-4232889_1280.png");
    background-size: cover;
}
#header img {
    display: block;
    width: 80px;
    height: 80px;
    margin: auto;
}
#header p {
    font-size: 25pt;
    color: #3b464c;
    padding-top: 5px;
    margin: 0;
    font-weight: bold;
    text-align: center;
}
.quote {
    font-size: 12pt;
    text-align: right;
    margin-top: 10px;
}
table {
    width: 100%;
}
table, th, td {
    border: 2px solid #cecece;
    border-collapse: collapse;
    text-align: center;
    table-layout: fixed;
}
.selected {
    background-color: #f36f48;
    font-weight: bold;
    color: white;
}
li {
    margin-bottom: 15px;
    font-weight: bold;
}
progress {
    width: 70%;
    height: 20px;
    color: #3fb6b2;
    background: #efefef;
}
progress::-webkit-progress-bar {
    background: #efefef;
}
progress::-webkit-progress-value {
    background: #3fb6b2;
}
progress::-moz-progress-bar {
    color: #3fb6b2;
    background: #efefef;
}
iframe, audio {
    display: block;
    margin: 0 auto;
    border: 3px solid #3fb6b2;
}
hr {
    border: 0;
    height: 1px;
    background: #f36f48;
}
form {
    text-align: center;
    margin-top: 0;
}
.submit {
    background-color: #3fb6b2;
    padding: 12px 45px;
    border-radius: 5px;
    cursor: pointer;
    color: #ffffff;
    border: none;
    outline: none;
    margin: 0;
    font-weight: bold;
}
.submit:hover {
    background-color: #43a09d;
}
textarea {
    height: 100px;
}
input, textarea {
    margin-bottom: 10px;
    font-size: 11pt;
    padding: 15px 10px 10px;
    border: 1px solid #cecece;
    background-color: #efefef;
    color: #787575;
    border-radius: 5px;
    width: 70%;
    outline: none;
}
.face {
    transform: scale(0.4);
    margin: 0 auto;
    display: block;
    margin-top: -35px;
    margin-bottom: -25px;
}
#contacts img {
    height: 50px;
    width: 50px;
    margin-left: 7px;
    margin-right: 7px;
}
#contacts a {
    text-decoration: none;
}
#contacts img:hover {
    opacity: 0.8;
}
#contacts {
    text-align: center;
}
.copyright {
    font-size: 8pt;
    text-align: right;
    padding-bottom: 10px;
    color: grey;
}

</style>
        <script>
            alert("Welcome to my blog page this page lets you know about me, basically this page is about myself,i have put down a form at the end to let you give your feedback.your feedback is stored nowhere so dont worry its only for fun.");
            function validatename() { //this function will alert the user that name field is empty
                if(document.myForm.name.value == "") {
                   alert("please enter a name");
                   }
            }
            function validatephone() { //this function will prompt the user that phone number is invalid
                if(document.myForm.PhoneNo.value < 9999999999) {
                    alert("Please Enter a Valid Phone no.");
                }
            }
        </script>
    </head>

    <body>
        <!-- header start -->
        <div id="header" class="section">
            <img alt="" class="img-circle" src="https://www.dlf.pt/png/big/14/140272_default-avatar-png.png">
            <p>Khushwant</p>
        </div>
        <!-- header end -->

        <!-- About Me start -->
        <div class="section">
            <h1><span>About Me</span></h1>
            <p>
                Hey! I'm <strong>khushwant</strong>. Coding has changed my world. It's not just about apps. Learning to code gave me <i>problem-solving skills</i> and a way to communicate with others on a technical level. I can also develop websites and use my coding skills to get things done. And I learned it all at <strong>by myself</strong>. Join me in this rewarding journey. You'll have fun, and learn along the way!
            </p>
            <p class="quote">"Declare variables, not war"</p>
        </div>
        <!-- About Me end -->

        <!-- My Schedule start -->
        <div class="section">
            <h1><span>My Coding Schedule</span></h1>
            <table>
                <tr>
                    <th>Day</th>
                    <th>Mon</th>
                    <th>Tue</th>
                    <th>Wed</th>
                    <th>Thu</th>
                    <th>Fri</th>
                </tr>
                <tr>
                    <td>8-8:30</td>
                    <td class="selected">Eat</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>9-10</td>
                    <td></td>
                    <td class="selected">Sleep</td>
                    <td></td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>1-1:30</td>
                    <td></td>
                    <td></td>
                    <td class="selected">Code</td>
                    <td></td>
                    <td></td>
                </tr>
                <tr>
                    <td>3:45-5</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td class="selected">Asla</td>
                    <td></td>
                </tr>
                <tr>
                    <td>6-6:15</td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td></td>
                    <td class="selected">Repeat</td>
                </tr>
            </table>
        </div>
        <!-- My Schedule end -->


        <!-- My Skills start -->
        <div class="section">
            <h1><span>My Skills</span></h1>
            <ul>
                <li>HTML <br />
                    <progress min="0" max="100" value="80"></progress>
                </li>
                <li>JavaScript <br />
                    <progress min="0" max="100" value="70"></progress>
                </li>
                <li>C <br />
                    <progress min="0" max="100" value="60"></progress>
                </li>
                <li>CSS <br />
                    <progress min="0" max="100" value="80"></progress>
                </li>
                <li>php <br />
                    <progress min="0" max="100" value="50"></progress>
                </li>
                <li>Python <br />
                    <progress min="0" max="100" value="85"></progress>
                </li>
                <li>C++ <br />
                    <progress min="0" max="100" value="75"></progress>
                </li>
            </ul>
        </div>
        <!-- My Skills end -->


         <!-- Media start -->
        <div class="section">
            <h1><span>My Media</span></h1>
            <right><iframe height="300" width="500" src="https://www.youtube.com/embed/gVqcUi9tpCw" allowfullscreen frameborder="0"></iframe></right>
            <br/>
            <iframe height="300" width="500" src="https://www.youtube.com/embed/GX8Hg6kWQYI" allowfullscreen frameborder="0"></iframe>
        </div>
        <!-- Media end -->

        <!-- Form start -->
       <div class="section">
            <h1><span>Give me Your Information</span></h1>

            <svg class="face" height="100" width="100">
                <circle cx="50" cy="50" r="50" fill="#FDD835"/>
                <circle cx="30" cy="30" r="10" fill="#FFFFFF"/>
                <circle cx="70" cy="30" r="10" fill="#FFFFFF"/>
                <circle cx="30" cy="30" r="5" fill="#000000"/>
                <circle cx="70" cy="30" r="5" fill="#000000"/>
                <path d="M 30 70 q 20 20 40 0" stroke="#FFFFFF" stroke-width="5" fill="none" />
            </svg>

            <form name="myForm" method="post">
                <input name="name" placeholder="Name" type="text" onblur="validatename()" /><br/>
                <input name="lastname" placeholder="lastname" type="text" /><br/>
                <input name="Age" placeholder="Age" type="number" min="1" required /><br/>
                <input name="PhoneNo" placeholder="Phone No." type="number" max="9999999999" onblur="validatephone()" /><br/>
                <input name="date" placeholder="date" type="date" required /><br/>
                <input name="email" placeholder="Email" type="email" required /><br/>
                <textarea name="message" placeholder="Message" required ></textarea>
               <!--i havent used this because it was told not to use this <input type="submit" value="SEND" class="submit" />-->
                <center>i haven't used a submit button since it was told not to but the coding is there in my file for the submit button</center>
           <br/>



           </form>
           <center>Here are some quick questions:</center>
                <h1>How Much do you like my Website ?</h1>

                         <input type="radio" checked="checked" name="radio">Its Awesome
                         <input type="radio" name="radio">Good
                        <input type="radio" name="radio">Ok
                        <input type="radio" name="radio">Bad

           <h1>what is the value of pie?</h1>

  <input type="checkbox">3.141
  <input type="checkbox">3.14159
  <input type="checkbox">3.14159265
  <input type="checkbox">all of these

        </div>
        <!-- Form end -->

        <!-- Contacts start -->
        <div class="section" id="contacts">
            <h1><span>Follow Me</span></h1>
            <div>
                <a href="#">
                    <img onclick="location.href = 'https://www.facebook.com/';" alt="Facebook" src="https://cdn.clipart.email/5b89a96f154a8105d767153819cc222b_facebook-logos-png-images-free-download_2000-2000.png"/>
                </a>
                <a href="#">
                    <img onclick="location.href = 'https://www.instagram.com/';" alt="Instagram" src="https://cdn3.iconfinder.com/data/icons/social-media-logos-flat-colorful/2048/5301_-_Instagram-512.png"/>
                </a>
                <a href="#">
                    <img  onclick="location.href = 'https://www.snapchat.com/';" alt="Snapchat" src="https://eurosagency.eu/wp-content/uploads/snapchat-logo-transparent.png"/>
                </a>
            </div>
        </div>
        <!-- Contacts end -->

        <!--this thing is to look my site more professional from line 345 to 347-->
        <div class="copyright">
            &copy; 2020 My Blog
        </div>

    </body>
</html>
