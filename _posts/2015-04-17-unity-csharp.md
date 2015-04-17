---
layout: post
title: Programming C# for Unity on Sublime Text
---

I can't deny, the Unity built in editor, [MonoDevelop](http://www.monodevelop.com/), is a nice IDE. It has all the features I expected, including code completion, error detection and debug integration with Unity. Sadly, it's not as stable as I expected, having some bugs that make it unusable for me (e.g. it doesn't handle quotes on my keyboard).

An alternative was to use Visual Studio, which has a nice integration using [Visual Studio Tools for Unity](http://unityvs.com/). Like MonoDevelop, it's possible to debug Unity scripts on Visual Studio. The only issue I have is that it doesn't work with the Express version (or am I mistaken?).

#### Sublime Text

My next plan was to go with my usual editor, [Sublime Text](http://www.sublimetext.com/). I've been using it for a while and it's working really nice (see the gif below). The only thing I miss is the debuging, which I've been doing with MonoDevelop.

![]({{ site.baseurl }}images/posts/unity-csharp/behaviour_demo.gif)

##### OmniSharp

The [OmniSharp](https://github.com/OmniSharp/omnisharp-sublime) package adds IDE features such as error reporting and IntelliSense code completion. It does the magic using a server which runs on background and parser your files. The downside is that it fails sometimes to find the Unity run time.

The package is available on [Package Control](https://packagecontrol.io/) and depends on an entry on your [project settings](https://www.sublimetext.com/docs/3/projects.html) to find the solution. I ended up creating a template for this:

{% gist JulioC/58556ae155e818a4bbc1 %}

##### Unity Reference Search

[Unity Reference Search](https://packagecontrol.io/packages/Unity3D%20Script%20Reference%20Search) allows you to search the Unity documentation for the selected text using `CTRL+'`.

##### Other helpers

A great annoyance for me was remembering the messages that Unity calls on MonoBehaviour. On the first days I used sublime completions file (which the source I can't remember), but OmniSharp overrides the suggestion list, making the completions inaccessible.

I ended up converting them into snippet files, which are available on my GitHub: [JulioC/unity-messages-snippets](https://github.com/JulioC/unity-messages-snippets). I also made a [MonoBehaviour snippet](https://gist.github.com/JulioC/a8ec963741d8699c221c).