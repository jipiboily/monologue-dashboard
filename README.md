# Monologue Dashboard

I have a dream...

This is a repo with nothing else than a README for now. This is outlining an extension for Monologue that I wish could exist. If you feel like starting it, awesome! I will <3 you forever. Beers are on me when we meet, for sure!

## Features
- Widget based Dashboard to provide an overview of what's happening on your blog
- analytics provided by Google Analytics-
  - Total page views in last 30 days
  - number of live visitors
  - most popular pages (top 5?)
    - today
    - week
    - month
    - year?
- stats about the RSS feed. Right now, as there is no JS, obvisouly, there is no stats for the RSS feed at all. That would be awesome if we could connect that with Google Analytics' API. Sending as much information as possible.
- Twitter followers
- Facebook Likes
- number of drafts (posts)

## Tools
- redis could be core to this I think
- Maybe we could use Dashing? http://shopify.github.io/dashing/  (maybe with https://github.com/Shopify/dashing/issues/5). Probably not the best path as not a lot of people want Dashing to be a Rails mountable engine. Also, I am not sure if it is doable or a good idea to have a mountable engine, mounted in a mountable engine...
- http://www.chartjs.org/

## Possible source of inspiration?

I actually like the look and feel of Ghost's dashboard. See Ghost's Dashboard, which is awesome: http://john.onolan.org/ghost
