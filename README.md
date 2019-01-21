# InfoCannon

A tool for automating the upload of Infowars videos to Facebook

**Tool Name**: InfoCannon  
**Source Code**: https://github.com/PatriotDevOps/InfoCannon  
**Language**: C# .Net 4.5 WinForms  
**Use Case**: Mass upload Infowars show archives and Special Reports into Facebook daily. For use on personal newsfeed or public page.  RIP [Infowars Live Feed](https://facebook.com/infowarslivefeed)  

#Directions:  

**Create a Facebook App**
1. Go to [developers.facebook.com](https://developers.facebook.com) 
2. Go to "My Apps" > "Add a New App". Go to My Apps > generate an Access Key key for it. This key will last for about 30-60 days.  
3. Enter a Display Name like "Video Uploader". You may want to keep the contact email the same.
4. Click **Create App ID**.  
5. 


Optional: Use [this StackOverFlow tutorial](https://stackoverflow.com/questions/17197970/facebook-permanent-page-access-token) to make the a new, permanent Access Key. If you do not, it will expire every few months.
2. Once you are up and running, you may have to make your app "live" in order for the posts to appear public.
3 Give the app **publish_pages** permission if you plan to post to a page.
4. Enter the API Key in the Access Key textbox.
5. For Page ID, Enter the Page ID of your page in the 2nd box. (If you are using your own newsfeed, enter "me"
6. Click the **Test** button to fire off a post that simply says "This is a test".
7. Click Save to save the settings, they will re-appear  when you open the tool. They are kept in a text file beside the .exe file.
8.  Select the show: Alex Jones Show, David Knight, War Room, or Special Reports
9. Select the date to gather videos from (The tool caches only the last 100 or so, don't go back more than a month or two.)
10. Click **Gather Videos**, if you have never uploaded this video before then it will have a Checkmark in the box to the left, otherwise it is unchecked.
11. Click **Post Videos**, all videos in the above listbox that are checked will be uploaded and posted to the page with full descriptions.

**NOTES**:  
1. Once you are up and running, check to make sure the app's posts are going up as "public". You need to check some settings of the page, or may have to make your app "live" in order for the posts to appear public.
2. DO NOT submit your app for Review, under any circumstances
3. Be ready to fight the Infowars, because we will all become a target for doing this.
