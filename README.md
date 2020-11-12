# recipe-app-api

<h2>HomeBaked</h2>
<p>This REST API is the framework for a digital recipe box. It allows the users to create multiple recipies with links to websites, estimated cost to prepare, tags for categorization and a customizable bank of ingredients that a user can pull from.</p>

<h2>Features</h2>
<p>Users are authenticated by utilizing the Django Admin Token Authentication.</p>
<img src="client/public/images/UserTokenAuthentication.png" alt="Screenshot of user authentiation">
<p>Each recipe can be defined by a tag to catagorize recipe's by cusine, or dietary restrictions. </p>
<img src="client/public/images/UpdatedTags.png" alt="Screenshot of recipe endpoint">
<p>The first step for creating a recipe is to define the ingredients. The enpoint allows user to create a bank of ingredients to pull from when creating recipes </p>
<img src="client/public/images/IngredientList.png" alt="Screenshot of ingredient endpoint">
<p>Once the recipe's necessary ingredients are added then the user can compile the recipe and attach a link to the original recipe.</p>
<img src="client/public/images/RecipeEndpoint.png" alt="Screenshot of user endpoint">
<p>Once the recipe is created, users can upload images to the recipe.The upload form provides a link to access photos.</p>
<img src="client/public/images/ImageUploadEndpoint.png" alt="Screenshot of user interface">
<p>Filtering was added to allow uses the ability to easily locate search recipes by ingredients or tags.</p>
<img src="client/public/images/ImageUploadEndpoint.png" alt="Screenshot of user interface">
<h2>Built With</h2>
  <ul>
    <li>PostgreSQL
    <li>Python
    <li>Django
    <li>Docker
    <li>Travis CI
    <li>Pillow
  </ul>

<h2>Authors</h2>
<p>Shahna Campbell</p>

<h2>Acknowledgments</h2>
<p>Made possible by Build a Backend REST API Advanced course on Udemy by Mark Winterbottom</p>


