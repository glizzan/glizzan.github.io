---
title: "Bundles of Sticks All the Way Down"
teaser: "The core goal of Concord is to create a system which allows people to adapt their community's permissions to meet their changing needs. I've tried to do this by breaking permissions down into component parts. Every permission can be treated separately, and configured in a variety of ways. The drawback to this approach is how hard it is to build back up sensible, expected behavior."
categories:
  - governance
  - projects
  - law
---

The core goal of Concord is to create a system which allows people to adapt their community's permissions to meet their changing needs. I've tried to do this by breaking permissions down into component parts. Every permission can be treated separately, and configured in a variety of ways.

The drawback to this approach is how hard it is to build back up sensible, expected behavior. I'm working on creating a templating system but as I start filling up my "template library" I find I often miss a step. Yesterday I was working on a template, meant to be applied to a list resource, which would give the list's creator the ability to do whatever they wanted, and allow other users to make changes but only if they got the creator's approval. After some fiddling I was able to do that -- only to realize that I hadn't given the creator the ability to apply the template.

Sometimes I worry that this system I've built is needlessly complex and poorly designed, and other times I suspect that *any* approach that tries to build permissions systems up from building blocks would be this complex. They say that property rights are a [bundle of sticks](https://en.wikipedia.org/wiki/Bundle_of_rights) - a messy conglomeration of many rights belonging to many people configured differently in different circumstances. I think that's true of all rights. "Free speech" may seem straightforward but cenutries of case law shows that it's not. Why should the digital world be any different?

Here's the behavior of the template I ended up making:

![screenshot]({{ site.url }}/assets/kybern/from_docs/list_template_example.gif)