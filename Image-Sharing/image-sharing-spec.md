## Outline
Deciding the best photo is hard, but other people can help you choose the best image in a set that you upload. Put together a platform that lets users upload sets of images (more than one) with a question ('Which is the cutest cat?') and let other users vote to determine the top photo. Users should also be able to have a conversation in comments about the photo sets.

## Assets (provided to students):
- name ("Pixelect")

## Must-Have Features
- Users (anonymous or logged in) must be able to upload sets of images and write a question/prompt that others will use as their voting criteria. (e.g. 'Which photo has the best composition?', 'Which photo of me is funniest?')
- Front page must show the most actively voted upon image sets from the last 24 hours and also recent uploads.
- Users must be able to log in; users who are not logged in can upload images, but cannot comment or vote.
- Users must have usernames, but a full profile is not necessary.
- Logged-in users must also be able to comment on, and upvote/downvote on other peoples’ image sets.
- Logged-in users must also be able to comment on other users’ comments.
- Images are uploaded to S3 and served from Amazon Cloudfront

## Nice-to-Have Features
- Track and display the view count for each image set.
- Photo sets can be uploaded via drag/drop to the site.
- Users can tag image sets with a category and browse sets by tag.
- Logged-in users are able to flag offensive image sets for moderation, and after 3 flags they are automatically hidden from the public.
- Users have the option to get notifications sent to them (with context; i.e. “User X replied to your comment, ‘Blah blah blah’ ”)
- Users can crop and apply filters to their photos
