# reddit_media_downloader
download images from a subreddit. you can choose how many posts to scan, filter according to time and how to sort the subreddit

example:

    reddit = RedditMedia()
    reddit.dl_sub_images('art', sort='top', limit=500, when='all')
    
in the working directory a folder should be created with the name of the subreddit containing the images.

### dependencies:
1. praw
2. requests
