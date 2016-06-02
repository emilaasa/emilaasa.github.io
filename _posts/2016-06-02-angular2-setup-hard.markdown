---
layout: post
title:  "Setting up Angular2 the hard way!"
date:   2016-06-02 06:36:46 +0200
categories: jekyll update
---
* TOC
{:toc}

## Step 1: TypeScript, typings and tslint

### Goal:
Be able to write and compile a TypeScript `Hello world`, with scaffolding for project-wide TypeScript support.


After this step we should have a tsconfig.json with settings for our compiler, a
tslint.json with settings for the linter, a typings.json config for our type
definition files and a folder where `typings` stores it's type definition files,
all in the root of the app.

### TypeScript
TypeScript only needs a compiler.
For a global install, use:
npm install -g typescript
Add a tsconfig.json with your projects rules.


### Typings
Typings works like a package manager for TypeScript definition files.

npm install --saveDev typings
typings init 

Now we have a typings folder. This is where `typings` will install it's type definition files.


### tslint

npm i --saveDev tslint

tslint.json:
take it from a style guide, for example the angular2webpack one

### Compiles!

## Step 2: Adding Angular 
Goal: Hello world from Angular 2
Currently we are adding the rc-1 tutorials dependencies

## Step 3:


{% highlight typescript %}
import { Bulk }
{% endhighlight %}


