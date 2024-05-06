View [Multimedia Centre concept](https://excalidraw.com/#json=4WlobPNG4meVHVc7IDCRH,4v_woZHgknrwTYQW0z3Q_Q)

## What contributes to digital sustainability?

- Filters (**hard boundary**)
- Sorting relevant results first (**soft boundary**)
- Skip unnecessary pages
- Annotate video highlights

**Note:** Faster task completion does not necessarily represent digital sustainability, because it may require more upfront resources

### What can we learn from top tasks?

- Most tasks involve _recent_ information - an opportunity to apply default date filter
- Audio and photos are being copied - highest quality needs to be _available_ but probably doesn't need to be served by search, provide links for CDN?

### What is currently not sustainable?

- ~~Encourages reproducing media rather than providing shared URLs (audio/video has embed)~~
- Filters apply _on click_ (multiplying filtered searches)
- Extra navigation required to get to Topics page + search on Topics link
- Unbound initial filter (700k+ photos) - users know what media type they're needing, suggest filtering beforehand

## Filters

### Problem

The existing filters UX has a large impact on the sustainability of the European Parliament (EP) site. Two aspects of the current filters that stand out are:

- Filters are applied for each _interaction_ rather than as a _single action_
- When viewing multimedia pages, the highlights and initial results are unfiltered and unbound (hundreds of thousands of results)

Both of these issues result in wasted resources and slowed down task completion.

### Solution

- Submit all changes to filters at once/search query
- Set reasonable default date, considering most top tasks involve recent information

![concept of filter](filter.png)

**Note**: mobile is not shown, but I'm picturing it functioning similarly to the autocompleted filter options when initally searching and as full screen when updating filters after a search

## Navigation

### Problem

The existing navigation slows down users looking for specific information in several ways, mainly:

- Highlights page is shown for each media format before being able to navigate to search/filters
- Navigating to different media formats, which are essentially filters, do not persist other filter selections

Both of these issues also result in wasted resources and slowed down task completion.

### Solution

- Move highlights to Home page
- Consolidate links that act as filters into Search page

![concept of top-task flows](flows.png)
