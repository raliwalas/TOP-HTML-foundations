# Assignment

### Iteration 1: initial structure

1. Within the odin-recipes directory, create an index.html file.
2. Fill it out with the usual boilerplate HTML and add an h1 heading “Odin Recipes” to the body.

### Iteration 2: recipe page

1. Create a new directory within the odin-recipes directory and name it recipes.
2. Create a new HTML file within the recipes directory and name it after the recipe it will contain. For example lasagna.html. You can use the name of your favorite dish or, if you need some inspiration, you can find a recipe to use here.
3. For now, just include an h1 heading with the recipe’s name as its content.
4. Back in the index.html file, add a link to the recipe page you just created. Example: Under the `<h1>Odin Recipes</h1>` heading, write out the link like so: `<a href="recipes/recipename.html">Recipe Title</a>`. The text of the link should again be the recipe name.

### Iteration 3: recipe page content

1. An image of the finished dish under the h1 heading that you added earlier. You can find images of the dish on Google or the [recipe site](https://www.allrecipes.com/) we linked to earlier.

2. Under the image, it should have an appropriately sized “Description” heading followed by a paragraph or two describing the recipe.

3. Under the description, add an “Ingredients” heading followed by an **unordered list** of the ingredients needed for the recipe.

4. Finally, under the ingredients list, add a “Steps” heading followed by an **ordered list** of the steps needed for making the dish.

### Iteration 4: add more recipes

1. Add two more recipes with identical page structures to the recipe page you’ve already created.

2. Don’t forget to link to the new recipes on the index page. Also, consider putting all the links in an unordered list so they aren’t all on one line.


Example

```
 <ul>
    <li><a href="recipes/yourrecipe.html">Recipe Title 1</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 2</a></li>
    <li><a href="recipes/yourrecipe.html">Recipe Title 3</a></li>
  </ul>
```

Your links won’t be flashy, but for now just focus on building them out.


## Viewing your project on the web
If you want to show your work (the project) to others, or submit a solution below, you will need to publish your site so that others can access it from the web, rather than just on your local machine. The good news is that if you have your project on GitHub (as described above), doing this is incredibly simple.

GitHub allows you to publish web projects directly from a GitHub repository. Doing this will allow you to access your project from your-github-username.github.io/your-github-repo-name.

> A GitHub paid account is required to publish a private repository.

There are a couple of ways to go about doing this, but the simplest is this:

- Make sure that the main HTML file of your project is called index.html. If it is not, you will need to rename it.
- Go to your GitHub repo on the web and click the Settings button as shown in the screenshot below.Screenshot pointing to the Settings located in an example repository
- Click on Pages on the left side bar.
- Change the Branch from none to main branch and click Save.
- It may take a few minutes (The GitHub website says up to 10, but we’ve seen it take up to an hour. Do not add a “theme” to your project, or you may have git conflicts, instead, be patient.) but your project should be accessible over the web from your-github-username.github.io/your-github-repo-name (obviously substituting your own details in the link).
- If your project does not publish after 1 hour, ensure that you have a file called index.html in the root of your repository and all the settings have been set correctly. Go to your repo on GitHub and click on Actions, if there are no entries, then go back to the settings, change the Branch from main branch to none and click Save, then change the Branch from none to main branch and click Save.
