---
published: false
---

[GitHub](https://github.com/) is well known as a 'social coding' site integrated with the version management software [git](http://en.wikipedia.org/wiki/Git_(software)). It's user friendly user interface and low price (it's free!) have led to explosive growth in its use over the last few years. Now GitHub is the de facto home of some of the most exciting free software projects on the planet including [QGIS](https://github.com/qgis/QGIS) and the daddy of all open source software projects, [Linux](https://github.com/torvalds/linux).

Fewer people know that GitHub can also act as a free shared (as opposed to [dedicated](http://en.wikipedia.org/wiki/Dedicated_hosting_service)) webserver. This short article explains how.

## Creating the online repository

GitHub is mostly accessed through the secure https:// hypertext address protocol, which is encrypted. However, when you put content into a special place in GitHub, it is served via the unencrypted and much more accessible http:// protocal.

### username.github.io

This special place is a repository called username.github.io. So if my username is robinlovelace, [for example](https://github.com/Robinlovelace/robinlovelace.github.io), my 'gh-pages' repository should be named robinlovelace.github.io. This is indeed the case.

Now, anything that I put inside this repository is automatically published to the internet at [http://robinlovelace.github.io/](http://robinlovelace.github.io/). Now, clicking on that you will see that it redirects you elsewhere, but that's just because I've set up a redirect. The [MassAtLeeds](https://github.com/MassAtLeeds) user, for example, has the following website address: [http://massatleeds.github.io/](http://massatleeds.github.io/) . So username would have the home address of http://username.github.io. You get the idea!

## Jekyll

All GitHub pages are pre-processed by [Jekyll](http://en.wikipedia.org/wiki/Jekyll_%28software%29), a static website system. This is not the place to describe Jekyll: check out their excellent home page, tutorials and try it.

To sum-up Jekyll, it allows you to build a website in the normal way with html or intelligently, using the [`_config.yml` file](https://github.com/MassAtLeeds/MassAtLeeds.github.io/blob/master/_config.yml) and markdown (.md) files. In fact, this post is [simply a .md file placed in MassAtLeeds.github.io](



## Jekyll - a static website builder



Enter text in [Markdown](http://daringfireball.net/projects/markdown/). Use the toolbar above, or click the **?** button for formatting help.
