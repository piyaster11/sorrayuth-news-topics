# เพจนี้โพสต์เรื่องอะไร — สรยุทธ สุทัศนะจินดา กรรมกรข่าว

A static dashboard of a **collected sample of 93 public Facebook posts** from [สรยุทธ สุทัศนะจินดา กรรมกรข่าว](https://www.facebook.com/sorrayuth9115) (Journalist, 5.4M followers), **14 October–11 November 2026**.

Live site: https://piyaster11.github.io/sorrayuth-news-topics/

The page shows **what was posted, not why**. Topic labels are editorial categories. This is a video/reel-heavy convenience sample, not a census of every post on the page.

A 9 November 2026 post in the sample discusses arsenic and heavy-metal pollution of the Mae Sai River.

## Files

- `index.html` — single-page dashboard (no build step; Chart.js from a CDN)
- `posts.json` — 93 dated posts (`date`, `text`, `topic`, `link`, `url`)
- Counts in the charts are computed in the browser from the `date` field, not hard-coded

## Collection

Viewed on the public page on 11 November 2026 (Bangkok time). During scrolling, Facebook virtualized and dropped many photo/text posts, so video and reel posts are over-represented. Dates were read from visible timestamps; three relative timestamps keep their as-shown wording alongside an approximate calendar date.

Categories used: politics, economy, crime, celebrity/entertainment, environment/pollution, world news, sports, personal/lifestyle, other. Each post is in exactly one category.
