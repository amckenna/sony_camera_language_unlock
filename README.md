# sony_camera_language_unlock

I was struggling to get the older (and abandoned?) ma1co/Sony-PMCA-RE application to work for unlocking a Sony RX1RM3 (RX1R III) that was language locked to Japan. After some digging and a lot of trial and error I found the following steps worked. I'm also including some additional instructions that may help others.

The specific Windows program versions are included in this repository, in case the ones people are sharing via Box links and whatnot are taken down or expire.

This is the video I followed - https://www.youtube.com/watch?v=BJhheKXs39A

Specifically the issue I ran into when following other instructions/videos online was after putting the camera into "service mode" via the Tweak menue, I had to select the now newly named Sony USB device and install the libusb driver a SECOND time. For some Sony cameras the second install doesn't seem to be necessary and putting it into service mode will work immediately.

If you'd prefer to use linux, you'll run into a weird axmlparserpy issue, but someone developed a workaround and documented it here: https://github.com/ma1co/Sony-PMCA-RE/issues/504#issue-2219426575 but this person wrote it up better here: https://www.reddit.com/r/RX100/comments/1pun1h5/how_i_finally_bypassed_the_japanonly_language/

Those last two links are archived here:
1. https://web.archive.org/web/20251211082802/https://github.com/ma1co/Sony-PMCA-RE/issues/504#issue-2219426575
2. https://web.archive.org/web/20260528013931/https://www.reddit.com/r/RX100/comments/1pun1h5/how_i_finally_bypassed_the_japanonly_language/
