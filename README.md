# Homework_1

Changed all generic <div> tags to semantic elements such as <header>, <nav>, <section>, <article>, <aside>, and <footer> tags.

Changed the title from "website" to "Horiseon Social Solution Services".

Added alt attributes to images in <section> and <aside>.

Moved "color: #ffffff;" from ".benefit-lead{}", ".benefit-brand{}", and ".benefit-cost{}" to ".benefit{}" in style.css. 

Removed:
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
Added:
    h3 {
    margin-bottom: 10px;
    text-align: center;
    }

Removed:
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
Added:
    .benefits img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
    }