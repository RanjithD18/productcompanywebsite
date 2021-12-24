# Web Design for a Software Product Company

## AIM:

To design a static website for a software product company company.

## DESIGN STEPS:

### Step 1:

Requirement collection.

### Step 2:

Creating the layout using HTML and CSS.

### Step 3:

Updating the sample content.

### Step 4:

Choose the appropriate style and color scheme.

### Step 5:

Validate the layout in various browsers.

### Step 6:

Validate the HTML code.

### Step 6:

Publish the website in the given URL.

## PROGRAM :
### Home Page Code:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Avengers Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Avengers</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/home.html">Home</a></div>
        <div class="menuitem"><a href="/static/products.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="./img/ironman_PNG12.png" alt="ironman" />
          <div class="contenttext">
             <b>Hello! Thanks for dropping into our store. 
            We hope you found something you love. The AVENGERS store is a space for fans, by fans. 
            We are fanboys and our aim is to create a space which celebrates the love of movies, TV shows, comics and all things pop culture.</b> 
            <br /><br><br>
            We take a lot of effort to try and provide fans like you with an awesome range of products that connects with you, is unique and most importantly is of great quality.
            We hope we have been able to give you this today. However, if you are less than happy with something you have picked from us, please feel free to reach out to me or my colleagues on the contact numbers mentioned at the end of this & we will be happy to assist you.
            <br>
            To tell you a bit more about us, here are 4 quick facts about us:
            <ul>
              <li>We're a young Saveetha Engineering College student</li>
              <li>We're big superhero fans and our team and us don't miss any new Marvel movieand series.</li>
              <li>Our first store was launched in M.G.R Street, Chennai & response we now have 8 physical stores across Bangalore, Mumbai, Chennai, Hyderabad, Pune and Surat.</li>
              <li>We sell only original merchandise, which means the content producers get a royalty per piece we sell.</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2021 Avengers Private Limited, Developed by Ranjith D.
      </div>
    </div>
  </body>
</html>
~~~
### Products Page Code:
~~~<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Avengers Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Avengers</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Hawkeye.png" alt="Hawkeye Bow">
                  </div>
                  <div class="itemname">Hawkeye Bow</div>
                  <div class="itemprice">Price: &#8377; 1,000.00 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/Captain.png"  alt="Captain Shield">
                  </div>
                  <div class="itemname">Captain Shield</div>
                  <div class="itemprice">Price: &#8377; 3,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Trick.jpg"  alt="Hawkeye Trick Arrow">
                </div>
                <div class="itemname">Hawkeye Trick Arrow</div>
                <div class="itemprice">Price: &#8377; 5,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/falcon.png"  alt="Falcon Wings">
                </div>
                <div class="itemname">Falcon Wings</div>
                <div class="itemprice">Price: &#8377; 10,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/Winter.png"  alt="Winter Soldier Arm">
                </div>
                <div class="itemname">Winter Soldier Metal Arm</div>
                <div class="itemprice">Price: &#8377; 13,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/war.png"  alt="War Machine armor">
                </div>
                <div class="itemname">War Machine Armor</div>
                <div class="itemprice">Price: &#8377; 20,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/spider.jpg"  alt="Spiderman Web Shooter">
                </div>
                <div class="itemname">Spiderman Web Shooter</div>
                <div class="itemprice">Price: &#8377; 25,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/iron.png"  alt="Ironman Armor">
                </div>
                <div class="itemname">Ironman Armor</div>
                <div class="itemprice">Price: &#8377; 40,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/eye.png"  alt="Eye of Agamotto">
                </div>
                <div class="itemname">Eye of Agamotto</div>
                <div class="itemprice">Price: &#8377; 45,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/hulkb.png"  alt="HulkBuster">
                </div>
                <div class="itemname">HulkBuster Armor</div>
                <div class="itemprice">Price: &#8377; 60,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/dr.png"  alt="Dr Strange Cape">
                </div>
                <div class="itemname">Dr Strange Cape</div>
                <div class="itemprice">Price: &#8377; 75,000.00 </div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/infinity.png"  alt="Infinity Gauntlet">
                </div>
                <div class="itemname">Infinity Gauntlet</div>
                <div class="itemprice">Price: &#8377; 1,00,000.00 </div>
              </div>

          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Avengers Private Limited, Developed by Ranjith D
      </div>
    </div>
  </body>
