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

Developed by: Shashin prasad.S
Reg no:212222230144

### sample.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NK PRIVATE LIMITED</title>
    <link rel="stylesheet" href= "./css/layout.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>NK PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitemselected"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="homecontent">
          <h1>About Us</h1>
          <img src="/static/img/bmw.png" alt="Building" />
          <div class="contenttext">
            NK PRIVATE LIMITED  is the exclusive dealer for BMW across Tamil Nadu and runs world class 4S (Sales, Service, Spares, Systems) facilities across the state. Trusted by many proud owners and adding more to the BMW family, NK PRIVATE LIMITED continues to remain committed in setting high benchmarks in sales and after sales in the luxury automotive sector across Tamil Nadu in Chennai, Ambattur, Coimbatore and in Puducherry.

            NK PRIVATE LIMITED team works with one motto – providing you with facts and details to make an informed decision and thereby helping you find the right BMW for yourself. We believe that it is essential to completely understand customer requirements and showcase the options that would best match his or her style, comfort and finances. All of this is further made easy by financing and leasing options made available by our BMW Financial Services team.

            NK PRIVATE LIMITED takes great pride in its state-of-art BMW Certified Service facilities across Tamil Nadu. Each of these facilities is fully equipped equipment and BMW trained technicians. With all these facilities we are ready to cater to our customers’ desires and exceed with BMW their expectations.

You know you have come to the right place when you reach a NK PRIVATE LIMITED facility. Feel free to walk into any of our facilities across Tamil Nadu or call us. It would be our pleasure to welcome you to any of our offices at your convenience. We look forward to share the sheer driving pleasure experience of a BMW with you.
            <br />
            
            <ul>
              <li>MODERN</li>
              <li>LUXURY</li>
              <li>CLASSIC</li>
            </ul>
          </div>
        </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 NK PRIVATE LIMITED DEVELOPED BY G.R.NANDHAKUMAR.
      </div>
    </div>
  </body>
</html>
```
### product.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NK Private Limited</title>
    <link rel="stylesheet" href="./css/layout.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>NK PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitemselected">
          <a href="/static/product.html">Products</a>
        </div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <div class="content">
        <div class="productcontent">    
          <h1><b>OUR PREMIUM PRODUCTS</b></h1>
          <div class="productitems">
              <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bmw x1.jpeg" alt="product image">
                  </div>
                  <div class="itemname">BMW X1</div>
                  <div class="itemprice">Price: Rs:2.40CR </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/bmw 7 series.jpeg"  alt="product image">
                  </div>
                  <div class="itemname">BMW 7 SERIES</div>
                  <div class="itemprice">Price: Rs:2.7CR </div>
              </div>
          <div class="productitem"> 
                  <div class="itemimage">
                  <img src="/static/img/m8.jpeg" alt="product image">
                  </div>
                  <div class="itemname">BMW M8</div>
                  <div class="itemprice">Price: Rs:2.65CR</div>
              </div>
              <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw i4.jpeg" alt="product image">
                </div>
                <div class="itemname">BMW I4</div>
                <div class="itemprice">Price: Rs:2.9CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw x3(upt).jpg" alt="product image">
                </div>
                <div class="itemname">BMW X3</div>
                <div class="itemprice">Price: Rs:2.10CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw i7.jpg" alt="product image">
                </div>
                <div class="itemname">BMW I7</div>
                <div class="itemprice">Price: Rs:3.10CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw ix.jpeg" alt="product image">
                </div>
                <div class="itemname">BMW IX</div>
                <div class="itemprice">Price: Rs:3.50CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw 3 series.jpeg" alt="product image">
                </div>
                <div class="itemname">BMW 3 series</div>
                <div class="itemprice">Price: Rs:2.4CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw z4.jpg" alt="product image">
                </div>
                <div class="itemname">BMW Z4</div>
                <div class="itemprice">Price: Rs:3.10CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw 6 series.jpg" alt="product image">
                </div>
                <div class="itemname">BMW 6 series</div>
                <div class="itemprice">Price: Rs:1.65CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw 5 series.jpg" alt="product image">
                </div>
                <div class="itemname">BMW 5 series</div>
                <div class="itemprice">Price: Rs:2.15CR</div>
            </div>
            <div class="productitem"> 
                <div class="itemimage">
                <img src="/static/img/bmw xm.jpg" alt="product image">
                </div>
                <div class="itemname">BMW XM</div>
                <div class="itemprice">Price: Rs:3.65CR</div>
            </div>
          </div>
          </div>        
      </div>
      <div class="footer">
        Copyright &#169; 2023 NK PRIVATE LIMITED DEVELOPED BY G.R.NANDHAKUMAR.
      </div>
    </div>
  </body>
</html>
 ```
