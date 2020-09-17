In this project, you will implement 3 web pages with Bootstrap. You will use all HTML/CSS/Accessibility/Responsive design/Bootstrap knowledges that you learned previously.

You won't have a lot of instruction, you are free to implement it the way that you want - the objective is simple: Have fully functional web pages that look the same as the designer file.

Here the final result:

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3c71cc99d2fc1c12a3d3.jpg?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=aaf8e7ad688cb8bece724617495d5ba7716a37e32bbebee4a6ecbdf57f3141a7)

This webpage has been designed by Nicolas Philippot, UI/UX designer. You can find final screens [here](https://intranet.hbtn.io/rltoken/zWn015BC2IEC-6_59KDpvw "here")

### Requirements

-   You have to use Bootstrap
-   Your `styles.css` must be as small as you can - **you must use as much as you can Bootstrap classes**

### Imports

For this project, you will need: fonts from Google, JQuery, Bootstrap CSS/JS

```
<link href="https://fonts.googleapis.com/css?family=Source+Sans+Pro&display=swap" rel="stylesheet">
<link href="https://fonts.googleapis.com/css?family=Coiny&display=swap" rel="stylesheet">

<script src="https://code.jquery.com/jquery-3.4.1.min.js" integrity="sha256-CSXorXvZcTkaix6Yvo6HppcZGetbYMGWSFlBw8HfCJo=" crossorigin="anonymous"></script>
<script src="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/js/bootstrap.min.js" integrity="sha384-wfSDF2E50Y2D1uUdj0O3uMBJnjuUD4Ih7YwaYd1iqfktj0Uod8GCExl3Og8ifwB6" crossorigin="anonymous"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>

<link rel="stylesheet" href="https://stackpath.bootstrapcdn.com/bootstrap/4.4.1/css/bootstrap.min.css" integrity="sha384-Vkoo8x4CGsO3+Hhxv8T/Q5PaXtkKtu6ug5TOeNV6gBiFeWPGFN9MuhOf23Q9Ifjh" crossorigin="anonymous">

```

* * * * *

Tasks
-----

 Done?\
Help

#### 0\. Read and be familiar with Figma mandatory

Create an account in [Figma](https://intranet.hbtn.io/rltoken/0OS4ME4Kjnw0I82IVkkoSw "Figma") and open these files:

-   [Homepage](https://intranet.hbtn.io/rltoken/RLej4Ua6W3EmDh7UCwGTzQ "Homepage") - [fig file](https://intranet.hbtn.io/rltoken/1ZTxYF-usvxpIjj44YYcyw "fig file")
-   [Pricing](https://intranet.hbtn.io/rltoken/xQCL77_ePGWntUAe4T7ebQ "Pricing") - [fig file](https://intranet.hbtn.io/rltoken/AdJ6ZyZrG90gRNAI5bt_lA "fig file")
-   [Courses](https://intranet.hbtn.io/rltoken/__3w9ryapSUAwMaAYYS6ZA "Courses") - [fig file](https://intranet.hbtn.io/rltoken/1JL-gCkfJ5Hqb0Sf2lmymw "fig file")

And "Duplicate to your Drafts" to have access to all design details.

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/559ad8d43fb61e310e2b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a804ea2f58cf87b373389575fe647c20881c7f75dde8c70184f368f84ca8633f)

Important notes with Figma:

-   if your computer doesn't have missing fonts, you can find them here: [source-sans-pro](https://intranet.hbtn.io/rltoken/4uQkoVbAjr7lRVqSVCWBcw "source-sans-pro") and [Spin-Cycle-OT](https://intranet.hbtn.io/rltoken/5HnXzrMbtVKLCScrdy4CIg "Spin-Cycle-OT")
-   some values are in float - feel free to round them
-   "Be pixel perfect" - yes! but mainly make sure colors, size and position are correct. #C271FF is not purple.

For this task, please write an amazing `README.md`

**Interactions note:**

-   Web pages must switch to the tablet version when the screen width is 768px
-   Web pages must switch to the mobile version when the screen width is 576px
-   button hover/active: `opacity: 0.9`

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `README.md`

 Done?\
Help

#### 1\. Header first mandatory

Let's start by the Homepage: **create the header/hero piece**

Here an archive of all assets needed (for the entire project):

-   [images_images.zip](https://intranet.hbtn.io/rltoken/LXJM1BKGUrHol3Nzu48eEQ "images_images.zip")
-   [holberton_school-icon.zip](https://intranet.hbtn.io/rltoken/CqKyRZebdi_xnT32SSNdWg "holberton_school-icon.zip")

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/4/13572c3773e26651761e8b4a74b3383300ed9563.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=d51826e73240f7a6876602f2462ea9dc867135c1e3b9e4d1320959e253c17173)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8854d68a957ef7dc2315.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=0283b5fc05ed7c8402379f5e0ad115bb27d407d76b22c4cd555fe34f7d564bf4)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `0-homepage.html, styles.css`

 Done?\
Help

#### 2\. Carousel of quotes mandatory

**Create the section "Carousel of quotes"**

By using a Carousel component of Bootstrap, create this Carousel of quotes.

You can have for the moment one quote or twice the same for testing (like example below)

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/8455560f9ac188658195.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e663b3cc1c731d90b3264c50e48a53f7b9fe0595c75bc957613dcaa94d849160)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `1-homepage.html, styles.css`

 Done?\
Help

#### 3\. Popular videos mandatory

**Create the section "Most popular tutorials"**

By using a Carousel component of Bootstrap, create this Carousel of video cards.

**Reminder:**

-   Desktop: 4 cards
-   Tablet: 2 cards
-   Mobile: 1 card

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/4b610dc2d2cc17ceb2f7.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a22d7a511318b49dc85955f05cd15ece67c402a62fb65de0456b384b05a9afce)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `2-homepage.html, styles.css`

 Done?\
Help

#### 4\. Row of smiles mandatory

**Create the section "Free membership"**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/970efd54768b693bbfac.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=283ea2d47066fa638791dc1c62e6e9a2b70f5a2e741f515890862c658a27b0f2)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `3-homepage.html, styles.css`

 Done?\
Help

#### 5\. Latest videos mandatory

**Create the section "Latest videos"**

Copy the block "Most popular tutorials" to "Latest videos"

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `4-homepage.html, styles.css`

 Done?\
Help

#### 6\. ... and the footer! mandatory

**Create the footer**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/739d7cc60098e7ff8f25.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=3297e761dddf59493d7fd27fe1721cb7ea01edbbd4f8d00787c61c6797c153b4)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `homepage.html, styles.css`

 Done?\
