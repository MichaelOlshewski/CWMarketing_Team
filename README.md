# __*Horiseon Social Solution Services*__
This was a homework assignment for the Case Western Reserve University Coding Boot Camp.


## __Details About This Assignment__
The purpose of this project was to be in the place of either a front-end web developer or a junior web developer that is contracted by "Horiseon Social Solution Services to update their HTML and CSS to be more user friendly by using semantic HTML tags and industry standard practices including proper SEO.


### __Process I Used to Edit HTML__
The website was originally developed using div tags for almost all elements, including the header, footer and sections. The header was originally `<div class="header"></div>` with the css `.header {}`, I changed that over to `<header></header>` and changed the css to `header {}`. I repeated that same process for other `<div>` tags in the file, such as ones with body content and the side contents. I moved the body content to a `<section></section>` and the side content to an `<aside></aside>`. The HTML files also did not have proper file references for the css and image files, they all started with a `./assets/css/style.css` or `./assets/images/ImgName.jpg` and I changed them to `assets/css/styles.css` or `assets/images/ImgName.jpg`.


### __Process I Used to Edit CSS__
The CSS file has alot of different classes in them, even some had to same parameters for different classes, so I combined those using nesting `.className h1, .className2 h1, .className3 h1 {}`. I repeated this process for the whole css file, taking it down to only 142 total lines of classes and id's.