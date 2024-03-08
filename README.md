# 100devs transcripts

Go to the output directory for cohort 2 transcripts.

## commands

`yt-dlp --yes-playlist --write-subs --write-auto-subs --sub-langs "en*" --skip-download -i <PlaylistUrl>`

`find ./tmp -name "*.vtt" -exec python vtt2text.py {} \;`

`mv tmp/*.txt output/`
