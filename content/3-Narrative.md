---
title: Narrative
nav: Narrative
topics: Narrative; Frame your ideas
description: >
    This section has example Bootstrap feature includes that can be used to add some interest to your lesson content. Directly below this is an example video embed!
youtubeid: moJgWrD6dwg
---
People remembers a story

## Frame your ideas with your audience's view
Facts and evidence rarely help as people tend to reject any information or facts that counter their beliefs. So, data has to be in a context. People remember how a story makes them feel. It is important to know your audience and frame your idea to align with their values / views.

### Biases to be aware of - Confirmation bias
"We give special weight to information that allows us to come to the conclusion we want to reach." We tend to cherry-pick information that confirms our existing beliefs or ideas.

### How to challenge bias?
If possible, get some background understanding of your audience. What would their current perception be, or potential concerns around the topic of interest? Can you approach your topic from a different direction?
For example, if you have someone that isn’t that interested in the environment, and thinks that environmental laws cost too much money for business, but you want to highlight climate change, talk about :

The rising cost of insurance due to more natural disasters, caused by the change in weather cycles
The financial benefit and potential profit of hosting electronic vehicle production in Australia or cheap maintenance on solar farms vs profit

### Success story by Bono (U2)
Did you know that Bono was a strong advocate of AIDS support? He reached out to the American evangelical community by framing the AIDS problem with christianity view and got their support. How? There is a nice article [here](https://www.pbs.org/wgbh/pages/frontline/aids/interviews/bono.html). 

## Structure your story
Craig Cormick says that “Knowing your audience and your communication objective is crucial, but if you can turn your message into a story, it has a much better chance of being accepted.” 
Narrative flow = Story (how it might be described in chronological order) + Plot (how the story is told)
### Storyboarding
A storyboard is a planning tool for visualising and organising ideas

A storyboard helps you:
Define the parameters of a story within available resources and time
Organize and focus a story
Figure out what medium to use for each part of the story
![image](https://user-images.githubusercontent.com/19921944/122855900-4c43e480-d359-11eb-8af8-94f06d42e8ce.png)



Content pages are written in markdown and can be enhanced using Liquid includes that are packaged with the template.
Start by editing the examples or creating new files in the "content" folder.

[Markdown](https://daringfireball.net/projects/markdown/) is a standard to [simplify writing](https://evanwill.github.io/_drafts/notes/writing-markdown.html) content for the web. 
[GitHub markdown flavor](https://help.github.com/articles/basic-writing-and-formatting-syntax/) can be used any where on GitHub and in Jekyll.
The basics are intuitive, you can learn in about a minute!
See [Markdown in a Minute](https://evanwill.github.io/_drafts/notes/markdown-minute.html) to get started.

At the top of each page is "YML front matter" used to configure the page.
Use these options:

- to include a page in the header and footer navigation, add `nav:` push the text you want to appear to the file's yml front matter. Alternatively, add `nav: true` to use the page's `title:` value. All pages with a `nav` value will appear in the top-bar, sorted by order of filenames. For simplicity use leading numbers in the lesson page filenames to create correct order.
- `title:` value will appear as `h1` at the top of the page.
- `topics:` will appear as a small feature below the title (optional). 
- `description:` will appear as an indented text block below the title (optional). This gives you a chance to summarize the section contents. 
- `youtubeid:` will add an YouTube video embed (optional). Find the id in the YouTube link. For example, in `https://youtu.be/moJgWrD6dwg` or `https://www.youtube.com/watch?v=moJgWrD6dwg` the youtubeid is `moJgWrD6dwg`.
- Alternatively, if you don't want `title` or other options to appear on the page, you can over ride the layout by adding `layout: default` 

## Components Includes

`workshop-template-b` contains a series of [Liquid "includes"](https://jekyllrb.com/docs/includes/) to add basic [Bootstrap components](https://getbootstrap.com/docs/4.1/components/) to your Markdown content.
Examples below demonstrate the includes.

--------

#### Figures 

`{% raw %}{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}{% endraw %}`

{% include figure.html img="uidaho-workshop.jpg" alt="workshop scene" caption="Library workshops!" width="75%" %}

----------

#### Alerts

`{% raw %}{% include alert.html text="This is a Bootstrap [Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}{% endraw %}`

{% include alert.html text="This is a [Bootstrap Alert](https://getbootstrap.com/docs/4.1/components/alerts/)" align="center" color="success" %}

-----------

#### Link Buttons 

`{% raw %}{% include button.html text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}{% endraw %}`

{% include button.html text="Bootstrap Docs" link="https://getbootstrap.com/docs/4.1/components/buttons/" color="info" %}

---------

#### Cards

```{% raw %}
{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.html text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}{% endraw %}
```

{% capture text %}
1. Can add more complex text using markdown.
2. Use a Liquid capture to create the text.
3. It magically becomes a [Bootstrap Card](https://getbootstrap.com/docs/4.1/components/card/).
{% endcapture %}
{% include card.html text=text header="Example Card" title="Title example" img="uidaho-workshop.jpg" %}

------------

#### Modal

`{% raw %}{% include modal.html button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}{% endraw %}`

{% include modal.html button="Try Me" color="success" title="Example Modal" text="This is a modal, with little text." %}

-------------

#### YouTube embed

`{% raw %}{% include video-embed.html youtubeid="moJgWrD6dwg" caption="Example video" %}{% endraw %}`

{% include video-embed.html youtubeid="moJgWrD6dwg" caption="Example video" %}
