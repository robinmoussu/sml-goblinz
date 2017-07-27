# sml-goblinz
A test of the awesome new boost.sml library candidate

This is my first attempt at using the awesome-looking boost sml state machine library.

It tests the interaction between asynchronous coding with asio and sml.

Please by all means update this project if there is a more correct way to do something with SML.

to build:

install cmake

```
cmake -H<source_dir> -B<build_dir>
cd <build_dir>
make
./goblinz
```

The cmake script will download all dependencies automatically via the incredible Hunter addon.

This project has been edited with clion. The .gitignore should be sufficient to prevent object files leaking back into the source tree.

#Rules of the game

A goblin, "gobbo" is born. He then kills a human every 200ms.

When a sufficient number of humans have been killed, he spontaneously dies!

After a while, his memory is forgotten.

Then the game ends.

Pretty cool, eh? I reckon I could sell this...
