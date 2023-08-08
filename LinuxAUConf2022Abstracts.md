# LINUX AU Conference 2022 Talk Abstracts

## Talk: Dealing with Conflict

"There is one problem every community will face at some point: conflict.
Ugh.
People are people...personalities are personalities...but how do you ensure early detection of potential conflict, engage with those involved effectively, and resolve any conflict quickly with a high degree of trust?
Jono Bacon, a leader in community management and author of 'People Powered:
How communities can supercharge your business, brand, and teams' will show you how with a pragmatic framework for every step of the conflict process.
This will give you a clear set of tools (and an insurance policy) to deal with conflict as and when it may occur.
You should sleep well at night… you have earned it.
However, he will also go much deeper and dig into other challenging moments...whether there is conflict or not...such as mismatched expectations, uncertainty, burnout, uncertainty, company/community relations, and much more.
Buckle yourself into a practical session with best practice and experience you can apply today, all underlined with Bacon's loose, entertaining, and engaging delivery."

## Talk: Taming Complex Distributed Systems

"Taming the complex distributed systems we're responsible for requires changing not just the tools and technical approaches we use; it also requires changing who is involved in production, how they collaborate, and how we measure success.
In this talk, you'll learn about several practices core to production excellence: giving everyone a stake in production, collaborating to ensure observability, measuring with Service Level Objectives, and prioritizing improvements using risk analysis."

## Talk: Growth of the UNIX operating system

"In barely 50 years, the Unix operating system has gone from a tiny two-person experiment in a New Jersey attic to a multi-billion dollar industry whose products and services are an integral part of the world's computing infrastructure.
Along the way, there have been many changes, but a surprisingly large amount is much the same as when it started.
How did this come about?
What are the good ideas in Unix that have been preserved and even spread?
What are the good ideas that have fallen by the wayside?
What are the not so good ideas that have prospered?
And what might the future hold?
As someone who was present at the creation (though assuredly not responsible for it), I'll present some humble but correct opinions on these and related topics."

## Talk: Buffer Overflows in the Linux Kernel

"Like all C/C++ programs, the Linux Kernel regularly suffers from buffer overflow flaws.
While stack overflows have been largely addressed, heap overflows remain common.
Especially frustrating is that the compiler usually has enough context to have been able to stop the overflow but C APIs are so terrible that it doesn't happen.
We'll take a quick look back through at least the last 3 years of heap buffer overflow CVEs in the kernel.
This will lead to the discovery that all 11 memcpy overflows from this timespan (which includes the heap buffer overflow flaw used by the BleedingTooth exploit), could have been detected and mitigated by the compiler.
However, limitations in C language usage, APIs, kernel coding conventions, and compiler bugs made this a difficult problem to tackle.
We will explore the path to solutions being developed in the Linux kernel for dealing with array index overflows, string manipulation overflows, and especially memcpy overflows.
We will cover the history of C flexible arrays, the unexpected places where the `-Warray-bounds` and `-fsanitize=bounds` compiler options don't work, the limits of `__builtin_object_size` (the work-horse of FORTIFY_SOURCE), and how memcpy is being effectively replaced to stop overflows from ever happening again."

## Talk: Stereoscopic Imagery and Projection

"Stereoscopic imagery (photography and videography) is a fascinating way to create 3-dimensional images of landscapes, unmoving and moving objects, and of course, people.
In this talk, I cover the basics of stereoscopic imagery and projection, discover how stereoscopic vision works, and how we can trick our brains into perceiving depth from two flat images.
I start with the principles of three-dimensional vision in humans: how our eyes use the combination of accommodation and vergence to signal two slightly different images of our surroundings to our brain, and how our brain then processes these images to give us the perception of depth.
Then, I discuss the techniques available to play tricks on our brains in which two slightly (but cleverly) distinct two-dimensional images are presented to our eyes in such a way that our mind conjures up depth where there objectively is none.
These techniques come in various forms, from very high tech (such as virtual reality goggles) to very low tech (like mechanical stereoscopic viewers), but some can deal without any projection technology at all: this is called free-viewing, and for most people it is a remarkably simple and low-cost way to enjoy stunning three-dimensional imagery.
I cover the parallel-view and cross view free viewing techniques.
I then dive into the simple but highly effective steps of making stereoscopic images, using run-of-the-mill cameras (even cell phones), and some straightforward image processing in the GIMP.
Finally, I talk about some neat little tricks to make stereoscopic videos, with minimal cost and investment.
We'll look at how we can make 3D video with just a GoPro, or a simple drone camera — again using a free software tool, namely the Shotcut video editor, for processing."

## Talk: Cementing Your Place in Developer Communities

"Our world is divided by professional, industry and disciplinary silos.
At the most basic level, we too often subconsciously assume that the person who is good at maths and science will be a poor communicator, the person who has done an Arts degree will struggle with science and maths.
Our world is enriched when we incorporate the ideas and skills from different professional communities.
We will all benefit the more that STEM becomes STEAM by welcoming people with Arts backgrounds into our technical and business teams.
Drawing on her professional journey which started in chartered accounting, then public relations, professional historical research and is now morphing into technical documentation, Yvonne will demonstrate how professionals outside the STEM disciplines are experimenting with technology and developing skills that can assist IT teams.
While professional communities should be looking outward and welcoming the ideas and skills of people in other professional communities, it is also important to make the effort to enter other professional worlds.
By speaking at this conference Yvonne is making that effort and is grateful to the Linux community for this opportunity.
Professional communities also span geographic boundaries.
In her talk Yvonne will discuss her experience learning from the global digital humanities field through online and face-to-face opportunities.
Online interactions have not been disrupted by the pandemic, but face-to-face opportunities have been severely curtailed.
Yvonne will discuss the implications of this for people who are seeking to cement their place in a community.
It is not enough to say that we welcome others, we also need to demonstrate that we are a welcoming community by every person exhibiting the kind of personal qualities that make people new to the community feel welcome.
It is also important that the newcomers in a professional community show a willingness to learn and listen.
Drawing on her personal experience, Yvonne will give both good and bad examples.
During this presentation Yvonne will talk about her work with digitised material provided by Australia’s GLAM sector, the Trove portal and Trove API provided by the National Library of Australia, demonstrating how these important public resources have contributed greatly to her professional development."

## Talk: Introduction to retro alpha support in Video CODECS

"Surveys of children from age 6 to 17 years old are showing a majority want to become either a professional vlogger, or YouTuber.
These new generations, beginning with millennials, are consuming video content like never before.
To make video editing and production easier, transitions with transparency capability have become very common.
These transitions have their own marketplaces.
They are mostly encoded using the royalty-free CODECs VP8 and VP9, and are stored into a WebM (Matroska for Web) container.
Unfortunately, these CODEC implementations do not support the alpha plane that provides transparency.
In this talk, Nicolas will introduce the audience to retro alpha support, a workaround specification designed by the Google WebM team to enable VP8 & VP9 to support transparency, and will dive into the architecture he has implemented in GStreamer to support this type of video, both with software decoders and hardware-accelerated V4L2 decoders."

