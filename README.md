# Clang Format Sample

This repo is meant to help generate a .clang-format file for the Gluster
project. Please send pull request to the .clang-format sample with your
changes. Once your change is merged, we'll run the following

    clang-format dht-common.c > formatted-dht-common.c

Then, we'll commit and push the code. This will update the
formatted-dht-common.c with the latest suggestions. This repo currently has the
original suggestions from [bug
1564149](https://bugzilla.redhat.com/show_bug.cgi?id=1564149) as best as
I could translate them. Please correct me if I'm wrong.
