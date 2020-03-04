# Ghana History Moments
Creating a queue for Instagram posts coming from a blog. Ghana History Moments by Elmina Java Museum.

- [Background](#background)
- [Process](#process)
- [Components](#components)
- [TO-DO](#to-do)
    * [Blockers](#blockers)
    
<!-- toc -->
  
## Background

To celebrate Ghana's 60th year of independence, the Elmina-Java Museum in Elmina, Ghana began a series of daily blog posts commemorating highlights and moments in Ghanaian history that have shaped the nation. This project was created to share those blog posts to social media sites.

## Process

1. Collect photographs related to each blog event
2. Store in S3 or local file storage
3. Use IFTTT pipeline to post from Instagram to Twitter with the photo included
4. Create a post in Facebook Creator Studio to schedule Instagram posts
5. Link Instagram and Twitter posts to the blog via Linktree


## Components

- [SquareSpace blog](https://www.eaumf.org/ejm-blog)
- Facebook Creator Studio
- [IFTTT](https://ifttt.com/)
- [Instagram](https://www.instagram.com/elminajava/)
- [Twitter](https://twitter.com/ElminaJava)
- [Linktree](https://linktr.ee/elminajava)


## TO-DO

Create API calls to work with local files and text to make posts in Creator Studio

### Blockers:
- No API in place to push posts from storage to Instagram.
- Automation to cropping; this would need to be performed locally.