## Talk: How Security will impact Open Source Communities and Vice-Versa

"When we look at any community two questions naturally arise.
The first is "who is in it?", and the second "do I want to be part of it?".
Sometimes the answers surprise us.
This is very likely to be the case when the community in question has anything to do with Open Source security.
The talk will examine how developments in computer security influenced seemingly unrelated disciplines such as build process.
How the decision processes of the networking community create a unique set of concerns for  security developers will be discussed.
How paranoia surrounding the development of cryptography code accelerated the globalization of Open Source development will be revealed.
All the while pointing out communities and relationships between them that can be uplifting or rocky on a day to day basis.
The presentation wraps up with predictions regarding directions the greater Open Source community with follow, how security will impact them and how they will impact security."

## Talk: Assessing and Working out Information Architectures for Technical Writers

"As technical writers, we already know that choosing the right words is important, and we also know that the style and layout of our pages matters.
The third leg of the stool is information architecture: getting the right content, in the right place, at the right time.
Great information architecture not only helps readers navigate our docs properly, but also influences whether they have a good or bad experience, helps them feel good about your company or product, and can even help them to find information they didn't know they were looking for.
Additionally, good information architecture can help you improve your SEO, improve dwell time on your site, and reduce bounce rates.
In this talk, Lana will discuss how to assess your current information architecture, work out what information architecture your docs require, and how to implement it for the best results.
Whether you are working with an aging docs suite, or starting fresh, if you can choose the right words, this talk will help you work out where to put them."

## Talk: Paperback Addressing Leaving digital assets to heirs.

"Leaving digital assets to your heirs is currently fairly risky.
You can put all of the information needed to access those digital assets in a will, but how much do you trust your lawyer to have good OPSEC? And what if you don't want to have to use a lawyer, or want to use several lawyers? Another common problem is wanting to have an encrypted backup system, but you're bad at remembering good passphrases.
Depending on your particular situation, these two scenarios can also overlap and you want to give your friends and family the ability to access backups or other private data in the case you are incapacitated or worse.
Paperback attempts to solve both of these problems through a fairly low-tech paper-based backup solution based on Shamir Secret Sharing (SSS).
While there are a few other threshold backup systems, paperback is the first one  I am aware of which is trying to make itself usable by a less technically-capable people (after all, the main user will be your heirs who are not necessarily technically capable) and not depend on any digital services except during the creation and recovery of backups.
It also supports some neat features (such as allowing new shards to be minted after the fact) which are straight-forward applications of SSS but to my knowledge are not found in many other SSS-based projects.
In this talk, we will go through the design and philosophy behind paperback, some interesting applications, the current state of the project and where you may be able to help.
Proposals for better names will also be accepted."

## Talk: ImageBuilder for traditional Linux Images and Builder for Container Images

"We’re seen a seismic shift in recent years from long lived compute environments to ephemeral short term workloads, be they cloud based virtual machines or containerised instances.
This changes not only how we provision and deploy workloads, but also our approaches for applying updates and security patches.
This session will look at two different approaches for creating our standard images.
- ImageBuilder for our traditional Linux Images  - Buildah for our container images.
ImageBuilder, based on the osbuild-composer project, allows you to create custom Linux system images in a variety of formats, and is compatible with a broad range of Cloud and Virtualization platforms.
Today it can also be used to define specialized images designed for deployment on edge devices.
Buildah <https://buildah.io> aims to be a drop-in replacement for the “docker build” process for container creation, whilst exposing a smaller attack surface and can support rootless builds.
It creates OCI compatible container images We’ll look at the strengths and weaknesses of these two tools and how they compare with alternatives, some steps for maintaining secure images, and looking into their roadmap."

## Talk: Citation Network Analysis

"Conceptually simple, but sometimes computationally intense - Citation Network Analysis (CNA) provides a robust method to examine the overall structure of a research field.
In citation network analysis, it is assumed that a cited document is related to the citing document as perceived by its author and each citation forms a link in a network which represents the collective view of the authors within the field.
Properties of this network can then be directly measured using various statistical techniques quantifying the relative number of connections between different papers or authors.
Traditionally a labour intensive process, CNA techniques are rapidly becoming more accessible through global citation databases and freely available software.
Existing software will always have its limits for researchers and so this talk will provide a crash course in how to perform a CNA from scratch using Python, including the main methodical considerations and metrics.
It will also provide an overview of currently available tools and challenges with proprietary databases."


## Talk: Current Status of the futex2 call

"The current futex syscall poses some limitations for modern workloads.
To solve these issues, long term research has been carried out on creating futex2, a new interface to overcome the issues faced by the previous iteration.
This research included talking with userspace developers and proposing some implementations.
Following the futex2 update presented at LCA last year, this talk will look at the current status of the futex2 syscall, the different approaches taken thus far, and some use cases."

## Talk: Orchestration Technologies Challenges

"Orchestration technologies make it very easy to deploy services and ensure they're up and running under specific circumstances, does that mean that those services are always going to be running as expected and processing as required?
Especially when it comes to internal tooling for teams, and with the ease of orchestration, it can be easy to forget or forego any standard operating requirements for products.
This can easily mean that these tools don't function, and without the right visibility we may never even know it.
This talk will take you on a journey through one such case and how it was discovered, with a little extra on the general way in which this situation can manifest itself.
Ideally, with plenty of tips and thoughts on how to prevent this situation from arising again!"

## Talk: Robot Operating System (ROS)

"ROS is the open-source robotics toolkit that has powered robots in academia for the last decade;Micro-ROS allows nearly seamless integration of ROS tools into micro-controller frameworks including Arduino.
In this talk, Brett will demonstrate some of the capabilities of Micro-ROS, linking state-of-the-art software to some of the cheapest hardware on the market"

## Talk: Torturing RCU as synchronization primitive using rcutorture

"Let's face it, using synchronization primitives such as RCU can be frustrating.
And it is only natural to wish to get back, somehow, at the source of such frustration.
In short, it is quite understandable to want to torture RCU.
(And other synchronization primitives as well, but you have to start somewhere!) Another benefit of torturing RCU is that doing so sometimes uncovers bugs in other parts of the kernel.
You see, RCU is not always willing to suffer alone.
This talk will give an overview of how to torture RCU using the rcutorture test suite.
It will also present a few of rcutorture's tricks that permit short tests on a smallish number of modest systems to nevertheless provide some assurance that RCU will run robustly on billions of systems across the inner solar system."

## Talk: A basic systemd service for security separation, per user resource constraints, and Noisy neighbours

"Noisy neighbours, security separation, per user resource constraints, 0 resources on idle, its all possible.
Its not a cloud service, or containers, its a basic systemd service file with a small number of MariaDB server code changes.
In this talk I'll line up some usage scenarios, show the configurations options that are all small variants of the default packaging of MariaDB.
If there's time,  I'll show the code, and show how easy it is to do for other service if interested.
Notes from talk: https://gist.github.com/grooverdan/ad68b0161aa2ba9860b769a5304e83ab"

## Talk: The missing functionality in 32-bit ARM processors

