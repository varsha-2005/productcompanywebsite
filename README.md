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

### COLOUR SCHEME
The color scheme of this CSS code includes a background color of #0B4F6C, text color of #17421d, banner text color of #F7CAC9, menu text color of #DCCCE3, selected menu text color of #F5FF98, and footer text color of #9c1018. The color scheme of this CSS code includes:

background color of dark blue
text color of dark green
banner text color of light pink
menu text color of light purple
selected menu text color of yellow
footer text color of dark red
Background Color and Text Color are COMPLEMENTARY.

## PROGRAM :
 ### home.html:
 ```
 <!DOCTYPE html>
<html lang="en">
  <head>
    <title>NEKOCHAN private limited </title>
    <link rel="stylesheet" href="/static/styles.css" type="text/css">
  </head>

  <body>
    <div class="container">
      <div class="banner">Neko Private Limited.</div>
      
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/product/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/images/robot.jpg" alt="tech">
          <div class="contenttext">
            At Neko, we understand the importance of technology in enhancing business efficiency and empowering <br>
            entrepreneurs. That's why we design our products to be user-friendly and adaptable to your specific needs.<br><br>
             Our latest offering,Neko Prime, takes this to the next level by making the <br>
             transition to automation and our platform simpler than ever before.<br>
              With an intuitive interface and customizable features, you can easily discover the <br>
              full potential of the product without needing to learn any new skills.<br>
               Edusoft Prime adapts to your unique business and working style,<br>
                providing greater flexibility and a transformed look and feel<br>
                 that will make you love it even more.<br>


            <ul>
              <li>Simple to learn, easier to use</li>
              <li>Insightful , actionable & customizable reports</li>
              <li>Anywhere, anytime and secure access</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 NEKOCHAN Private Limited, Developed by Varsha.
      </div>
    </div>
  </body>
</html>
```

### product.html :

```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>Nekochan Private Limited</title>
    <link rel="stylesheet" href="/static/styles.css" type="text/css">
    
  </head>

  <body>
    <div class="container">
      <div class="banner">Neko Private Limited.</div>
      <div class="menu">
     <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/product/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>Our Premium Products</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images//aot.jpg" alt="product image">
                  </div>
                  <div class="itemname">Attack On Titan</div>
                  <div class="itemprice">Price: Rs.200 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/bsd.webp"  alt="product image">
                  </div>
                  <div class="itemname">Bungo Stray Dogs</div>
                  <div class="itemprice">Price: Rs.350 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/demonslayer.jpg" alt="product image">
                  </div>
                  <div class="itemname">Demon Slayer</div>
                  <div class="itemprice">Price: Rs.450 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/dn.jpg" alt="product image">
                  </div>
                  <div class="itemname">Death Note</div>
                  <div class="itemprice">Price: Rs.290 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/hxh.jpg" alt="product image">
                  </div>
                  <div class="itemname">Hunter X Hunter</div>
                  <div class="itemprice">Price: Rs.500 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/jjk.jpg" alt="product image">
                  </div>
                  <div class="itemname">Jujutsu Kaisen</div>
                  <div class="itemprice">Price: Rs.440 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/jojo.jpg" alt="product image">
                  </div>
                  <div class="itemname">Jojo Bizarre Adventure</div>
                  <div class="itemprice">Price: Rs.300 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/mha.jpg" alt="product image">
                  </div>
                  <div class="itemname">My Hero Academia</div>
                  <div class="itemprice">Price: Rs.420 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/naruto.jpg" alt="product image">
                  </div>
                  <div class="itemname">Naruto</div>
                  <div class="itemprice">Price: Rs.280 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/op.jpg" alt="product image">
                  </div>
                  <div class="itemname">One Piece</div>
                  <div class="itemprice">Price: Rs.400 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/spyxfam.webp" alt="product image">
                  </div>
                  <div class="itemname">Spy X Family</div>
                  <div class="itemprice">Price: Rs.250 </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/tokyo.jpg" alt="product image">
                  </div>
                  <div class="itemname">Tokyo Revengers</div>
                  <div class="itemprice">Price: Rs.370 </div>
              </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 Nekochan Private Limited, Developed by Varsha.
      </div>
    </div>
  </body>
</html>
```

