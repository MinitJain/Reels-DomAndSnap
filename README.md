# Reels-DomAndSnap

I built this as a Reels-style video feed using pure HTML, CSS, and JavaScript.

HTML: I created a simple container (.allReels) where all reels are rendered dynamically.

JavaScript:

I stored all reel data (video, likes, follow state, mute state, captions, etc.) in a single reels array.

Using addData(), I loop through this array and generate the entire UI with template literals.

I used event delegation on .allReels to handle likes, follow/unfollow, and mute/unmute efficiently.

Every interaction updates the data first, then re-renders the UI to keep everything in sync.

CSS:

I used scroll-snap to mimic Instagram-style vertical scrolling.

Absolute positioning and gradients were used for overlays (user info, icons, captions).
