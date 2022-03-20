---
title: "Git Push"
date: 2022-02-24T02:35:47+08:00
draft: false 
---
So I did the "about" page.  I believe there was a serious syntax error when I amended the about markdown file. I tried to copy the _index.md file in the example site.  It worked.  So, I just copy the whole thing again.  That's not a high level problem though.

And I deployed the hugo site on the Netlify server.  To be clear, compiled the files in hugo locally (at the predator), push the site folder onto my git hub repository. Actually,I think the files need not be compiled at all.  When I connect the repository to the Nelify server, it has an appliction to compile the md files into static html files.  The compiling speed is crazy fast. 
https://suspicious-swirles-f76550.netlify.app/posts/

There are still something unclear to me.  
1.The git commands.  There are init, commit, add and push/pull.  Commit has a -m flag, I have not I idea what that means. In my understanding, I first init something.  "add" a repository locally, commit to a "branch".  When I commit, I insert comment as follow:
`git commit -m "fixed some error"`
The "fixed some error" comment will show in the git repository metadata. 
After I commit, I can hit `git push`
Anyways, I still don't know what is "add" and "branch"
2.I want to have it in my domain, http://space.gallerieboii.sbs. It said it need some DNS thing. Will have to check it out.
3.The portfolio needs update.  I may write a post here for every project of my life.  That would be cool.

