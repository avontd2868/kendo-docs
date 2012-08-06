---
title: Kendo UI Documentation Repo
slug: root-readme
publish: false
---

# Kendo UI Public Documentation

Test.
Welcome to the GitHub repo for [Kendo UI](http://www.kendoui.com) [Documentation](http://docs.kendoui.com). This repository contains the source content--written in Markdown--that we use to power the Kendo UI Documentation at [docs.kendoui.com](http://docs.kendoui.com). If you've arrived here wanting to search and peruse our docs, you'd be better served heading over to [docs.kendoui.com](http:\\docs.kendoui.com) where our content is prettified and searchable. 

We believe that the documentation for a product is at its best when the content is a collaboration between the builders and consumer of that product. As such, this documentation is both public, and open sourced under and MIT license (see below). That means you can clone this repository, read the docs off line, or even load the entire thing to an Apple Newton, if that's your thing.

It also means that you can play a role in making our docs better for everyone, and if helping us make the Kendo UI docs better sounds interesting to you, read on.

## Contributing

There are two ways you can contribute to the public Kendo UI documentation: either create an issue in this repository, or fork the repo, make the change and send us a pull request!

* **Create an issue** - If you find an issue with our docs that needs to be addressed, the best way to let us know about it is by [creating an issue in this repository](https://github.com/telerik/kendo-docs/issues?state=open). When creating an issue, provide a descriptive title, be as specific as possible and link to the document in question (If you can provide a link to the closest anchor to the issue, all the better). Here's an example:

		Title: api/DataViz/chart.md is missing an image
		Description: Example 3 is missing an image right after the code sample. https://github.com/telerik/kendo-docs/issues?state=open
 
> Note: When creating issues, please don't modify the assignee or milestone fields. Also, please create one issue per fix or change. "Bundled" entries will be deleted.

* **Send us a pull request** - Creating an issue is great--and we certainly appreciate them--but what we really love are pull requests. So, if you find an issue in the docs, or even feel like creating new content, we'd be happy to have your contributions! If you're just getting started with open source, Git and GitHub, we suggest you first read up on [forking repos](https://help.github.com/articles/fork-a-repo) and [sending pull requests](https://help.github.com/articles/using-pull-requests), both great articles from the GitHub bootcamp.  
	
	Once you've read these--or you've already memorized them--you're ready to contribute to the Kendo docs. Start by creating a local clone of our repo either using [GitHub for Windows](http://windows.github.com/), [GitHub for Mac](http://mac.github.com/) or your friendly command-line:

		git clone git@github.com:telerik/kendo-docs.git

	Then, open up the kendo-docs folder in your favorite text editor and contribute away! Of course, as you work with the docs, we do ask that you follow a couple of ground rules:

	- Fixing grammar, punctuation and other general errors is always appreciated. So are changes that expand on key ideas or correct errors in logic phrasing or otherwise. If your ambitions are greater, however, and you want to add completely new content to the site--like a new tutorial on using Kendo UI with an Atari 2600, for instance--we suggest you contact a member of the team first (or enter an issue!) to vet your idea. [John Bristowe](http://twitter.com/johnbristowe), [Burke Holland](http://twitter.com/burkeholland), [Todd Anglin](http://twitter.com/toddanglin) and [Brandon Satrom](http://twitter.com/brandonsatrom) would all be happy to hear your idea and offer advice.
	- Each document in this repo contains a section of YAML Front Matter at the very top. This content, which looks like the text below, is used by our auto-import tool when content is processed for the [docs.kendoui.com](http://docs.kendoui.com) site. Please don't edit the content in this section of a document.

		---
		
		title: kendo.dataviz.ui.Chart
		
		slug: dataviz-kendo.dataviz.ui.chart
		
		tags: api,dataviz

		publish: true
		
		---

	- When adding content or making changes, please use only standard Markdown syntax, and make to preview your additions or changes before sending us a pull request. You can use an online tool like [Dillinger.io](http://dillinger.io/) or [Marked](http://markedapp.com/) on OSX to view what your changes will look like when ported to HTML.

	Once you've made your changes, commit, pull, merge, push and [send us a pull request](https://help.github.com/articles/using-pull-requests)! We--and Kendo UI users everywhere--thank you for making our docs the best front-end library documentation on the web! 

## License

The Kendo UI Documentation is licensed under an MIT license. This license applies to the markdown (.md) files in this site **ONLY**, and does not convey, override or modify any existing licenses covering the runtime source and components of Kendo UI. For information about available licensed for the Kendo UI Library, visit our [license page](http://www.kendoui.com/faq/licensing.aspx) at [KendoUI.com](http://kendoui.com).

### MIT License

Copyright (c) 2012 Telerik

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.