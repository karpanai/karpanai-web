---
title: 'Hunting in Groups'
date: '2005-03-27T23:10:53-04:00'
status: publish
permalink: /2005/03/27/hunting-in-groups
author: Karthik
excerpt: ''
type: post
id: 126
tags: []
post_format: []
---
With the sheer quantity of information available on the internet, mining it for relevance is where a lot of cool technology is being developed. [Pagerank ](http://www-db.stanford.edu/~backrub/google.html)revolutionized search and made it more democratic. Searching is no longer hit or miss – today, Google can search over 8 billion web pages and return the most relevant results in less than a second.

What's next in searching? What search engines lack is the ability to customize results depending on the user. Specific search terms return good results: (“Fourier Transform”, “Aishwarya Rai on Letterman” etc.) Vague, general searches (“Interesting science fiction “, “Funny blog”) might not return what you expect; even if they do, everyone gets the same results – your “funny blog” might suck ass to me.

[Collaborative Filtering, ](http://en.wikipedia.org/wiki/Collaborative_filtering)might be the solution. The idea is simple enough – if someone else buys the same books that you do, then there is a good chance that you'll be interested in the next book she buys. [Amazon](http://www.amazon.com), and [Netflix ](http://www.netflix.com)use it to recommend books and movies to users; it is straighforward for online merchants to do this.

But how could a search engine use Collaborative Filtering to tailor results? The easy way would be to ask users what they like, but that's not gonna work well, is it? At Amazon, apparently, only about 1% of the items have user ranks. More subtle, implicit methods would look at the user's browsing patterns and form “opinions” from them.

A fascinating [article](http://www.economist.com/science/tq/displayStory.cfm?story_id=3714044) from the [Economist Technology Quarterly](http://www.economist.com/science/tq/). Will this be the next PageRank?

> Collaborative filtering starts off by collecting data on individuals' preferences. This can be an explicit process, by which a user ranks a book (or CD, or restaurant) on a numerical scale, typically on a scale of one to five. It can also be an implicit process–a purchase, for instance, is a clear indication that an individual is interested in the item in question. But implicit measures can also be more subtle; for instance, the amount of time spent viewing a web page, or even just the “clickstream”–the sequence of links clicked on by a person browsing on the web. These different methods can then either be aggregated into a single score, or stored separately to allow more detailed analysis. And sometimes, consumers will be asked to score the same item in different ways–for instance, what one thought of the food at a restaurant, and what one thought of the service.

> Where the user of a search engine is on a solitary quest, the user of a collaborative-filtering system is part of a crowd. Search, and you search alone; ramble from one recommendation to another, and you may feel a curious kinship with the like-minded individuals whose opinions influence your own–and who are, in turn, influenced by your opinions.