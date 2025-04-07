# Archiving Hillside Hermitage
A guide on how to archive Hillside Hermitage/Samanadipa content

## Download all videos from a channel:
The following links provide all the videos from each channel as a playlist in order of most recent to least recent.

HH: https://www.youtube.com/playlist?list=UUKejmWAt_kNpRMq5gQEGAqw
SD: https://www.youtube.com/playlist?list=UUJqF_kQbrhBX4Wl_k0V1n8g

If you have youtube premium, you can download these playlists to your device.

Otherwise one can download them on Mac/Linux with the yt-dlp commandline tool. The following commands downloads the HH and SD content as mp3s

yt-dlp --extract-audio --audio-format mp3 -o "%(playlist_index)s - %(title)s.%(ext)s" "https://www.youtube.com/playlist?list=UUKejmWAt_kNpRMq5gQEGAqw"

yt-dlp --extract-audio --audio-format mp3 -o "%(playlist_index)s - %(title)s.%(ext)s" "https://www.youtube.com/playlist?list=UUJqF_kQbrhBX4Wl_k0V1n8g"
