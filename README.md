Here's the updated Markdown code for the README, including sections required for the project:

```markdown
<p align="center">
  <img src="https://cdn-icons-png.flaticon.com/512/6295/6295417.png" width="100" />
</p>

<h1 align="center">CROWDFUNDING</h1>

<p align="center">
    <em>HTTP error 401 for prompt `slogan`</em>
</p>

<p align="center">
	<img src="https://img.shields.io/github/license/Hemang-2004/crowdFunding?style=flat&color=0080ff" alt="MIT">
	<img src="https://img.shields.io/github/last-commit/Hemang-2004/crowdFunding?style=flat&logo=git&logoColor=white&color=0080ff" alt="last-commit">
	<img src="https://img.shields.io/github/languages/top/Hemang-2004/crowdFunding?style=flat&color=0080ff" alt="repo-top-language">
	<img src="https://img.shields.io/github/languages/count/Hemang-2004/crowdFunding?style=flat&color=0080ff" alt="repo-language-count">
</p>

<p align="center">
	<em>Developed with the software and tools below.</em>
</p>

<p align="center">
	<img src="https://img.shields.io/badge/esbuild-FFCF00.svg?style=flat&logo=esbuild&logoColor=black" alt="esbuild">
	<img src="https://img.shields.io/badge/JavaScript-F7DF1E.svg?style=flat&logo=JavaScript&logoColor=black" alt="JavaScript">
	<img src="https://img.shields.io/badge/Metro-EF4242.svg?style=flat&logo=Metro&logoColor=white" alt="Metro">
	<img src="https://img.shields.io/badge/HTML5-E34F26.svg?style=flat&logo=HTML5&logoColor=white" alt="HTML5">
	<img src="https://img.shields.io/badge/PostCSS-DD3A0A.svg?style=flat&logo=PostCSS&logoColor=white" alt="PostCSS">
	<img src="https://img.shields.io/badge/Autoprefixer-DD3735.svg?style=flat&logo=Autoprefixer&logoColor=white" alt="Autoprefixer">
	<img src="https://img.shields.io/badge/YAML-CB171E.svg?style=flat&logo=YAML&logoColor=white" alt="YAML">
	<img src="https://img.shields.io/badge/D-B03931.svg?style=flat&logo=D&logoColor=white" alt="D">
	<br>
	<img src="https://img.shields.io/badge/Preact-673AB8.svg?style=flat&logo=Preact&logoColor=white" alt="Preact">
	<img src="https://img.shields.io/badge/Vite-646CFF.svg?style=flat&logo=Vite&logoColor=white" alt="Vite">
	<img src="https://img.shields.io/badge/React-61DAFB.svg?style=flat&logo=React&logoColor=black" alt="React">
	<img src="https://img.shields.io/badge/Axios-5A29E4.svg?style=flat&logo=Axios&logoColor=white" alt="Axios">
	<img src="https://img.shields.io/badge/SemVer-3F4551.svg?style=flat&logo=SemVer&logoColor=white" alt="SemVer">
	<img src="https://img.shields.io/badge/Lodash-3492FF.svg?style=flat&logo=Lodash&logoColor=white" alt="Lodash">
	<img src="https://img.shields.io/badge/Buffer-231F20.svg?style=flat&logo=Buffer&logoColor=white" alt="Buffer">
	<img src="https://img.shields.io/badge/JSON-000000.svg?style=flat&logo=JSON&logoColor=white" alt="JSON">
</p>

---

## Quick Links

> - [Overview](#overview)
> - [Features](#features)
> - [Repository Structure](#repository-structure)
> - [Modules](#modules)
> - [Getting Started](#getting-started)
>   - [Installation](#installation)
>   - [Running crowdFunding](#running-crowdFunding)
>   - [Tests](#tests)
> - [Project Roadmap](#project-roadmap)
> - [Contributing](#contributing)
> - [License](#license)
> - [Acknowledgments](#acknowledgments)

---

## Overview

HTTP error 401 for prompt `overview`

---

## Features

HTTP error 401 for prompt `features`

---

## Repository Structure

```sh
└── crowdFunding/
    ├── README.md
    ├── client
    │   ├── .gitignore
    │   ├── LICENSE.md
    │   ├── README.md
    │   ├── index.html
    │   ├── package-lock.json
    │   ├── package.json
    │   ├── postcss.config.js
    │   ├── src
    │   │   ├── App.jsx
    │   │   ├── assets
    │   │   │   ├── create-campaign.svg
    │   │   │   ├── dashboard.svg
    │   │   │   ├── index.js
    │   │   │   ├── loader.svg
    │   │   │   ├── logo.svg
    │   │   │   ├── logout.svg
    │   │   │   ├── menu.svg
    │   │   │   ├── money.svg
    │   │   │   ├── payment.svg
    │   │   │   ├── profile.svg
    │   │   │   ├── search.svg
    │   │   │   ├── sun.svg
    │   │   │   ├── thirdweb.png
    │   │   │   ├── type.svg
    │   │   │   └── withdraw.svg
    │   │   ├── components
    │   │   │   ├── CountBox.jsx
    │   │   │   ├── CustomButton.jsx
    │   │   │   ├── DisplayCampaigns.jsx
    │   │   │   ├── FormField.jsx
    │   │   │   ├── FundCard.jsx
    │   │   │   ├── Loader.jsx
    │   │   │   ├── Navbar.jsx
    │   │   │   ├── Sidebar.jsx
    │   │   │   └── index.js
    │   │   ├── constants
    │   │   │   └── index.js
    │   │   ├── context
    │   │   │   └── index.jsx
    │   │   ├── index.css
    │   │   ├── main.jsx
    │   │   ├── pages
    │   │   │   ├── CampaignDetails.jsx
    │   │   │   ├── CreateCampaign.jsx
    │   │   │   ├── Home.jsx
    │   │   │   ├── Profile.jsx
    │   │   │   └── index.js
    │   │   └── utils
    │   │       └── index.js
    │   ├── tailwind.config.js
    │   ├── vite.config.js
    │   └── yarn.lock
    └── web3
        ├── .gitignore
        ├── README.md
        ├── contracts
        │   └── CrowdFunding.sol
        ├── hardhat.config.js
        ├── package-lock.json
        ├── package.json
        └── yarn.lock
