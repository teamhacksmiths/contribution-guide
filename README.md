# Hacksmiths Style Guides and Other Resources

## Style Guides
Here at Hacksmiths, we take writing good code very seriously.  We follow strictly the below style guides and best practices, in some cases with a few small modifications, in an effort to grow a reusable codebase of which we can all be proud.

It is recommended that _every_ contributor read through the following guides. Doing so will enable an open dialog regarding style and will encourage everyone to become conscious of the importance of best practices and style.

### Front End
From working on several large scale React projects, we have developed a collection of configuration and organization best practices.  We begin with the AirBnb JSX and Javascript style guides.
* [Javascript](https://github.com/teamhacksmiths/javascript)
* [AirBNB React / JSX Styleguide](https://github.com/teamhacksmiths/javascript/tree/master/react)

And then we setup a few minor modifications.  See below for a guide to setup ESLint using our configuration file.
* [Setting up ESLint](https://github.com/teamhacksmiths/project-resources/blob/master/configuration/about.md)

ECMAScript (ES6-7):
We recommend that our projects adopt stable features of the ECMAScript specification as they are released to the public.  We will use Babel until all of the desired features are included in the majority of web browsers. 

An example of the [Babel presets](https://github.com/RyanCCollins/react-redux-simple-starter/blob/master/package.json) we have used are as follows
```
  "presets": [
    "es2015",
    "react",
    "stage-0"
  ]
```

Please take the time to study ES6 onwards.
* [ES6 Features](http://es6-features.org/)
* [ES6 And Beyond](https://github.com/getify/You-Dont-Know-JS/tree/master/es6%20%26%20beyond) from the YDKJS Series by Kyle Simpson.

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
* [Khan Academy's Python Style Guide](https://github.com/teamhacksmiths/style-guides/blob/master/style/python.md).

### iOS
* [Swift Style Guide](https://github.com/ryan-collins-forks/swift-style-guide)
* [Objective-C](https://github.com/Khan/objective-c-style-guide)

### Android
* [Java Style Guide](http://source.android.com/source/code-style.html)

### Git
Our Git style is a combination of a few different philosophies. For one, we mostly follow the [Feature Branch Workflow](https://www.atlassian.com/git/tutorials/comparing-workflows/feature-branch-workflow).  We follow a strict [Commit Message Style Guide](https://udacity.github.io/git-styleguide/) written by Udacity.  Finally, for everything else, we follow this [Git Style Guide](https://github.com/jonathanong/git-style-guide).  

### Other
As our codebase grows, we will update our guides, adding our tools and configuration.  As we make decisions to implement new technologies, we will update this guide and commit our tools to the Hacksmiths github team account.

#### Commenting
Commenting is not only considerate to your teammates, it's considerate to the future version of you! Do us all a favor and adopt a commenting pattern.

Examples:
The [Hindley Milner Type signature](https://en.wikipedia.org/wiki/Hindley%E2%80%93Milner_type_system) is a self documenting way to write functional code type signatures.
```
// myAmazingFunction :: String -> [String] -> {Action}
// functionName :: ArgumentType -> AnotherArgumentType -> ReturnType
```

Standard (any language) docs comments
```
/**
 * @function myAmazingFunction
 * @description An amazing function that is seriously awesome and amazing
 * @param String - Some amazing string
 * @param [Object] - An array / list of amazing strings
 * @return {Action} - An Action object
 */
```
This will make our code self documenting, eliminating the need for us to duplicate documentation efforts.  The litmus test for whether a comment is good or not is whether there is a documenation generator that can parse it, so feel free to use your favorite documentation / commenting tools.

References:
* [JSDocs](http://usejsdoc.org/)
* [Yard Docs](http://yardoc.org/)
* [Hindley Millner Type Signature](https://github.com/MostlyAdequate/mostly-adequate-guide/blob/master/ch7.md) from the Mostly Adequate Guide to Functional Programming.

### Testing
At Google, there is only 1 QA tester for every 10 Software Engineers.  They have nurtured a culture that encourages testing at every stage of the process. We intend to do the same!

We recommend TDD, BDD, or any other DD you can think of.  We will rely on your best judgement and will also participate in code review and QA testing at various stages throughout the process.

#### Documentation and Project Management
Our strategy for documentation will evolve over time.  It's recommended that we utilize agile, but our exact tools and processes are still being determined.

At the time of writing, we are utilizing Asana for Project Management and Ticketing, Google Documents for V1 specs and [Slate](https://github.com/tripit/slate), or another static site generator, to document our APIs. See the [Food Drivr Project](https://github.com/teamhacksmiths/food-drivr) and [API Reference](http://teamhacksmiths.github.io/food-drivr-api-documentation/) for a reference.  As much as we try to utilize other tools, keeping our projects centered around Github is best.  Make sure to update documentation within the repos and link to other tools where appropriate.
