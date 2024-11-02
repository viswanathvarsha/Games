ails Girls Guides
Rails Girls

The purpose of Rails Girls is to give tools for women to understand technology. The Rails Girls events do this by providing a great first experience on building the Internet.

Rails Girls was founded at the end of 2010 in Helsinki. Originally intended as a one-time event, we never thought to see so many chapters from all around the world! This guide will help you get started.

You can use our materials and instructions to roll out your own workshop in your city, workplace or kitchen! Read more about Rails Girls at https://railsgirls.com

Quick start
View the guides at https://guides.railsgirls.com or clone this repo and install & run jekyll

Installing jekyll
$ cd guides.railsgirls.com
$ bundle install
Pygments and Code Highlighting
The guides use the pygments library to do syntax highlighting. If you don't have it installed you won't be able to see the highlight sections like the following:

{% highlight %}
{% endhighlight %}
If you aren't editing the code blocks, you can safely ignore this. If you want pygments, you can follow the install instructions in the "Pygments" section.

Coach highlights
A custom Liquid tag is available for coach notes. Add these to guides when you want the coach to explain something. Use this tag to make sure the visual element is always the same and easy to recognize.

{% coach %}
Add helpful text here for the coach!
{% endcoach %}
Run jekyll
$ bundle exec jekyll server --watch
Styling
Wrap keyboard shortcuts with kbd HTML tag.

To make posts consistent in style use Ctrl+C over CTRL-c/ctrl+c

To shut down the server you can hit <kbd>Ctrl</kbd>+<kbd>C</kbd>
Having trouble?
You might find some useful hints in this jekyll issue if it's not working as expected: Issue 503

Contributing a Guide
To contribute a guide, view the instructions at https://guides.railsgirls.com/contributing

X
For updates and more, follow @railsgirls on X

Website & Blog
Official website and blog for Rails Girls movement can be found at https://railsgirls.com

E-mail list
Global mailing list for Rails Girls events can be found at https://groups.google.com/group/rails-girls-team

Credits
Karri Saarinen / @karrisaarinen / github
Linda Liukas / @lindaliukas / github
Vesa Vänskä / @vesan / github
Terence Lee / @hone02 / github
Tom de Bruijn / @tombruijn / GitHub
..and all the other coaches and people making Rails Girls awesome. Please add yourself!