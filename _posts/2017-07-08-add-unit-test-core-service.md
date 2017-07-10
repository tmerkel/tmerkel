---
layout: post
title: Adding Unit Testing to an Asp.Net Core Web Service
---

# Adding Unit Testing to an Asp.Net Core Web Service

**NOTE:** I have chosen to use XUnit. While NUnit has been used previously by teams, they don't seem to be as good at keepking tooling up to date for .Net Core/Visual Studio releases.  XUnit is also used by the .Net Core team...so it's more likely that things will work.

## Add unit test project

Right-click on your solution and choose **Add->New Project**.

Select **.Net Core** from the left-hand menu and then choose **xUnit Test Project (.NET Core)**

By convention, test projects will be named <ProjectName>.Tests (as in, the tests for this project).

Add a reference to the project being tested.

## Add unit tests

For each class to be tested, right-click on the unit test project and choose **Add->New Item**.

Choose **Class** as the item type to add.

By convention, unit test files will be named <ClassName>Tests.cs (as in, the tests for this class).

## Run unit tests

Unit tests can be run using your favorite test runner.

## Next Steps

