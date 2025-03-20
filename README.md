Bash script that presents a user-friendly interface to merge mp3 files.

![image](https://github.com/user-attachments/assets/25db8acb-25f4-4336-b187-d1c6b984ad31)

Using ffmpeg on the command line can be a bit tricky, and other free solutions usually inject unwanted metadata on the final result file, so I wrote this little script to make my life easier :)
Hopefully it could benefit other people out there too.

All the user needs to do is run it from the directory containing the mp3 files, and select the ones to be merged from the menu that will show up.

Naturally, it works best if the script (mp3merge file -- or a link to it) is located somewhere within the system PATH (suggestion: $HOME/.local/bin).

Dependencies are 'fzf' (for the selection menu) and 'ffmpeg' (for the actual merging routine).

Thanks to Derek Taylor (DT) for the inspiration on using fzf as a menu selector. Make sure to check out his video https://youtu.be/Ya_0p_MkxhE?si=XuTZrpDVgqLALcTy
