# FE3-youtubeclone

# Tasks outlined:

1. Create the ui as shown in the figma.

2. Create 2 pages - index.html(home page), videoDetails.html.

3. Make sure the UI is exact - use the font Inter ( from google fonts)

4. You can extract the other assets from figma itself.

5. Implement the UI for the Search Bar, and One Video Item design.

6. On landing onto the home page fetch 20 videos for the empty search string.

7. Make the design of one video we can reuse the same for all the videos.

8. Implement a javascript function that takes a list of video objects and renders them onto the UI.

9. When clicked on a video item, navigate to the video details screen by sharing the video_id to that page (we can use either cookie storage , localStorage, sessionStorage to share data across multiple web pages of the same website).

10. Video Details screen
Capture the Video_id from the cookieStorage and fetch the video content and play it.
Using the same video_id make an api call to load the statistics of the video (like count, dislike count, subscribers, channel name etc..).
Also make another network call to fetch the comments of the video.



# Features:

1. Search Functionality- On Searching for a video we receive a list of videos this API will drive the same where we send the search String to Youtube’s API and it sends the list of videos as per our search.

2. Video Details- The api will give us the details of a particular video. We need to send the videoId which uniquely identifies the video and what details we need in the `part` parameter.

3. Play Video


Here's the Figma file for reference: https://www.figma.com/file/53msLWP0JcqWdt4n0fjAZu/YouTube-UI-Clone-Design-(Community)?type=design&node-id=3-185&mode=design&t=9E1wUw956BSodnIp-0

For any queries, reach out at hasanmrizvi72@gmail.com
