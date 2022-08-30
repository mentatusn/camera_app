# DelsaBookReader
Delsa book reader is a audio book reader. It's implemented using image processing. 

project consist of two part:
A server and a android application

User take a picture of book and send it to server, server (which is written by flask) recieve it, compare it to book's images and send the voice of reading that page to user. User can play/pause and replay it taking until next image.
Book's pages and voices should be stored in server before usage.

## book;
current project is personalized for a kid book named Miss Brush in persian language. Voice are generated by a robot.
It can be personalized by any book with any language and anybody's voice.

## comparing;
we use SIFT (Scale-Invariant Feature Transform) algorithm form opencv for comparing images together.