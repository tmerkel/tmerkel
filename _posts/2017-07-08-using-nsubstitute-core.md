---
layout: post
title: Using NSubstitute when Unit Testing an Asp.Net Core Web Service
---

# Using NSubstitute when Unit Testing an Asp.Net Core Web Service

Many teams use NSubstitute for mocking. There appears to be an issue adding this package if you're testing a Asp.Net Core site.  You may see something like:

```
Severity Code Description Project File Line Suppression State Error Package Microsoft.Composition 1.0.27 is not compatible with netcoreapp1.1 (.NETCoreApp,Version=v1.1). Package Microsoft.Composition 1.0.27 supports: portable-net45+win8+wp8+wpa81 (.NETPortable,Version=v0.0,Profile=Profile259)
```

The workaround for this is documented [here](https://github.com/dotnet/corefx/issues/9788#issuecomment-288678333).