Help

#### 7\. Pricing - header mandatory

Now, let's do the pricing page: **create the header/hero piece**

The mobile version must be the same as the Homepage - it's time to reuse code!

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/ccd30a4d80a990b96740.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=fca19a02ccfd5cb1fdf17337d46f6a3e4f3789b60497fc5a7bcf959fbdfdb23a)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `0-pricing.html, styles.css`

 Done?\
Help

#### 8\. Prices grid mandatory

**Create the prices grid**

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/0ac3872946a0014e4f99.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=299d48ff54fb4547d62fece48da3e97f4cee4f618e2bc57228ddbaef845f388a)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/edea8172b9cc0a867237.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=a415d0e85688ace7844a27a9c15450c6af77cf32349a1cdb4ceac877c295ddb0)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `1-pricing.html, styles.css`

 Done?\
Help

#### 9\. Quotes section mandatory

Same as the Homepage, **create the Carousel of quotes**

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `2-pricing.html, styles.css`

 Done?\
Help

#### 10\. FAQ mandatory

**Create the FAQ grid**

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/db8f90e37593a29c1ab6.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=9e41dc412f8de3114b47860a781bf95f79463b9b9d4b465555c760a2095cc6a4)

**Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/eaeb117d40690a451c7b.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=089a542eff58386e7fda1a0f2639c848863d54ed6999b3a119e528da06788bb4)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `3-pricing.html, styles.css`

 Done?\
Help

#### 11\. Close the page with a footer mandatory

Same as Homepage, **create the footer**

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `pricing.html, styles.css`

 Done?\
Help

#### 12\. Courses - header mandatory

Now, let's do the courses page: **create the header/hero piece**

The mobile version must be the same as the Homepage - it's time to reuse code!

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/a5ba265af5dd643ad942.png?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=bf198e6097ffb5398c7e440910137fdecc5e9c24d09cb6142f8205db6d9ebc7a)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `0-courses.html, styles.css`

 Done?\
Help

#### 13\. Search filters mandatory

**Create the search filters section**

Dropdown is a nice way to create filters.

For the selected/placeholder value of both dropdown, no need to have dynamic value - static content is totally ok.

**Desktop:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/98c0564e59ec5620990e.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=e2653f0f7ca50dd26806172b713f6a83ed8cce3f9f1ace9c2e54aa6fe0e0e8c3)

**Tablet/Mobile:**

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/3627550eccca7958d390.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=f5330f3fc4423862ab8b333949025ec73379652a889c0eca0fae8a716aaa6b88)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `1-courses.html, styles.css`

 Done?\
Help

#### 14\. List of result mandatory

**Create the result section of courses**

You can reuse the same cell for testing. Don't forget to test with odd and even number of cells.

![](https://holbertonintranet.s3.amazonaws.com/uploads/medias/2020/3/76b2074f3f6bbd25cdb9.gif?X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIARDDGGGOUWMNL5ANN%2F20200917%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20200917T012240Z&X-Amz-Expires=86400&X-Amz-SignedHeaders=host&X-Amz-Signature=8d4354d836367de5b72efe460dbce1015ff302520a5b4bc7e20997252519763c)

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `2-courses.html, styles.css`

 Done?\
Help

#### 15\. Close the page with a footer mandatory

Same as Homepage and Pricing page, **create the footer**

**Repo:**

-   GitHub repository: `holberton-smiling-school`
-   File: `courses.html, styles.css`

Copyright © 2020 Holberton School. All rights reserved.
