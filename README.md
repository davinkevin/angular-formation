# Angular (2+) Formation 

This repository represents source code of slides deck used during formation on Angular 2+

## Table of contents
- Technical Requirements

### Technical Requirements

To be able to do Practical Work during the formation, you need to have : 
* A computer (the one from your company or your personal if this one is better)
* An execution environment based on NodeJS 6+, NPM (or YARN) and AngularCLI
* An evergreen browser
* An development environment

#### The computer

You need to have a computer with some technical requirements : 
* At least 8 Gb of ram
* A good hard drive (SSD is preferred) with free space (~10 Gb)
* A decent CPU (Core I5 or more)

This minimal requirement represents the minimum vital choice to use, work and develop in good condition

#### Execution environment

##### NodeJS v6+

![Image of Yaktocat](/img/our_practical_exercise/logo_nodejs.svg)

It's preferred to follow the instruction relative to your operating system available on the official [NodeJS website](https://nodejs.org/en/download/)

You can check if the install is correct by executing the following command in a Shell (bash, Power-Shell & co)

```shell
$ node -v
v7.6.0
```

##### NPM 

NPM, the default package manager should be installed if you follow the NodeJS installation instruction.

You can check if NPM is correctly installed by execution the folowing command :

```shell
$ npm -v
4.1.2
```

##### YARN  

Yarn is a new alternative to NPW which is very (VERY) faster.

You can install YARN by using NPM with the following command

```shell
$ npm install -g yarn
```

Depending of your plateform, this command should be launched with admin rights (sudo for Mac & Linux for example).

You can check the correct installation of YARN by execution the following command

```shell
$ yarn -V
0.20.3
```
 
##### AngularCLI

The AngularCLI is a simple NodeJS project which could be installed by following the intruction on its [official GitHub Repo](github.com/angular/angular-cli)

To simplify, a standard installation should be : 

```shell
$ npm install -g @angular/cli
```

You can check the correct installation of the AngularCLI by execution the following command (the result depends of the AngularCLI, node and os version)

```shell
$ ng -v

                             _                           _  _
  __ _  _ __    __ _  _   _ | |  __ _  _ __         ___ | |(_)
 / _` || '_ \  / _` || | | || | / _` || '__|_____  / __|| || |
| (_| || | | || (_| || |_| || || (_| || |  |_____|| (__ | || |
 \__,_||_| |_| \__, | \__,_||_| \__,_||_|          \___||_||_|
               |___/
@angular/cli: 1.0.0-beta.32.3
node: 7.6.0
os: darwin x64
```

#### Evergreen Browser

You need to have on your computer a, so called, evergreen browser, which represents the top last version of Chrome, Firefox or Edge. You can realise the Practical work on any of this browser

A part of the practical work will be done with Chrome, so an up-to-date version of chrome is required for some example.

#### Development Environment

##### IDE

The work during the formation will be done in TypeScript, HTML, SASS, JSON... You mainly need to have a dev environment which allow you to be efficient to write code in those languages.

To do that, I recommend to use JetBrains WebStorm (under license, free trial of 30 days)

You can use Microsoft VSCode, which is open source
 
If you have a preference for another environement, free to you to use it, but a lot of the PW will be simpler if you have auto-complete, IDE help and other stuff provided by a powerfull environement... 

##### Git

You need for this formation to have on your computer a recent version of Git. The installation / update version of git is linked to your OS, so you need to refere to online documentation on How to install git on your post

You can check the correct installation of the GIT by execution the following command

```shell
$ git --version
git version 2.10.0
```

