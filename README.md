# link-checker  <img src="https://i.imgur.com/7HcdYSd.png" data-canonical-src="https://i.imgur.com/7HcdYSd.png" width="25" height="25" />


When you're reading an article or a blog post, you often wonder whether clicking on a particular link would redirect you to new tab or the same tab. When you click on a link which would open in the same tab, your whole context would get lost. This add-on helps you to determine whether a particular link will open in new tab or the same tab.

## What it does

This extension includes:

* a background script, "background.js"
* a page action

It adds the [page action](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/API/pageAction)  to every tab the user opens. Clicking the page action for a tab applies some CSS using [tabs.insertCSS](https://developer.mozilla.org/docs/Mozilla/Add-ons/WebExtensions/API/tabs/insertCSS).

Clicking again removes the CSS using [tabs.removeCSS](https://developer.mozilla.org/docs/Mozilla/Add-ons/WebExtensions/API/tabs/removeCSS).

## What it shows

* A toggle switch to apply or remove this add-on.
* If applied, it would show  the below icon when you hover on the link if it were to open in a new tab.
 <img src="https://i.imgur.com/7HcdYSd.png" data-canonical-src="https://i.imgur.com/7HcdYSd.png" width="50" height="50" />

## Demo

![](https://j.gifs.com/ANzrO3.gif)
