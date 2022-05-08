# <img src="https://user-images.githubusercontent.com/79321771/154670474-5407d2d2-8e29-41b3-a3fc-674f795425f5.png">
<p align=center><a href="https://heroku.com/deploy?template=https://github.com/yunus-25jmi/Rclone-Heroku/"><img src="https://www.herokucdn.com/deploy/button.svg" width="200"></a></p>
<b>Simple docker based workflow to run a rclone server on heroku any vps (only which supports docker). Also this is running rclone web gui as a user interface, so it's very easy to use this</b>

- watch this video on how to setup rclone web gui on AWS - <a href="https://youtu.be/GYLscUPs2Sw">Click here</a>
- watch this video on how to setup this workflow - <a href="">will be soon</a>
- default password and username is ``` admin ```

# Configuration
- `CONF_BASE64` - Your pre-configured ***rclone.conf*** encoded by base64. You can use any tool (ex: https://da.gd/base64)
- `USERNAME` - Any self specified username.
- `PASSWORD` - Any self specified password.

# Deployment
- Generate your rclone.conf file locally from this <a href="http://www.youtube.com/watch?v=n8qghZC1Kuc">video.</a> (if you have a rclone.conf file skip this step)

- Just click deploy button, fill envs and deploy it. 

- Go to resources tab and check if the dyno is on if it isn't just turn it on and click view app from more options menu. 

# Notes
- Your ***rclone.conf*** file is a must and there is no way to generate new configs for some oath systems like google drive from web gui. ***(<a href="https://github.com/rclone/rclone-webui-react/issues/43">issue on github of web-gui</a>)***
- After they fixed it I just need to register ```53682``` port on heroku and it will be solved! 
- ```This is still under development :D```
<br>
<p align=center><a href="https://www.reddit.com/u/poppitxd/"><img src="https://telegra.ph/file/c4d5c54694f322ff91079.png" width="140"></a></p>
