+++
date = "2017-05-05T00:00:00"
title = "Architecting the Future: Abstractions and Metadata"
abstract = "Kubernetes and Docker are two of the top open source projects, and they’re built around abstractions and metadata. These two concepts are the key to architecting in the future. Come with me as I dig a little deeper into these concepts within k8s and Docker and provide some examples from my own work."
abstract_short = ""
event = "CodeStock"
event_url = "http://www.codestock.org/"
location = "Knoxville, Tennessee"

selected = false
math = true

url_pdf = "https://drive.google.com/uc?export=download&id=0B88WpFWKRdpYcS1XZnFRTTRzdkU"
url_slides = "https://www.slideshare.net/DanielBarker4/architecting-the-future-abstractions-and-metadata-codestock"
url_video = ""

# Optional featured image (relative to `static/img/` folder).
[header]
image = "headers/arc-design-01.jpg"
caption = ""

+++
<iframe src="//www.slideshare.net/slideshow/embed_code/key/J5seCWwXE06MHJ" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/DanielBarker4/architecting-the-future-abstractions-and-metadata-codestock" title="Architecting the Future: Abstractions and Metadata - CodeStock" target="_blank">Architecting the Future: Abstractions and Metadata - CodeStock</a> </strong> from <strong><a target="_blank" href="https://www.slideshare.net/DanielBarker4">Daniel Barker</a></strong> </div>

This talk will explore these concepts within k8s and Docker as well as work I've done in my current role around continuous delivery pipelines. Attendees will leave with an appreciation for these two concepts and the tools necessary to begin architecting their systems similarly.

Abstractions and metadata are the future of architecture in systems engineering as they were before in software engineering. In many languages, there are abstractions and metadata. However, systems engineering has never adopted this view. Systems were always thought of as too unique for any standard abstractions. Now we've standardized the lower-level abstractions and we’re ready to build new system-level abstractions.

Docker has become the standard unit of processing, which has alleviated many of the diversity issues within systems. Docker did this with abstractions around networking, cpu, memory, and filesystems.

Kubernetes is now using Docker to create higher-level abstractions, but they've even abstracted away the runtime. Kubernetes uses concepts like PersistentVolumes, Routes, Services, and Deployments as abstractions.

My team has created an abstraction around continuous delivery pipelines that provides us more flexibility with underlying resources. It's a simple system based on certain abstractions and specific metadata. We've abstracted the build and deploy systems from the deployment pipeline model as well as accumulated metadata attributed to people, data, and pipelines to ensure security and compliance at scale.
