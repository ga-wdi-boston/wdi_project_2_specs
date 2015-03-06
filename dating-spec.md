# CodeDate: Dating Site

## Outline

Produce a new online dating platform, allowing programmers to find potential dates.

## Required Features:
- Users must be able to log in (manually or optionally with a GitHub account)
- Users must have usernames, photos, and profiles with personal information
- Users must be able to 'like' each others' profiles. They must also receive notifications when their profile has been 'liked'.
- Users must be able to answer a set of questions with multiple-choice answers to build their 'personality' which can be used to match with other users.
- Browsing of users in their geographic area, ordered by their 'match'
- A chat service that allows users to send messages to other users. However, this will only be active when two users 'like' each others' profiles.

## Optional Features

- User profiles must link up with their GitHub accounts and include information about peoples’ programming habits

## Assets (provided to students):
- name (“JoinTable”)

### Gotchas

A dating site appears simple at first, but has a lot of small moving parts to consider. The matching can be accomplished in multiple ways and is something to research into; but don't go overly complicated at first.

Image upload must persist to Amazon S3/Cloudfront, and handling the upload process with JavaScript is tricky. We have included some code for Rails that can help out greatly with this. Don't just blindly use the code however, and make sure that you use `pry` to trace through it completely, and potentially even refactor it.
