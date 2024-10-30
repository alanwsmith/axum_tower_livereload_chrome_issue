# axum tower_liverealod chrome issue

This is a test repo to verify behaviour I'm seeing. 
It contains several static HTML files. If I start
the server with `cargo run` and then click around
on: 

http://localhost:3232

things work fine in Firefox, but after following
a few link in Google Chrome on my Mac the browser
hangs for several seconds. It clears after a bit
but then hangs again when moving around links
quickly. 

I'm on Google Chrome:

Version 130.0.6723.70 (Official Build) (arm64)

On a Mac running:

macOS 14.5 (23F79)

If I remove the .layer(livereload) line 
I can click as fast as I can on the links and
the browser never hangs. 





