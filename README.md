# __*Horiseon Social Solution Services*__
This was a homework assignment for the Case Western Reserve University Coding Boot Camp.


## __Details About This Assignment__
The purpose of this project was to be in the place of either a front-end web developer or a junior web developer that is contracted by "Horiseon Social Solution Services to update their HTML and CSS to be more user friendly by using semantic HTML tags and industry standard practices including proper SEO.


## Changes to HTML
Changed `<div class="header"></div>` to `<header></header>`. <br>
Changed the `<div></div>` used for navigation to `<nav></nav>`. <br>
Changed `<div class="hero"></div>` to: `<figure><img src="" class="hero" alt="" /></figure>`. <br>
Added `<main></main>` to inform browser there is a main content area. <br>
Changed `<div class="content"></div>` to `<section class="content"></section>`. <br>
Changed other `<div></div>`'s to `<section></section>`'s. <br>
Changed `<div class="content"></div>` to `<aside class="benefits"></aside>`. <br>
Changed `<div class="footer"></div>` to `<footer></footer>`. <br>




## Changes to CSS

Combined multiple classes with the same styles to one, such as:
```
.benefit-lead,
.benefit-brand,
.benefit-cost {
    margin-bottom: 32px;
    color: #ffffff;
}
```
I continued that througout the whole CSS document for other classes with the same declarations. <br>

I also changed the corresponding classes such as `.header` or `.footer` to `header` and `footer` to work with the previous `<div>`'s that were changed over to semantic HTML.
