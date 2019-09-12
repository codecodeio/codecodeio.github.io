---
layout: post
title:  "Too Long Didn't Read... TLDR"
date:   2019-09-11 00:00:00 -0400
categories: tldr
---
Man pages make my eys bleed. They are an illegible smattering of commands and options that leave me guessing every time. 

Enter [tldr-pages](https://tldr.sh). Want to learn the basics of nginx, just type... 
{% highlight bash %}
$ tldr nginx
{% endhighlight %}

And you are met with this simple list of descriptions and examples

{% highlight bash %}
- Start server with the default config file:
    nginx

- Start server with a custom config file:
    nginx -c config_file

- Start server with a prefix for all relative paths in the config file:
    nginx -c config_file -p prefix/for/relative/paths

- Test the configuration without affecting the running server:
    nginx -t

- Reload the configuration by sending a signal with no downtime:
    nginx -s reload
{% endhighlight %}

Or use a man page and decipher this...
{% highlight bash %}
$ man nginx
nginx [-?hqTtVv] [-c file] [-g directives] [-p prefix] [-s signal]
{% endhighlight %}

Ok but how to I tldr all the things?

 {% highlight bash %}
$ brew install tldr
{% endhighlight %}

Don't have brew? [Get brew](https://brew.sh/).

Enjoy!