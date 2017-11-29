# Developer Documentation
----

This Documentation helps you to understand code.

If you want to report a bug or ask a question, create and issue.

## Summary ##

* [General](#general)
* [Requirements](#requirements)
* [Installation](#Installation)
* [How to use program](#how-to-use)
* [Code style](#code-style)
* [Code structure](#code-structure)

## General ##

- **Author** : 사고7조
- **Version** : version 0.2
- **Compatibility** : [Fill it]

## Requirements ##

1. **Bundler** : [`Bundler install`](https://bundler.io)

## Installation ##

1. Run `git clone https://github.com/HyeJinP/os_second_project.git`
2. Installation Requirements
3. Run `npm install -g eslint eslint-config-airbnb-base eslint-plugin-import` to install `NPM dependencies`

## How to use ##

[Fill it]

## Code style ##

We use [ESLint](https://eslint.org/) based on Google code style to maintain javascript code style.  
Check code style with :
```
npm run lint

# or  

grunt eslint
```


## Code structure ##

```
os_second_project  
├── .github  
├── css  
├── js  
├── docs  
├── slide  
├── meme  
└── texts  
```

| File/Folder | Description |
|-------------|-------------|
| **.github**     |Contains file templates for GitHub|
| **css**         |Contains css code files|
| **js**          |Contains javascript code files|
| **docs**        |Contains user and developer documentation|
| **slide**       |Contains Cardnews image and source to make visible|
| **meme**        |Contains Card Generator|
| **texts**       |Contains license and software guarantee||  

#### Views ####

```
├── slide  
    ├── a.html
    ├── ...
    ...
...
```

|File/Folder|Description|
|---|---|
|**slide**|Contains main screen's partial Cardnews|
|**slide/a.html**|Contain Cardnews images.|
|...|...|
|**slide/e.html**|Contain Cardnews images.||

#### html ####

```
├── index.html
├── login.html
└── upload.html
```

|File/Folder|Description|
|---|---|
|**index.html**|Contails main screen.|
|**login.html**|Contains login screen.|
|**upload.html**|Contain uploading Cardnews images.||

#### javascript ####

```
├── js
    └── index.js
...
└── slide
    ├── jquery.slides.min.js
    ├── rrssb.js
    └── rrssb.min.js
```

|File/Folder|Description|
|---|---|
|**index.js**|Contain method of uploading Cardnews images.|
|**jquery.slides.min.js**|Contain method of moving(sliding) Cardnews images.|
|**rrssb.js**|Contain method of sharing Cardnews images.|
|**rrssb.min.js**|Minimized rrssb.js||
