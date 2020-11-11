# recipe-app-api

<h2>HomeBaked</h2>
<p>This REST API is the framework for a digital recipe box. It allows the users to create multiple recipies with </p>

<h2>Features</h2>
<p>Users are authenticated by utilizing the Django Admin Token Authentication.</p>
<img src="client/public/images/UserTokenAuthentication.png" alt="Screenshot of user authentiation">
<p>Once logged in, users can click their profile in the right part of the navbar at the top to see possible actions. The dashboard will display the user's recipes, which they can view to see in more detail.</p>
<img src="" alt="Screenshot of recipe endpoint">
<p>The first step is to add ingredients that the user wishes to track in recipes. Users have access to common ingredients added by default but they will not be able to edit or delete those ingredients.</p>
<img src="" alt="Screenshot of ingredient endpoint" width="35%" height="auto">
<p>Once the recipe's necessary ingredients are added, or otherwise available in the ingredient list, the user can add a new recipe using the "Add New Recipe" option. Once in the expanded recipe view, users can see the recipe name, recipe image, the list of ingredients needed for the recipe, the quantity and quantity type of each recipe ingredient, how much of that ingredient the user already has in their pantry, and how much they need to purchase to cook the recipe. If needed, the user may edit or delete the recipe.</p>
<img src="" alt="Screenshot of user endpoint">
<p>Once the user has added the recipe ingredients to the grocery list, they can then go through the grocery list while at the grocery store, check off ingredients they have, and if the quantities they obtained are different (such as if you cannot buy only 0.125 ounces of dill), they can edit the quantity purchased before or after checking off the ingredient. Users may also add extras to the grocery list, which are not tracked in the pantry, for items such as snacks which the user does not wish to track. Once the shopping trip is completed, the grocery list is cleared, and all checked off items (unless they were added as an extra) are added to the pantry.</p>
<img src="" alt="Screenshot of image upload" width="35%" height="auto">
<p>Once the items are added to the pantry, the user can edit or delete the pantry as needed, or add items to the pantry if desired. To deduct the recipe ingredients when the user cooks the recipe, they can go back to the expanded recipe view, and use the "Cook Recipe" option. This action will deduct the recipe ingredients from the user's pantry.</p>
<img src="" alt="Screenshot of user interface" width="35%" height="auto">
<h2>Built With</h2>
  <ul>
    <li>PostgreSQL
    <li>Python
    <li>Django
    <li>Docker
    <li>Travis CI
  </ul>

<h2>Authors</h2>
<p>Shahna Campbell</p>

<h2>Acknowledgments</h2>
<p>Made possible by The Build a Backend REST API Advanced course on Udemy by Mark Winterbottom</p>


