# Ex-06-Book-Cover-Design
Name: POOJASREE B

Reference Number: 23012790

Department: CSE

## AIM:
To design a book-cover-design using HTML and CSS.
## DESIGN PROCEDURE:
## STEP 1:
Start define the document type as HTML.

## STEP 2:
Open the HTML structure with necessary head and body sections. In the head section ,set the title as Book Cover and define the styles for the bookcover.Use the CSS styles in the code.The styles include: background-color, background-image, background-position, background-repeat, cellpadding, font-size, font-family, display, line-height.
## STEP 3:
In the body section, create a division with the text with respective to the headings: "BESTSELLER", "The Kid who came from space", "My sister and I used to be close", " but now she is light years away...", "Bestselling author of Time Travelling ", " Ross Welford ".
## STEP 4:
Close the HTML structure.
## CODE:
```
<!DOCTYPE html>

    <html lang="en">
    <head>
        <title>Book Coverpage</title>
         <style>
       .bookpage
        {
            width:400px;
            height:650px;
            padding:20px;
            background-image:url("web cover.jpg") ;
            background-position: center;
            margin-left: 500px;
            background-repeat:no-repeat;
          }
        .h1
        {
            color:white;
        }

        .toptext
        {
            color:white;
            padding-left:5px;
            font-size: 14px;
            font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
        }
        .tophr
        {
            color:white;
            width:225px;
        }
        hr
        {
            color:white;
        }
        .booktitle
        {
            font-family:Arial, Helvetica, sans-serif ;
            color:white;
            padding:10px 10px 0px 10px;
            display:flex;
            align-items:center;
            justify-content:center ;
            /*margin-left:10px;
            margin-right:20px;*/
            line-height:normal;
            font-size: 22px;
        }
        .author
        {
            color:white;
            display:inline;
            position:relative;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            font-size: 20px;
            line-height: 5px;
        }

        .subtext
        {
            color:white;
            font-family: Arial, Helvetica, sans-serif;
            display:flex;
            line-height: 5px;
           /* margin-right:10px;
            margin-left:20px;*/
            font-size: 15px;
        }
        .footer
        {
            color:white;
            padding-top:180px;
        }
        .image
        {
            color:white;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 20px;
         }

        .bottomhr
        {
            color:white;
            width:400px;
        }
        img
        {
            width:90px;
            height: 100px;
            margin-right: 20px;
            vertical-align: bottom;
        }

        .edition
        {
            color:white;
            font-family: Arial, Helvetica, sans-serif;
            font-size: 12px;
            line-height:bottom;
        }
    </style>
    </head>
   <body>
    <div class="bookpage">
        <div class="toptext">BESTSELLER</div>
        <div class="tophr"><hr></div>
        <div class="booktitle"><h1>The Kid who came from space</h1></div>
        <h3 class="subtext">&nbsp;My sister and I used to be close</h3>
        <h3 class="subtext">&nbsp;but now she is light years away...</h3>
        <div class="footer">
            <h2 class="edition">&nbsp;&nbsp;Bestselling author of Time Travelling&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; <img src="web cover author.jpg"></h2>
            <div class="bottomhr"><hr></div>
            <div class="author"><h3>&nbsp;&nbsp;Ross Welford&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;</h3></div>
        </div>
    </div>
   </body>
    
    
</html>
```
## OUTPUT:
![Alt text](<Screenshot 2023-12-16 191248.png>)

## RESULT:
Thus the book-cover design has been successfully created using HTML and CSS.