# DFL2.0_W_Extra
Just added a few extra scripts to the bottom of the DFL 2.0 Colab to make people's lives easier

Everything is the same but I added an Extra tab at the bottom that implements FFMPEG and Youtube-DL to make out lives easier. 

What it includes:
1. Youtube-DL which allows you to download videos from (obviously youtube) and many other adult sites like Pornhub.com. I'll also add that it will automatically save as "data_src.mp4" for ease, but if you'd rather it be "data_dst.mp4" just rename it. You'll be fine. I also made sure it sticks to the .mp4 format since that's what we'll be using for DFL.

2. I added a ffmpeg script that will split the video file named "data_src.mp4" into 5 minute segments. Bypassing you doing this manually in a video editor. So whatever section you want to be working on; just rename it to data_src/data_dst.mp4.

3. And since the only script in the Colab is based on files which already exist in the folder heirarchy, I added a upload to Google Drive at the bottom so you can upload any file in your project (like the split video files) into your google drive.


Why did I make this?

Because it already existed via code, but so many of us would us it in the terminal outside of Colab or use a video editing program. So this was an obvious way to improve the Colab and make our lives easier when making different facesets. There's nothing more annoying than waiting 5 minutes to upload something from your computer to Colab so hopefully this will take out that irritation. 

How do I use this?

I didn't want to host my own Colab on Google Drive so I just uploaded the ipynb file to github. It's easy to use, just download this file and open Google Colab. From there just click "File" then "Upload Notebook." (If someone wants to host the Colab file, that's fine by me.)
Eh, screw it. Here you go lol I love you guys.
https://colab.research.google.com/drive/1Im4FvbXS0arXmDjtU7mk_lj10WX1cF4T?usp=sharing

(If something isn't working like the privacy settings or something similar, let me know either on Github or in the MrDeepFakes forums.)
