# cover-page-design
## AIM:
To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:
Write your own steps here.

### Step 2:
Make a new folder templates inside your app and create a html and map them using views and url.

### Step 3:
Write down the code for book cover using HTML and CSS.

### Step 4:
Add images and other contents using CSS record a screenshot of it.

## Code:

cover.html

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
            color: black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back2.jpg);
            background-size: cover;
        }
            

        .insight{
            color: pink;

        }

        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color: purple;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'permanent marker', Courier, monospace;
            font-size: larger;
            text-align: left;
            position: relative;
            top: 50px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            font-size: medium;
            position: relative;
            color: orchid;
            top:155px;
            left:330px;
        }
        .ed{
            color:orange;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: larger;
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
                <hr style="color: purple;">
            </div>
            <div class="booktitle">
                <h1>Machine Learning </h1></div>
            <div class="subtitle">
                For Absolute Beginners
            </div>
            <div class="mypic">
                <img src="/static/images/my9.jpg" width="95" height="125" alt="">
            </div>
            <div class="id">
                <hr style="color: indigo;">
            </div>
            <div class="author">
               <p><b>Theoblad</b></p>
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

## Client output:
![Screenshot (144)](https://github.com/Gopika-9266/cover-page-design/assets/122762773/67fe6517-f876-4439-90ad-cba977d94978)

## Server Output:
![Screenshot (146)](https://github.com/Gopika-9266/cover-page-design/assets/122762773/0a1b882f-190c-4789-a635-f12d8e0cc985)

## Html Validator:
![Screenshot (147)](https://github.com/Gopika-9266/cover-page-design/assets/122762773/a7886ee1-033d-472f-834a-5c4977611695)

## Result:
Thus a website to display the cover page design of a book was successfully created.
