---
published: false
---

## Diving into C# with Unity

An overview on my learning process of C# while starting out with Unity development

### The enviroment

I can't deny, the built in editor, [MonoDevelop](http://www.monodevelop.com/) is a nice IDE, with all the features I expected from it, including code completion, error detection and debug integration with Unity. Sadly, it's not as stable as I expected and has some bugs that make it unusable on my machine (it doesn't handle quotes from my keyboard).

An alternative was to use Visual Studio, which has a nice integration using [Visual Studio Tools for Unity](http://unityvs.com/). Like MonoDevelop, it's possible to debug Unity scripts on Visual Studio. The only issue I have is that it doesn't work with the Express version (correct me if I'm wrong).

#### Sublime Text setup

My next plan was to go with my usual editor, [Sublime Text](http://www.sublimetext.com/). I'd heard about [OmniSharp](https://github.com/OmniSharp/omnisharp-sublime), a plugin for Sublime which adds IDE features such as error reporting and IntelliSense-like code completion. The image below is from [a post by Jonathan Channon](http://blog.jonathanchannon.com/2014/11/12/csharp-first-class-citizen-sublime-text/) where he goes in detail about the plugin. His setup is not made for Unity, so I've made [a gist]() with the settings I'm currently using.

![](http://i.imgur.com/IkirwAE.gif)

Another useful package I'm using is [Unity Reference Search](https://packagecontrol.io/packages/Unity3D%20Script%20Reference%20Search), which adds the `CTRL+'` shortcut for searching on the Unity docs. On [Package Control](https://packagecontrol.io/) there is a collection of [snippets for Unity C#](https://packagecontrol.io/packages/Unity%20C%23%20Snippets). I didn't feel confortable with them, so I'm creating my own as I go ( for now, it's not usefull enough to be public).

### Learning C#

I consider myself a C++ programmer with some Java knowledge, so the idea was to get an overview of C# reading comparassions  . Since C# is s

...