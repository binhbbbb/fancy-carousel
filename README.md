# \<fancy-carousel\>

[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://beta.webcomponents.org/element/annsonn/fancy-carousel)
[![Build Status](https://travis-ci.org/annsonn/fancy-carousel.png?branch=master)](https://travis-ci.org/annsonn/fancy-carousel)
[![Issue Count](https://codeclimate.com/github/annsonn/fancy-carousel/badges/issue_count.svg)](https://codeclimate.com/github/annsonn/fancy-carousel)
  
[![Published on Vaadin  Directory](https://img.shields.io/badge/Vaadin%20Directory-published-00b4f0.svg)](https://vaadin.com/directory/component/annsonnfancy-carousel)
[![Stars on vaadin.com/directory](https://img.shields.io/vaadin-directory/star/annsonnfancy-carousel.svg)](https://vaadin.com/directory/component/annsonnfancy-carousel)


Carousel which gives you options for multiple fancy transistions and different ways to include images.

## Example

```
<fancy-carousel>
    <img src="https://app-layout-assets.appspot.com/assets/bg1.jpg">
    <img src="https://app-layout-assets.appspot.com/assets/bg2.jpg">
    <img src="https://app-layout-assets.appspot.com/assets/bg3.jpg">
    <img src="https://app-layout-assets.appspot.com/assets/bg4.jpg">
</fancy-carousel>
```

| Properties      | Type    | Comment                                                                                  |
| --------------- |:-------:| ---------------------------------------------------------------------------------------- |
| apiKey          | String  | API key for Google image search                                                          |
| imageTopic      | String  | The topic for image search                                                               |
| noControls      | Boolean | Do not display control buttons for left/right (Default: false)                           |
| searchEngineCx  | String  | CX key for Google                                                                        |
| transitionTimer | Number  | Timer for transitioning to the next slide                                                |
| transitionType  | String  | Type of transition animation (Currently available types: spread, paint, shift, collapse) |


## Running 
Use the 'polymer-cli' to test/demo component

### To Demo/Test Component
```
polymer serve
```
Then go to 'localhost:8080/components/fancy-carousel' to view component

### To run tests:
```
polymer test
```
