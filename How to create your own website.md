# How to create a personal Github Site

1. Go to <https://github.com> and create a Github account

2. Login to your new account and click "New repository"

3. Name your new repository *<span><font color = "orange">username.github.io</font></span>*, where<font color = "orange"> *username*</font> matches your Github username

4. Initialize your repository with a README file and create the repository

5. Install Chrome Extension [EXLcode](https://chrome.google.com/webstore/detail/exlcode-vs-code-based-onl/elcfpiphmolcddmecegalaikjiclhdjc?hl=en) and open the IDE. If you are not using Chrome, go to the editor [directly](http://exlcode.com/ide).

6. Sign in to your Github account on the EXLcode IDE

7. Click "Choose Repository" and select the repository you just created

8. Create a new file and name it <font color = "orange">index.html</font>

9. Add the following text to your "index.html" file and replace the text with your personal information
```html
<!DOCTYPE html>
<html>
  <head>
    <title>Hello World!</title>
    <script async src="./javascript/index.js"></script>
    <link rel="stylesheet" href="styles/styles.css" />
  </head>
  <body>
    <img id= "self-portrait" src="https://exlinc.com/wp-content/uploads/2017/10/freelancer-image-02.png" alt="freelancer-image-02">
    <h1 id="name">John Doe</h1>
  </body>
  <div id="introduction"> 
    <h2 id='utc'></h2>
    <h1 id="about">About Me</h1>
    <div id="details">
      Name: John Doe <br/>
      Age: 25<br/>
      Occupation: Freelancer<br/>
      Education Level: Bachelor<br/>
      Country: United States<br/>
      Favourite Food: Steak<br/>
      Hobbies:
      <ul>
        <li>Reading</li>
        <li>Football</li>
        <li>Photography</li>
      </ul> </br> 
    </div>
    <div id="contact">
      Contact Information:
    </div>
    <div id="details"> <font color = "white">
      Address: 111 Grove Street, South Bend, IN 11111 </br>
      Phone Number: +1 (111) 111-1111 </br>
      Email: johndoe@johndoe.com
    </font></div>
  </div>
</html>
```
10. Create a new folder in your repository called <font color = "orange">javascript</font>

11. In your "javascript" folder, create a file named <font color = "orange">index.js</font>

12. Add the following text to your "index.js" file
```js
document.getElementById('utc').innerHTML = "Last Updated: " + new Date().toDateString();
```

13. Create another folder in your repository called <font color = "orange">styles</font>

14. In your "styles" folder, create a file named <font color = "orange">styles.css</font>

15. Add the following text to your "styles.css" file
```css
body {
  text-align: center;
  background: linear-gradient(to right,#2980B9,#6DD5FA);
}
#self-portrait{
  position: absolute;
  right: 0px;
  width: 600px;
  padding: 10px;
}
#name{
  color: white;
  font-family: cursive;
  font-weight: 700;
  font-size: 50px;
}
#introduction{
  text-align: left;
  padding-left: 120px;
}
#utc{
  font-size: 20px;
}
#about{
  color: darkorange;
  font-weight: 900;
  padding-top: 10px;
  font-size: 30px;
}
#details{
  padding-top: 20px;
  font-size: 18px;
  font-weight: 500;
}
br{
  line-height: 150%;
}
#contact{
  color: yellow;
  padding-top: 0px;
  font-size: 24px;
}
```
16. Go to File -> Save and save each file individually with a commit message
17. Congratulations you've successfully set up your own personal website! Open up a new tab and go to *<span><font color = "orange">username.github.io</font></span>* to check out your website
18. Edit the HTML, JavaScript, and CSS files to further customize your website 