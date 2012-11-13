:orphan:

.. _contents:

Nginx Community Docs
====================

.. warning:: This documentation project is currently under extremely heavy
   development. DO NOT consider anything in here production ready until this
   notice is removed.


Nginx is a free, open-source, high-performance HTTP server and reverse proxy,
as well as an IMAP/POP3 proxy server. Nginx is known for its high performance,
stability, rich feature set, simple configuration, and low resource consumption.

Unlike traditional servers, Nginx doesn't rely on threads to handle requests.
Instead it uses a much more scalable event-driven (asynchronous) architecture.
This architecture uses small, but more importantly, predictable amounts of
memory under load. Even if you don't expect to handle thousands of simultaneous
requests, you can still benefit from Nginx's high-performance and small memory
footprint. Nginx scales in all directions: from the smallest VPS all the way up
to large clusters of servers.

Nginx powers several high-visibility sites, such as Netflix, Hulu, Pinterest,
CloudFlare, Airbnb, WordPress.com, GitHub, SoundCloud, Zynga, Eventbrite,
Zappos, Media Temple, Heroku, RightScale, Engine Yard, and many others.

Getting Started
===============

Tutorial 1: The Basics
----------------------

You can't just dive in without a clue and hope to achieve something great. Nginx
is NOT Apache. It is not lighttpd. It is not IIS. A successful Nginx deployment
requires basic understanding of your server and of Nginx configuration. In this
tutorial, we aim to get you through the "bare minimum" basics.

1.  :doc:`Getting Started with Linux<topics/tutorials/basics_linux>`
2.  :doc:`Getting Started with BSD<topics/tutorials/basics_bsd>`
3.  :doc:`Getting Nginx Installed<topics/tutorials/basics_installation>`
4.  :doc:`Serving Hello World<topics/tutorials/basics_hello>`

Tutorial 2: Get Configured
--------------------------

Now that you know what's going on, you're ready to put a configuration together
and get rocking with Nginx. Are you excited yet?

1.  :doc:`The Basic Nginx Configuration<topics/tutorials/config_basic>`
2.  :doc:`The Static Content Configuration<topics/tutorials/config_static>`
3.  :doc:`The Dynamic Content Configuration<topics/tutorials/config_dynamic>`
4.  :doc:`Things to Avoid at all Costs<topics/tutorials/config_pitfalls>`

Tutorial 3: Dynamic Content
---------------------------

Now that you have the basics out of the way, you're ready to get something a bit
more useful out of Nginx. After all, you probably are interested in serving more
than just static content. Most content on the web is dynamic, this tutorial
focusses on getting you familiar with how Nginx serves dynamic content.

1.  :doc:`Why is it Different<topics/tutorials/dynamic_why>`
2.  :doc:`Serving PHP<topics/tutorials/dynamic_php>`
3.  :doc:`Serving Python<topics/tutorials/dynamic_python>`
4.  :doc:`Serving Ruby<topics/tutorials/dynamic_ruby>`
5.  :doc:`Serving CGI<topics/tutorials/dynamic_cgi>`

Quick Start
===========

Pre-canned Configurations
-------------------------

As you learned in the tutorials, most Nginx configuration files are very
similar. You can apply the same logic to most web applications and achieve the
desired result. There are some applications that have weird little quirks that
tend to throw a wrench in things.

Nginx happens to have a very well rounded community that has worked to first
address these quirks and then share the resulting configurations. This has
resulted in many "copy and paste" configurations that are almost guaranteed
to work.

1.  :doc:`Application Configurations<topics/apps>`

Other Examples
--------------

Of course, Nginx can do much more. We're barely scratching the surface. If
you're interested, you can take a look at some other examples that have been
developed.

1.  :doc:`Examples<topics/examples>`

Nginx in Depth
==============

Tricky Concepts
---------------

1.  :doc:`Why IF Really is Evil<topics/depth/if>`
2.  :doc:`How Rewrites Work<topics/depth/rewrites>`
3.  :doc:`The Tricky Location Blocks<topics/depth/location>`

Advanced Deployments
--------------------

1.  :doc:`Compiling Nginx<topics/depth/compiling>`
2.  :doc:`Adding Aditional Modules<topics/depth/modules>`
3.  :doc:`Nginx Version Numbers<topics/depth/versions>`

Getting Help
============

The Community
-------------

This documentation project is entirely a community effort driven by the `Nginx
Community Center`_ and not directly affiliated with the `Nginx Company`_. Our
goals are different and here we care strictly about the community (you).

.. _`Nginx Community Center`: http://ngx.cc/
.. _`Nginx Company`: http://nginx.com/

We offer additional resources if you get stuck or just get bored and want to talk.

1.  :doc:`IRC Channel<topics/community/irc>`
2.  :doc:`Nginx Planet<topics/community/planet>`
3.  :doc:`Mailing List<topics/community/email>`
4.  :doc:`Bug Tracking<topics/community/bugs>`
5.  :doc:`Getting Involved<topics/community/get_involved>`

