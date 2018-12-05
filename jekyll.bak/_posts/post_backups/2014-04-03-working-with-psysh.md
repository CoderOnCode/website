---
layout: post
title: "Working with Psysh"
published: true
type: post

keywords: php repl, php development, php tools, programming, debugging
description:
gradient: 		2
categories: php development programming debugging

author: 		Allan MacGregor
bio: 			MCD+, Author, Mad Scientist Developer, Lead Magento Developer @demacmedia.
twitter: 		"http://twitter.com/allanmacgregor"
github: 		"http://github.com/amacgregor/"
google: 		"https://plus.google.com/+AllanMacGregor?rel=author"
linkedin: 		"http://ca.linkedin.com/in/allanmacgregor"
rss: 			"http://feeds.feedburner.com/CoderOnCode"
tag: article
---

I previously mentioned Boris, a terrific REPL for PHP, and while Boris is a great and functional REPL, is not the only available.

**Psysh** is actually more than a simple REPL it's also an interactive debugger; which means you can say goodbye to the endless barrage of var_dump() and die() statements.



But do we really need another REPL for PHP, well honestly we could probably get by with the solutions currently available however **Psysh** has an extremely interesting Ace under the sleeve, it can also function as a realtime debugger.

Regardless of the mode on which is running **Psysh** can offer a lot of information about our current application state and code. For example the PHP documentation is available by using the doc command:

<!-- INSERT showterm.io -->
<iframe src="http://showterm.io/5581ee8f7c7d8d91e8c61" width="100%" height="400" ></iframe>

We can also get more information about our current application objects and their properties:

<!-- INSERT showterm.io -->
<iframe src="http://showterm.io/eaea65fdda60f865cd205" width="100%" height="400" ></iframe>

**Psysh** has also been integrated with several popular frameworks like:

- [Laravel](https://github.com/ahmadsherif/laravel-**Psysh**)
- [Drupal](http://www.twinbit.it/en/blog/drupal-and-**Psysh**-drupal-repl)

If you are looking for a powerful REPL to integrate with your PHP project, **Psysh** might the right tool for the job; with powerful features and an integrated debugger **Psysh** has a lot of value to offer to any project.