"Preventing software bugs from becoming security vulnerabilities has been an ongoing project for numerous kernel developers.
Things like array bounds checking, stack smash detection and limiting memory access in kernel mode aren't directly fixing bugs, they're making current and future bugs easier to catch while making them less damaging.
Many of these measures can be done in an architecture-independent fashion to benefit all Linux users.
Others require custom code for each family of processors.
Several of these critical mitigations have not yet been implemented for 32-bit ARM processors.
This presentation will describe the missing functionality,explain how those gaps enable potential security exploits, outline several possible ways that were evaluated for each implementation, and finally show the architecture chosen for merging upstream."

## Talk: Memory Management with MMTk (the Memory Management Toolkit) and integration with MRI (the main Ruby Interpreter)

"If you've learned a new programming language in the past 20 years, there's a good chance it features automatic memory management.
One of the most popular ways of managing memory is through a garbage collector (GC), which frees memory by regularly deallocating unreferenced data.
Optimising programming languages' GC algorithms and implementations can be key to improving the performance of large scale, low-latency and high-throughput systems.
However, state-of-the-art GC algorithms can be difficult to implement, which often results in new language designers trading performance for simplicity.
Additionally, garbage collectors are often tightly integrated into the language runtime, which makes it difficult for existing languages to optimise their GC or switch to new algorithms altogether.
In this talk, we introduce the Memory Management Toolkit (MMTk), an Open Source runtime-agnostic garbage collection framework being developed by researchers at ANU.
MMTk provides developers with a large library of high-performance GC algorithms (ranging from tried-and-tested to cutting-edge), exposed behind a unified bidirectional API.
The project aims to simplify GC implementation for both researchers and the developers of new & existing programming languages alike.
We discuss the lessons learned from integrating MMTk into MRI, the main interpreter for the Ruby programming language."

## Talk: Qiskit an SDK for working with Quantum Computers

"Qiskit [kiss-kit] is an open-source software development kit for working with quantum computers at the level of pulses, circuits and algorithms.
Quantum computers are machines that use the properties of quantum physics to store data and perform computations.
This may sound like science fiction, but small quantum computers are available now and publicly accessible over the cloud.
To help quantum-curious developers learn how to use these devices, the qiskit community team has developed an online interactive textbook, as well as hosted and supported numerous online local and global events.
In this presentation, I will introduce quantum computing using qiskit and describe the fantastic global community we have built around in."

## Talk: Godot an Open-Source Game Engine

"It’s fun to play video games.
It’s even more fun to make video games.
Did you know there’s a completely free, open source game engine, with features that make the commercial, proprietary game engines jealous?Maybe you did, maybe you didn't, but there’s never been a better time to learn the Godot game engine.
In this session, together, we will:
* learn what Godot is and how it works
* take a tour of Godot’s features and powerful scripting system
* quickly build a game, showcasing the Godot editor
* build the game for macOS, Windows, and Linux
Game development can, and should be, for everyone.
Godot makes the tools available, you just need to bring the time, tenacity, and ideas.
And you’ll need to learn some coding, but it’s fun because it makes things _move_.
Build that game that’s been itching at the back of you mind for years; code a game with your kids; build a little game that you’ll **never** show anyone, but you’ll know you made it.
Whatever your interest, you’ll get something out of this session.
Basic programming knowledge assumed, but nothing major."

## Talk: Open Practice Library

"The Open Practice Library is both a repository for team practice, an open source project, and a community.
Content is available under a creative commons license, and the site code is on github.
This Library brings together two different worlds; that of product and agile software development principles and that of open source, distributed collaborative software creation.
This session will briefly demonstrate HOW to contribute, and then invite attendees to file an issue, post a patch, share a practice, and join the community!"

## Talk: HootSuite and Locust for performance evaluation of configuration and component changes

"Learn how Hootsuite used load testing to evaluate the performance of Prometheus and Grafana based metrics platforms, developing a framework based on the open-source tool Locust that can be used to quickly evaluate the performance impact of configuration and component changes prior to deployment."

## Talk: The seL4 Microkernel a machine-checked proof of implementation correctness

"The seL4 microkernel is the world's first operating system (OS) kernel with a machine-checked proof of implementation correctness (originally completed in 2009 for 32-bit Arm processors).
This was followed by more wold-firsts: proofs of security enforcement, proof of correctness of the executable binary, sound worst-case execution-time analysis.
SeL4 had been developed and verified at NICTA, a public-sector research organisation, and open-sourced in 2014.
With NICTA being absorbed into CSIRO in 2015, the seL4 developers, known as the Trustworthy Systems (TS) team, became part of CSIRO, and research, development and community support continued there, mostly through funding from the US government (DARPA) and industry.
However, uptake remained limited outside the defence sector.
In April 2020 we created the seL4 Foundation (as a project of the Linux Foundation) as a way to encourage broader community engagement as well as removing dependency on a single organisation.
The importance of the latter aspect became obvious when in May 2021 CSIRO announced that it was abandoning the Trustworthy Systems group and its research agenda of developing truly secure computer systems.
This was a near-death experience for seL4: many of our highly-skilled staff and students had job offers within days.
The TS team would have disintegrated within weeks, leaving seL4 orphaned, had not UNSW stepped up and offered to fund the team to the end of the year, giving us much needed breathing space.
This was followed by an amazing rallying of the community.
While before we had trouble scaling Foundation membership beyond the half-dozen initial members, companies we never heard of (but who were already building seL4 into their products) joined, increasing the Foundation's membership revenue ten-fold over a period of about 2 months.
Many former staff increased their engagement (with backing from their employers), and community contributions increased massively.
At the same time the TS continued to hit new firsts, especially on verification and security proofs for seL4 on 64-bit RISC-V.
The technology and its ecosystem are very much alive and growing.
Which leaves a number of questions to explore, specifically:

1. Why did we not achieve more community engagement before the cataclysmic events of May 20, and

2. Why did things suddenly take off after?I can only attempt to provide (at best partial) answers, and will welcome feedback from other community leaders.

However it is clear that

1. Had to do with the steep learning curve of seL4, but also organisational barriers.
Specifically, seL4 development was not really open until we set up the Foundation, and even then it took a long time to move everything out from CSIRO, a process that was still on-going when the divorce was announced.
Yet it became clear that there was far more seL4 adaptation in industry than we were aware of.

2. Was clearly enabled by this existing activity: people realised that the whole of seL4 was under threat, and they had to contribute back if they wanted it to live on.
Which leaves us with the question of what could we have done differently to get them engaged earlier, and how can we engage even more of the adopters? There are clearly many more out there."

## Talk: OpenDev Collabolaratory

"OpenDev is a collaboratory for open source software development at scale.
Its focus is on code review, continuous integration, and project hosting provided exclusively through open source solutions like Git, Gerrit, Zuul, and Gitea.
It started life as the infrastructure behind the OpenStack project but has grown to support many other projects who value developing with truly open source infrastructure.
The production systems "dogfood" the tools they help develop to build, test and deploy into production.
The major driver is the Zuul CI system, which works with a combination of Gerrit, Ansible, containers and the compute resources donated to the project.
All infrastructure code is public and open source and any developer may propose changes that are CI tested, reviewed and approved by peers then committed and deployed to production automatically by ("gitops" would be the current umbrella term).
This talk will show how these components come together to run the services used by thousands of developers to develop key parts of the open source ecosystem."

