# Signal Audit

Run this on any account with per-post data. Compute with code when there are more than about 20 posts.

## 1. Clean the table

- One row per post. Keep deleted and archived posts, marked as such.
- Columns: id/url, published (one time zone, stated), format (reel/short/video, carousel, image, text, story), pillar (topic group), caption first line, reach, views, likes, comments, shares, saves, watch time, follows, profile visits, link taps.
- Posts younger than 3 days are still collecting reach. Show them, but leave them out of comparisons.
- Tag each post with a pillar using simple, stated rules (keywords in the caption) so anyone can reproduce the grouping.

## 2. Per-post rates

For each post, per 1,000 reached (use views when reach is missing, and say so):

| Rate | Formula |
|---|---|
| send rate | shares / reach x 1000 |
| save rate | saves / reach x 1000 |
| like rate | likes / reach x 1000 |
| comment rate | comments / reach x 1000 |
| follow rate | follows / reach x 1000 |
| hold | average watch time / video length (or % watched) |

Account rate = total actions / total reach. Typical post = the median of per-post rates. Report both: the account rate is dragged by big posts, the median is what a normal post does.

## 3. Shape of reach

- Concentration: share of total reach from the top 5 posts. Above 40% means the account lives on outliers. Say it plainly.
- Typical post: median reach, and the 25th to 75th percentile range.
- Follower vs non-follower views: if most views come from non-followers, recommendations drive the account, so recommendation eligibility and send rate matter most.

## 4. Breakdowns

For format, pillar, and posting window (for example 0-5, 6-11, 12-17, 18-23 in the account's time zone), show:

| group | posts | median reach | median send rate | median save rate | share of total reach |

Rules:
- Show the post count on every row. Under about 10 posts: "hint, not finding".
- Look at medians first, then check whether one huge post explains a group's total.
- Hour effects are usually weak once format and topic are accounted for. Do not prescribe a posting time unless the gap is large and holds without the top posts.

## 5. Hygiene flags

Count each and list examples:

- **Repeat uploads:** same video or same opening line posted more than once. Platforms limit already-posted content. Recommend a new cut.
- **Deletions:** posts removed after publishing. Recommend archiving instead, and keeping a log of why.
- **Caption problems:** empty, hashtags only, or internal notes left in (slide specs, script directions, labels like "Hook:" or "Description:").
- **Feed crowding:** many low-value posts in a short span (thank-yous, admin updates, near-identical announcements). Move to Stories, a weekly roll-up carousel, or Highlights.
- **Originality risk:** reposted clips, watermarks from other apps, borders, mostly-text videos.
- **Engagement bait:** "comment YES", "tag 3 friends", "like if". Replace with an earned ask.
- **Conflicting numbers:** the same goal, price or offer stated differently across posts. Pick one source of truth.

## 6. Measurement gaps

List every Signal Stack layer the data cannot see. Typical gaps: watch time, skip rate, follows per post, link taps per post, and anything off-platform (sales, donations, bookings). If the goal is money and the money is not tracked per source, the first fix is a tracked link per channel and one place that records results.

## 7. Write it up

- Verdict in three lines.
- The tables above.
- Findings: one sentence each, number first.
- What the data cannot tell you.
