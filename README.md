# Samuel Cheong W.S.

<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

.column {
  float: left;
  width: 25%;
  padding: 5px;
}

/* Clearfix (clear floats) */
.row::after {
  content: "";
  clear: both;
  display: table;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width: 500px) {
  .column {
    width: 100%;
  }
}
</style>
</head>
<body>

<h2>Responsive "Side-by-Side" Images</h2>
<p>How to create side-by-side images with the CSS float property. On screens that are 500px wide or less, the images will stack on top of each other instead of next to each other:</p>
<p>Resize the browser window to see the effect.</p>

<div class="row">
  <div class="column">
    <img src="glendon.png" alt="glendon" style="width:25%">
  </div>
  <div class="column">
    <img src="christabelle.png" alt="christabelle" style="width:25%">
  </div>
  <div class="column">
    <img src="choon.png" alt="choon" style="width:25%">
  </div>  
  <div class="column">
    <img src="jishnu.png" alt="jishnu" style="width:25%">
  </div>
</div>


</body>
</html>










<!---

# Samuel Cheong W.S.

Undergraduate Student in National University of Singapore

I am an aspiring programmer, interested to automate tasks to improve our quality of life.

## Education

###National University of Singapore
Bachelor of Computing (Hons)
Computer Sciences Courses


###Hwa Chong Institution
IP Programme


-->





Useful Links:  [editor on GitHub](https://github.com/samuelcheongws/Github-website/edit/main/README.md) · [Jekyll](https://jekyllrb.com/) · [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/) · [repository settings](https://github.com/samuelcheongws/Github-website/settings/pages) · [documentation](https://docs.github.com/categories/github-pages-basics/) · [contact support](https://support.github.com/contact)
