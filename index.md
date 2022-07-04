---
title: "My impressions on the Aiven developer resource site"
menuTitle: "Aiven for developers"
description: "What are your first impressions, is this a project you would be proud to contribute to? What do you like about the project in its current state? Are there any particular resources that appeal to you? What would you recommend we change and why? This could be content, layout/style, or a suggestion for a section we should add."
author: Dorota Wójcik
date: 2022-06-20
---

## My thoughts on the GitHub project

## What I like

* Comprehensive and informative README
* Orderly logic structure
* Choosing Mermaid over PlantUML
* Info in `REVIEWING` and `CONTRIBUTING`. Still, I think there is some space for adding more, e.g. regarding style guidelines
* Idea of using Vale - it seems a very handy and customizable tool. Perhaps some more tests/ checks could be added.

## My ideas for improvement

* Use more labels for PRs, e.g. for prioritization of issues.
* Make sure there's a linkage (links) between an issue and the related PR.
* Remove branches that are no longer needed.
* Use tags more (there is just one so far) - it's good to be able to return to a specific version at any point.
* Centralize all CSS style-related components and files.
* Introduce some standards for naming issues and PRs.

## My thoughts on the website

## What I like

* Dark theme
* Logo
* `Did you find this useful?` utility
* Search function
* Well-organized sidebar with all services displayed
* Right-side ToC, which makes the page easily navigable
* Including integrations docs is a great idea (Devs need adaptable pluggable solutions to be able to customize their development environments. Relevant docs are also needed to cover all required configuration operations.)

## My ideas for improvement

### Layout & style

* Change the homepage into a simple display with only a few major entry points. The sidebar and more details would only occur after entering a particular entry point. The homepage entry points could reflect major usage scenarios, domains of most of our customers, and worst-case scenario - services themselves
* Add a button for switching between the dark and light modes.
* Change the accent color from red to something less alarming.
* Make the font thinner (it's too thick) and a bit smaller but I'd make bigger the spaces between lines - the plain text is not that readable as-is.
* Make all the lines in UI thinner, e.g. around the search field, the line separating the sidebar from the main pane, and the main pane from ToC
* Remove the disclaimer from most of the pages.
* Make ToCs on the index pages behave in the same way as they do in the sidebar - drop-downs, ie. subsections only available after selecting the superior item.
* Add breadcrumbs.
* Try to be consistent in including and naming categories and subcategories and all the services applying parallel grammar and content structures.
* Fix the mechanism of linking to subsections - now, when you link to a subsection, what gets displayed is the area just below the subsection heading (the heading itself is not visible). It may be confusing for some users - where have we landed up actually?
* Use the code font only in the plain text (not in headings, menu items, tables, lists, etc) - after all, it's for distinguishing the code from the plain text, no need to distinguish something that has already been distinguished one way or another.
* Company logos look good here and there in the docs. On the other hand, adding common icons (preceding e.g. **Concepts**, **HowTo**, **Reference**) or emojis doesn't make the documentation look neat and professional (except for icons for recurring content items, e.g. **Read more**, **Get support** or **Warning**).

### Content-wise

* Add more use cases and user journeys.
* Add as much integration documentation as possible - it seems that's what the users look for very often these days.
* Articles, especially instructions are too wordy and sometimes lack categorization in logical sections, e.g. prerequisites, testing, etc.
* Each article needs to have `PREVIOUS` and `NEXT` buttons somewhere at the bottom to guide the user. Similarly, sections `Before you start` and `Next steps` should be included in most of the articles.
* Add more diagrams in conceptual docs.
* Add more videos/ screenshots in the instructions.
