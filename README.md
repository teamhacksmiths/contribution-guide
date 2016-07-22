# Hacksmiths Style Guides and Other Resources

## Style Guides
Here at Hacksmiths, we take writing good code very seriously.  We follow strictly the below style guides and best practices, in some cases with a few small modifications, in an effort to grow a reusable codebase of which we can all be proud.

It is recommended that _every_ contributor read through the following guides. Doing so will enable an open dialog regarding style and will encourage everyone to become conscious of the importance of best practices and style.

### Front End
From working on several large scale React projects, we have developed a collection of configuration and organization best practices.  We begin with the AirBnb JSX and Javascript style guides.
* [Javascript](https://github.com/teamhacksmiths/javascript)
* [AirBNB React / JSX Styleguide](https://github.com/teamhacksmiths/javascript/tree/master/react)

And then we setup ESLint starting with the AirBnb configuration and adding a few modifications.  See below for a guide to setup ESLint.
* [Setting up ESLint](https://github.com/teamhacksmiths/project-resources/blob/master/configuration/about.md)

#### HTML 5 Guidelines
* [HTML 5 Best Practices](https://github.com/teamhacksmiths/project-resources/blob/master/HTML5-GUIDELINES.md)

#### Front End Organization
Our earlier work followed the File-Type-First structure, as seen in [this Boilerplate Project](https://github.com/RyanCCollins/react-redux-simple-starter)

However, it has occured to us that following a feature first mindset has enabled reusability and scalability and thus we will try to migrate to the feature first organization pattern when appropriate to do so.  For an example of the latter, please see the [React Boilerplate](https://github.com/mxstbr/react-boilerplate) project, read [this series](http://engineering.kapost.com/2016/01/organizing-large-react-applications/) and / or [watch this talk](https://vimeo.com/168648012) about scaling React by the creator of the React Boilerplate.

#### Other resources
Although we do not strictly follow the [Khan Academy Style Guides](https://github.com/teamhacksmiths/style-guides/blob/master/style/react.md), please read it as it contains many useful hints and best practices for working with React.

### Back End
* [Ruby Style Guide](https://github.com/bbatsov/ruby-style-guide)
* [Tooling for Style Guide (Rubocop)](https://github.com/bbatsov/rubocop)

#### Python
* [Khan Academy's](https://github.com/teamhacksmiths/style-guides/blob/master/style/python.md).

### iOS
* [Swift Style Guide](https://github.com/ryan-collins-forks/swift-style-guide)
* [Objective-C](https://github.com/Khan/objective-c-style-guide)

### Android
* [Java Style Guide](http://source.android.com/source/code-style.html)

### Git
Our Git style is a mashup of a few different philosophies. For one, we mostly follow the [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).  We follow a strict [Commit Message Style Guide](https://udacity.github.io/git-styleguide/) written by Udacity.  Finally, for everything else, we follow this [Git Style Guide](https://github.com/jonathanong/git-style-guide).  

### Other
As our codebase grows, we will update our guides, adding our tools and configuration.  As we make decisions to implement new technologies, we will update this guide and commit our tools to the Hacksmiths github team account.

#### Documentation and Project Management
Our strategy for documentation will evolve over time.  It's recommended that we utilize agile, but our exact tools and processes are still being determined.

At the time of writing, we are utilizing Asana for Project Management and Ticketing, Google Documents for V1 specs and [Slate](https://github.com/tripit/slate), or another static site generator, to document our APIs. See the [Food Drivr Project](https://github.com/teamhacksmiths/food-drivr) and [API Reference](http://teamhacksmiths.github.io/food-drivr-api-documentation/) for a reference.  As much as we try to utilize other tools, keeping our projects centered around Github is best.  Make sure to update documentation within the repos and link to other tools where appropriate.
