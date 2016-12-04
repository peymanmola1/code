# Code

## HTML
<!DOCTYPE html>
<html>
<head>
<meta charset="utf-8">
<title>Untitled Document.md</title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <link rel="stylesheet" href="normalize.css">
<style></style>
  
</head>
  
<body id="preview">
<h1><a id="Chicken_Pie_0"></a>Chicken Pie</h1>
  
  
  <img src="https://raw.githubusercontent.com/peymanmola1/my-recipe/master/chickenpie_80250_16x9.jpg" alt="This is chicken pie">

  
<h4><a id="Preparation_timeless_than_30_mins_4"></a>Preparation time:less than 30 mins</h4>
  
<h4><a id="Cooking_time30_mins_to_1_hour_5"></a>Cooking time:30 mins to 1 hour</h4>
<h4><a id="Serves4_6"></a>Serves:4</h4>
<h2><a id="Ingredients_8"></a>Ingredients</h2>
  
<ul>
  <li>2 tbsp butter, plus extra for frying</li>
  <li>1 heaped tbsp flour</li>
  <li>200ml/7fl oz chicken stock</li>
  <li>3 tbsp double cream</li>
  <li>squeeze of lemon juice</li>
  <li>sprig of fresh tarragon (optional)</li>
  <li>1 medium green pepper, sliced</li>
  <li>handful button mushrooms, wiped and quartered</li>
  <li>400g/14oz cooked chicken, shredded</li>
  <li>225g/8oz ready-made puff pastry</li>
  <li>1 medium free-range egg, beaten</li>
</ul>
<h2><a id="Method_21"></a>Method</h2>
<ol>
  <li>
    <p>Preheat the oven to 200C/180C (fan)/Gas 6.</p>
  </li>
  <li>
    <p>For the sauce, melt the butter in a heavy-bottomed saucepan, add the flour and cook slowly over a low heat for 3 minutes, or until the mixture smells toasty. Pour in the chicken stock, turn up the heat and stir constantly until simmering. Add the cream and gently simmer until the sauce until it has a syrupy consistency. Add the lemon juice and tarragon. Turn off the heat.</p>
  </li>
  <img src="http://www.bunkycooks.com/wp-content/uploads/2011/02/Melting-butter-in-pan.jpg">
  <li>
    <p>In another pan, gently fry the chicken, peppers and mushrooms in a knob of butter for 5 minutes, then add to the sauce.</p>
  </li>
  <li>
    <p>Butter an ovenproof dish large enough to hold the chicken pie mixture with room to spare. Add the chicken mixture to the dish.</p>
  </li>
  <li>
    <p>Roll out the pastry on a floured work surface, to a thickness of about ¼in/1cm. Place the pastry over the filling and carefully trim the edges. Use the trimmings to make cut-out shapes to decorate the surface of the pie. Cut a couple of air holes with a knife to allow the steam to escape. Brush the pastry with the beaten egg.</p>
  </li>
  <img src="https://raw.githubusercontent.com/peymanmola1/my-recipe/master/how_to_make_puff_pastry_65905_16x9.jpg">
  <li>
    <p>Bake the pie in the preheated oven for about 25-35 minutes. The top should be nicely browned and the filling piping hot. Remove, allow to cool slightly and serve.</p>
  </li>
</ol>
<h2><a id="Recipe_Tips_34"></a>Recipe Tips</h2>
<p>To freeze, allow the sauce to cool completely before adding the chicken, peppers and mushrooms (You won’t need to reheat the chicken before freezing, either). Place the pie filling in a freezer-to-oven safe dish or a foil tin. Roll the pastry out, place on the top of the pie and freeze before baking. To bake from frozen, preheat the oven to 180C/160C Fan/Gas 4 and bake the pie for 40-50 minutes until golden-brown and piping hot inside.</p>
  <h4>
    <a href="https://www.jusrol.co.uk/pastry-tips/how-to-roll-puff-pastry">Tips</a></h4>
</body></html>

## CSS
body {
  font-family: "Open Sans", sans-serif;
  background-color: bisque;
}

h1 {
 color: black;
  text-align: center;
}

h2 {
  color: black;
}

h4 {
  color: black;
  text-align: center; 
}

ul {
  color: black;
}

ol {
  color: black;
}

p {
  color: black;
}

body {
  font-family: "Open Sans", sans-serif;
  background-color: bisque;
}
img {
  max-width: 100%;

}
@media (min-width: 40rem) /* this line is the query */
{
  /* if the query is true, then the following rules are applied.. */

  body 
  {
    max-width: 40rem;
    margin: 0 auto; /* centre it horizontally */
  }

  /* ..up to here */
}
