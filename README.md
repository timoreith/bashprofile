# mybashprofile
My personal bash profile backup

To include a custom profile, append this to ~/.profile:

if [ -f "$HOME/[path]/.mybashprofile" ]; then
    . "$HOME/[path]/.mybashprofile"
fi