## Talk: XOS a museum experience operating system

"Your museum of screen culture in Melbourne (ACMI) went through a multi-year renewal, introducing the Story of the Moving Image (SOMI) to the public in February 2021.
SOMI is an interactive free public experience exploring film, tv, video games and art culture with First Nations story telling at its heart.
To bring SOMI to life we built XOS, a museum experience operating system that links our collections management system to ~400 Raspberry Pis to display interactive museum labels, play our moving image content, and let you collect objects from the museum to take home and explore further.
XOS exposes a range of private APIs within the ACMI network to feed the hungry machines, most of which require API Keys to read and write.
When it came time to design and develop a public API, we wanted to prioritise:
* Keeping our private museum APIs private
* Making the public API secure
* Making the public API fast
* Making the public API easy to use
* Making the public API searchable
In this talk we’ll discuss the architecture and software we chose, why we chose it, and how it’s working out.
We’ll also talk through the content licensing discussions we had to have to make it happen, and the timelines to go from prototype to production, including costs and our business case.
We’ll finish up showing you a couple of experiments we built using the API, and what we’re hoping you (and we) might use it for in the future."

## Talk: Linux Improvements made for Remote File Access and (QUIC)

"Over the past year many improvements have been made in Linux for accessing files remotely.
This has been a great year for cifs.ko with the addition of new SMB3.1.1 features and optimizations.
It continues to be the most active network/cluster file system on Linux.
And now with the addition of a kernel server to Linux (ksmbd), there are multiple Linux server options (Samba and ksmbd).
Improvements to performance with handle leases (deferred close), multichannel, signing improvements, huge gains in read ahead performance, and directory and metadata caching improvements have been made.
And security has improved with support for the strongest encryption, and more recently the exciting work on QUIC.
Many other security improvements have been added and will be described.
This presentation will go through the features added over the past year to the Linux client, and demonstrate how they help common scenarios, from accessing the cloud faster (like Azure) to accessing Samba, Windows, Macs and the new Linux kernel server (ksmbd)."

## Talk: Linux as a proper Router

"Did you know Linux has the capability to be a proper router?
Curious about VLANs, OSPF,  BGP and other networking acronym's you've not looked into?
Here's a few pointers on what that all means, how to build a proper router with Linux, why use a 'real' one and some tools and techniques for learning about these things on the way."

## Talk: Web Assembly for running other programming languages in the Browser (Python)

"Turns out the browser can run more than just JavaScript! Using WebAssembly we can compile and run other languages too.
It gets even more fun when you're trying to mix the asynchronous world of a JavaScript UI with synchronous blocking operations like reading from stdin in Python.
Join me to learn what WebAssembly can do and how to use browser features like postMessage, Web Workers, and `SharedArrayBuffer` to smoothly interact with Python in a terminal in the browser."

## Talk: systemd in a container - what! Why!?

We've got our Reasons, and I'll even explain them.
But more interesting than the "why" is the "how", and that's what this talk is about.
Come and learn about upcoming and already-delivered Kernel and Kubernetes security features that enable better container isolation and secure deployment of systemd-based workloads.
This is a talk about what happened when a handful of complete container newbies tried to port their massive, complex, "legacy" application to Kubernetes.
In a single "monolithic"container.
Based on systemd.
The container runtime shunned our application.
Cloud engineers howled in dismay at our architecture decisions.
Ultimately, like the hackers we are, we ignored their admonitions and doubled down.
If the container runtime won't run our application, well, we'll just modify the container runtime!And so we did.
Our journey took us into the darkest corners of container runtimes, Kubernetes and systemd.
And we have emerged to tell you the tale.
There will be demos.
Attendees should expect to learn more about the security technologies that underpin Linux containers, including namespaces and cgroups, as well as the behaviour of systemd in containers."

## Talk: Accessing Information From the Government Agencies

"If you want to get information out of a government agency, the Freedom of Information Act is here to help you!Governments can be secretive, frustrating beasts.
Knowledge is power, and they don't like to share.
Hear from a tech nerd how they learned to use the Freedom of Information Act to get information out of governments that they often don't want to share.
You too can quickly and easily file an FOI request using online tools and get information you crave to learn about CensusFail, robodebt, and more!
Learn the tips and tricks learned from bitter experience so you can avoid the mistakes someone else already made.
Navigate the bureaucratic maze with this handy ball of string so you don't get lost, or at least not for long!"

## Talk: The Security Enhanced Linux (SE Linux)

"NSA Security Enhanced Linux (SE Linux) first became known to the Linux community at Ottawa Linux Symposium 2001.
I planned to spend a few weeks working on it but ended up spending 20 years, and the work continues.
I will describe how my skills as a Linux programmer developed while SE Linux improved, how things could have been done better in retrospect, the ways that my initial plans didn't match reality, and how a few weeks changed to 20 years.
This talk is aimed at an audience of beginner to intermediate level.
I hope that someone at an early stage of their Linux career will watch this and feel inspired to get in at the start of a major project and develop their skills as the project progresses.
But I think that experts will find it interesting."

## Talk: How Open Source and Open Hardware have impacted the Retro Computing Community.
"From a project to replace a scarce CPU to the Firmware that has launched a dozen 8 Bit home brew computers while resurrecting an Operating System from the 70's
Explore how the old and new combine to give a truly exciting and nostalgic computing experience."

## Talk: Number Conversion from Human to Machine Form

"Ordinarily, we think of things like converting numbers between the way we see them and the way computers use them as a solved problem, and for many purposes, they are.
As data volumes grow and people's patience doesn't, we sometimes find that there is still room for improvement, and improve them even fairly novice low-level coders can.
When our time together is done, you will have learned about some recent advances in this, a few of which I've brought to PostgreSQL, some of the things to consider when attempting such improvements, and looked at the world from a new perspective."

## Talk: AGTech Startup Platform

"The glow of agtech promises a future where farmers farm better, growing more food at a lower cost while they improve the quality of their soil.
The reality in Australia is that we have a lot of good will, but agtech remains underfunded, and many applications and platforms are struggling to simultaneously survive and build scale, integration, and interoperability.
In 2019 Lyndsey took on the CTO role of Australian agtech startup Platform.
The function of the application had been proven, but the work of attracting funding, re engineering for scale, and releasing the application in stores was still ahead.
While leading a small team through this journey, we also took the time to spearhead the development of open data standards for the viticulture industry through the “Collabriculture” project.
This project brought together grape growers, industry stakeholders, startups, and developer and mapping experts for a series of workshops leading to the creation of the viticulture data standards.
These standards, published openly on github help developers with the naming conventions and considerations of the data model that makes up a vineyard when they go to build, and of course this should make future data sharing easier.
Open source mapping standards have been used internally and in the community work we have led.
Using Mapbox and Open Street Maps means that data elements such as vine rows, block boundaries, and satellite imagery have been able to be more easily shared.
The use of open source software and approaches makes it easier to talk about interoperability and to nudge others into thinking about how the data they input can be shared, exported, and used in other applications.
Data standards in the agtech industry are also important and evolving.
Farms as a business have a right and expectation that they will have control over the data from their business, and at the same time there is data that if shared helps regions and growing practices.
So we will look at this a bit as well.
And last but not least we will talk about farmers and growers and those working on farms to give an insight into considerations to help developers build tools that will make a difference."