### people.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NEKOCHAN Private Limited</title>
    <link rel="stylesheet" href="/static/styles.css" type="text/css">
  </head>

  <body>
    <div class="container">
      <div class="banner">Neko Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/product/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1>PEOPLE AT NEKO</h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/kenjirotsuda.webp" alt="kenjiro tsuda">
                  </div>
                  <div class="itemname">Kenjiro Tsuda</div>
                  <div class="itemprice">Managing Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/marinainoue.webp"  alt="marina inoue">
                  </div>
                  <div class="itemname">Marina Inoue</div>
                  <div class="itemprice">Co-founder and Chairman of the Board </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/fujikaze.webp" alt="fuji kaze">
                  </div>
                  <div class="itemname">Fuji Kaze</div>
                  <div class="itemprice">Lead Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/saorihayami.webp" alt="saori hayami">
                  </div>
                  <div class="itemname">Saori Hayami</div>
                  <div class="itemprice">Independent Director India </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/takuyaeguchi.webp" alt="takuya eguchi">
                  </div>
                  <div class="itemname">Takuya Eguchi</div>
                  <div class="itemprice">Independent Director </div>
              </div>
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/images/yuiishikawa.webp" alt="yui ishikawa">
                  </div>
                  <div class="itemname">Yui Ishikawa</div>
                  <div class="itemprice">Independent Director </div>
              </div>
             
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2021 NEKOCHAN Private Limited, Developed by Varsha.
      </div>
    </div>
  </body>
</html>
```
### contactus.html:
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NEKOCHAN private limited</title>
    <link rel="stylesheet" href="/static/styles.css" type="text/css">

  </head>

  <body>
    <div class="container">
      <div class="banner">Neko Private Limited.</div>
      <div class="menu">
        <div class="menuitemselected"><a href="/home/">Home</a></div>
        <div class="menuitemselected"><a href="/product/">Products</a></div>
        <div class="menuitemselected"><a href="/people/">People</a></div>
        <div class="menuitemselected"><a href="/contactus/">Contact Us</a></div>
      </div>
      <div class="content">
          
            <h1>Contact Us</h1>
  <p>If you have any questions or feedback, please don't hesitate to reach out to us.</p>
  <ul>
    <li>Address: 123 Main Street, Mumbai, India</li>
    <li>Phone: +91 8765432109</li>
    <li>Email: contact@edusoft.com</li></ul>
  
<h2> Sales Inquiries</h2>

<ul><li>India 1800 103 11231800 572 3535</li></ul>
    <h2>Press Inquiries</h2> 
<ul><li>press@edusoft.com</li>

<li>Nanya Srivastava</li>
<li>nanya@edusoft.com</li></ul>
    <h2>Analyst Relations</h2> 

    <ul><li>Sandra Lo</li>
    <li>+1-925-924-9500</li>
    <li>pr@edosoft.com</li></ul>
        <h2>Customer Relations</h2> 

    <ul><li>Peter S. Balaji</li>
    <li>Director of Sales & Customer Service</li>
    <li>peterbalaji@edusoft.com</li>
    </ul>
    
  </div>
   <div class="footer">
        Copyright &#169; 2021 NEKOCHAN Private Limited, Developed by Varsha.
      </div>
      </div>
</body>
</html>
```
### style.css :
```
 * {
  box-sizing: border-box;
  font-family: Arial, Helvetica, sans-serif;
}
body {
  background-color: rgb(159, 219, 245);
  color: #000000;
}
.container {
  width: 1080px;
  margin-left: auto;
  margin-right: auto;
  border-width: 10px 10px 10px 10px;
  border-style: solid;
  box-shadow: 10px 10px 5px #D8D8D8;
}

.banner {
  width: 100%;
  height: 250px;
  text-align: right;
  padding-bottom:120px ;
  padding-right: 140px;
  font-size: 60px;
  background-image: url("/static/images/best.jpg");
  background-size: 100% 100%;
  margin: 0px 0px 0px 0px;
  padding-top: 100px;
  color: rgb(233, 223, 223);
}
 

.menu {
  display: block;
  width: 100%;
  height: 50px;
  font-size: larger;
  background-color: #74a7d1;
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
  color: rgb(212, 228, 69);
}

.menuitem a {
  text-decoration: none;
  color: #DCCCE3;
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
  background-color: #0d2e58;
  text-align: center;
  padding-top: 10px;
  margin: 0px 0px 0px 0px;
  color: #fff7f7;
}
```

## OUTPUT:

### Home page :
![homepage](https://user-images.githubusercontent.com/119288183/215257663-64f18d61-894d-477b-bb2e-8b93e40772ee.jpg)


###product page :

![product](https://user-images.githubusercontent.com/119288183/215257678-c4ffb556-781f-45e2-b915-060c4822a237.jpg)

### people page :

![people](https://user-images.githubusercontent.com/119288183/215257682-a9f56037-d504-4344-a50f-a69f10251617.jpg)

 
### contactus page :

![contactus](https://user-images.githubusercontent.com/119288183/215257686-a6452dc6-c8ae-4b24-abbf-4863844f573a.jpg)

### html validator :
![html](https://user-images.githubusercontent.com/119288183/215257691-6eae9795-b678-4b3b-9582-606e63bbb2db.jpg)




## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.

