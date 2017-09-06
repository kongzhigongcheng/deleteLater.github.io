---
layout: post
title: Hello,Wolrd
date: 2018-09-12 10:09:54 +0800
description: Where i start my bolg life. # Add post description (optional)
img: hello-world.jpg # Add image post (optional)
tags: [Blog, StartPoint]
author: Zhang # Add name author (optional)
---
You’ll find this post in your _**_posts**_ directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run _**jekyll serve**_, which launches a web server and auto-regenerates your site when a file is updated.

To add new posts, simply add a file in the _**_posts**_ directory that follows the convention _YYYY-MM-DD-name-of-post.ext_ and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets,but here i want use highlight.js to render my code:

<pre><code class="csharp">namespace HelloWolrd
{
    public class HelloWolrd
    {
        public HelloWolrd()
        {
            // ctor
        }

        /// &lt;summary&gt;
        /// Introduce yourself to other
        /// &lt;/summary&gt;
        /// &lt;param name="yourName"&gt;your name&lt;/param&gt;
        public void SayHello(string yourName)
        {
            System.Console.WriteLine($"Hello,everyone, My name is {yourName}");
        }
    }
}
</code></pre>

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
