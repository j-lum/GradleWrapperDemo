# GradleDemo

## Introduction

This is a repo to investigate the bootstrapping of a gradle project from a provided gradle wrapper.

## Getting started

1. Clone this repo 
2. Run `gradlew init`
3. Follow the instructions to bootstrap your project
    1. Select 6 to bootstrap a java-application
    2. Select 1 to use groovy (I speak kotlin/scala but not groovy)
    3. Select 3 to use junit as the test framework
    4. Enter the project name.
    5. Enter the package name (usually your organization's URL in reverse)  

If you're using IntelliJ IDEA, you can `Import Gradle project` after bootstrapping to ensure that your files are 
being tracked properly.