## Talk: Velociraptor, VQL an open-source DFIR framework

"Velociraptor is the new open source DFIR framework that everyone is talking about! Have you ever needed to respond to an incident in a large enterprise network? Have you wondered how many of your 10,000 endpoints are compromised? You know you should be hunting for common forensic artifacts but how do you do it in a scalable way, in a reasonable time? Well… now you can!This talk will introduce Velociraptor and cover specifically the recent capabilities investigating and monitoring the security of Linux hosts.
Velociraptor's superpower is its flexible and powerful query language called VQL.
Using VQL we can implement novel detection, hunt for compromise and automate all our response needs.
We cover some common use cases such as hunting for ssh keys across large networks or automatic escalation when suspicious events are discovered.
We also cover real time monitoring of the endpoint (for example webshell detection via process parent/child analysis) and how VQL can be used to build sophisticated alerting around process execution chains, network connections and even bash instrumentation of the command line, all done at scale with the click of a few buttons."

## Talk: eBPF an in-kernel virtual machine

"eBPF is the in-kernel virtual machine which lets us use the kernel and leverage a very safe & efficient programming model where we can extract telemetry data from arbitrary points in the kernel as well as supplement certain throughput critical parts in a programmable way.

This model is much safer than writing a custom kernel-module which has high maintenance & can cause kernel-panics/crashes, eBPF does not suffer from these issues as, it has an in-kernel verifier which allows a very restricted set of functionalities.
Although, eBPF was earlier targeted at only the network data path, it now has evolved into a framework which can be used in almost everywhere in the kernel.
Novel usages include writing TCP congestion control algorithms entirely in user-space and load them to the kernel without having to go through a full kernel release cycle.
Apart from the network stack, there are various ad-hoc telemetry data that we can extract from the kernel which can aid in tackling performance problems without modifying the kernel.
The advantage of eBPF is its dynamic nature, where we only have the overhead whenever we are running a specific ad-hoc eBPF telemetry program.
This talk is an introduction to the eBPF subsystem from a perspective of a non-kernel programmer.
The talk will explore ideas similar to eBPF like the integration of Lua with nginx, web-asm etc.
The talk will touch on the end-to-end life cycle of an eBPF program, how we write a program in the user-space, then compile it to the eBPF VM bytecode and how we load the program in the kernel.
Once the program is loaded, it still cannot run, unless we attach it to any hook/event in the kernel.
These events could be a tracepoint/kprobe or a perf-event.
This talk also will touch upon the various types of eBPF programs that are possible e.g xdp, monitoring.
For completion an introduction to eBPF maps (storage) which allow us to make state-full decisions for the otherwise stateless eBPF programs."

## Talk: DNS Maturity Assessments

"In every organisation DNS is a critical system, but it rarely gets the attention that it deserves.
We rely on DNS for the smooth operation of our businesses; if your customers can’t reach your website or email you, then your business is effectively cut-off.
Organisations will keep disaster recovery plans and business continuity procedures for their corporate websites, mail servers and internal systems; but how many of these plans and procedures include DNS?Over the past few years, attacks against DNS have been on the rise.
These attacks may be direct attacks against DNS server software; but they can also come from compromised credentials or DNS zone misconfiguration such as dangling DNS entries.
In this session, I am going to walk through performing a DNS maturity assessment and how you can improve the management of DNS with tools like DNSControl."

## Talk: An entertaining look into the modern world of open typography.

"Why fonts are the clothes words wear ( credit: Beatrice Warde)

How do you make a font with free software?How do you QA a font with CI CD
How do you get listed on Google Webfonts and other CDN's / Registries
Developer specific typography Variable fonts and more.
By the end you'll have a great appreciation for beauty in the written universe be within your terminal to your daily spaces."

## Talk: Capabilities of the hacked Knitting Network Printer

"In her last talk in 2018, Sarah introduced LCA delegates to her hacked Knitting Network Printer with her novel 3 colour knitting method.
Since then Sarah has pushed the capabilities of her creation to the limit with a giant starmap of the night sky.
In this talk Sarah will discuss:
- Going viral
- Lighting up every visible star with bespoke electronics
- Building a unique interactive experience
- Logistics of working with physically large projects
- Working with a conservation team to preserve the work for 100 years
- The coming exhibition in Melbourne"

## Talk: Making GCC and Clang generated code more efficient

"The C and C++ programming languages are well known for the performance of the generated code.
However, the code is generated by a particular compiler and runs in a particular operating system and on a particular hardware.
C and C++ are very fast, but there are compiler extensions, which which help to produce even faster code.
Also the hardware provides extensions, which are hard to employ from C and C++ and we need Assembly to get the fastest code.
In this talk we'll explore which code GCC and Clang compilers generate for several C and C++ constructions and how to make the code more efficient.
We'll also dig into the x86-64-specific code optimizations.
This talk covers following topics with plenty of micro benchmarks:
* How x86-64 executes the code and works with memory
* Several GCC and Clang compiler optimizations and extensions
* When x86-64 assembly is faster and easier to use than C
* Gotchas with programming for multi-core systems
* Spectre mitigations in the modern compilers
* Profiler guided optimizations and when it doesn't help"

## Talk: Making life easier for SRE's and Ops

"Making life easier for SRE's and Ops is important, so is visualising component interactions inside a cluster to see where improvements can be made to help drive development focus, and let's face it seeing graphs and visual traces is fun :)
Swift can log very verbosely but on production, especially with very large clusters you don't want to turn up your logging too much.
Especially if a customer is having an issue, sometimes all you can do it come up with a hypothesis from the logs and then test in staging or dev environments.
But what if you could start tagging a request through the cluster.
Better, what if that trace was integrated into the software itself so we can breakdown not only the inter node requests but delve into whats happening on the node itself?Well that's exactly what I've been playing with.
What started out as middleware bench-marking, and sharing initial results with our SREs has snowballed into request tracing... And to be honest, it's pretty fun.
Now we can see:
- where a request spend it's time.
- Start getting a visual understanding of what different requests look like in the cluster
- Use the information to better tune the configuration and topology of the cluster
- Find areas where we need to put more developer time to optimise different code paths."

## Talk: Encrypting Data Stored in Relational Databases

"There is a growing trend of encrypting data stored in relational databases such as PostgreSQL and MariaDB.
The goal is to improve the security of the data we store.
But how effective is encryption at meeting that goal?
Hint: not as effective as you might think! So what are the limitations of an encrypted database and what should you be aware of to mitigate potential attacks? (And while maintaining performance, scalability and usability!)
In this talk, Dan Draper summarises several recent papers from Cornell, Stanford and the University of Illinois on practical attacks against encrypted databases.
He also provides some guidance and examples of how to mitigate these risks, how they can be factored into a threat-model and provides a look some alternative approaches that go some way towards addressing the problems."

