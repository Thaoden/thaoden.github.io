---
layout: default
title: "Hello World!"
date: 2019-02-24
---
# Hello World
I'm hosted with GitHub Pages.

## What is this about?
I've been working as a C# developer for a few years now, mostly writing web applications and services (MVC, WebApi). When .NET Core was released, I was happy enough to just start a new greenfield project so that I could adopt ASP .NET Core from the very beginning.

For quite some time, I've taken an interest in functional programming, namely F#, but didn't quite find the time (or the project) to learn it. I watched some videos from conferences talking about it, read some website on how to use it but I still couldn't think of what to do with it.

Also for quite some time, I wanted to start a blog about the things that I do - only I didn't know what to write about, thinking that all has been said already by someone else, more clever than I am. So why repeat it?

Then came the idea to combine it: Start a project written in F# and document the steps I had taken and why. As my wife and I have more than a few cooking and baking books and journals, every time we want to redo some special recipe we spend a lot of time to find it again (because of course we don't write down what recipe worked for us and what didn't). Thus I had the plan to write some website around a database where we could enter all the recipe books and journals that we own together with the recipes contained and of course make it searchable and bookmarkable. It sounds like an easy enough project that I can use it to learn an unfamiliar language. Document the progress in public so that maybe, I can get some feedback on it.

As I want to host the code on GitHub, I think it's natural to use GitHub Pages with Jekyll for the accompanying blog. I plan to use GitHub Project to track the features that should be implemented, though I will have to look deeper into both.

The "Hello World" opening came from the Getting Started section of GitHub Pages (Who would have guessed). The first thing I noticed after setting up the theme was that it wasn't rendered. I made sure I had a `_config.yaml` page in the folder structure, but it still wasn't picking up the layout.

After googling a bit, I found the same question in the [Github Community Forum](https://github.community/t5/GitHub-Pages/Page-not-showing-the-theme/m-p/5545/highlight/true#M393) as it turns out, one has to remove all html tags but the body, so that the Jekyll configuration can kick in. Don't forget the trailing `</html>` tag!

Next thing to do will be to set up a local install of Jekyll so that I can check the appearance of a new post before making it publicly available. Also, I need some layout for date and time (and maybe for comments).

So that's it for the introductory post. If you have some feedback, I'd be happy to hear it (though I still have to figure out how you can send it to me - I guess for now, file an issue on [GitHub](https://github.com/Thaoden/thaoden.github.io) ).
