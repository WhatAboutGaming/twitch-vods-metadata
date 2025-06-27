# twitch-vods-metadata
A compilation of metadata of videos and clips hosted on the Twitch channels WhatAboutGamingLive and TwitchTriesToPlay.

# Notes
1) Categories are not available on the metadata provided by Twitch, categories had to be entered manually, so there may be some inaccuracies when it comes to categories.
2) Some videos were streamed under multiple categories (or games), videos that have multiple categories will have multiple ``Category`` tags, one per line.
3) Some videos had to be upscaled to 1280x720 (720p) or 1920x1080 (1080p) before being uploaded to YouTube to avoid being downscaled by YouTube. Videos smaller than 1280x720 (720p) but larger than 853x480 (16:9) or 640x480 (4:3) (480p) will get downscaled by YouTube to 480p, and native video resolution will not be available. This will be indicated by the tag ``Upscaled`` in the description.
4) Some videos are stuck at non-native resolution. This will be indicated by the tag ``Non-native``.
5) Videos that are upscaled will have a link to both an upscaled and a non-upscaled YouTube upload. (Again, non-native resolution videos on YouTube will have lower quality and lower resolution.)
6) At some point, Twitch mass converted videos to a newer format. Some videos unfortunately were broken during this conversion process, rendering the videos unwatchable on Twitch. Broken videos can be identified by an incredibly low resolution, and often very long portions of just black screen and silence. This will be indicated by the tag ``Broken Video`` in the description.
7) Not all videos or clips have chat logs available, especially really old videos from before Twitch began saving chat logs to videos. This will be indicated by the tag ``Missing Chat Log``.
8) Chat logs are not exactly human readable. To generate videos of chat logs, use the app [TwitchDownloader](https://github.com/lay295/TwitchDownloader).
9) Not all videos have thumbnails, sometimes Twitch fails to generate thumbnails. This will be indicated by the tag ``Missing Thumbnail``.
10) In some cases, lower video ID will have newer date that some videos with higher ID.
11) Metadata and thumbnails were downloaded using the app [Twitch Metadata Downloader](https://github.com/WhatAboutGaming/twitch-metadata-downloader).
12) Some videos are split in multiple parts, those videos will be indicated by the tags ``Split Video`` and ``Parts``.
13) Some videos are completely missing but the metadata still exists, those videos will be indicated by the tag ``Missing Video``
14) All videos will have the link to the original video hosted on Twitch, but those links might not work.
15) This list is incomplete, there are many videos that were lost to time before this list was compiled. Some lost videos might still exist on YouTube but their video IDs and dates are unknown.
16) All videos in this list are hosted on [this YouTube Channel](https://www.youtube.com/@ItsMeWaggle/videos).
17) Filenames follow this naming convention: {{TimeInMilliseconds}}\_{{Year}}\_{{Month}}\_{{Day}}T{{Hour}}\_{{Minute}}\_{{Second}}Z\_{{ChannelID}}\_{{VideoID}}
18) Some clips don't match the date of the stream they are from, clips can be created years after a stream has ended.
19) Some videos might have wrong ID or title, that's because videos have been erroneously uploaded with the wrong title or video ID, but multiple copies of the same video with the right ID exist.
20) Some videos with different IDs might be duplicates and videos with the same ID might also be duplicates because videos have been uploaded multiple times to YouTube.
