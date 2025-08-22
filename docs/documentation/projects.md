---
layout: page
title: Projects
permalink: /docs/projects/
---

last edited: 2025-08-22

---

There’s a large set of steps required to transform raw course materials into something ready to publish online. We’re working to automate as much of this publication pipeline as possible. Since not everything can be automated, we’re also building tools to speed up the tasks that require human involvement. We’re designing these tools as simple web apps so we can quickly onboard people to help—no technical setup or expertise required. This makes it easy to scale up how many courses we can publish.

Here's a sample of our ongoing projects, in no particular order. 

### Automated face blurring
When we don’t have explicit permission, we need to ensure that students are not identifiable in our lecture recordings. Our system automatically blurs student faces while leaving the professor visible. Since automation isn’t perfect, we’re also building a manual workflow to correct mistakes or handle cases the system misses entirely. The manual tool runs in the browser: users can easily mark regions of pixels and time ranges, and a separate process then ingests those annotations to generate and apply the blur masks to the video.

### Automated copyright handling
Publishing course materials requires carefully handling third-party media (figures, tables, images, etc.) that may be copyrighted. Our tools help streamline this process by classifying whether something can be used under fair use, requires permission, or should be recreated with substitutes. We’re building browser-based workflows to make attribution easier, track decisions across classes, and assist with tasks like reverse image search, contacting rights holders, and preparing substitute graphics. Substitutes are created either by hiring a human designer or by generating alternatives with AI, ensuring we can preserve meaning while avoiding infringement. Once a decision is made, automation also applies the change directly to the lecture slides, reducing manual editing. Routine checks are handled automatically, while humans make the final calls and provide oversight where judgment is needed.

### Automated multi-camera video editing
Some courses are recorded with multiple camera angles, but the final edit needs to present a single, coherent view—usually one main angle plus a smaller picture-in-picture close-up of the professor. We’re building automation to sync the raw video and audio streams, align them, and generate the composite view. To handle cases where automated switching isn’t perfect, we’re also developing browser-based tools that let users quickly mark timestamps for camera changes, which are then ingested by a script to produce the final edited video.

### Automated slide-synced lecture reconstruction
Many lectures are recorded as a single wide shot of the professor speaking in front of projected slides, which leaves the slides low-resolution and hard to read. To improve quality, we’re developing methods to automatically detect slide transitions and align them with the original slide PDFs. This lets us reconstruct a crisp, high-resolution video where the slides take center stage, with a picture-in-picture view of the professor overlaid in the corner.

### Lecture scribing
High-quality lecture notes can sometimes serve as an effective substitute for video recordings, especially when professors are hesitant to share lecture videos publicly. We’ve experimented with hiring students to scribe lectures in LaTeX, producing detailed, polished notes that capture as much of the lecture experience as possible. Our pilot at MIT showed this can be a cost-effective way to capture lectures at scale when recordings aren't possible. More details can be found in this [blogpost](https://ashay.io/blog/crowdsourcing-lecture-scribing/).




