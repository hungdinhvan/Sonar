---
id: stetho
title: Stetho Guidance
sidebar_label: Stetho Guidance
---

In 2015, we introduced [Stetho](http://facebook.github.io/stetho/), an Android debugging bridge built on top of Chrome dev tools. While it was a valuable tool to us and many members of the community, we felt that it limited us in what we could do with it. Stetho is Android-only and while Chrome dev tools gave us a nice foundation to build upon, they also limited us in what we could build. Stetho is an Android tool and Chrome dev tools is built for web developers. This means we can only provide a good experience for the intersection of those two development environments, which was very limiting. With Sonar being built as a standalone app, we can do more things, like handling adb connections and supporting iOS, which wasn't easily achievable with stetho.

This is why we built Sonar. We wanted to create a platform that gives us all the flexibility we need to build more advanced features and support for iOS. One of Sonar's core concept is it's extensibility using [plugins](create-plugin.md). Plugins are written in react and we provide a set of ready-to-use UI components that allows developers to build great plugin UIs with a few lines of code.

While offering many new features, Sonar also already covers most of the features provided by Stetho. This includes network and layout inspection, and an advanced log viewer. We are committed to continuously improving Sonar with new features and plugins, however we are aware that not all stetho features are currently supported by Sonar. If you are using a particular feature of Stetho which isn't supported by Sonar, we are more than happy to hear about your use-case. Stetho will continue to work and we are not abandoning it so you can choose the tool that fits your needs best. We are confident that Sonar will work well for most use-cases and are more than happy to accept contributions from the open-source community adding new features.
