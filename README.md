<!-- Design your personal web page -->
<!-- 1. Basic Tags. [10%] -->
<!-- 2. Background: Set a background color. [10%] -->
<!-- 3. Font: Different types of fonts and different font colors and sizes. [10%] -->
<!-- 4. Headings: Two different headings. [10%] -->
<!-- 5. Images: Images with link, image description (mouse cursor). [10%] -->
<!-- 6. Links: Two links, link to section of page, link to other web page. [10%] -->
<!-- 7. Email. [10%] -->
<!-- 8. Lists. [10%] -->
<!-- 9. Misc: at least TWO different horizontal dividing lines. [10%] -->
<!-- 10. Div: use Div to organized your webpage into left and right division. [10%] -->

<!DOCTYPE html>
<html>

<head>
    <style>
        /*  CSS  */
        h1 {
            font-family: 'Bush Script MT',
        cursive;
        }
        h2 {
            font-family: 'Courier New',
        cursive;
        }
        h3 {
            font-family: 'Garamond, serif',
        cursive;
        }
        .test{
            overflow: hidden;
        }
        .photo{
            float:left;
            width:35%
        }
        .text{
            float:right;
            width:60%
        }
    </style>
</head>

<body style="background-color:rgb(155, 209, 171)"style="display:flex;">
    <!-- Don't forget to submit HTML file to your GitHub repository -->
    <!-- Write your code here -->
    <div class="photo",center>
        <img src="bb.jpg"style="width:150px;height:150px;"title="hi"/>
        <br>
        <a href="#x">name</a>
        <br>
        <a href="https://www.youtube.com/">youtube</a>
        <br>
        <a href="mailto:t110590019@ntut.org.tw">Send email</a>
    </div>    
    <div class="text",center>
        <h1 style="color:Tomato;">Biography</h1>
        <h2 style="background-color:rgb(255, 99, 71);"id="x">Name</h2>
        <p>Benson</p>
        <h3 style="background-color:rgb(255, 71, 227);">Birthday</h3>
        <p>91/11/24</p>
        <hr/>
        <ol>
            <li>學號:110590019</li>
            <li>性別:男</li>
            <li>學歷:高中畢業</li>
        </ol>
        <hr/>
    </div>
</body>

</html>