</html>
~~~
### People Page Code:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Avengers Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
        <div class="banner">Avengers</div>
        <div class="menu">
          <div class="menuitem"><a href="/static/home.html">Home</a></div>
          <div class="menuitem">
            <a href="/static/products.html">Products</a>
          </div>
          <div class="menuitemselected"><a href="/static/people.html">People</a></div>
          <div class="menuitem"><a href="/static/contactus.html">Contact Us</a></div>
        </div>
        <div class="content">
            <div class="productcontent"> 
                <h1>Our Leadership</h1>
                <div class="productitems">
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/Robert.png" alt="Robert Downey Jr">
                        </div>
                        <div class="itemname">Robert Downey Jr</div>
                        <div class="itemprice"><b>Chairman</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/chris.png" alt="Chris Evans">
                        </div>
                        <div class="itemname">Chris Evans</div>
                        <div class="itemprice"><b>Chief Executive Officer</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/hem.png" alt="Chris Hemsworth">
                        </div>
                        <div class="itemname">Chris Hemsworth</div>
                        <div class="itemprice"><b>Managing Director</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/mark.png" alt="Mark Ruffalo">
                        </div>
                        <div class="itemname">Mark Ruffalo</div>
                        <div class="itemprice"><b>Chief Operating Officer</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/scar.png" alt="Scarlett Johansson">
                        </div>
                        <div class="itemname">Scarlett Johansson</div>
                        <div class="itemprice"><b>Executive Director</b></div>
                    </div>
                    <div class="productitem"> 
                        <div class="itemimage">
                        <img src="/static/img/Jeremy.png" alt="Jeremy Renner">
                        </div>
                        <div class="itemname">Jeremy Renner</div>
                        <div class="itemprice"><b>Director</b></div>
                    </div>
                </div>
            </div>
            <div class="footer">
                Copyright &#169; 2021 Avengers Private Limited, Developed by Ranjith D
              </div>
        </div>
    </body>
</html>
~~~
### Contact Us Page Code:
~~~
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Avengers Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner">Avengers</div>
      <div class="menu">
        <div class="menuitem"><a href="/static/home.html">Home</a></div>
        <div class="menuitem">
          <a href="/static/products.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contactus.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">
            <h2>Contact Info</h2>
            <div>AMR Tech Park II,No.23 & 24,<br>
                Madhavaram, M.G.R Main Road,<br> 
                Chennai 600 068, India<br>
                Customer Care:1800 129 2183<br>
                E-mail: avengerpvt@gmail.com
            </div>
        </div>
       </div>
       <div class="footer">
        Copyright &#169; 2021 Avengers Private Limited, Developed by Ranjith D
      </div>
    </div>
   </body>
</html> 
~~~
### CSS Code:
~~~
* {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: whitesmoke;
  color: #17421d;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 1px 1px 1px 1px;
  border-style: solid;
  box-shadow: 15px 15px 8px gray;
}
.banner {
  display: block;
  width: 100%;
  height: 250px;
  text-align: left;
  font: italic small-caps bold 12px/30px
  Georgia, serif;
  font-size: 60px;
  background-image: url("/static/img/44846.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 20px;
  padding-left: 10px;
  color: #da0303;
}

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #530201;
  text-align: center;
  padding-top: 15px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
}

.menuitem {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
}
.menuitemselected {
  display: inline-block;
  margin-left: 10px;
  margin-right: 10px;
  color: whitesmoke;
}

.menuitem a {
  text-decoration: none;
  color: whitesmoke;
}

.content {
  display: block;
  width: 100%;
  background-color: #cffffd;
  min-height: 500px;
  margin: 0px 0px 0px 0px;
  border-width: 1px;
  border-color: white;
  border-style: solid;
}
.homecontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}
.homecontent h1 {
  text-align: left;
}
.homecontent img {
  float: right;
  width: 400px;
  height: 300px;
  margin-left: 10px;
}

.contenttext {
  text-align: justify;
}

.productcontent {
  min-height: 500px;
  margin: 10px 10px 10px 10px;
}

.productcontent h1 {
  text-align: left;
}

.productitems {
  display: block;
}

.productitem {
  display: inline-block;
  width: 30%;
  height: 250px;
  text-align: center;
}

.productitem img {
  width: 100px;
  height: 100px;
  display: block;
}
.productitem .itemimage {
  display: block;
  margin-left: auto;
  margin-right: auto;
  width: 100px;
  margin-bottom: 5px;
}

.productitem .itemname {
  display: block;
}
.productitem .itemprice {
  display: block;
}

.footer {
  display: block;
  width: 100%;
  height: 40px;
  background-color: #530201;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: whitesmoke;
}
~~~

## OUTPUT:

### Home Page:

![Home](https://github.com/RanjithD18/productcompanywebsite/blob/main/Screenshot%20(34).png?raw=true)

### Products Page:
![products](https://github.com/RanjithD18/productcompanywebsite/blob/main/Screenshot%20(35).png?raw=true)

### People Page:
![People](https://github.com/RanjithD18/productcompanywebsite/blob/main/Screenshot%20(36).png?raw=true)

### Contact Us Page:
![contactus](https://github.com/RanjithD18/productcompanywebsite/blob/main/Screenshot%20(38).png?raw=true)
## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
