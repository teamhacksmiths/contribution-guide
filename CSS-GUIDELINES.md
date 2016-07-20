# CSS Guidelines
This serves as a generic overview of the CSS guidelines and best practices.  Note that some sections here refer to specific tools that may or may not be used in future projects.  As new tools are used, this guide will be updated with descriptions of the best practices used with those tools.

## Tools

### CSS Modules
Whenever possible, using [React CSS Modules](https://github.com/gajus/react-css-modules) will eliminate most of the need to follow naming conventions.  When using CSS Modules, each component will have a related styling file.  To seperate global vs. local styles, name your module files as follows:
```
ComponentName.module.scss
```
where ComponentName is the name of the react component.

An example file structure is as follows:
|-components
|--ComponentName
|---ComponentName.js
|---ComponentName.module.scss


### Sass
Follow the same rules as explained in the CSS Modules when using Sass.

### BEM
When not using React CSS Modules, please follow the [BEM naming convention](https://www.sitepoint.com/bem-smacss-advice-from-developers/).

BEM stands for Block Element Modifier. It provides a rather strict way to arrange your CSS classes into independent modules. There are a few variations on the idea but the most common one looks like this:
```
.block {}
.block__element {}
.block--modifier {}
.block__element--modifier {}
```

### Post CSS
We have adopted [PostCSS](http://postcss.org/) to manage our CSS for the Food Drivr Project. PostCSS allows us to add specific plugins and enrich the development experience. Among the many options to make our CSS life better we started with just a few simple ones but we are planning on adding others in the future.

If interested in using PostCSS in future projects, please refer to the [Food Drivr repository](https://github.com/teamhacksmiths/food-drivr-frontend/blob/master/CSS-GUIDELINES.md) for an example of PostCSS in use.