### people.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NK PRIVATE LIMITED</title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>NK PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitemselected"><a href="/static/people.html">People</a></div>
        <div class="menuitem"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
              <h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;Our Proud Management Crew!!!</h2>
              <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/chairman.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                    Oliver Zipse (Chairman)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/headexe.jpeg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Ritu Chandy (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/headexe2.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                 Kathrin Frauscher (Head Executive)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/manager1.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Xavier Naxxy (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/manager2.jpeg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                 sheeta Lakshmi (Manager)</h2></centre>
                  <centre>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  <img src="/static/img/robert.jpg" height="600" width="600"><br><h2>&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;&emsp;
                  Robert Downy Jr (Deputy Manager)</h2></centre>
      </div>
      <div class="footer">
        Copyright &#169; 2023 NK PRIVATE LIMITED DEVELOPED BY G.R.NANDHAKUMAR.
      </div>
    </div>
  </body>
</html>
```
### contact.html
```
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>NK PRIVATE LIMITED </title>
    <link rel="stylesheet" href="./css/contact.css" />
    <link rel="icon" href="/static/img/bmw.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="banner"><b>NK PRIVATE LIMITED.</b></div>
      <div class="menu">
        <div class="menuitem"><a href="/static/sample.html">Home</a></div>
        <div class="menuitem"><a href="/static/product.html">Products</a></div>
        <div class="menuitem"><a href="/static/people.html">People</a></div>
        <div class="menuitemselected"><a href="/static/contact.html">Contact Us</a></div>
      </div>
      <body>
          <div class="content">
            <h1>&emsp;Contact Us</h1>
                    <p><b>&emsp;Here are the details listed below. Do contact us for any need</b></p>
                    <b><h2>&emsp;Contact Information:</h2></b>
                    <p><b>&emsp;&ensp;Address:</b>
                         No:6A,Thirumangalaam main road,Chennai,Tamilnadu,India.
                    </p>
                    <ul>
                        <li><b>&emsp;Phone</b>:&emsp;9934567789</li>
                        <li><b>&emsp;Shop owner no</b>:&emsp;9586456745</li>
                        <li><b>&emsp;Shop Manager Number:</b>7010586334</li>
                        <li><b>&emsp;Email Id:</b>&emsp;nkprivatelimited1@gmail.com</li>
                        <li><b>&emsp;Email Id:</b>&emsp;nkprivatelimited2@gmail.com</li>
                    </ul>
          </div>
          </div>
      </div>
      <div class="footer">
        Copyright &#169; 2023 NK PRIVATE LIMITED DEVELOPED BY G.R.NANDHAKUMAR.
      </div>
    </div>
  </body>
</html>
```
### layout.css
```
*{
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  
  body {
    background-color:#260a65e5;
    color: #09d7ee;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-color: aquamarine;
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: #09d7ee;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color:  #09d7ee;
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
    color:  #09d7ee;
  }
  
  .menuitem a {
    text-decoration: none;
    color: darkblue;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color:darkblue;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color: #09d7ee;
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
    background-color: #09d7ee;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: #1b044ce5;
  }
  
   ```     
### contact.css
```
* {
    box-sizing: border-box;
    font-family: Arial, Helvetica, sans-serif;
  }
  body {
    background-color: darkblue;
    color: #09d7ee;
    background-image: url("/static/img/background2.jpg");
    background-repeat: no-repeat;
    background-size: cover;
  }
  .container {
    width: 1080px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
    box-shadow: 15px 15px 8px white;
  }
  
  .banner {
    display: block;
    width: 100%;
    height: 250px;
    text-align: center;
    font-size: 60px;
    font-family: inherit;
    background-image: url("/static/img/Hero-banner.jpg");
    background-size: 100% 100%;
    margin: 0px 0px 0px 0px;
    padding-top: 150px;
    color: #09d7ee;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 50px;
    font-size: larger;
    background-color: #09d7ee;
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
    color: #09d7ee;
  }
  
  .menuitem a {
    text-decoration: none;
    color: darkblue;
  }
  
  .content {
    display: block;
    width: 100%;
    background-color: darkblue;
    font-size: 20px;
    min-height: 500px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
    border-color:#09d7ee;
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
    background-color:#09d7ee;
    text-align: center;
    padding-top: 10px;
    margin: 0px 0px 0px 0px;
    color: darkblue;
  }
  ```

## OUTPUT:

### Home page:
![NK about us](https://github.com/shashinprasad/productcompanywebsite/assets/129143499/c97162e2-c094-47ef-a2f8-fcb343ddba26)


### Product page:
![NK product page](https://github.com/shashinprasad/productcompanywebsite/assets/129143499/58afdfe7-978c-42cb-9228-f22c17eb93fa)


### People page:
![NK people page](https://github.com/shashinprasad/productcompanywebsite/assets/129143499/9865429a-c83a-4057-aeb1-65777f80052b)


### Contact page:
![NK contact page](https://github.com/shashinprasad/productcompanywebsite/assets/129143499/1ae6bdb7-b050-4a3e-8e85-87e1ce8ed2b6)


### Server page:
![server page](https://github.com/shashinprasad/productcompanywebsite/assets/129143499/f682a501-3398-47ae-a717-ebbfc1bf4f6a)


## Result:

Thus a website is designed for the software product company and the HTML,CSS code are validated.
