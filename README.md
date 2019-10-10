# Artiklar

## [JavaScript Modules: From IIFEs to CommonJS to ES6 Modules](https://tylermcginnis.com/javascript-modules-iifes-commonjs-esmodules/)

Introduktion till vad moduler i JavaScript är. Och historik över hur vi tidigare modulariserat JS, jämfört med hur ES6 modules fungerar. Ganska grundläggande, men viktigt att veta för att förstå hur man bygger delbara moduler.

## [How to Publish NPM Packages](https://medium.com/@rossbulat/how-to-publish-npm-packages-4e519744c416)

Praktisk guide till publicering av NPM-paket. Förklarar även en del koncept som är viktiga att känna till, tex. skillnaden på scoped och unscoped paket.

## [Checklist for Writing Highly Reusable Components in React and Vue](https://hackernoon.com/checklist-for-writing-highly-reusable-components-in-react-and-vue-531f963864bd)

En checklista för för att bygga generiska komponenter, lite API-design, patterns etc.

## [Why Lerna and Yarn Workspaces is a Perfect Match for Building Mono-Repos – A Close Look at Features and Performance](https://doppelmutzi.github.io/monorepo-lerna-yarn-workspaces/)

En artikel som går igenom vad ett mono repo är, och hur man kan använda [Lerna](https://github.com/lerna/lerna) och [Yarn Workspaces](https://yarnpkg.com/lang/en/docs/workspaces/) tillsammans med [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0-beta.2/) för att få ett smidigt arbetsflöde med mono-repos.

# Verktyg

## [React Cosmos](https://github.com/react-cosmos/react-cosmos)

En playground för Reactkomponenter. Bra verktyg för att utveckla komponenter i en isolerad miljö, och bygga upp ett bibliotek av komponenter.

## [Storybook](https://storybook.js.org/)

Alternativ till React Cosmos. Detta är mer begränsat och lämpat till stateless UI-komponenter.

## [rollup.js](https://rollupjs.org/guide/en/)

En alternativ bundler till webpack. 

Tidigare har en generell regel varit att använda webpack för att bundla applikationer och rollup till moduler för publicering. Rollup togs fram just för att bundla fristående moduler för distrubution, och har därför varit fördelaktikt för att bygga komponentbibliotek och komponenter som ska återanvändas. Rollup har tex. implementerat tree shaking sedan länge för att ta fram så små moduler som möjligt. Nu har dock webpack respektive rollup kommit ikapp varandra, och båda är alternativ för att bundla komponenter. 

[Här](https://medium.com/webpack/webpack-and-rollup-the-same-but-different-a41ad427058c) kan man läsa en gammal artikel om detta om man är intresserad av historiken. Rollup är ändå ett bra val av bundler för komponentbibliotek.

## Testning

[Testing Javascript with Kent C. Dodds](https://testingjavascript.com/)

Javascript-testnings gurun sajt med många läsvärda artiklar.
