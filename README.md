# resturant
@import url('https://fonts.googleapis.com/css?family=Lato|Supermercado+One');

/* Use the 'Lato' font family at 18px throughout the body of the document, and cover the background with the 'map-bg.jpg' image. */
nav {font-family: sans-serif; font-size: 10px;}
body {font: lato; font-size: 18px; background-image:url(map-bg.jpg);} 
#main {width: 900px; margin: 10px auto;}
/* Use the 'Supermercado One' font at 45px (colored #5d4037) for the restaurant name. */
h1 {font: supermeracdo one; font-size: 45px; color: #5d4037}
/* Set the separator between the columns (the "column-rule") to be 2px dashed rosybrown. */
#menu {columns: 400px 2; column-gap: 100px; column-rule: 2px dashed rosybrown}

section {margin-bottom: 50px;}

/* Show each of the section headings of the menu (e.g. "Starters") in small caps, colored #6d4c41. */
h2 {margin: 0;
color: #6d4c41}
/* Make the name of each menu item appear in bold in a 20px size. */
dt {font-size: 20px}


dd {margin: 0 0 12px 0; display: flex;}

.details {order: 1;}

/* Show the price of each item in a large font, in the color named 'firebrick' */
.price {order: 2; padding-left: 10px;}
.price {font-size: larger; color: firebrick}
/* Draw a 2px dashed rosybrown border around the address/footer */
address {padding: 10px;}
footer {border: 2px dashed; border-color: rosybrown; color: black}
