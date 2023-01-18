# neovim-rename-test
test to describe issue with lspsaga rename

Here is a video showing my problem:

https://user-images.githubusercontent.com/22821635/213165156-2f3dad39-0a3a-4feb-a079-998ffdfa8a62.mov

What is happening?

1. I'm renaming the function *double* to *doubleMe* which correctly renames it at the place of definition, and at the place of usage.
2. I'm seeing an additional screen after the renaming is done, prompting me to rename any additional occurancess of "double" after that.

What I find to be wrong?

1. I don't want to rename words across the whole project, I just want the variable rename (simple, as it was in the past)
2. I can't close the additional screens unless I do :q on them (selecting them 1 by one)
