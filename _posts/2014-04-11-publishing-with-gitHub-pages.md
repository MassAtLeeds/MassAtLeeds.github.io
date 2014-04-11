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

To sum-up Jekyll, it allows you to build a website in the normal way with html or intelligently, using the [`_config.yml` file](https://github.com/MassAtLeeds/MassAtLeeds.github.io/blob/master/_config.yml) and markdown (.md) files. In fact, this post is [simply a .md file placed in MassAtLeeds.github.io](https://github.com/MassAtLeeds/MassAtLeeds.github.io/blob/master/_posts/2014-04-11-publishing-with-gitHub-pages.md)!

## prose.io

Another useful thing about GitHub that not everyone knows is that it has a diverse plugin 'ecosystem'. Third parties can gain access your accout and do [useful things like create online mass-editable maps](http://robinlovelace.net/maps/2013/11/16/mapping-for-the-masses.html) via geojson.io. Another useful plugin which makes adding content to GitHub pages even easier, is [prose.io](http://prose.io/). This, and the entire processes of publishing collaborative content using GitHub is described in the video below.

<iframe width="420" height="315" src="//www.youtube.com/embed/Dv2ZUvH-pho" frameborder="0" allowfullscreen></iframe>

## Conclusion

Git frequently amazes new users with its capabilities. GitHub is the online extension of this that can provide what feels like superpowers to the collaborative coder. Clearly this is useful to programmers and makes it easier than ever to contribute to and produce digital content available to anyone. It also has great potential to help academics, sometimes accused of sitting in [ivory towers](http://www.theguardian.com/commentisfree/2012/may/07/academics-cant-answer-criticism-analysis), engage with wider online communities and make their work and reproducible results available to the public.
