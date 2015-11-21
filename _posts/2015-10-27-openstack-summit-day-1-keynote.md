---
author: slowe
comments: true
date: 2015-10-27
layout: post
title: OpenStack Summit 2015 Day 1 Keynote
categories: Liveblog
tags:
- OpenStack
- OSS
---

This is a liveblog of the Day 1 keynote at the OpenStack Summit here in Tokyo, Japan. As is quite often the case at conferences like this, the wireless network is strained to its limits, so I may not be able to publish this liveblog until well after the keynote ends (possibly even later in the day).

After a brief introduction by one of the leaders of the OpenStack Japan User Group (I couldn't catch his name), Jonathan Bryce takes the stage. Jonathan takes a few minutes to welcome the attendees, thank the conference sponsors, and go over some logistics (different hotels, meals, getting help, etc.). Jonathan announces the first individual certification for OpenStack---the Certified OpenStack Administrator. The certification test will be available starting in 2016. Not many details are given; I assume that more details will be released in the coming days and weeks.

Jonathan also takes a moment to talk about Liberty, the 12th release of OpenStack. Based on the features added, he feels that manageability, scalability, and extensibility were the key themes for Liberty. This leads Jonathan into a discussion of users and developers, sometimes (not beneficially) separated by sales and product management. Jonathan feels that the open development model employed by OpenStack is better in that users and developers are interacting and working together at all phases of design and development.

This topic, in turn, leads Jonathan into a discussion of OpenStack's new program management guidelines (aka "the Big Tent" model). He starts with a discussion of the interoperability guidelines (DefCore), and he brings out Egle Sigler to talk about DefCore's work. Egle says that interoperability is really about user experience---interoperability and DefCore is about making sure that "special flavors" of OpenStack don't evolve and fracture the community (or the user experience). According to Sigler, DefCore is a community-driven process that involves scoring capabilities, take those scores back to the community for feedback, and then incorporate that information into guidelines upon the next release. Want to get involved? Sigler says you can get involved by using RefStack to upload cloud test data to the Foundation; another way to get involved is to participate in DefCore meetings on IRC or the DefCore mailing lists. At this point, Egle leaves the stage and Jonathan takes over again.

Maturity and adoption are critically important to Jonathan, and he announces a new section on the OpenStack web site called the "Project Navigator." The Project Navigator is another way for users to browse data from users, the Technical Committee, the Operators meetup, Stackalytics, etc., to allow viewers to gauge breadth of adoption, maturity, age, etc. It's found at [http://www.openstack.org/software](http://www.openstack.org/software). Jonathan shifts from that discussion into a discussion of how OpenStack deployments are evolving---from just VMs, to VMs plus bare metal, and then to VMs plus bare metal plus containers. And, of course, that evolution will continue to include Platform as a Service (PaaS), container orchestration, etc.

At this point, Jonahtan brings Lachlan Evenson from Lithium to talk about how Lithium and their journey to use containers with OpenStack. Lachlan talks briefly about Lithium, and how they got started with Docker containers and OpenStack. He also provides a live demo of how Lithium is using BitBucket, post-commit hooks, OpenStack, AWS, and containers to do a live upgrade of a game ("Croc Hunter").

Jonathan takes the stage again to introduce another user, this one who is using a different set of technologies. At this point, Takuya Ito from Yahoo Japan takes the stage. Takuya starts with the scale of Yahoo Japan, which hosts 64.9 billion pageviews a month (31.9 billion views from smartphones alone). 270 million apps downloaded from Yahoo Japan over the last year, and currently needs to support over 100 different services. They are running approximately 50,000 instances, with over 20 clusters running and using about 20 PB (petabytes) of data. That scale has doubled in the last year (it was about half this size last year). This leads Takuya into a discussion of a major traffic spike Yahoo Japan; this spike was related to applications that Yahoo Japan uses to provide information about natural disasters, and last year there was an earthquake in Japan. This caused a major traffic spike to which Yahoo Japan had only seconds to respond. OpenStack helped them deal with this traffic spike, enabling Yahoo Japan to "abstract the data center" and leverage the same APIs regardless of the underlying hypervisor(s). Yahoo selected OpenStack for a number of reasons, including a common API, the fact it is open source, and because Yahoo Japan believes that co-creation with vendors (developing features/functionality in conjunction with vendors in an open source fashion) is important.

Jonathan takes the stage again to wrap up Takuya's session and re-iterate a few points: one platform to support multiple technologies, for example. Federated Identity, announced in conjunction with the Kilo release, is already supported by a number of "downstream" products and vendors. Jonathan closes his portion of the keynote with a "thank you" to contributors and supporters of OpenStack.

Next up is the Superuser award, which is granted to NTT Group for their outstanding use of OpenStack to transform their organization while still significantly contributing to the OpenStack Community.

Following the Superuser Award, Jonathan shows a video by NEC and introduces Tsugikazu Shibata, an OpenStack Foundation Board member and from NEC. He spends a few minutes talking about OpenStack and the OpenStack community. Tsugikazu also spends a few minutes talking about NEC's capabilities as both integrator and user in OpenStack environments/deployments.

Once NEC wraps up, Jonathan takes the stage again to introduce Erica Brescia, COO of Bitnami, takes the stage. The topic of Erica's discussion centers around banishing the "shadow cloud," which is defined as any cloud other than the one you're building or that you want your users to consume. She spends a moment talking about Bitnami and Bitnami's services and user base, and indicates that she's really excited to see the momentum that OpenStack is seeing in the cloud provider space. Erica takes a few minutes to talk about the key features that a cloud solution needs to have: speed (as in agility), ease of use, consistency, automation, curation, and "development to production" (needs to support the entire software lifecycle). In summary, Erica states that you need to focus on building a complete solution. Distros are a good start, she says, but you need to work with technology partners as well. Erica also feels that Murano and Heat are a good start, but they need to be populated. Finally, she mentions that solutions out there already exist---don't sit around and wait for OpenStack to solve these problems. Make your cloud easier, more convenient--and that will banish the shadow cloud.

After a brief video, Imad Sousou from Intel takes the stage. Imad takes a few minutes to talk about Intel's vision of deploying tens of thousands of new clouds to enable "cloud for all." Part of that effort is the OpenStack Innovation Center, created in conjunction with Rackspace. The OpenStack Innovation Center comprises both an upstream engineering team that will work closely with the working groups as well as two data centers that will be open to all users. Imad announces today that one of the two data centers is already open. Another part of Intel's efforts is their investment in Mirantis. Imad wraps up with a demo of some of Intel's efforts to improve OpenStack; in particular, he showed an optimization for VM startup times.

At this point, the keynote transitions to some native Japanese speakers, and I have to leave the keynote to get ready for some other sessions.