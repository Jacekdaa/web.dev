---
layout: handbook
title: Third-party contributions
authors:
  - katiehempenius
date: 2019-07-28
description: |
  Web.dev's policies regarding third-party contributions.
---

The following are some things to keep in mind when contributing to web.dev:

## Prioritize simple, well-supported, and open-source methods.


### Simple

Content should use “vanilla” code as much as possible. In addition, content should use minimal dependencies. This keeps the focus on the topic in question and makes it easier for users to apply web.dev learnings to their own projects.


### Open source

For topics that require non-native dependencies, open-source tools and libraries should be used as much as possible. Using open-source software helps keep web.dev accessible to as many developers as possible.

For topic areas that are dominated by proprietary solutions, web.dev should provide at least one open-source option (when available) along with proprietary options. 


### Use well-known and well-established tooling.

Choosing tooling can be one of the most overwhelming and time consuming aspects of web development. We want users to feel confident and well-supported with the tooling they choose, so web.dev deliberately focuses on providing instructions for the most well-known and well-established tooling and libraries. The tooling mentioned on web.dev is not intended to be an exhaustive listing of all available options.

Third-party contributions should focus on tooling that meets at least one of these criteria:



*   **[HTTP Archive](https://httparchive.org)** **data:** Tooling is used by ≥ 10K domains
*   **npm weekly downloads statistics:** Tooling consistently has ≥ 50K weekly downloads.

If the nature of the tooling in question makes it impossible to use either of these data sources to verify its popularity (e.g., if you were writing an article on servers, neither of these data sources could be used to verify usage of nginx), this can alternatively be demonstrated by providing a list of 5–10 well-known sites who’ve self-identified as users. 


## Follow the web.dev style.

Although some of the information found on web.dev overlaps with documentation or blog posts that can be found elsewhere, content for web.dev should be unique and adapted to the web.dev style and format. See the [web.dev handbook](https://web.dev/handbook) for more information.

## Focus on building for the web.

Content is a good fit for web.dev if it focuses on building for the web. There are many different aspects to building for the web, so web.dev further organizes content into “collections” that address specific web topics like speed or accessibility.

If content is a good fit for web.dev, but there isn’t an existing collection for it to fit into, it can exist as a standalone blog post until there is enough related content to create a collection for it.


## Provide support

Third-party contributions to web.dev should provide a point of contact who can respond to  GitHub issues related to their content within a week of being submitted. The web.dev team will tag the point of contact in issues so that they can respond.
