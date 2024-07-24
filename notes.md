---
layout: post
title: "Text Formatting"
author: "Paul Le"
categories: sample
tags: [sample]
image: arctic-1.jpg
---

# Markdown Support

As always, Jekyll offers support for GitHub Flavored Markdown, which allows you to format your posts using the [Markdown syntax](https://guides.github.com/features/mastering-markdown/). Examples of these text formatting features can be seen below. You can find this post in the `_posts` directory.

## Basic Formatting

With Markdown, it is possible to emphasize words by making them *italicized*, using *astericks* or _underscores_, or making them **bold**, using **double astericks** or __double underscores__. Of course, you can combine those two formats, with both _**bold and italicized**_ text, using any combination of the above syntax. You can also add a strikethrough to text using a ~~double tilde~~.

## Paragraphs

This is what a paragraph looks like. For the purpose of demonstration, the rest of this paragraph and the next paragraph after will mean absolutely nothing. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.

Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Mauris lobortis nulla et felis ullamcorper bibendum. Phasellus et hendrerit mauris. Proin eget nibh a massa vestibulum pretium. Suspendisse eu nisl a ante aliquet bibendum quis a nunc. Praesent varius interdum vehicula. Aenean risus libero, placerat at vestibulum eget, ultricies eu enim. Praesent nulla tortor, malesuada adipiscing adipiscing sollicitudin, adipiscing eget est.


## Headings

Sometimes it is useful to have different levels of headings to structure your documents. Start lines with `#` to create headings. Multiple `##` in a row denote smaller heading size. The following demonstrate the full range of heading sizes:

# Heading One (h1)

## Heading Two (h2)

### Heading Three (h3)

#### Heading Four (h4)

##### Heading Five (h5)

###### Heading Six (h6)

## Links

You can create an inline link by wrapping link text in square brackets `[ ]`, and then wrapping the URL in parentheses `( )`. For example, it is very easy to [link to Google!](http://google.com).

## Blockquotes

Blockquotes are useful for denoting quotes, or highlighting a large block of text. Single line blockquote:

> This quote will change your life.

Multi line blockquote with a cite reference:

> People think focus means saying yes to the thing you've got to focus on. But that's not what it means at all. It means saying no to the hundred other good ideas that there are. You have to pick carefully. I'm actually as proud of the things we haven't done as the things I have done. Innovation is saying no to 1,000 things.

## Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers - like GitHub or most Jekyll themes - support syntax highlighting. Which languages are supported and how those language names should be written will vary from renderer to renderer. You can find the full list of supported programming languages [here](https://github.com/jneen/rouge/wiki/List-of-supported-languages-and-lexers). Also, it is possible to do `inline code blocks`, by wrapping the text in ` ` ` quotations.

```
No language indicated, so no syntax highlighting.
```

```ruby
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
```

{% highlight js %}
// Example can be run directly in your JavaScript console

// Create a function that takes two arguments and returns the sum of those arguments
var adder = new Function("a", "b", "return a + b");

// Call the function
adder(2, 6);
// > 8
{% endhighlight %}

Another option is to embed your code through [Gist](https://en.support.wordpress.com/gist/).

## Unordered and Numbered Lists

You can make an unordered and nested list by preceding one or more lines of text with `-`, `*`, or `+`, and indenting sublists. The following lists show the full range of possible list formats.

* List item one
    * List item one
        * List item one
        * List item two
        * List item three
        * List item four
    * List item two
    * List item three
    * List item four
* List item two
* List item three
* List item four

Numbered lists are made by using numbers instead of bullet points.

1. List item one
    1. List item one
        1. List item one
        2. List item two
        3. List item three
        4. List item four
    2. List item two
    3. List item three
    4. List item four
2. List item two
3. List item three
4. List item four

## MathJax Example

The [Schrödinger equation](https://en.wikipedia.org/wiki/Schr%C3%B6dinger_equation) is a partial differential equation that describes how the quantum state of a quantum system changes with time:

$$
i\hbar\frac{\partial}{\partial t} \Psi(\mathbf{r},t) = \left [ \frac{-\hbar^2}{2\mu}\nabla^2 + V(\mathbf{r},t)\right ] \Psi(\mathbf{r},t)
$$

[Joseph-Louis Lagrange](https://en.wikipedia.org/wiki/Joseph-Louis_Lagrange) was an Italian mathematician and astronomer who was responsible for the formulation of Lagrangian mechanics, which is a reformulation of Newtonian mechanics.

$$ \frac{\mathrm{d}}{\mathrm{d}t} \left ( \frac {\partial  L}{\partial \dot{q}_j} \right ) =  \frac {\partial L}{\partial q_j} $$

## Tables

Title 1               | Title 2               | Title 3               | Title 4
--------------------- | :-------------------: | :-------------------- | --------------------:
lorem                 | lorem ipsum           | lorem ipsum dolor     | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit
lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit | lorem ipsum dolor sit

## Embedding

Plenty of social media sites offer the option of embedding certain parts of their site on your own site, such as YouTube and Twitter:

<iframe width="560" height="315" src="https://www.youtube.com/embed/mthtn1X4eUY" frameborder="0" allowfullscreen></iframe>

<a class="twitter-grid" data-partner="tweetdeck" href="https://twitter.com/paululele/timelines/755079130027352064">New Collection</a> <script async src="//platform.twitter.com/widgets.js" charset="utf-8"></script>

## Inline HTML elements

HTML defines a long list of available inline tags, which you can mix with Markdown if you like. A complete list of which can be found on the [Mozilla Developer Network](https://developer.mozilla.org/en-US/docs/Web/HTML/Element).

## Useful Resources

More information on Markdown can be found at the following links:

- [Markdown Here Cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Here-Cheatsheet#code)
- [Quick Markdown Example](http://www.unexpected-vortices.com/sw/rippledoc/quick-markdown-example.html)
- [Markdown Basics](https://daringfireball.net/projects/markdown/basics)
- [GitHub Flavoured Markdown Spec](https://github.github.com/gfm/)
- [Basic writing and formatting syntax](https://help.github.com/articles/basic-writing-and-formatting-syntax/#lists)



---
layout: post
title: "About the Author"
author: "Paul Le"
categories: facts
tags: [sample]
image: cuba-2.jpg
---

Hi there! I'm Paul. I’m a physics major turned programmer. Ever since I first learned how to program while taking a scientific computing for physics course, I have pursued programming as a passion, and as a career. Check out [my personal website](https://www.lenpaul.com/) for more information on my other projects (including more Jekyll themes!), as well as some of my writing.
---
layout: post
title: "Learning Resources"
author: "Paul Le"
categories: resources
tags: [documentation,sample]
image: arctic-2.jpg
---

The beauty of computer programming is that you do not need to formally go to school to learn how to program. You can learn almost everything that you would need to know online, and for free. The following resources are some that I have used personally, that I highly recommend, for anyone looking to learn more about computer programming.

## [Free Code Camp](https://www.freecodecamp.org/)

My personal favourite for learning full stack web development. They offer a great front and back end curriculum that requires you to complete a variety of projects in order to apply the knowledge that you learn during the lessons. As a bonus, at the end of the curriculum you will have a few impressive projects under your belt for your portfolio.

## [Codecademy](https://www.codecademy.com/)

---
layout: post
title: "Learning Resources"
author: "Paul Le"
categories: resources
tags: [documentation,sample]
image: arctic-2.jpg
---

The beauty of computer programming is that you do not need to formally go to school to learn how to program. You can learn almost everything that you would need to know online, and for free. The following resources are some that I have used personally, that I highly recommend, for anyone looking to learn more about computer programming.

## [Free Code Camp](https://www.freecodecamp.org/)

My personal favourite for learning full stack web development. They offer a great front and back end curriculum that requires you to complete a variety of projects in order to apply the knowledge that you learn during the lessons. As a bonus, at the end of the curriculum you will have a few impressive projects under your belt for your portfolio.

## [Codecademy](https://www.codecademy.com/)

Not only does Codecademy have many great courses on various web development languages such as [HTML](https://www.codecademy.com/learn/learn-html), [CSS](https://www.codecademy.com/learn/learn-css), and [JavaScript](https://www.codecademy.com/learn/introduction-to-javascript), but they even offer a course on [how to deploy a Jekyll site](https://www.codecademy.com/learn/deploy-a-website). If you are completely new to Jekyll, I would recommend working through that course as a great start for learning how to deploy your Jekyll site.

## [Khan Academy](https://www.khanacademy.org/)

A great resource not only for learning mathematics (what most people probably know Khan Academy for), but also [computer programming](https://www.khanacademy.org/computing/computer-programming). What Khan Academy offers that is different from the other two above resources is that it offers courses in [computer science related](https://www.khanacademy.org/computing/computer-science) topics, such as [algorithms](https://www.khanacademy.org/computing/computer-science/algorithms) and [cryptography](https://www.khanacademy.org/computing/computer-science/cryptography). This is unique in that most online resources mostly focus on the programming side of things.

---
layout: post
title: "Welcome to Millennial!"
author: "Paul Le"
categories: documentation
tags: [documentation,sample]
image: cuba-1.jpg
---

Millennial is a minimalist Jekyll theme. The purpose of this theme is to provide a simple, clean, content-focused blogging platform for your personal site or blog. Below you can find everything you need to get started.

## Getting Started

[Getting Started]({{ site.github.url }}{% post_url 2016-10-10-getting-started %}): getting started with installing Millennial, whether you are completely new to using Jekyll, or simply just migrating to a new Jekyll theme.

## Example Content

[Text and Formatting]({{ site.github.url }}{% post_url 2016-09-09-text-formatting %})

## Questions?

This theme is completely free and open source software. You may use it however you want, as it is distributed under the [MIT License](http://choosealicense.com/licenses/mit/). If you are having any problems, any questions or suggestions, feel free to [tweet at me](https://twitter.com/intent/tweet?text=My%20question%20about%20Millennial;via=paululele), or [file a GitHub issue](https://github.com/lenpaul/Millennial/issues/new).

## More Jekyll!

### Lagrange

Lagrange is a minimalist Jekyll blog theme that I built from scratch. The purpose of this theme is to provide a simple, clean, content-focused blogging platform for your personal site or blog.

Feel free to check out <a href="https://lenpaul.github.io/Lagrange/" target="_blank">the demo</a>, where you’ll also find instructions on <a href="https://lenpaul.github.io/Lagrange/journal/getting-started.html">how to use install</a> and use the theme.

### Portfolio Jekyll Theme

This is a Jekyll theme built using the [DevTips Starter Kit](http://devtipsstarterkit.com/) as a foundation for starting, and following closely the amazing tutorial by [Travis Neilson over at DevTips](https://www.youtube.com/watch?v=T6jKLsxbFg4&list=PL0CB3OvPhDA_STygmp3sDenx3UpdOMk7P). The purpose of this theme is to provide a clean and simple website for your portfolio. Emphasis is placed on your projects, which are shown front and center on the home page.

Everything that you will ever need to know about this Jekyll theme is included in [the repository](https://github.com/LeNPaul/portfolio-jekyll-theme), which you can also find in [the demo site](https://lenpaul.github.io/portfolio-jekyll-theme/).

### Jekyll Starter Kit

The Jekyll Starter Kit is a simple framework for starting your own Jekyll project using all of the best practices that I learned from building my other Jekyll themes.

Feel free to check out <a href="https://github.com/LeNPaul/jekyll-starter-kit" target="_blank">the GitHub repository</a>, where you’ll also find instructions on how to use install and use the theme.
