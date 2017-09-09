## Etterna Wiki

This is the Wiki for <a href="https://github.com/etternagame/etterna">Etterna</a>

It's done using <a href="https://pages.github.com/">gh-pages</a>, <a href="https://github.com/jekyll/jekyll">Jekyll</a> and a little bit of <a href="http://getbootstrap.com/">Bootstrap</a>. It's not done using gh-wikis because having a repository allows us to control changes, have a more powerful history and get pull requests for new or edited content.


### Contributing

#### How to make changes and request their addition

If you want to contribute, the best way is to make a fork of this repo, download it, edit it, push your changes to your fork to test them, and then Pull Request.

I recommend you get <a href="https://git-scm.com/">Git</a> if you dont already have it and make a <a href="https://github.com/join">GitHub Account</a>.

Once you have those, open a commandline or terminal on the folder you want simply clone from your fork by running "git clone https://github.com/yourusername/wiki.git" (Replace your username)
 https://github.com/etternagame/wiki.git
 
Then make your changes and run "git push gh-pages" (Or "git push https://github.com/yourusername/wiki.git gh-pages")

To verify the changes open https://yourusername.github.io/wiki

Once your fork has your changes, open a <a href="">Pull Request</a> towards this repo to request the addition of those changes to the wiki.


#### Jekyll Basics

To add a new page just make a new markdown .md file. <a href="https://github.com/jekyll/jekyll">Jekyll</a> will take care of parsing it and transforming it into an html page(Which will use the default layout).

#### Structure

The 'cpp' folder contains the files for the c++ wiki, and 'lua' the ones for the lua wiki.

Both of these folders and the root folder contain a _Sidebar.md file, which is the sidebar for the respective subwiki(If you add a new page and want to add it to the sidebar, you should edit this file).


#### Markdown Basics

You can find some markdown documentation <a href="https://guides.github.com/features/mastering-markdown/">here</a>.

