# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Clone the GitHub repository and create a Django admin interface.
### Step 2:
Write HTML and CSS code for designing book cover page and execute them.
## Code:
```
<!DOCTYPE html>
<html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            color:red;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(bgimage.jpg);
            background-size: cover;
        }
         .insight{
            color: brown;

        }

        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: red;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
            }
        .id {
            width:400px;
            position: relative;
            top:180px;
             }
        .pub{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color: blue;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
             left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">
                SEC INSIGHT
            </div>
            <div class="hrstyle">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Life After 18 yrs old</h1></div>
            <div class="subtitle">
                Trust the timing of your life
                </div>
                 <div class="mypic">
                <img src="myphoto.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>Manisha selvakumari.S.S.</b></p>
            </div>
            <div class="pub">
                SEC
            </div>
            <div class="ed">
                <b>Third Edition</b>
            </div>
        </div>
    </body>
</html>
```

## Output:
![image](https://github.com/MANISHA21SS/cover-page-design/assets/147474298/3dee1c93-22ea-48b3-9a8e-870766237e12)


## Result:
The program for designing book cover page using HTML and CSS is executed successfully.
