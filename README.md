# Ex-06-Book-Cover-Design
To develop a website to display the cover page design of a book

# Design Steps :

Step 1:

Create a new Django project and app.

Step 2:

Create a static file directory and mention the changes in settings.

Step 3:

Make a new folder templates inside your app and create a html and map them using views and url.

Step 4:

Write down the code for book cover using HTML and CSS.

Step 5:

Add images and other contents using CSS record a screenshot of it.
# Code :
```
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Book Coverpage</title>
        <style>
        h1{
           color:white;
        }
         .bookpage{
             width: 400px;
             height: 650px;
             
             margin-left: auto;
             margin-right: auto ;
             padding: 20px;
             background-image: url("wp8903918.webp");
             background-size: 500px 300px;
             background-position: center;
             background-color: black;
             background-repeat: no-repeat;
         }
         .toptext{
             color:white;
             padding-left: 5px;
             font-size: 14px;
             font-family: Arial, Helvetica, sans-serif;
             
         }
         .tophr{
             color: orange;
              width: 180px;
         }
         hr{
             color: orange;
            
         }
         .booktitle{
             font-family: Arial, Helvetica, sans-serif;
             padding: 10px 10px 0px 10px;
             display: flex;
             margin-right: 10px;
             margin-left: 10px;
             font-size: 20px;
             line-height:normal;
         }
         .author{
             color:white;
             display:inline;
             position:relative;
             font-family: Arial, Helvetica, sans-serif;
             display: inline;
             font-size: 24px;
             line-height: 5px;
              
             
         }
         .sub-text {
             color:white;
             position: 14px;
             font-family: Arial, Helvetica, sans-serif;
             display: flex;
             line-height: 5px;

            
            
        margin-right: 10px;
        margin-left: 10px;

        font-size: 14px;
        }
        
        .footer {
            color:orange;
            padding-top:180px;
        }
        .image {
            color:white;
                    font-family: Arial, Helvetica, sans-serif;
            font-size: 22px;
            margin-right: px;
        }
        .bottomhr { 
            color: red;
                    width: 400px;

        }
        img {
            width: 90px;
            height: 100px;
            margin-right: 20px;
            vertical-align:bottom;
        }
        .edition {
            color:orange;
                    font-family: Arial, Helvetica, sans-serif;
            font-size: 22px;
            line-height: bottom;
        
        }
        
        div.relative {
            position: relative;
            left: 12px;
          }
        div.edit{
            position: relative;
            left: 12px;
            
          }
        
          div.image{
            position: relative;
            top: 45px;
            left:69%;
          }

        </style>z
        </head>
            <body>
                <div class="bookpage">
                    <div class="toptext">EXPERT INSIGHT</div>
                    <div class="tophr"><hr></div> 
               <div class="booktitle"><h1>MERN STACK</h1></div>
               <h3 class="sub-text"><div class="relative">
                Full Stack Web App Devolopment with
                </div>
                </h3>
                <h3 class="sub-text"><div class="relative">
                    Mongo DB - Express JS - React JS - Node JS
                    </div></h3>
                    <div class="footer">
                            <div class="image">
                                <img src="1648826979292.jpg">
                            </div>
                            
                            <div class="edit">
                                <h2>Third Edition</h2>
                            </div>         
                      
                        <div class="bottomhr"><hr></div>
                    <div class="author"><h3><div 
                        class =relative>Valeri Karpov </div></h3></div>
                    
                </div>
                </div> 
                
            </body>
        
    
</html>

```
# Output :
![Screenshot 2023-12-20 083221](https://github.com/Naveenganesan1/cover-page-design/assets/145181288/7e519339-43f5-4c9c-8abe-4786ee8a3b54)

# Result :

Successfully designed a website to display the cover page of the book "Mern Stack".
