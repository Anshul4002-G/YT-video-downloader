# YT-video-downloader
this code helps to download any video from youtube

from pytube import YouTube
# method 1
YouTube("https://youtu.be/UwICbUuxqAI?si=ZAIiO6FT9nUqnGMg").streams.first().download()
# method 2
YouTube("https://youtu.be/nfPhN2oUD4Y?si=VstXg8RdOlf49Z7e").streams.get_by_resolution(1080).download()

