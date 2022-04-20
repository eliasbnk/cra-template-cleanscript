# cra-template-cleanscript

This template is a cleaned version of the official TypeScript template for [Create React App](https://github.com/facebook/create-react-app).

By clean I mean:

- without files and folders that everyone usually deletes
- with preconfigured eslint + stylelint + prettier + airbnb + husky + lint stage  ( running `yarn husky` enables pre-commit checking )
- with preconfigured github workflow that runs both on macos and ubuntu

To use this template, add `--template cleanscript` when creating a new app.

For example:

```sh
npx create-react-app my-app --template cleanscript

# or

yarn create react-app my-app --template cleanscript
```
