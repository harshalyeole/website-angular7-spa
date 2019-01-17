# [Pune Weekend - Free Bootstrap 4 UI Kit](https://demos.creative-tim.com/paper-kit-2-angular/)

![version](https://img.shields.io/badge/version-1.1.0-blue.svg) [![license][license-badge]][LICENSE] [![GitHub issues open](https://img.shields.io/github/issues/creativetimofficial/paper-kit-2-angular.svg?maxAge=2592000)](https://github.com/creativetimofficial/paper-kit-2-angular/issues?q=is%3Aopen+is%3Aissue) [![GitHub closed issues](https://img.shields.io/github/issues-closed-raw/creativetimofficial/paper-kit-2-angular.svg?maxAge=259200)](https://github.com/creativetimofficial/paper-kit-2-angular/issues?q=is%3Aissue+is%3Aclosed) [![Chat](https://img.shields.io/badge/chat-on%20discord-7289da.svg)](https://discord.gg/E4aHAQy)
![Pune Weekend](https://s3.amazonaws.com/creativetim_bucket/products/65/original/opt_pk2_angular_thumbnail.jpg "Pune Weekend Free")

Pune Weekend is a free Bootstrap 4 UI Kit with pale colors, beautiful typography built for Angular 7.

All components are fully responsive and look great on every screen size. Transitions, shadows, colors, they all resemble the flow you would have using pieces of paper.

We have created Paper UI Kit kit having pastel colors and paper in mind. It feels light, fresh and easy to go through.

Pune Weekend is using Ng Bootstrap (https://ng-bootstrap.github.io/#/home), as core framework.

**Bootstrap 4 support**

Pune Weekend is built on top of Bootstrap 4, so it fully supports it. Most of the elements from the framework are re-designed to resemble sheets of paper and color pastels. If the are elements that we have not touched, they will gracefully fall back to the Bootstrap 4 default.

## Table of Contents

* [Versions](#versions)
* [Demo](#demo)
* [Quick Start](#quick-start)
* [Documentation](#documentation)
* [File Structure](#file-structure)
* [Browser Support](#browser-support)
* [Resources](#resources)
* [Reporting Issues](#reporting-issues)
* [Technical Support or Questions](#technical-support-or-questions)
* [Licensing](#licensing)
* [Useful Links](#useful-links)


| HTML | Angular |


## Demo

- [Start page](https://demos.creative-tim.com/paper-kit-2-angular/home)
- [Landing Page](https://demos.creative-tim.com/paper-kit-2-angular/landing)
- [Register Page](https://demos.creative-tim.com/paper-kit-2-angular/signup)
- [Profile Page](https://demos.creative-tim.com/paper-kit-2-angular/user-profile)

[View More](https://demos.creative-tim.com/paper-kit-2-angular/).


## Quick start

Quick start options:

- [Download from Github](https://github.com/creativetimofficial/pk2-angular.git).
- [Download from Creative Tim](https://www.creative-tim.com/product/paper-kit-2-angular).
- Clone the repo: `git clone https://github.com/creativetimofficial/pk2-angular.git`.


## Documentation

Once you download the archive, you will be able find a tutorial page inside it explaining how to start using it. You can also check the [documentation online](https://demos.creative-tim.com/paper-kit-2-angular/documentation/tutorial).

## File Structure

Within the download you'll find the following directories and files:

```
paper-kit-2-angular
├── CHANGELOG.md
├── ISSUE_TEMPLATE.md
├── LICENSE.md
├── README.md
├── angular.json
├── documentation
│   ├── css
│   ├── js
│   └── tutorial-components.html
├── e2e
├── karma.conf.js
├── package-lock.json
├── package.json
├── protractor.conf.js
├── src
│   ├── app
│   │   ├── app.component.html
│   │   ├── app.component.scss
│   │   ├── app.component.spec.ts
│   │   ├── app.component.ts
│   │   ├── app.module.ts
│   │   ├── app.routing.ts
│   │   ├── components
│   │   │   ├── basicelements
│   │   │   │   ├── basicelements.component.html
│   │   │   │   ├── basicelements.component.scss
│   │   │   │   ├── basicelements.component.spec.ts
│   │   │   │   └── basicelements.component.ts
│   │   │   ├── components.component.html
│   │   │   ├── components.component.ts
│   │   │   ├── components.module.ts
│   │   │   ├── modal
│   │   │   │   ├── modal.component.html
│   │   │   │   ├── modal.component.scss
│   │   │   │   ├── modal.component.spec.ts
│   │   │   │   └── modal.component.ts
│   │   │   ├── navigation
│   │   │   │   ├── navigation.component.html
│   │   │   │   ├── navigation.component.scss
│   │   │   │   ├── navigation.component.spec.ts
│   │   │   │   └── navigation.component.ts
│   │   │   ├── notification
│   │   │   │   ├── notification.component.html
│   │   │   │   ├── notification.component.scss
│   │   │   │   ├── notification.component.spec.ts
│   │   │   │   └── notification.component.ts
│   │   │   ├── nucleoicons
│   │   │   │   ├── nucleoicons.component.html
│   │   │   │   ├── nucleoicons.component.scss
│   │   │   │   ├── nucleoicons.component.spec.ts
│   │   │   │   └── nucleoicons.component.ts
│   │   │   └── typography
│   │   │       ├── typography.component.html
│   │   │       ├── typography.component.scss
│   │   │       ├── typography.component.spec.ts
│   │   │       └── typography.component.ts
│   │   ├── home
│   │   │   ├── home.component.html
│   │   │   ├── home.component.scss
│   │   │   ├── home.component.spec.ts
│   │   │   ├── home.component.ts
│   │   │   └── home.module.ts
│   │   ├── landing
│   │   │   ├── landing.component.html
│   │   │   ├── landing.component.scss
│   │   │   ├── landing.component.spec.ts
│   │   │   └── landing.component.ts
│   │   ├── profile
│   │   │   ├── profile.component.html
│   │   │   ├── profile.component.scss
│   │   │   ├── profile.component.spec.ts
│   │   │   └── profile.component.ts
│   │   ├── shared
│   │   │   ├── footer
│   │   │   │   ├── footer.component.html
│   │   │   │   ├── footer.component.scss
│   │   │   │   ├── footer.component.spec.ts
│   │   │   │   └── footer.component.ts
│   │   │   └── navbar
│   │   │       ├── navbar.component.html
│   │   │       ├── navbar.component.scss
│   │   │       ├── navbar.component.spec.ts
│   │   │       └── navbar.component.ts
│   │   └── signup
│   │       ├── signup.component.html
│   │       ├── signup.component.scss
│   │       ├── signup.component.spec.ts
│   │       └── signup.component.ts
│   ├── assets
│   │   ├── css
│   │   ├── fonts
│   │   ├── img=
│   │   └── sass
│   │       ├── paper-kit
│   │       └── paper-kit.scss
│   ├── environments
│   ├── favicon.ico
│   ├── index.html
│   ├── main.ts
│   ├── polyfills.ts
│   ├── styles.scss
│   ├── test.ts
│   ├── tsconfig.app.json
│   ├── tsconfig.spec.json
│   └── typings.d.ts
├── tsconfig.json
└── tslint.json

```
## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">

## Useful Links

- [More products](https://www.creative-tim.com/bootstrap-themes) from Creative Tim

- [Tutorials](https://www.youtube.com/channel/UCVyTG4sCw-rOvB9oHkzZD1w)

- [Freebies](https://www.creative-tim.com/bootstrap-themes/free) from Creative Tim

- [Affiliate Program](https://www.creative-tim.com/affiliates/new) (earn money)
