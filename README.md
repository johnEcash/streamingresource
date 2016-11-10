# streamingresource
resources for livestreaming and online playback

# Scripts
- setup-basic will build nginx + rtmp module following this tutorial:<br> 
https://obsproject.com/forum/resources/how-to-set-up-your-own-private-rtmp-server-using-nginx.50/ <br>
make it executable and run as sudo <br>
<br>
- generateconfig is used to change nginx.conf<br>
usage: ./generateconfig Configname.conf, this will swap out the nginx configuration with the selected.<br>
added is setup-basic-config, this is the standard config after running the setup-basic script



# tools and programs:
* nginx
* nginx-rtmp-module
* ffmpeg
* hls / dash
* html5 playback
* OBS broadcaster

# Links:
https://www.nginx.com/blog/scalable-live-video-streaming-nginx-plus-bitmovin/ <br>
https://obsproject.com/forum/resources/how-to-set-up-your-own-private-rtmp-server-using-nginx.50/ <br>
https://github.com/arut/nginx-rtmp-module <br>
https://www.ffmpeg.org/ <br>
https://github.com/Eyevinn/docker-dash-packager
