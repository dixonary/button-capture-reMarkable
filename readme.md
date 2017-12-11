# button-capture
 
## A simple event reader and responder for the reMarkable tablet.

This small program works in conjunction with [draft](https://github.com/dixonary/draft) to provide functionality.

It can be run on its own - with small modification - to provide additional button functionality!

By default, it has only one behaviour: When the middle button is held for 1 second and released, it will run the contents of /etc/draft/.terminate. (Yes, this is obviously insecure. If you are worried about people hacking your reMarkable, don't use this.)
