# Cam-Stream
A simple Flask App that streams your webcam


This app was originally made to stream a live stream of my 3d printer to my ip and then put on the web using cloudflared

If you want to host it on cloudflared or just want to acces your stream on https connection then here are the stpes

1 - Clone This repo by git clone https://github.com/The-UnknownHacker/Cam-Stream/ or downloading a zip
2 - Open the main.py file and run it
3 - Install cloudflared on your machine - https://developers.cloudflare.com/cloudflare-one/connections/connect-networks/downloads/
4 - Run the cloudflared tunnel by using this command  - cloudflared tunnel --url http://localhost:5000
