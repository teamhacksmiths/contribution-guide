# Hacksmiths Style Guides and Other Resources

## Style Guides
Here at Hacksmiths, we take writing good code very seriously.  We strictly follow the below style guides, in some cases with a few tweaks.  The main purpose of the Hacksmiths is to give us all an opportunity to grow our experience.  Thus, we will strive to implement best practices in all of our work in an effort to grow a reusable codebase that we are proud of.

### Front End
From working on several large scale React projects, we have developed a collection of configuration and organization best practices.  We begin with the AirBnb style guides and add a few small tweaks.
* [Javascript](https://github.com/teamhacksmiths/javascript)
* [AirBNB React / JSX Styleguide](https://github.com/teamhacksmiths/javascript/tree/master/react)
* [Setting up ESLint](https://github.com/teamhacksmiths/project-resources/blob/master/configuration/about.md)
* [File Organization](https://github.com/RyanCCollins/react-redux-simple-starter)
* [HTML 5 Best Practices](https://github.com/teamhacksmiths/project-resources/blob/master/HTML5-GUIDELINES.md)

Although we do not strictly follow the [Khan Academy Style Guides](https://github.com/teamhacksmiths/style-guides/blob/master/style/react.md), please read it as it contains many useful hints and best practices for working with React.

#### Front End Organization
We will use the above linked boilerplate as a starting point and eventually will migrate over to the [React Boilerplate](https://github.com/mxstbr/react-boilerplate) file organization when appropriate.  The main difference is that the React Redux Simple Starter project seperates out actions and reducers into seperate folders whereas the React Boilerplate encourages encapsulating all functionality for a single component within the component folder. If you're not clear on how this works, please read [this article](http://engineering.kapost.com/2016/01/organizing-large-react-applications/) about organizing large scale react apps. 

### Back End
* [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide)
* [Tooling for Style Guide (Rubocop)](https://github.com/bbatsov/rubocop)

### iOS
* [Swift Style Guide](https://github.com/ryan-collins-forks/swift-style-guide)

### Android
* [Java Style Guide](http://source.android.com/source/code-style.html)

### Git
Our Git style is a mashup of a few different philosophies. For one, we mostly follow the [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).  We follow a strict [Commit Message Style Guide](https://udacity.github.io/git-styleguide/) written by Udacity.  Finally, for everything else, we follow this [Git Style Guide](https://github.com/jonathanong/git-style-guide).  

### Other
As our codebase grows, we will update our guides, adding our tools and configuration.  As we make decisions to implement new technologies, we will update this guide and commit our tools to the Hacksmiths github team account.

#### Documentation and Project Management
Our strategy for documentation will evolve over time.  It's recommended that we utilize agile, but our exact tools and processes are still being determined.

At the time of writing, we are utilizing Asana for Project Management and Ticketing, Google Documents for V1 specs and [Slate](https://github.com/tripit/slate), or another static site generator, to document our APIs. See the [Food Drivr Project](https://github.com/teamhacksmiths/food-drivr) and [API Reference](http://teamhacksmiths.github.io/food-drivr-api-documentation/) for a reference.  As much as we try to utilize other tools, keeping our projects centered around Github is best.  Make sure to update documentation within the repos and link to other tools where appropriate.