## Talk: Persistent Memory issues and solutions

"Persistent Memory (PMEM) is a byte-addressable memory device which has not only nearly the same speed and latency of DRAM but also the non-volatility and large capacity of storage.
As a result, many software (e.g database, log-based filesystem, distributed filesystem) expects PMEM as new age device.
When they want to access the data on the remote PMEM the speed of data transfer based on TCP/IP is obviously slower than that of accessing PMEM.
This is a motivation to access the data on the remote PMEM access by using Remote Direct Memory Access (RDMA).
However there are some issues about supporting remote PMEM access based on traditional RDMA, for example traditional RDMA WRITE operation has no guarantee to make persistency.
In this session, I would like to introduce these issues and two solutions (RPMA and RDMA extension).
Note: If CFP of OSSJ2021 is passed, this will be same talk with it."

## Talk: The Electromagnetic Spectrum using RX/TX SDR (LimeSDR)

"If I would have to pick a super power, it would definitely be being able to see the whole of the electromagnetic (EM) spectrum rather than the tiny sliver our evolution under a yellow sun ☀️ has limited us to.
This talk covers seeing in different parts of the EM spectrum using an RX/TX SDR (LimeSDR).
More specifically in microwave frequency ranges for observing moisture in the air and precipitation.
These are the ISM bands around 2.5GHz, 5GHz and 10GHz, no one wants to license them due to weak propagation characteristics, however they present excellent experimental frequencies for radar design.
We will discuss the briefly the history of radar meteorology, the hardware needed to make a modern solid-state X-band phased array radar.
The talk will extend to more advanced topics such as polarisation in radars and radar cross section (RCS) based on precipitation density and even drop shape.
We will also cover retrieval of precipitation motion and wind information using Doppler.
Finally we will discuss the community and social benefits radar brings with increased observability of the weather and use cases with a deployment in Africa."

## Talk: The CPU Namespace

"The CPU namespace aims to extend the current pool of namespaces in the kernel to isolate the system topology view from applications.
The CPU namespace virtualises the CPU information by maintaining an internal translation from the namespace CPU to the logical CPU in the kernel.
The CPU namespace will also enable the existing interfaces interfaces like sys/proc, cgroupfs and sched_set(/get) affinity syscalls to be context aware and divulge information of the topology based on the CPU namespace context that requests information from it.
The aim of this talk is to propose a mechanism to isolate CPU topology information from applications that are running in a containerized environment.
The potential utilities of having the proposed CPU isolation are as follows:1. An interface for coherent information:

- Today, most applications that run on containers enforce their CPU limits requirements with the help of the cgroup interface. Cgroups is a control interface rather than an information interface; hence applications do not have a coherent view of the systems and the restrictions they incur.

- The problem extends beyond to coherency of information.

Cloud runtime environments can requests for CPU runtime in millicores, which translate to using CFS period and quota to limit CPU runtime in cgroups.
However, generally, applications operate in terms of threads with little to no cognizance of the millicore limit or its connotation.
This can lead to unexpected running behaviors as well as have high impact on performance.
Hence, having a coherent interface for divulge information based on constraints set by different subsystems is important.
2. Potential security and fair use implications on multi-tenant systems:

- A case where an actor can be in cognizance of the CPU node topology can schedule workloads and select CPUs such that the bus is flooded causing a Denial Of Service attack.

- A case wherein identifying the CPU system topology can help identify cores that are close to buses and peripherals such as GPUs to get an undue latency advantage from the rest of the workloads.

Currently, all of these problems mentioned above can be mitigated with the use of light weight VMs - Kata Containers.
However with the use of a CPU namespace, the isolation advantages that are provided by a Kata Container can be achieved without the heaviness of a virtual machine.
A survey RFD had been posted here highlighting the problem, its impact and the current solutions that exist in the userspace as well as kernel: https://lore.kernel.org/lkml/fe947175-62f5-c3fa-158c-7be2dd886c0e@linux.ibm.com/T/"

## Talk: Artificial Reality Roadblocks

"Artificial Reality is great, but there are two big roadblocks: Cost and Creep factor.
Can we do useful wearable tech involving cameras and head-mounted displays without overdosing on either of those?This talk looks at a platform I've been building for my own needs - to view documentation and instrument readings while my hands are busy, and to read miniscule part numbers and other fine detail.
The platform consists of a  single board computer from somewhere in the pi milieu (there are a number of suitable products), a budget head-mounted display from vufine, a gravity mouse (with bonus keyboard) and enough batteries, IO and sensors to function as a combination microscope and multimeter display.
If you don't have five thousand bucks for a top line immersive AR system, let's get as far as we can for \$500."

## Talk: KernelCI Ecosystem

"KernelCI is a project focused on testing the upstream Linux Kernel on different hardware with an open testing philosophy and high modularity.
Thanks to this approach, KernelCI is expanding its testing ecosystem by allowing new tests and trees to be easily integrated into KernelCI.
We will talk about two main systems of growing the current KernelCI ecosystem:
- Adding to the KernelCI code
- Using KCIDB (KernelCI’s common reporting system) From a CIP project (Civil Infrastructure Platform) testing member and KernelCI CIP instance mentor, you will get an overview of the effort of the CIP project to merge its current testing system into KernelCI, and how it is possible to collaborate and send test results to KernelCI using KernelCI’s common reporting system KCIDB.
This talk will give an overview of what we learned from making GKernelCI (Gentoo Kernel automatic testing system) and CIP testing systems collaborate with KernelCI.
What we did, what is still missing and what is planned in the future.
We hope that this experience will help future collaboration with the KernelCI project."

## Talk: Public Infrastructure and Accessibility Issues in Code

"Our day-to-day lives are shaped by public infrastructure.
From roads and footpaths to power lines and fibre-optic cables, we rely on basic foundations to access both utilities and communal spaces.
Similarly, much of the Internet is built on top of open-source frameworks that make it easy to develop complex websites and applications.
Not all of our public infrastructure is easy for people with disabilities to access.
However, the Internet is far less accessible than physical public spaces.
Various sources have come up with different numbers for 'the percentage of public websites that disabled people can't use'; most are over 50 percent, and depending on the specific disability referenced, some are as high as 98 percent.
What are the barriers that have resulted in that figure being so high?  There are quite a few of them, but one important reason is that so much of the modern internet is built on frameworks, plugins, and extensions.
In the same way that complex signage in cities stops people with cognitive disabilities from travelling independently, and crumbling sidewalks limit wheelchair users to their homes, inaccessible frameworks create a lot of difficulty for folks with disabilities.
Anyone creating a website using them has to do a lot of remediation work if they want the final product to be accessible, and due to time and budget constraints, that work often doesn't happen.
Of course, provided that they're open-source, anyone can contribute to the common frameworks that power our software.
This gives us an opportunity to make improvements that others can leverage, rather than just remediation issues in your own work.
However, this requires more than just web development skills.
If you want to contribute to accessibility upstream, there are a few things that you'll need to know.
This talk will cover the differences between remediating accessibility issues in your own code, and doing so in open-source projects.
We'll learn how to identify the types of issue that we should attempt to fix upstream, and answer some common questions from open-source maintainers about why accessibility improvements are important.
Finally, we'll go over ways that project owners can test changes to ensure that they're usable by people with disabilities, and how you can use them yourself before you start submitting pull requests."

