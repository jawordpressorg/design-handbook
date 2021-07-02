# WordPress Core About page

Every WordPress release has an About page. It is shown to users after they finish updating to the new version, and it tells them what the new features are and who contributed to making them.

This is a great marketing opportunity as lots of people get to see this page. It would be fun to have each major About page customized by one of the designers in the WordPress community (otherwise we fall back on an existing design).

This trend started with WordPress 4.7, you can view the previous designs on Figma: [https://www.figma.com/file/LrjiQZDts99EakxvZ6YcuMIr/About-Page](https://www.figma.com/file/LrjiQZDts99EakxvZ6YcuMIr/About-Page)

If you want to create a page like this, here are the steps to follow:

## Steps

*   Know your deadline: ideally, have this all lined up so the page is ready for RC, as once in RC, the text may not be changed anymore.
*   Create a ticket for the about page kick-off, like this: [https://core.trac.wordpress.org/ticket/46901](https://core.trac.wordpress.org/ticket/46901)
*   Clearly state what steps are:
    *   Coordinate between release leads and either marketing or a copywriter, to draft initial page copy.
        *   Draft in a google doc so multiple people can write and suggest edits.
        *   Check-in with release leads to headline features.
        *   Check-in with any feature leads if you’re unclear about details.
        *   Go through Beta posts on /news/ to populate features and find copy inspiration.
        *   Go through dev notes on make/core to populate the developer happiness section.
        *   Make sure to go through features of Gutenberg and create a section to call it out with “new editor feature this release”.
    *   Create images — could be illustrations, icons, or screenshots.
    *   Finalize copy (after release lead last review).
    *   Finalize design.
    *   Get the page made up.
    *   Test the page in various browsers, checking for image quality.
*   Release Post (for those leading a release).
    *   Draft a new post on wordpress.org/news.
    *   Copy content over from the About page.
    *   Add images, changing size, alignment, or positioning to fit the blog layout.
    *   Pass off to release lead to include credits shortcode and release name.
    *   Get the musician’s name from the release squad lead.
    *   Post slug should be wp.org/news/yyyy/mm/**musician.**
    *   Keep the post with an “album cover” feel.

## Design 

The About Page has a set framework and it is not meant to be redesigned from scratch each release.

Layout should be thought of as a stack of containers, which can be 1-4 columns. The content in the columns can be anything — text, video, images, embeds, etc. These containers can have no background color, a “subtle” background color, or “accent” background color (these change with each About page using colors from the header feature). Columns can also have one of these background colors. Containers are stacked on top of each other to create the page.

Wondering why the About Page is not done in the block editor? The biggest blocker is translations. Every string on the page is wrapped in a translation function, with additional translation notes as needed. We’d need to find a way to do that with Gutenberg as well. 

Some items to watch for:

*   The header has the most freedom. It can have a design element background or text effect. Check that is accessible.
*   Images, illustrations, and videos are allowed in the content.
*   There can be 1, 2, 3, or 4 columns and have a colored background.
*   For tech requirements, look here: [https://gist.github.com/ryelle/91ef6cd84a197b6af880dc055be21cc9](https://gist.github.com/ryelle/91ef6cd84a197b6af880dc055be21cc9)
*   Talk to the developer in-charge of coding and committing the About Page.

Examples of how the boxes can look like:

![](https://i1.wp.com/make.wordpress.org/design/files/2020/09/Screen-Shot-2020-07-28-at-10.31.13-AM.png?resize=776%2C434&ssl=1)

*   ![](https://i2.wp.com/make.wordpress.org/design/files/2020/09/Screen-Shot-2020-07-28-at-10.34.31-AM.png?resize=697%2C1024&ssl=1)
    
*   ![](https://i0.wp.com/make.wordpress.org/design/files/2020/09/Screen-Shot-2020-07-28-at-10.45.54-AM.png?resize=693%2C1024&ssl=1)
    

Examples of how the boxes in the About page can stock up. The colored boxes can be replaced with images, videos, or more text.

## Images

*   Images can be edge-to-edge or have a 32px padding on all four sides.
*   We don’t recommend putting images or videos in 3 & 4-column containers.
*   Images and videos resize a bit on mobile.

![](https://i0.wp.com/make.wordpress.org/design/files/2020/09/about-sizes.png?resize=604%2C1024&ssl=1)

Examples of image sizes within columns.

### Videos

**For accessibility,** if the video has voice audio, a text equivalent needs to be provided. If the video just shows a flow or action being performed, then the process needs to be described in text. Key thing is remembering the target audience for the description, and that they need to get the same level of information from the description as a sighted audience gets from watching. It is important that the description of the video is clearly associated with the video.

The figcaption should be connected to the figure using aria-labelledby; this is required to support IE11.

#### **Tech requirements**

*   Videos must be 480 px wide  (in general, most users will see this video at 436px wide, large phone sizes might see it up to 488px)
*   The space for a full-width video is 936px wide, and for a wider 2 column layout is 602px.
*   Record using [Kap](https://getkap.co/) (this is different than the recommendation in the post but [@joen](https://profiles.wordpress.org/joen) recommended this instead of Screeny)
*   Convert .mov files to .mp4 using FFMPEG. Kap does appear to have the ability to export as MP4 and WebM though. Using that is preferable to converting if it works well.
*   [How to: Good UI demo videos](https://automattic.design/2019/11/12/good-ui-demo-videos/)