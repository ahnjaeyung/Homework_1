# Homework_1

Changed all generic <div> tags to semantic elements such as <header>, <nav>, <section>, <article>, <aside>, and <footer> tags.

Changed the <h2> tag in <footer> into <h4> tag because <h2> was already being used above.

Changed the title from "website" to "Horiseon Social Solution Services".

Added alt attributes to images in <section> and <aside>.

Moved "color: #ffffff;" from ".benefit-lead{}", ".benefit-brand{}", and ".benefit-cost{}" to ".benefit{}" in style.css. 

Removed (style.css):
    .benefit-lead h3 {
      margin-bottom: 10px;
        text-align: center;
    }

    .benefit-brand h3 {
        margin-bottom: 10px;
        text-align: center;
    }

    .benefit-cost h3 {
        margin-bottom: 10px;
        text-align: center;
    }
Added (style.css):
    h3 {
    margin-bottom: 10px;
    text-align: center;
    }

Removed (style.css):
    .benefit-lead img {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }

    .benefit-brand img {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }

    .benefit-cost img {
        display: block;
        margin: 10px auto;
        max-width: 150px;
    }
Added (style.css):
    .benefits img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
    }

Removed (style.css):
    .search-engine-optimization {
        margin-bottom: 20px;
        padding: 50px;
        height: 300px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        background-color: #0072bb;
        color: #ffffff;
    }

    .online-reputation-management {
        margin-bottom: 20px;
        padding: 50px;
        height: 300px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        background-color: #0072bb;
        color: #ffffff;
    }

    .social-media-marketing {
        margin-bottom: 20px;
        padding: 50px;
        height: 300px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        background-color: #0072bb;
        color: #ffffff;
    }
Added (style.css):
    .search-engine-optimization, .online-reputation-management, .social-media-marketing {
        margin-bottom: 20px;
        padding: 50px;
        height: 300px;
        font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
        background-color: #0072bb;
        color: #ffffff;
    }

Removed (style.css):
    .search-engine-optimization img {
        max-height: 200px;
    }

    .online-reputation-management img {
        max-height: 200px;
    }

    .social-media-marketing img {
        max-height: 200px;
    }
Added (style.css):
    .content img {
        max-height: 200px;
    }

Removed (style.css):
    .search-engine-optimization h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }

    .online-reputation-management h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }

    .social-media-marketing h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }
Added (style.css):
    h2 {
        margin-bottom: 20px;
        font-size: 36px;
    }

link to deployed application: https://ahnjaeyung.github.io/Homework_1/