## Talk: Computerized Translation Software for world's languages

"We urgently need computerised translation software for the rest of the world's languages.
We will probably lose around 90% of the world's languages in the next 80 years.
If you want to build a translator that can translate all the world's languages, you can't use Google translate's approach of training on millions of documents because most of the world's languages don't even have a million words written down.
You have to be much more parsimonious with your data.
I've been writing software that populates the Leaftop database which has the goal of being the largest lexiconary (it currently has automatically extracted an average of 300 words from each of 1400 languages), and I am also building a universal grammar extractor which can currently inflect a plural from a singular for 11% of the world's nouns.
It learned all the Latin noun declensions on its own.
This is a talk for language geeks and machine learning nerds.
I'll talk about the weirdest distance metric you'll ever see (and why it is so easy to code), and I'll talk about Hiligaynon and Swahili, why Chadian Arabic was so helpful and the trouble with Khmer.
You'll see more unicode character sets in one presentation than you'll see in an internationalisation conference."

## Talk: Design Patterns of Gstreamer and ROS

"Complex systems are easier to manage when they're made of simpler modules.
Gstreamer and ROS are both message-oriented software frameworks for high-performance (soft)real-time systems.
GStreamer lets you plug modules together to make multi-media processing pipelines, ROS lets you plug modules together to build robots.
In this talk, I'll contrast the design patterns of the two frameworks, show how the two frameworks can be combined to create a more flexible free software ecosystem, and share my surprise at how quickly new infrastructure code gets adopted."

## Talk: Linux in Harsh Environments Space

"Linux is everywhere, even in space... But space is a harsh environment with many challenges.
Radiation disrupting electronics, wild temperature swings damaging circuit boards, no communications for hours, days, or even weeks at a time.
How do you build computers and software systems for such demanding conditions?
Let's take a look at who is already using Linux in space, what they had to do in order to build their systems on Linux, and how you can get involved in helping open source software destined for space."

## Talk: The GNU Public License Version 3

"In 2007, the FSF published version 3 of the GNU General Public License.
One of its goal is to prevent Tivoization - the practice of preventing software modifications in a system by means of hardware restrictions, such as secure boot.
A lot of people (myself included) does not like this restriction, as it prevents them modifying the behavior of something they already owned.
So how did I ended up implementing one of these?
In this talk, I will start by introducing mechanisms involved in secure boot, which usually differ across vendors but are based on the same principles.
We will look at some reasons why secure boot might be desirable for the manufacturer, customer, and even the general public; followed by a peek at things that does not have it and how it works out for them.
I will also share my experiences in implementing one, including some blockers and factors that were considered.
We will finish with some guides in case you too, would like to undertake the journey to become a tyrant."

## Talk: Cryptography and third party libraries

"Cryptography forms the backbone of how we securely use information online, but most developers don’t have more than a surface level understanding of cryptography.
Shannon's maxim states that “one ought to design systems under the assumption that the enemy will immediately gain full familiarity with them”.
Open source makes this feasible for cryptography, with open source cryptographic libraries handling a huge proportion of information on the internet in flight and at rest.
Developers place a lot of trust in the authors of these libraries to get the cryptography engineering right.
But when basic usability issues result in developers using the libraries incorrectly, that trust and painstaking cryptography engineering can be for naught.
Worse still, developers often believe they have used the libraries to build something that is secure.
But that belief is often mistaken — their use of these libraries is actually insecure.
In this talk, attendees will learn:
1. What research says about how the usability of cryptographic libraries impacts the ability of users to deliver code that handles data securely
2. What common usability traps open source cryptography projects fall into
3. How authors, maintainers, and communities around open source cryptographic library can make their users successful"

## Talk: Gprofng a next generation profiling tool for Linux

"In this talk we present an overview of gprofng, a next generation profiling tool for Linux.
This profiler has its roots in the Performance Analyzer from the Oracle Developer Studio product.
Gprofng is a standalone tool however and specifically targets Linux.
It includes several tools to collect and view the performance data.
Various processors from Intel, AMD, and Arm are supported.
The focus is on applications written in C, C++, Java, and Scala.
For C/C++ we assume gcc has been used to build the code.
In the case of Java and Scala, OpenJDK and compatible implementations are supported.
Among other things, another difference with the widely known gprof tool is that gprofng offers full support for shared libraries and multithreading using Posix Threads, OpenMP, or Java Threads.
Unlike gprof, gprofng can also be used in case the source code of the target executable is not available.
Gprofng also works with unmodified executables.
There is no need to recompile, or instrument the code.
By profiling the production executable it is ensured that the profile reflects the actual run time behaviour and conditions of a production run.
After the data has been collected, the performance information can be viewed at the function, source, and disassembly level.
Individual thread views are supported as well.
Through command line options, the user specifies the information to be displayed.
In addition to this, a simple, but yet powerful scripting feature can be used to produce a variety of performance reports in an automated way.
This may also be combined with filters to zoom in on specific aspects of the profile.
For example, it is very easy to zoom in on one or more threads, but also to compare the behaviour across threads.
One of the very powerful features of gprofng is the ability to compare two or more profiles.
This allows for an easy way to spot regressions, or find scalability bottlenecks for example.
In the talk, we start with a description of the architecture of the gprofng tools suite.
This is followed by an overview of the various tools that are available, plus the main features.
A comparison with gprof will be made, but the bulk of the talk consists of examples to show the functionality and features.
We conclude with the plans for future developments.
This includes a GUI to graphically navigate through the data."

## Talk: Linux Kernel Testing

"Testing the Linux Kernel has never been more important, and there are a number of tools within the kernel to help, each with their own use-cases and quirks.
Join us as we look at when to use the KUnit kernel unit-testing framework and when to use other tools like kselftest, and what the differences between these frameworks are.
We'll also cover efforts to standardise test result formatting between different kernel frameworks, specifically the different versions of the TAP and KTAP standards.
These allow (or will allow) tooling between them to be shared.
Finally, we'll look at how to use KUnit to test more complicated or hardware-specific kernel code, focusing on new functionality such as QEMU support in kunit_tool and SKIP test support, as well as how to write fake structures and devices."

## Talk: Kubevirt modernization for VM workloads

"Most organizations have a large investment in VMs, the applications they run, and the infrastructure and processes that manage and maintain them.
An all-or-nothing approach to modernizing applications on containers is often not feasible and too slow.
Kubevirt allows for an immediate, calculated path to modernization for VM workloads.
You can proactively move applications now and manage them side-by-side with the latest innovations in Kubernetes and other open-source cloud-native technologies.
OpenShift virtualization is also the perfect solution for developers challenged with supporting applications and VMs that will never be converted to containers due to complexity or time-boxed shelf life.
These can continue to run as VMs until they can be re-platformed for containers or they reach their natural end of life.
In this 1hr presentation, see a live demonstration of deploying VMs and Containers with Kubevirt.
Agenda Deployment of Kubevirt/OpenShift Virtualisation Deploy a VM and Application Containers Connecting to the newly deployed VMConfiguring external access to VM"

