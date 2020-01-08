# React Minimum Template

A simple template with dependencies that usually are used or needed.

## Motivation

The idea behind this template is setup a basic react application with the most basic dependencies that you may need:
- Code formatter
- Linter
- Test library 
- Props checker

### Libraries

For each one of the items above, I have choose one dependencies, you probably know all of them but I will talk about it.

#### Eslint and Prettier

As a code formatter, I have choosed prettier with eslint as our linter. This two are powerful togheter, after work with them, I can't see myself without it. The linter is configured to maily follow the Airbnb rules, but its also configured to let prettier do the rules about code format, so anything you want to change, just access the prettier rules and change it. The linter for hooks are also installed on the project, it is call eslint-plugin-react-hooks. To help with accessibility, the eslint-plugin-jsx-a11y is also installed.

#### Testing Library

Also known as React Testing Library, it's a popular library that replaces things as Enzyme. As it is recommended on the docs of this library, we also installed jest-dom with it.

#### Props Checker

Propably the most famous of all libraries being used here, this is prop-types. It's the library used to check and validate props that are pass to a component.