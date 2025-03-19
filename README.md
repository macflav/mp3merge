Command line user-friendly interface to merge mp3 files.

Manually using ffmpeg can be a bit tricky, and other solutions might inject unwanted metadata on the final product, so I wrote this little script to make my life easier :)
Hopefully it could benefit other people out there :)

All the user needs to do is select files from a menu.

It works best if located somewhere within the system PATH (suggestion: $HOME/.local/bin)

Dependencies are 'fzf' and 'ffmpeg'.

Thanks to Derek Taylor (DT) for the inspiration on using fzf as a menu selector.
