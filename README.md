# bdsmlr-updates
Updates for community on BDSMLR development

## September, 16 2021 fixes 

- Optimized /firstload and /infinite queries
- Added partitioning for the database
- Updated database version
- disabeled /newposts query until we're able to refator it - right now it's too heavy on the db and leads to server crashes
- started frontend refactoring 

## July, 27 2021 fixes 

- Fixed chat problem that kept users from sending messages from the blog preview because the enter button wasn't working.
- Resolved issue that prevented some users from logging in on the web browser if they had an ad blocker turned on.

## July, 20 2021 fixes 

Made the following fixes and improvements:
- Fixed issue with the server hosting subdomains causing some blogs to not load properly.
- Added loaders and error messages to make the UX smoother.
- Fixed link forming from the messages page so users can go straight to the user profile.
- Improved layout for the chat pop-up and the page itself.

We will get back to posting regular updates here, so stay tuned!

## May, 5 2021 fixes 
- tags issue is fixed. There was a problem with some tags were redirecting to the chat. Now the tag functionality is back. Possible to click on it and see more content, and the icon near it expect to go to the chat which is currently broken.
- the bdsmlr blog will be implemented soon
- fully CI/CD-automated development environment is built for BDSMLR to help us with our patches and goals, this is where we can now test new and old stuff without ruining user experience
- the issues will be solved faster starting in 2 weeks, as far as we expand the team

## April, 13 2021 fixes 
- user profiles pictures are fixed on the main domain bdsmlr.com
- the link to development updates is on the main page now
- platform improvement: the test environment is set up. We will test changes before deploying it to production. It's a good practice
- working on integration with chat platform by post tags. There will be most popular tags define. User can click it and go to chat with others who is interested in particular topic.

## April, 5 2021 fixes 
- user profile pictures - there is a problem with pictures are not shown or broken sometime. User profiles pictures are fixed on blogs subdomains - **XXX**.bdsmlr.com.  It's a known issue that some profiles pictures are still not loading on the main site https://bdsmlr.com, this will be addressed in the next release.
- reset password - some users could not restore their password via email. The problem is fixed. If you have this problem again, report a ticket to zendesk with username and we'll help you to restore.
- receiving emails - there was a problem with receiving emails from bdsmlr.
- restored some accounts - we got some requests to unban accounts. We are checking all accounts and unban those who can be unbaned due to our policy. There are some accounts that can not be restored