## Talk: Current State of GTK 4

"In December 2020 the GTK project released the new major version of the toolkit after more than four years of work, and 9 years after the previous major API version.
This was a major milestone in the history of the project, but it doesn't mean work has stopped.
In the past year, GTK developers made two additional minor releases, including: a whole new and improved GL-based renderer; a whole set of additional CSS properties to affect how UI elements can draw their content; new visual cues for entering text on non-English keyboard layouts; and a completely revamped documentation stack that tries to bridge the distance between the underlying C API and the various languages that can be used to write GTK applications.
In this presentation we're going to catch up with the current state of GTK 4, and where we're going in the future."

## Talk: Biometrics and Smart Devices

"Smart devices have been permitted to measure many aspects of our everyday lives, from our browsing habits to our sleeping patterns.
Many of us rely on smart watches to remind us to take a break from our desks and to count the number of steps we take in a day.
People have even posted screenshots of their heart rates spiking as a record of the moment they were dumped.
With the inclusion of increasingly sensitive hardware into the devices we use, developers are able to build software that measures and predicts things about their users' bodies - but without a strong grounding in the ways that human measurements have been used and abused in a pre-smartphone era, we risk retreading some of the more sinister paths history has drawn us down.
This talk is your guide down some of the most misguided of these roads.
You'll learn how the biometrics craze of the nineteenth century led to the development of phrenology, a pseudoscience that used the shape of the skull to justify everything from matchmaking to murder.
You'll follow the echoes of this thinking through to the more recent past, where the ability to measure a human body in detail initially left the menstrual cycle out entirely and then swung hard the other way, allowing employers to buy access to live feeds of their employees' fertility planning.
And you'll hear about what's happening now: of facial recognition systems that cover cities, of how employers have monitored locked-down employees as they work from home, and of the ethical frameworks that activists argue for compared to the ones companies adopt.
There's a lot that our bodies can tell us - but we need to learn how to draw out the right stories."

## Talk: NorNet an Internet test bed platform for research on multi-homed systems

"The NorNet test bed (<https://www.nntb.no>) is an Internet test bed platform for research on multi-homed systems.
The particular property of multi-homed systems is to be connected to multiple Internet Service Providers (ISP) simultaneously.
Its initial purpose is of course to still provide connectivity in case of ISP/network failures.
But does it really work that well, also with current protocols and applications?
And redundancy does not come for free.
A user connected to multiple ISPs will also receive multiple Internet bills each month.
So, is there a possibility to make further use of multi-homing in the usual case where nothing goes wrong? Obviously, there are a lot of interesting research questions, which need to be examined in realistic Internet setups! Therefore, we are building up the NorNet open Internet test bed platform as a Linux- and Open-Source-software-based infrastructure, which currently spreads over multiple sites in different countries.
NorNet makes extensive use of advanced Linux features like Kernel-based Virtualisation (KVM), Linux Containers (LXC), BTRFS file system features, IP routing rules, Stream Control Transmission Protocol (SCTP), Multi-Path TCP (MPTCP), and many more.
The goal of this talk is therefore to present an overview of the test bed, its underlying Linux features, and how they are combined to provide the multi-homing features to the various test bed users.
This particularly includes an overview of how to make use of multi-path transport with MPTCP – based on the Linux MPTCP implementation – in multi-homed environments.
The idea is to provide guidelines for also utilising multi-homing features in own projects."


## Talk: The Compact C Type Debugging Format

CTF (Compact C Type Format) is a debugging format whose main (but not only) purpose is to convey type information of C program constructs.
We have added support for CTF to the GNU Toolchain - CTF is now fully supported in GCC, linker (with type deduplication), binary utilities (dumping the contents of .CTF sections in human readable format), a GNU poke description for editing encoded CTF, and GDB.
Although the origins of CTF were to convey C type information, CTF format is now open for discussion (on the public mailing list on ctfstd.org) for format changes needed to support the new found use-cases like generation of backtraces and ABI analysis.
All this without sacrificing CTF's compactness and simplicity.
In this talk we will discuss these and other planned changes for CTF V4.
We invite wider community participation in the involved technical discussions via the medium of this talk.

## Talk: MusicBrainz.org and Wikidata.org APIs for information extraction

Musicbrainz.org is a database useful for tagging your local music collection.
Wikidata.org is a structured database used to store facts for wikipedia.
Both store information but they have different needs and are designed in different ways.
What can we learn from the designs and how to use the api's to extract information.

## Talk: Github Actions

"GitHub Actions is a continuous integration (CI) service from GitHub, allowing projects to run arbitrary code on their provided server instances.
GitHub Actions provides unlimited free compute to public repositories, and I can't think of a more deserving recipient than Linux.
There's a lot of stuff to build and test when it comes to Linux.
The matrix of release versions, architectures, compilers, configs, platforms etc is near-infinite, so we need every resource we can get.
GitHub Actions can't quite get us to infinity, but it can get us a bit closer.
We'll cover:
- a technical overview of GitHub Actions & how to get started
- available platforms & workarounds to get more
- using ccache with GitHub's caching feature for huge speedups
- using "problem matchers" to produce context-aware warnings & errors from gcc, clang & sparse
- implementing smart diffs between runs to find regressions
- how GitHub Actions gets used to drive CI for arch/powerpc
- some undocumented restrictions I've run in to- the time GitHub sent me 250,000 emails in 60 minutes"

## Talk: Configuration Orchestration Tools in the Linux World

In the Linux world, there are many ways that you can setup and configure your systems.
There are at least 10 configuration orchestration tools out there.
To name a few: ansible, cfengine, pupper, chef, salt and many others.
When I first started learning Linux, I did  my configuration with bash scripts + ssh.
Then I crank up to cfengine, and try to be puppet master.
Finally, I ended up playing with ansible and living with it since then.
In this 20 minutes talk, I will share my Ansible journey, from shell script to galaxy, with some examples and demo.

## Talk: Communities as Systems

Many of us work with systems in our professional lives.
Most likely, they take the form of cyber- or cyber-physical systems, where the constituent components - boxen, VAXen, Docksen, ESPen, are quite literally connected - possibly over some form of internet protocol.
These systems may be orchestrated or organic - but always serve a purpose.
They can co-operate, collide and compete with each other (and then there were 15 standards).
They can operate loosely or be tightly controlled.
They exist for a brief period of time (less brief if they contain COBOL), until they are disassembled, disaggregated and decommed back to electrons and e-waste.
But what about the people in those systems?
How are they connected?
Why are they part of the system? Or not?
What roles do they serve?
What are their inputs and outputs?
Plot twist! Communities are systems too!
The concepts we use for thinking about computer and cyber systems can also be used to uncover insights about communities, and how we go about creating, curating and concluding them.
