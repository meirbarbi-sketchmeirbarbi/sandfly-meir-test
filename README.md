# sandfly-meir-test

Unofficial, experimental personal build of the open-source SandFly screen reader (https://github.com/aaron-gh/SandFly, Apache License 2.0), based on tag v0.5.0, commit 1547dd63bbced659e9cbeb712c607d28c2b4b566.

This repository holds only a patch and a build workflow. The patch makes a separate app (package `io.github.aaron_gh.sandfly.meirtest`, label "SandFly Meir Test") that tries to keep the service running with a quiet ongoing notification. It also turns off the official updater and low-latency audio by default. It changes no vibration or sound files.

This is not an official SandFly release and is not supported by its authors. It is untested on a device. All original copyright and license notices of SandFly apply.
