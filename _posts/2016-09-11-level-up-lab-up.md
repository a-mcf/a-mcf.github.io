---
layout: post
title: Level-up, Lab-up, Part 1
subtitle: Be the Arbiter, or Victim of Change
tags: [vagrant, lability]
#bigimg: /img/sharing.jpg
---

# Times Are Changing
Let’s face it, on the average, in-house IT is terrible. As someone in IT Ops, understanding that fact only makes watching the uptick in adoption of cloud services by corporations and governments more intimidating. Organizations are outsourcing more and more aspects of their IT infrastructure because they can get superior solutions for less money. Ten years ago, if you were an Exchange administrator for your organization, you were in the cat-bird’s seat. Now, you’re either very nervous, have learned another discipline, or are in for a rude awakening. This is trend is only going to continue, and will make inroads into other aspects of IT Operations.

The good news is that information systems are becoming a larger and larger part of what organizations are doing. The bad news is that the sort of repetitive tasks that many of us have specialized in for years are being automated out of existence. There is still a [role for IT Operations]( https://blog.devopsguys.com/2015/06/30/what-does-the-future-of-it-operations-look-like-in-a-devops-world/), but it’s going to be different. It’s managing infrastructure at scale. It’s understanding the digital supply chain and delivery pipeline. It’s understanding your organization’s application better than anyone else does. It’s learning new tools and understanding new processes to help get changes into production faster. It’s getting out ahead of things before you get swept away in a tidal wave of change.

# Take Control
All of these require some new skills, many of which can be difficult to acquire if your organization is doing things the old way. It’s no excuse, you’ve got to elevate yourself. You need to [read]( http://stevenmurawski.com/devops-reading-list/), you'll need to train, and you’ll need to spend at least some of your free time doing it. Oh, and you don't get to stop.

## Build a Lab
Nothing beats learning by doing. By building test environments, you can be more aggressive than you'd ever be on the company's servers, and you have a free hand to learn what you want. What you don't want to do is spend all of your time installing operating systems. This is something that you *know* how to do. We need a way to quickly spin up lab environments so that we can break free of the drudgery and get to the good stuff, the stuff you don't *yet* know how to do.

In this series, we are going to explore a couple of different approaches to building Windows environments from code. This will allow us to create consistent, repeatable environments that can destroyed and rebuilt at will. This may sound intimidating, but there are tools to help us on the way.

In the next post, we'll run through using [Vagrant](https://www.vagrantup.com/) to quickly provision test environments.
