# [Find By Face](https://demos.creative-tim.com/material-kit-react)


![build](https://img.shields.io/travis/USER/REPO.svg) ![version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![Product Presentation Image](public/cover.png)


## Table of Contents


* [Demo]()
* [Frameworks-Used](#frameworks-used)
* [Dependencies](#dependencies)
* [Installation](#installation)
* [File Structure](#file-structure)
* [Contributors](#contributors)
* [Browser Support](#browser-support)
* [Reporting Issues](#reporting-issues)


## Frameworks Used

- [Nodejs](nodejs/node) by Ryan Dahl.
- [Reactjs](facebook/react) by Facebook.
- [Material Kit React](creativetimofficial/material-kit-react) by Creative Tim.


## Dependencies

 - [NodeJs](https://nodejs.org/en/download/) and npm (alrealy bundled w/ node)
 - [MiniConda](https://conda.io/miniconda.html)
 - [OpenCV](https://sourceforge.net/projects/opencvlibrary/)
 
```shell
▖~ # run as administrator in Anaconda Prompt
▖~ # Once Miniconda is installed, conda pkg-manager used to install packages, create environments etc.
▖~ conda update -n base conda
▖~ conda create -n FindByFace
▖~ activate FindByFace
▖~ conda install python=2 numpy matplotlib
▖~ pip install cython
▖~ python -m pip install --upgrade pip
▖~ pip install opencv-python
```


## Installation

- Downloads
```shell
▖~ git clone https://github.com/aniruddha0pandey/FindByFace.git && cd FindByFace
▖~ 
```
- Build
```shell
▖~ npm install
▖~ npm start
```
<sub>Navigate to http://localhost:3000/ if not automatically redirected.</sub>
- Deploy
```shell
▖~ npm install -g serve
▖~ serve -s build
```
<sub>Navigate to http://192.168.209.1:5000/ if not automatically redirected.</sub>


## File Structure
Within the download you'll find the following directories and files:

```
FindByFace/
.
├── CHANGELOG.md
├── LICENSE.md
├── README.md
├── package.json
├── public
│   ├── index.html
│   └── manifest.json
└── src
    ├── index.js
    ├── routes
    │   └── index.jsx
    ├── assets
    │   ├── img
    │   │   └── kit
    │   │       ├── faces
    │   │       └── free
    │   │           └── examples
    │   ├── jss
    │   │   ├── material-kit-react
    │   │   │   ├── components
    │   │   │   └── views
    │   │   │       ├── componentsSections
    │   │   │       └── landingPageSections
    │   │   └── material-kit-react.jsx
    │   └── scss
    │       ├── core
    │       │   ├── mixins
    │       │   └── variables
    │       ├── plugins
    │       └── material-kit-react.scss
    ├── components
    │   ├── Badge
    │   │   └── Badge.jsx
    │   ├── Card
    │   │   ├── Card.jsx
    │   │   ├── CardBody.jsx
    │   │   ├── CardFooter.jsx
    │   │   └── CardHeader.jsx
    │   ├── Clearfix
    │   │   └── Clearfix.jsx
    │   ├── CustomButtons
    │   │   ├── Button.jsx
    │   │   └── IconButton.jsx
    │   ├── CustomDropdown
    │   │   └── CustomDropdown.jsx
    │   ├── CustomInput
    │   │   └── CustomInput.jsx
    │   ├── CustomLinearProgress
    │   │   └── CustomLinearProgress.jsx
    │   ├── CustomTabs
    │   │   └── CustomTabs.jsx
    │   ├── Footer
    │   │   └── Footer.jsx
    │   ├── Grid
    │   │   ├── GridContainer.jsx
    │   │   └── ItemGrid.jsx
    │   ├── Header
    │   │   ├── Header.jsx
    │   │   └── HeaderLinks.jsx
    │   ├── InfoArea
    │   │   └── InfoArea.jsx
    │   ├── NavPills
    │   │   └── NavPills.jsx
    │   ├── Pagination
    │   │   └── Pagination.jsx
    │   ├── Snackbar
    │   │   └── SnackbarContent.jsx
    │   └── Typography
    │       ├── Danger.jsx
    │       ├── Info.jsx
    │       ├── Muted.jsx
    │       ├── Primary.jsx
    │       ├── Quote.jsx
    │       ├── Small.jsx
    │       ├── Success.jsx
    │       └── Warning.jsx
    └── views
        ├── Components
        │   ├── Components.jsx
        │   └── Sections
        │       ├── SectionBasics.jsx
        │       ├── SectionCarousel.jsx
        │       ├── SectionCompletedExamples.jsx
        │       ├── SectionDownload.jsx
        │       ├── SectionExamples.jsx
        │       ├── SectionJavascript.jsx
        │       ├── SectionNavbars.jsx
        │       ├── SectionNotifications.jsx
        │       ├── SectionPills.jsx
        │       ├── SectionSignup.jsx
        │       ├── SectionTabs.jsx
        │       └── SectionTypography.jsx
        ├── LandingPage
        │   ├── LandingPage.jsx
        │   └── Sections
        │       ├── ProductSection.jsx
        │       ├── TeamSection.jsx
        │       └── WorkSection.jsx
        ├── ProfilePage
        │   └── ProfilePage.jsx
        └── SignupPage
            └── SignupPage.jsx
```


## Contributors

<a href="../../../../aniruddha0pandey" target="_blank"><img src="https://avatars1.githubusercontent.com/u/31156696?s=460&v=4" 
alt="Aniruddha Paney" width="70" height="70" border="10" /></a> <a href="../../../../shubham007kumar" target="_blank"><img src="https://avatars1.githubusercontent.com/u/34106521?s=460&v=4" alt="Shubham Kumar" width="70" height="70" border="10" /></a>

## Browser Support

At present, we officially aim to support the last two versions of the following browsers:

<img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/chrome.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/firefox.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/edge.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/safari.png" width="64" height="64"> <img src="https://s3.amazonaws.com/creativetim_bucket/github/browser/opera.png" width="64" height="64">


## Reporting Issues

We use GitHub Issues as the official bug tracker. Standard Issue/Bug request is supported.
