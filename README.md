# Lemur Learner

The primary purpose of this site is to provide potential and current students in the SBU study abroad program in madagascar a reference for lemur information in general as well as the specific research being done by Centre Val Bio.

The prototype of the site will contain lemur photos from a database besides the SBU database as well as empty PDFs for the research.

A data-driven MERN-stack web application that allows users to search for entries on lemur species. An entry contains photos, sounds, population graph, fun facts, and a card listing essential details about the lemur. There is also a scroll bar on the bottom listing other species in the lemur family.

Users have the functionality to upload photos/sounds of lemurs onto the site. An identification tool built using tensorflow will then attempt to identify the photo/sound. However, a photo will only actually be marked as classified once a user with an adminsitrative account marks it as such.

There is login/signup functionality. There are three types of views:
- Administrator view: CRUD functionality for species entries and everything inside of it, approve/edit approval of uploaded photos and sounds, star pages they are interested in, use identification tool
- Non-administrative view: Retreive species entry, upload photos/sounds and wait for approval, star pages they are interested in, use identification tool
- Not signed in view: Retreive species entry, use identification tool

Future Updates:
- More compelling data visualization
- Mobile app version of website
- 360-degree virtual tour of sections of Ranomafana National Park
