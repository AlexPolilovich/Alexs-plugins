# Alexs-plugins
little plugins


Hello Bro!

This is a little script, which you can use to auto posting your content in social web vk.com (vkontakte). 
All, what you need to use this daemon: access token, group id, time frame what you like to post and contents (text, hash-tags and photo(photos already must be uploaded on vk.com)), the number of messages on the wall that you want to display at the same time.  Vk.com has limits for all actions, and for number of posts on wall in group/public it also has its limitations, this is 50 for it.  You can set any time frame posting you would like (example from 13:00 - to 15:00, 18:00-22:00 etc.). This script can calculate count of posts with random pauses, to convince vk.com that you aren't a bot. 


For example. 
You say 13:00 - to 15:00, 50 posts, 3 posts to show. Script divide 50 posts by 2 hours. And now you have 25 posts per hour and 3 posts won't delete on wall. More 3 posts will delete from tail.

You say 13-15, 17-19, 21-23, 50 posts(it is limit, also you can say 10 or 24 or any number), 5 posts to show. Script will divide 50 posts by 6 hours. And now you have 8 posts per hour and 5 posts won't delete on wall. More 5 posts will delete from tail.
