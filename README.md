# bugtrackerpreview
The repo already exists for the bug tracker but contains the database keys.  This repo is for the preview of that bug tracker!

![bugtracker wireframe2](https://user-images.githubusercontent.com/97564630/168741363-a8319231-c334-4ebe-9840-7f39d0f78724.png)


To see a figma wireframe walkthrough of the mobile app:
https://www.figma.com/proto/BlfT6oavCVtFDUQALoqjWj/Untitled?node-id=2%3A2&scaling=scale-down&page-id=0%3A1

This app can be used to log in, read, edit, create and delete posts and is used as a ticketing app for tracking bugs across Mythic Softwares.
Users can log in with Google authentication for security,

they can see all public issue tickets being tracked

they can add issues with a form that asks for a subject line and a description of the issue.  Issue description form allows for rich text markup, so that authors may use bold, italics, or strikethru marks in their composition.

Users are able to mark issues private or public.  Private issues may not be seen by other users.

App is reactive and adaptive to new screen resolutions and orientations and can be used on a wide variety of devices

Users can emphasise the subject line to create a bold header for urgent issues

Users can edit their tickets, which brings them back to the add ticket page but the forms are filled in with the information the user already input

Editing a ticket automatically sets the ticket to private until the user elects to share the ticket publically, even if the original ticket was public.  This allows the user to add private details to previously public issue tickets.

Users can delete their own tickets with a single click.  This reduces latency if a user accidentally shares information that should be private.

Deleting with the one click button removes the ticket from the database instantly.

Users can view their tickets on their dashboard.

A public issue tickets page allows users to see all public tickets.

Users can log out securely.



Optimizations:
Archive option that allows completed tickets to be held for 30-60 days

Ability to attach screenshots

Status workflow - beginning with added form to mark urgent, low priority, known but with no intention to fix, archived, starred, incomplete, complete

Two step deletion process - Currently when a user clicks delete on their own issue it's gone instantly

