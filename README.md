# picture-in-picture-player
I guess I'm not the only one getting distracted easily when watching a video, right? 😉 
That is exactly why I created this custom picture in picture player.

The player makes itself sticky in the bottom right corner of the page,
while you continue browse the website.

###The Picture-in-Picture web API

Before we dive into how I created my own custom picture-in-picture player, it is worth mentioning there is also a native web API for picture in picture.

This API works great and is in a lot of cases the way to go. However, because browsers don't want websites to randomly spam video windows all over the place, the API has some limitations.

The biggest limitation is that there's a user interaction (for example a click) required before this API can be triggered. That means that you can't just trigger the picture-in-picture mode if you scroll down on the page like you see in the example above.

So we couldn't use this API for our use case. We had to roll our own.
