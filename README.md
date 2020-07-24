# cra-template-ajlende

This is a template for [Create React App](https://github.com/facebook/create-react-app) with additional configurations that I typically use when creating a new React app.

In addition to the default CRA features, it includes:

- [TypeScript](https://www.typescriptlang.org/)
- [Chakra UI](https://chakra-ui.com/) & [Emotion](https://emotion.sh)
- [Prettier](https://prettier.io/)
- [ESLint](https://eslint.org/) tweaks
- New scripts `lint` and `format`
- Pre-commit lint and format hook

And in order to simplify things, it removes:

- Google web-vitals
- PWA service worker

To use this template, first clone the project, then add `--template ./cra-template-ajlende` when creating a new app.

For example:

```sh
git clone https://github.com/ajlende/cra-template-ajlende.git

# then

yarn create react-app my-app --template file:./cra-template-ajlende
```

For more information, please refer to:

- [Getting Started](https://create-react-app.dev/docs/getting-started) – How to create a new app.
- [User Guide](https://create-react-app.dev) – How to develop apps bootstrapped with Create React App.

MIT © [Alex Lende](https://github.com/ajlende)