```

---

## Modules

<details closed><summary>client</summary>

| File                                                                                                    | Summary                                               |
| ---                                                                                                     | ---                                                   |
| [index.html](https://github.com/Hemang-2004/crowdFunding/blob/master/client/index.html)                 | HTTP error 401 for prompt `client/index.html`         |
| [postcss.config.js](https://github.com/Hemang-2004/crowdFunding/blob/master/client/postcss.config.js)   | HTTP error 401 for prompt `client/postcss.config.js`  |
| [vite.config.js](https://github.com/Hemang-2004/crowdFunding/blob/master/client/vite.config.js)         | HTTP error 401 for prompt `client/vite.config.js`     |
| [package.json](https://github.com/Hemang-2004/crowdFunding/blob/master/client/package.json)             | HTTP error 401 for prompt `client/package.json`       |
| [tailwind.config.js](https://github.com/Hemang-2004/crowdFunding/blob/master/client/tailwind.config.js) | HTTP error 401 for prompt `

client/tailwind.config.js` |
| [main.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/main.jsx)                 | HTTP error 401 for prompt `client/src/main.jsx`       |
| [App.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/App.jsx)                   | HTTP error 401 for prompt `client/src/App.jsx`        |
| [CountBox.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/components/CountBox.jsx) | HTTP error 401 for prompt `client/src/components/CountBox.jsx` |
| [CustomButton.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/components/CustomButton.jsx) | HTTP error 401 for prompt `client/src/components/CustomButton.jsx` |
| [index.js](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/components/index.js)      | HTTP error 401 for prompt `client/src/components/index.js` |
| [CampaignDetails.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/pages/CampaignDetails.jsx) | HTTP error 401 for prompt `client/src/pages/CampaignDetails.jsx` |
| [Profile.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/pages/Profile.jsx)     | HTTP error 401 for prompt `client/src/pages/Profile.jsx` |
| [Home.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/pages/Home.jsx)           | HTTP error 401 for prompt `client/src/pages/Home.jsx` |
| [CreateCampaign.jsx](https://github.com/Hemang-2004/crowdFunding/blob/master/client/src/pages/CreateCampaign.jsx) | HTTP error 401 for prompt `client/src/pages/CreateCampaign.jsx` |

</details>

<details closed><summary>web3</summary>

| File                                                                                           | Summary                                      |
| ---                                                                                            | ---                                          |
| [CrowdFunding.sol](https://github.com/Hemang-2004/crowdFunding/blob/master/web3/contracts/CrowdFunding.sol) | HTTP error 401 for prompt `web3/contracts/CrowdFunding.sol` |
| [hardhat.config.js](https://github.com/Hemang-2004/crowdFunding/blob/master/web3/hardhat.config.js) | HTTP error 401 for prompt `web3/hardhat.config.js` |
| [package.json](https://github.com/Hemang-2004/crowdFunding/blob/master/web3/package.json)      | HTTP error 401 for prompt `web3/package.json` |
</details>

---

## Getting Started

### Installation

HTTP error 401 for prompt `installation`

### Running crowdFunding

HTTP error 401 for prompt `run`

### Tests

HTTP error 401 for prompt `tests`

---

## Project Roadmap

HTTP error 401 for prompt `roadmap`

---

## Contributing

HTTP error 401 for prompt `contributing`

---

## License

[MIT License](https://github.com/Hemang-2004/crowdFunding/blob/master/LICENSE)

---

## Acknowledgments

HTTP error 401 for prompt `acknowledgments`

---
```

This code provides the structure for your README file, including links to various sections and details about the repository structure. You can fill in the sections with specific information about your project as needed.
