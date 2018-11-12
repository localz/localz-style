# Fannypack
[![All Contributors](https://img.shields.io/badge/all_contributors-3-orange.svg?style=flat-square)](#contributors)

<p align="center"><img src="./fannypack.png" width="400px"></img></p>

> Note: Fannypack is still work in progress, meaning that it's APIs will most likely change in the future until a stable 1.0.0 release.

[Read the docs here](https://fannypack.style)

## Installing Fannypack

Run the following command to install **Fannypack**:

```curl
yarn add fannypack
```

## Getting set up

To start using the components, please follow these steps:

1. Wrap your application in a `<ThemeProvider>` which is provided by **Fannypack**:

```jsx
import { ThemeProvider } from 'fannypack';

const App = () => (
  <ThemeProvider>
    // ... your app
  </ThemeProvider>
);
```

2. Now you can start using components like so!:

```jsx
import { Button } from 'fannypack';

const MyApp = () => (
  <Button>
    Hello world!
  </Button>
);
```

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
| [<img src="https://avatars3.githubusercontent.com/u/7336481?v=4" width="100px;"/><br /><sub><b>Jake Moxey</b></sub>](https://jxom.io/)<br />[💻](https://github.com/jxom/fannypack/commits?author=jxom "Code") [📖](https://github.com/jxom/fannypack/commits?author=jxom "Documentation") [🤔](#ideas-jxom "Ideas, Planning, & Feedback") [👀](#review-jxom "Reviewed Pull Requests") | [<img src="https://avatars3.githubusercontent.com/u/19571028?v=4" width="100px;"/><br /><sub><b>Samantha Wong</b></sub>](https://shooting-unicorns.com)<br />[🤔](#ideas-samantha-wong "Ideas, Planning, & Feedback") | [<img src="https://avatars3.githubusercontent.com/u/10344370?v=4" width="100px;"/><br /><sub><b>Dave Olsen</b></sub>](http://daveolsen.com.au)<br />[💻](https://github.com/jxom/fannypack/commits?author=daveols "Code") [🤔](#ideas-daveols "Ideas, Planning, & Feedback") [👀](#review-daveols "Reviewed Pull Requests") |
| :---: | :---: | :---: |
<!-- ALL-CONTRIBUTORS-LIST:END -->
Thanks goes to these wonderful people

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

## Acknowledgements

Thanks [Luke Edwards](https://twitter.com/lukeed05) for handing over the `fannypack` npm name!
