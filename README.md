<a name="readme-top"></a>

<div align="center">
  <!-- You are encouraged to replace this logo with your own! Otherwise you can also remove it. -->
  <img src="logo.webp" alt="logo" width="140"  height="auto" />
  <br/>

  <h3><b>To-do List</b></h3>

</div>

<!-- TABLE OF CONTENTS -->

# 📗 Table of Contents

- [📖 About the Project](#about-project)
  - [🛠 Built With](#built-with)
    - [Tech Stack](#tech-stack)
    - [Key Features](#key-features)
  - [🚀 Live Demo](#live-demo)
- [💻 Getting Started](#getting-started)
  - [Setup](#setup)
  - [Prerequisites](#prerequisites)
  - [Install](#install)
  - [Usage](#usage)
  - [Run tests](#run-tests)
  - [Deployment](#deployment)
- [👥 Authors](#authors)
- [🔭 Future Features](#future-features)
- [🤝 Contributing](#contributing)
- [⭐️ Show your support](#support)
- [🙏 Acknowledgements](#acknowledgements)
- [❓ FAQ (OPTIONAL)](#faq)
- [📝 License](#license)

<!-- PROJECT DESCRIPTION -->

# 📖 To Do List <a name="about-project"></a>

**To Do List** is a web application that allows users to keep track of their tasks.

## 🛠 Built With <a name="built-with"></a>

### Tech Stack <a name="tech-stack"></a>

<details>
  <summary>Client</summary>
  <ul>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/en-US/docs/Web/JavaScript">JavaScript</a></li>
    <li><a href="https://webpack.js.org/">Webpack</a></li>
  </ul>
</details>

<details>
  <summary>Server</summary>
  No server-side technologies were used for this project.
</details>

<details>
<summary>Database</summary>
  No database was used for this project.
</details>

<!-- Features -->

### Key Features <a name="key-features"></a>

- **Add Tasks**
- **Delete Tasks**
- **Order Tasks**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LIVE DEMO -->

## 🚀 Live Demo <a name="live-demo"></a>

[Live Demo Link](https://10-menachi.github.io/todo-list/dist)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- GETTING STARTED -->

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps.

<ul>
  <li>Open the HTML file in a browser of your choice</li>
</ul>

The link below provides details on browser support <br />

<a href="https://www.w3schools.com/tags/ref_html_browsersupport.asp">Browser Support</a>

### Prerequisites

In order to run this project you need:

- Stylelint
- ESLint
- Webpack

```sh
  npm install -g stylelint
  npm install -g eslint
  npm install -g webpack
```

OR if on Yarn,

```sh
  yarn global add stylelint
  yarn global add eslint
  yarn global add webpack
```

However, whilst everything is included in the package.json file, you can simply run:

```sh
  npm install
```

OR if on Yarn,

```sh
  yarn install
```

Don't know how to use Package Managers? Check out the [Beginner's Guide](https://www.sitepoint.com/yarn-vs-npm/)

### Setup

Clone this repository to your desired folder:

```sh
  cd my-folder
  git clone https://github.com/10-menachi/todo-list.git
```

### Usage

To run the project:

```sh
  cd todo-list
  npm run dev
```

OR if on Yarn,

```sh
  cd todo-list
  yarn dev
```

The website is hosted on localhost:9000 by default. <br />

You can change this in the webpack.config.js file, under the devServer property.

```js
  devServer: {
    contentBase: './dist',
    port: [YOUR PORT HERE]  // Change this from :9000 to your desired port,
  },
```

<a href="https://www.w3schools.com/tags/ref_html_browsersupport.asp">Browser Support</a>

### Run tests

There are no tests for this project

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- AUTHORS -->

## 👥 Authors <a name="authors"></a>

👤 **Christian Wamalwa**

- GitHub: [@githubhandle](https://github.com/10-menachi)
- Twitter: [@twitterhandle](https://twitter.com/christian_timbe)
- LinkedIn: [LinkedIn](https://linkedin.com/in/chris-droid)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE FEATURES -->

## 🔭 Future Features <a name="future-features"></a>

- [ ] **User Authentication**

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->

## 🤝 Contributing <a name="contributing"></a>

Contributions, issues, and feature requests are welcome!

Feel free to check the [issues page](../../issues/).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- SUPPORT -->

## ⭐️ Show your support <a name="support"></a>

If you like this project, please give it a ⭐️!

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGEMENTS -->

## 🙏 Acknowledgments <a name="acknowledgements"></a>

I would like to thank Microverse for giving me this opportunity to learn and build this project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->

## 📝 License <a name="license"></a>

This project is [MIT](./LICENSE) licensed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>
