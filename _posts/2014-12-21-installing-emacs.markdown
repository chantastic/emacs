---
layout: post
title: Installing Emacs
published: true
categories:
---

We're going to talk about Emacs. I've never used it before and I'm curious what all the fuss is about.

## How I Installed Emacs

I use [Homebrew](http://brew.sh/) to install commandline tools. So, here's how to do it with Homebrew:

{% highlight bash %}
$ brew install emacs
{% endhighlight %}

With no additional options, that installs `24.4.1` on my machine, the current version (Dec 2014).

## Additional flags

I'm using Emacs in Terminal but you can build it with a GUI, using the `--cocoa` flag, and get full color support with the `--srgb` flag.

{% highlight bash %}
$ brew install emacs --cocoa --srgb
{% endhighlight %}

Further installation instructions and options [here](http://www.emacswiki.org/emacs/EmacsForMacOS#toc16) and [here](http://wikemacs.org/wiki/Installing_Emacs_on_OS_X#Homebrew), if you care. I don't really.

## Opening Emacs

I had to start a new Terminal session. After that, I could run `emacs` and get the non-system version, version `24.4.1`.

It's off to the races.