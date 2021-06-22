---
title: Knowledge is incremental
nav: Knowledge
---

Every piece of information we learn is founded on something we have already learned before. Thus, layering information is critical. It is a tool you can use to guide your audience through a complex story. In data storytelling, we can achieve this by:
- Compounding builds in visualisation
- Sequencing different types of visualisations
- Drilling deeper into a single visualisaion

## Putting it together
Do you know Dr Ignaz Semmelweis? 
{% include figure.html img="DrSemmelweis.jpg" alt="Dr Semmelweis" caption="Dr Semmelweis" width="75%" %}

Watch his story from [here]

### Lessons learnt from Semmelweis story
1. Timeliness and Clarity
- He did not publish for 14 years
- His findings were not well communicated
2. Audience and the Curse of Knowledge
- His audience (Doctors) at the time were not used to being criticised
- Instead of concept sharing and patience, he went on the attack and threw insults at his critics
3. Narrative Evokes Emotion
- Failed to tell the story of his data- did not humanize his patients but treated them as numbers
- Provided numbers instead of impact
4. Power of Data Visualization
- Relied primarily on data tables
- Ignored the Visual effect of graphs

### Activity
If you were Dr Semmelweis, how would you storyboard your ideas and re-tell your story?

Things you may want to think are:
- What audience would you focus on?
- What angle would you use to appeal to your audience?
- What would be your call to action? - Not sure that I understand 'call to action"
- Develop a brief flow of ideas about how you would most logically convey the story.



To learn about using `workshop-template-b`, the [Readme](https://github.com/evanwill/workshop-template-b/blob/master/README.md) and content pages have some documentation.

Workshop sites using this template:

- [Make OER!](https://evanwill.github.io/make-oer/) (presentation)
- [Hey API!](https://evanwill.github.io/hey-api/) (workshop)
- [Teaching Tech Hands-on](https://evanwill.github.io/tech-hands-on/) (presentation)
- [Refine APIs](https://evanwill.github.io/refine-apis/) (workshop)
- [Mini Web Crash Course](https://evanwill.github.io/mini-web-crash-course/) (workshop)

Other workshop sites an [minimal version of this template](https://github.com/evanwill/workshop-template) (no bootstrap):

- [get-git](https://evanwill.github.io/get-git/)
- [hello-arduino](https://evanwill.github.io/hello-arduino/)
- [clean-your-data](https://evanwill.github.io/clean-your-data/)
- [go-go gh-pages](https://evanwill.github.io/go-go-ghpages/)
- [Make @ the MILL](https://uidaholib.github.io/make-at-the-mill/)

# Reference

### Git & GitHub

[GitHub](https://github.com/) is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and [free static web hosting](https://pages.github.com/) powered by [Jekyll](https://jekyllrb.com/).
Accounts are free.
To learn more check out Hello World on [GitHub Guides](https://guides.github.com/) or [GitHub Learning Lab](https://lab.github.com/).

### Markdown

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to simplify writing content for the web. 
Markdown can be used any where on GitHub and in Jekyll.

- [Mastering Markdown GitHub Guide](https://guides.github.com/features/mastering-markdown/){:target="_blank" rel="noopener"}
- [GitHub Markdown documentation](https://docs.github.com/en/free-pro-team@latest/github/writing-on-github/basic-writing-and-formatting-syntax){:target="_blank" rel="noopener"}
- [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html)

### Bootstrap 4

[Bootstrap](https://getbootstrap.com/) is a CSS framework designed to streamline developing user interfaces for your website. 
It is combined with a JavaScript library [jQuery](https://jquery.com/) to simplify adding interactive components. 

### FontAwesome 5

[FontAwesome](https://fontawesome.com/) is an icon set used to easily add icons to websites.
Check the [gallery](https://fontawesome.com/icons?d=gallery&m=free) for the freely available icons.

### YAML

[YAML](http://www.yaml.org/) is a human readable plain text data format.
It is used in Jekyll for configuration, site data, and front matter.
Jekyll projects are [configured](https://jekyllrb.com/docs/configuration/) using the `_config.yml` file.

### Liquid

[Liquid](http://shopify.github.io/liquid/) is a flexible template language.
[In Jekyll]((https://jekyllrb.com/docs/liquid/) it allows you to layout pages built from modular components and data, using the `_includes`, `_layouts`, and `_data` directories.
Liquid includes features such as operators, loops, and filters to manipulate raw content. 
Liquid statements are enclosed by {% raw %}`{%  %}`{% endraw %} and variables in {% raw %}`{{  }}`{% endraw %}.

### Sass  

[Sass](http://sass-lang.com/) is a CSS extension / preprocessor. 
All normal CSS is valid SCSS, but Sass adds many powerful functions and programmatic features. 
Writing SCSS is often easier and more sensible, for example by supporting nesting, variables, and operators. 
Jekyll lets you write SASS in modular chucks called partials, in the `_sass` directory, that will be combined and compiled into normal CSS files when the site is built.
