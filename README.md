# Highly customizable Vue and Typescript chart

<span class="badge-npmversion"><a href="https://npmjs.org/package/d3-org-chart" title="View this project on NPM"><img src="https://img.shields.io/npm/v/d3-org-chart.svg" alt="NPM version" /></a></span>

- This repo is a using d3-org-chart with Vue & Typescript 
- This is highly customised design from the original chart
- see original repo below


# Original d3 based organization chart
- Visit original repo by Bumbeishvili to checkout fullfunctionality and other uses. [D3-Org-Chart](https://github.com/bumbeishvili/org-chart)
```
npm i d3-org-chart
```
```
import { OrgChart } from 'd3-org-chart';

 new OrgChart()
     .container(<DomElementOrCssSelector>)
     .data(<Data>) // https://github.com/bumbeishvili/sample-data/blob/main/data-oracle.csv
     .render();
```

## Recommended IDE Setup

[VSCode](https://code.visualstudio.com/) + [Volar](https://marketplace.visualstudio.com/items?itemName=Vue.volar) (and disable Vetur) + [TypeScript Vue Plugin (Volar)](https://marketplace.visualstudio.com/items?itemName=Vue.vscode-typescript-vue-plugin).

## Project Setup

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Compile and Minify for Production

```sh
npm run build
```
