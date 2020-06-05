PWAs aim to provide faster, more resilient, and more engaging web apps. Here are two simple faults that likely to happen in PWAs:

The simple PWA here doesn't work offline. I didn't precache the offline page during the service worker install. The offline page is displayed to users when they are offline. That makes PWAs work while not being a connection to the internet. We don't have the offline page, as a result, the PWA doesn't work offline.

The simple PWA here can't be added to the home screen and installed. I left out the display property in the manifest file, as a result, the install banner isn't shown to users.

So there are some faults in PWAs, as a result, some mutation operators can be defined based on them. I am looking for more faults, and particularly I hope to find the severe ones.