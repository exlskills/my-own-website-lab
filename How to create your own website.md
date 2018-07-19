# How to create a personal Github Site

1. Go to <https://github.com> and create a Github account

![Step 1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%201.png)

2. Login to your new account and click "New repository"

![Step 2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%202.png)

3. Name your new repository *<span><font color = "orange">username.github.io</font></span>*, where<font color = "orange"> *username*</font> matches your Github username

![Step 3](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%203.png)

4. Initialize your repository with a README file and create the repository

![Step 4](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%204.png)

5. Install Chrome Extension [EXLcode](https://chrome.google.com/webstore/detail/exlcode-vs-code-based-onl/elcfpiphmolcddmecegalaikjiclhdjc?hl=en) and open the IDE. If you are not using Chrome, go to the editor [directly](http://exlcode.com/ide).

![Step 5-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%205%20(1).png)

![Step 5-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%205%20(2).png)

6. Sign in to your Github account on the EXLcode IDE

![Step 6](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%206.png)

7. Click "Choose Repository" and select the repository you just created

![Step 7](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%207.png)

8. Create a new file and name it <font color = "orange">index.html</font>

![Step 8-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%208%20(1).png)

![Step 8-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%208%20(2).png)

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

![Step 9](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%209.png)

10. Create a new folder in your repository called <font color = "orange">javascript</font>

![Step 10-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2010%20(1).png)

![Step 10-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2010%20(2).png)

11. In your "javascript" folder, create a file named <font color = "orange">index.js</font>

![Step 11-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2011%20(1).png)

![Step 11-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2011%20(2).png)

12. Add the following text to your "index.js" file
```js
document.getElementById('utc').innerHTML = "Last Updated: " + new Date().toDateString();
```

![Step 12](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2012.png)

13. Create another folder in your repository called <font color = "orange">styles.</font> Do not create the "styles" folder inside the "javascript folder"

![Step 13-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2013%20(1).png)

![Step 13-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2013%20(2).png)

14. In your "styles" folder, create a file named <font color = "orange">styles.css</font>

![Step 14-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2014%20(1).png)

![Step 14-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2014%20(2).png)

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

![Step 15](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2015.png)

16. Go to File -> Save and save each file individually with a commit message

![Step 16-1](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2016%20(1).png)

![Step 16-2](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2016%20(2).png)

17. Congratulations you've successfully set up your own personal website! Open up a new tab and go to *<span><font color = "orange">username.github.io</font></span>* to check out your website

![Step 17](https://raw.githubusercontent.com/Hellboy1008/Hellboy1008.github.io/master/Screenshots/Step%2017.png)

18. Edit the HTML, JavaScript, and CSS files to further customize your website 