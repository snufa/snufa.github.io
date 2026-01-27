# How to add links and videos to your abstract

If you're the author of a paper and you would like to add a link to a page (e.g. related paper, or your website), please submit a pull request on the [SNUFA github repository](https://github.com/snufa/snufa.github.io). Each abstract has a page in the directory structure that should be easy to find. Here's an example of how to add a YouTube embedded video and a couple of links, just add this at the top of the ``.md`` file:

```
---
youtube: ucL5AvmdD1E?si=HoubevvZefGur1Vg&start=337&end=467
links:
  - title: Paper
    url: https://neural-reckoning.org/pub_neuromodulation_enhances_sensory.html
  - title: Abdel's page
    url: https://neural-reckoning.org/abdelqader_alkilany.html
---
```

The YouTube code is what you get if you go to the video, click Share and then copy the end part of the URL.

For links, the format should be obvious. You can have as many as you like in a list.