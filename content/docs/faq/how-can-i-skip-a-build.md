## How can I skip a build

Not every commit might need a build on wercker, for instance when you’re working
on a README or other type of documentation.

In order to skip a build you can include `[ci skip]` or `[skip ci]` anywhere in
your commit message.

Wercker will mark this build as aborted in your feed and build list.
