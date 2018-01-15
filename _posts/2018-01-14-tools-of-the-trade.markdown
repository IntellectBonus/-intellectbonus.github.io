---
layout: post
title: "Falling for VS Code"
date: 2018-01-14 12:00:00 -0500
categories: programming
---

About 20 years ago I started to code in QBasic. Over time the languages and tools available have steadily improved. As a professional I've developed software with C# and Visual Studio. Visual Studio has a lot of nice features but has limited multi-language support. With more of my hobby projects moving to JavaScript, Visual Studio has become less attractive as an IDE (Integrated Development Environment). To solve that problem I've recently switched to using VS Code. 

VS Code is a cross platform IDE developed by Microsoft. It is billed as the editor that stays out of the way so you spend less time configuring your environment and more time coding. 

It is easy to fall in love with VS Code. It is fast, simple, customizable and most importantly extendable. VS Code has support for multiple languages as well as intellisense and debugging. 

There are a ton of extensions from Microsoft and the community. As you'd expect there are extensions for the usual suspects including; linters, snippets, and debuggers, but the options are numerous. I was really surprised to see the extension eco-system for VS Code is much more vibrant then Visual Studio's.

VS Code helps remove the tedious parts of coding. As an example to start a new html document, press ! followed by tab and VS Code will get you started with this snippet:

{% highlight html %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
{% endhighlight %}

VS Code completion and intellisense save you time, but these features just get the fun started. The command palette is ready to serve up commonly used tasks - just press control + shift + P. 

If you are working with markdown, VS Code has great markdown edit support and when you're ready to preview just press control + shift + v. 

You no longer have to leave your IDE for source control. VS Code make it more accessible with git support out of the box. If you don't use git, don't worry, VS Code also has SCM (Source Control Module) providers for TFS(Team Foundation Server), SVN (Apache Subversion), Hg (Mercurial), Perforce, Source Depot and RCS (Revision Control System) integration.

If you haven't taken VS Code for a ride yet I really suggest that you do.