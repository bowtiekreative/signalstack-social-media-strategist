# Platform signals (official sources)

Last verified: 2026-10-15. Platforms change. Before relying on a claim for a big decision, re-open the source and check the date. Label anything not from the platform itself as secondhand.

## Instagram

Source: Instagram, "Instagram Ranking Explained" https://about.instagram.com/blog/announcements/instagram-ranking-explained

| Surface | Signals, in the stated order of importance | Main predictions |
|---|---|---|
| Feed | your activity; information about the post; information about the person who posted; your history of interacting with them | spend a few seconds on the post, comment, like, share, tap the profile photo |
| Explore | information about the post; your activity in Explore; history with the poster; information about the poster | likes, saves, shares |
| Reels | your activity; history with the poster; information about the reel; information about the poster | reshares, full watch-through, likes, visits to the audio page |
| Stories | viewing history, engagement history, closeness (no order stated) | tap in, reply, move to next |

Limits named by Instagram:
- Posts that break the Recommendation Guidelines stay on Instagram but are kept off Explore, Reels, Search and suggestions. Repeated violations can make an account's posts ineligible for a period. Check **Account Status** in the app.
- Reels are limited in recommendations for low resolution, watermarks, being muted, borders, being mostly text, and having already been posted on Instagram.
- Feed pacing: the system avoids showing many posts from the same person in a row.

Originality (Instagram for Creators, 2026-04-30) https://creators.instagram.com/blog/rewarding-original-creators-on-instagram
- Accounts that mostly post unoriginal content are no longer shown where Instagram recommends content. Content from followed accounts is unaffected.
- Edits count as original when they add real value (new context, new information, remix). Borders, watermarks, subtitles or a credit in the caption do not.
- Eligibility comes back when most recent posts in a rolling 30 days are original.

Secondhand: Instagram head Adam Mosseri has publicly named watch time, sends per reach and likes per reach as three of the most important signals (reported by Social Media Today, https://www.socialmediatoday.com/news/instagram-shares-algorithm-2025/738034/).

Per-post metrics available through the Instagram Graph API (useful when asking someone to export): reach, views, likes, comments, shares, saved, reposts, follows, profile_visits, total_interactions, ig_reels_avg_watch_time, reels_skip_rate. https://developers.facebook.com/docs/instagram-platform/reference/instagram-media/insights/

## TikTok

Source: TikTok Newsroom, "How TikTok recommends videos #ForYou" (2020-06-18) https://newsroom.tiktok.com/en-us/how-tiktok-recommends-videos-for-you/
- Inputs: user interactions (likes, shares, follows, comments, content created), video information (captions, sounds, hashtags), device and account settings (lower weight).
- Strong signal example: watching a longer video to the end.
- Follower count and past high-performing videos are not direct factors.
- The feed mixes in diverse content; it generally avoids two videos in a row with the same sound or creator; duplicated content and spam are excluded.

## YouTube

Source: YouTube Help, "How YouTube recommendations work" https://support.google.com/youtube/answer/16089387
- Uses watch history, search history, subscriptions, likes, dislikes, "Not interested", "Don't recommend channel", and satisfaction surveys ("satisfaction, not just watch time").
- Shorts feed is personalized to what the viewer is likely to want next.
- AI-made videos can be recommended as broadly as others.

## LinkedIn

Source: LinkedIn Engineering, "Understanding feed dwell time" https://engineering.linkedin.com/blog/2020/understanding-feed-dwell-time
- Dwell time (time a post is at least half visible, and time after a click) is used to predict skips and to rank.
- Other predicted actions: click, react, comment, share. Affinity with the author and context such as time of day are features.
- LinkedIn states "time well spent is better than more time spent".

## Facebook

Source: Meta, "Fighting Engagement Bait on Facebook" (2017-12-18, updated 2019) https://about.fb.com/news/2017/12/news-feed-fyi-fighting-engagement-bait-on-facebook/
- Demotes posts, Pages, comments and video audio that bait likes, reactions, shares, tags or comments ("LIKE this if you're an Aries").
- Exception: asking for help, advice or recommendations, such as a missing child report, raising money for a cause, or travel tips.

## How to use this file

- Quote the signal, name the source, give the date.
- If a user asks about a platform not listed, find its official help or newsroom page before answering, or say you could not verify.
