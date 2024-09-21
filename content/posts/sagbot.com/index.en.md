+++
title = "SAGBOT.com"
date = 2024-09-21
author = "Lurgrid"
tags = ["SAGBOT", "Lurgrid", "Website"]
keywords = ["Lurgrid", "SAGBOT", "SAGBOT.com", "Hugo", "Markdown", "Website"]
cover = "image.png"
+++

## *SAGBOT.com* history

*SAGBOT.com* was launched at the end of 2021. Since its launch, the site has undergone numerous visual evolutions, each marked by frequent updates. However, one common thread runs through all these changes: the project has never been completely finished. Often, I lacked the motivation to work on the front-end, not really having the soul of an artist, nor the pen of a writer, I didn't know what to write to enrich the content.

The old versions were essentially made with **HTML/CSS/PHP/JS** and were often single-page websites (*SPA*). And as I said before, they were frequently empty of content, or even still contained fillers (*placeholder*) and even in the worst case links leading to *404* pages, because they weren't coded yet.

It got to the point where for months *SAGBOT.com* (before finally making this website) looked like this, just a black page with a simple &laquo; Welcome to SAGBOT.com &raquo; and a little animation that makes the text move.

{{ figure src="/posts/sagbot.com/old_sagbot.com.gif" alt="Gif Old SAGBOT.com" position="center" caption="GIF of the latest version of <i>SAGBOT.com</i>" captionPosition="center" >}}

## Current version

The current version of *SAGBOT.com* is no longer based on the same technologies, and no longer has the same purpose. As the *SAGBOT* project has evolved and become more personal, *SAGBOT.com* has become a personal website. As a result, *SAGBOT.com* is now a blog where I'll be posting articles on IT or even the evolution of the project, like this one.

### Design

Before coding, you need to ask yourself &laquo; How do I want *SAGBOT.com* to look? &raquo;. After some thought and even discussion with friends and family, I came to the conclusion that *SAGBOT.com* should become a blog about computer science, to be more in line with my career plan, which is to become a teacher-researcher (see [About](https://www.sagbot.com/fr/about)). Given that in the world of research, article writing is commonplace.

Now that I've got the subject of the website, I need to know how to format it. First of all, single-page layout is out, because it's not really compatible with blogs. I also need to keep article writing simple, so that I don't have to recode a **HTML** page for each article, otherwise it'll be a hindrance to writing and the site will end up like other <u>vides</u>. Mastering **LaTeX** and **Markdown** and their syntaxes being simple and being reaction-centric, I needed to be able to generate a **HTML** page from a document in one of these two languages. One of the greatest advantages of **LaTeX** is the freedom it gives you, and the numerous packages (*package*) that allow you to customize your page layout (*Tikz*, etc.). Unfortunately, this advantage can become a drawback in our case, as it complicates the compatibility of all the packages in our **HTML** page generator. As a result, we're left with a real choice: **Markdown**.

As I'm an admirer of the **Rust** programming language, I initially wanted to build the site with the [markdown-rs](https://github.com/wooorm/markdown-rs) or [mdx-rs](https://github.com/wooorm/mdxjs-rs) libraries. When I looked into [**MDX**](https://mdxjs.com/), it seemed the perfect candidate for making the articles, as this **Markdown** format allows you to use **JS/JSX** in a **Markdown** document. But when I talked to friends and family who also had websites, they advised me not to use **MDX**, but to use **Markdown** website builder tools such as [**Hugo**](https://gohugo.io/) or [**Zola**](https://www.getzola.org/), as it would be more suited to my needs and simpler than redoing the whole thing. One of my relatives already had a website created with **Hugo** and was very happy with it.

After reading the documentation for both tools, **Hugo** seemed simpler and more in tune with what I wanted to do. That's how I came to use **Hugo**. As I said at the beginning of this article, I'm not really an artist, so I'm using a theme that [panr](https://radoslawkoziel.pl/) has made available to everyone &laquo; [Hugo Terminal](https://themes.gohugo.io/themes/hugo-theme-terminal/) &raquo; with colors generated from his [Terminal.css](https://panr.github.io/terminal-css/) tool.

### Articles

As I said before, the articles that will appear on *SAGBOT.com* will be computer-related, on a variety of subjects that appeal to me. The aim will be to write some from time to time, hoping that people will find them interesting. To make the articles as available as possible, all of them will be translated into English, as it's an international language.

## Conclusion

The creation of *SAGBOT.com* has been a true quest for learning and perseverance. Despite the many challenges encountered, this project has grown to reflect my personal and professional aspirations. From a simple single-page site to a blog, I was able to transform an unfinished idea into a dynamic and useful platform.

Adopting **Hugo** as my website generator was an important decision, facilitating the management of articles and ensuring scalability. This transition underlines the importance of choosing the right tools for the long-term vision of a project. In addition, the integration of themes gave *SAGBOT.com* a visual identity, despite my self-perceived lack of artistic ability.

In the future, *SAGBOT.com* will continue to grow as a resource dedicated to IT and the evolution of the *SAGBOT* project. I'm looking forward to sharing more knowledge, insights and discoveries with an international audience through English translations. This site represents not only a showcase for my technical skills, but also a space for expression and sharing in the field of research.

I'm grateful for the support and advice I received throughout the development process, which were instrumental in overcoming the obstacles and bringing this project to fruition.

Now all I have to do is write articles!

---

### Thank you

I would like to thank [T. RENAUX VERDIERE](https://renauxv.fr/) and [Mirabelle S. P.](https://github.com/oiimrosabel) for their advice throughout the research and creation of this website. Special thanks to T. RENAUX VERDIERE for proofreading this article and the other pages of the website.