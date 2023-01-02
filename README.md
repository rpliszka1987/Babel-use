# Intro to Babel transpiler for JavaScript

## Table of Content

- [Introduction](#introduction)
- [Transpilation](#transpilation)
- [caniuse](#caniuse)
- [Babel](#babel)

## Introduction

This is a Code Academy course which this section focuses on Transpilation using Babel.

## Transpilation

**Transpilation** term for tranlate code to different formats of the same language. Used for older browsers which might not support newest features of the programing language.

Example:

- Using JavaScript ES6 in older browsers

## Caniuse

Website which you can look up which broswers, and browsers versions support feature we are trying to use. This can be found on the website: https://caniuse.com/

## Babel

**Babel** is a popular transpiler for JavaScript that can be integrated into your projects. You can find out more on the site:
https://babeljs.io/

**Running Babel**

`    $ npm run build`

## Babel Setup

Step 1 - Initiating our npm project

    $ npm init -y

This step will initiate the npm package and create the **package.json** file in the directory.

Step 2 - Add to package.json script to run Babel

    "scripts" : {
        "build" : "babel src -d out"
    }
