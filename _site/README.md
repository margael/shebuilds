Middle School Memories

Software-Design-lab

May 19,2020

Middle School memories is a static site that I created using Jekyll.

My goal was to experiment with buildind a site. I spent most of the time working on the technical aspect of it. The content is much less important and I plan to improve it over time.

I use a Windows OS so I will be sharing my technical journey with building this site through the Windows user point of view.

Jekyll is a static site generator.  Instead of using a database for your website, it allows you to create static pages and serve with a simple command from the shell. 
In order to use Jekyll, I had to download Ruby 2.7. Jekyll is written in Ruby

Once I finished installing Ruby step by step as indicated, I install jekyll from the command line. Then I asked jekyll to create a new site. 
Jekyll generated a new site with all the basic folders needed to create a site including posts, layout, assets, config, gemfile, index, and so forth.

Then I executed 
# Bundle exec jekyll serve
which serve the website to my localhost/4000
The site came with a minima theme which is the most basic jekyll theme. It had an index page, an about page, and one blog post already with filler content. It had a footer with values for [insert email] amd [social media name] already built in in the config file.

I made several changes to the look of the site in the main.scss file.
I added background-color to the header, change the formatting of the text and titles by changing the font style, the letter spacing, the text-alignment, the font weights etc., I added background color to the list posts and changed the colors of the links. I added css class attributes for the twitter feed.

I made several changes to the layouts.
I changed the order of the navigation list. I added a twitter feed to the default layout using a javascript code that I sourced from my <a href= "https://hreconstructed.github.io/"> Heritage Reconstruction project.</a> (although I spent two days trying to get the twitter feed to float up but I still can't figure out how to do it. And I've watched many a-tutorials and followed their steps exactly)
I also created a header banner  in the includes folder which I did not use.

I created the content for the site making the stylistic decisions about text and image.
I created two more pages using the page layout. I also created three posts where each contain text and image. I wrote inline html for the posts, especially for the figure elements because i added stylistic values like opacity and border-radius.

My two main struggles which I never was able to figure out was how to get the twitter feed to display correctly and how to get the header bannerto work. I would have published this project much sooner if I had. I hope to continue working on this project over the summer and learning more about the coding languages and things like ruby gems in jekyll themes as well as things like sass which I did not know existed prior to this project. 

In addition to this readme document. I wrote a blog post detailing my personal experience of building the project, not just the technical stuff I was able to do but the way I was affected by the process from the frustrating moments, small victories and what I learned overall. this journal entry will be in my journal repository which which you can find <a href= "https://github.com/margael/journal">HERE</a>

Thank you Patrick for helping me get my layout and includes folder in to my project folder because without seeing the html for the layout, I wouldn't have been able to read the css file.