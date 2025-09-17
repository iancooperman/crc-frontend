---
layout: posts
title: About
permalink: /about/
---

Ian is a Computer Science graduate with hands-on experience in IT, supporting one of the largest school districts in the country. He’s developed a knack for solving problems quickly, whether that means repairing hardware on the spot or streamlining day-to-day workflows. Currently, he’s working toward transitioning into DevOps, with the long-term goal of moving into machine learning. At the core, Ian is driven by a desire to build tools and systems that make people’s work simpler and more effective.

This site was built with [Jekyll](https://jekyllrb.com) using a customized Minimal Mistakes theme and is hosted on Amazon S3, distributed via CloudFront, and managed with Route 53. Continuous integration and deployment are handled through AWS CodePipeline and CodeBuild, which uses Microsoft’s jekyll:2-bullseye Dev Container to build the site from a [GitHub repo](https://github.com/iancooperman/crc-frontend). Artifacts are deployed to S3, which triggers a Lambda to invalidate CloudFront’s cache, ensuring visitors always see the latest content.

The long-term goal for this site is to serve as a central hub, bringing together Ian’s work, projects, and writing. In addition to technical content, it will also feature personal reflections and commentary—ranging from thoughtful insights to lighthearted takes on topics that don’t necessarily matter.

