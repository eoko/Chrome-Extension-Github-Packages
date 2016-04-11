# Chrome-Extension-Github-Packages

## Pitch

A Chrome extension that extends github repositoriy page with a shinny button that enable quick install and some improvements related to package managers.

## Why?

Github is great! There is a lot of integration inside your project like `composer`, `npm`, `bower`... The goal of this extension is to add a repository exploration that read package files like `packages.json`, `bower.json`, `composer.json`, ... and give us a simple button for install without reading the `README.md`. 

This project is also a simple example of a Chrome/Chromium extension for [a JS Lyon Event](http://lyonjs.org/)

## An Idea

![Image](/slide/src/img/capture.png)

## Tasklist

- [ ] Add Js Lyon presentation link
- [ ] Content Script : 
  - [ ] Add a "package" button 
    - [ ] On click, display install cmd
    - [ ] On click, copy to clipboard
  - [ ] Add a "follow" button
    - [ ] Bind "Follow" event for a local save of the package(s)
- [ ] Background
  - [ ] On Chrome event "save", store localy the package
  - [ ] On Chrome event "save", retrieve information for repositories
- [ ] Popup
  - [ ] Show stats
  - [ ] Add label each time a new update is done
  - [ ] Display a link for 
    - [ ] a local app
- [ ] Option
  - [ ] Set config
    - [ ] Github account
- [ ] App
  - [ ] Display a list of followed packages
  - [ ] Filter list for different package manager flavour
  - [ ] Display a list of update
