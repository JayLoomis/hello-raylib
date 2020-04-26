# hello-raylib
A repository for an iterative, explorative game using Raylib.

Why Raylib? I've been playing around with Godot and dipping my toes in other,
modern game engines. The problem is that they all provide so much more than I
need, and their structure adds complexity to my process. Raylib provides the
system abstraction and hardware acceleration that I want without trying to tell
me how to structure or create my game (and without the assumption of what kinds
of games I want to make with it.

We'll see how it goes.

## How did I set this thing up?
Here's how to be able to repeat what I've done here to make other games with
Raylib:

1.  Build Raylib locally:
    -   The short answer is that I followed the instructions
        for working on macOS on the
        [Raylib wiki](https://github.com/raysan5/raylib/wiki/Working-on-macOS).    
        I am useing VSCode, and the wiki also has handy
        [instructions for that](https://github.com/raysan5/raylib/wiki/Using-raylib-in-VSCode).
        Read on for my own notes about the process.
    -   I tried using the prebuilt library by installing via Homebrew, but what
        you get from `brew` is very different from what you have when you clone
        the repo and build locally. The build your own from master solution is
        what the instructions (for VSCode, for example) assume. While I could
        figure out how to ake everything work with the ostensibly easier
        Homebrew install, it turns out it would be more work than building the
        libraries myself.
    -   Some of the names in the instructions are out of sync with reality.
        Don't sweat it! The goods build in `[repo-root]/src`.


<!--
----|----1----|----2----|----3----|----4----|----5----|----6----|----7----|----8
         0         0         0         0         0         0         0         0
-->
