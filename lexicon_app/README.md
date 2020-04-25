# 👋 Welcome to the lexicon-app project
> Personalized web lexicon for USR Classroom students 

📤 This project was bootstrapped with [Initializr](http://www.initializr.com/). It's a simple HTML/CSS/JS template responsive website with mobile first approach.

## Project structure
- **css** folder that contains all the styles shared across the site.
- **js** folder for JavaScript files.
- **img** folder that contains all the images that this web app needs.
- **pages** folder that contains **name-surname** subfolders for students.

## Contributing

If you are a student looking to complete this task, use the following steps:
- Create a **[name-surname]** branch. This is where you will do all of your work.
- Create a **pages/[name-surname]** folder. Place your html and css files inside of it and images inside of **~/img** folder. Check **pages/josip-volarevic** for an inspiration.
- Once done with your html and css, make sure to connect your page with **~/index.html** such as:
```
<li><a href="pages/josip-volarevic/index.html">Josip Volarević</a></li>
```
- Submit the task when finished by pushing your changes and merging your branch into **origin master**.

*Make sure to use `git pull origin master` before pushing changes to your remote branch!

## Styleguides

Try to follow these styleguides and conventions as much as possible. If they overwheling for you at the moment, feel free to loosen them up.

- Use [Semantic Commit Messages](https://seesparkbox.com/foundry/semantic_commit_messages) when commiting.
For example: `git commit -m "feat: finish josip-volarevic site"` when finishing your task
- Use [BEM](http://getbem.com/introduction/) convention for naming classes.
- Make sure to prioritize [Semantic HTML](https://www.w3schools.com/html/html5_semantic_elements.asp) over non-semantic where reasonable.
