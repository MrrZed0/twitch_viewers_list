Twitch Viewer List In HTML Using Twitch API

Step By Step Video Guide: https://youtu.be/CR7LHpdVEig

------------
Requirements
------------
- Twitch Channel ID Finder: https://streamscharts.com/tools/convert-username
- Access Token & Client ID Finder: https://twitchtokengenerator.com/
- OBS-Studio or StreamElements


-------------------------------
How To Get Token And Client ID:
-------------------------------
1) Go To https://twitchtokengenerator.com/
2) Click On Bot Chat Token
3) Authorize With Twitch
4) Do The I'm Not A Robot
5) Now Scroll Down To 'Select All' And Click On Select All
6) Now Click On The Blue Request Token!
7) Enter Your Twitch Username And Email
8) Check Your Email {Spam Folder Too}
9) Copy The URL From The Box And Paste Into Browser
10) Scroll Down To Everything Looks Good
11) You Should Get A Email With Your Token And Client ID


---------------------------------------------------
How To Get My Twitch Channel ID & Modrator User ID:
---------------------------------------------------
1) Go To https://streamscharts.com/tools/convert-username
2) Enter Your Twitch Username
3) Click The Button
4) Copy Your ID



-------------
How To Setup:
-------------
1) Download The viewers_list.htm file
2) Place It Inside Your OBS-Studio Install [C:\Program Files\obs-studio]
3) Right Click On viewers_list.htm > Open With > Notepad
4) Now Replace The Twitch Client ID, Twitch Access Token, Twitch Channel ID, Moderator User ID With Your Own  [Twitch ID & Moderator ID Is The Same]
   ``` 
        const CLIENT_ID = "ENTER TWITCH CLIENT ID HERE"; // Twitch Client ID
        const ACCESS_TOKEN = "ENTER YOUR TWITCH ACCESS TOKEN HERE"; // OAuth Token
        const BROADCASTER_ID = "ENTER YOUR TWITCH ID HERE"; // Your Twitch Channel ID
        const MODERATOR_ID = "ENTER YOUR TWITCH ID HERE"; // Your Moderator User ID
        const REFRESH_INTERVAL = 10000; // Update every 30 seconds
   ```
   5) Now Save The File
   6) Now Open Up OBS-Studio or StreamElements
   7) Click On Docks > Custom Browser Docks
   8) Under Dock Name Enter Twitch Viewer List
   9) Under URL Enter C:\Program Files\obs-studio\viewers_list.htm
   10) Click On Apply



![Test Image 1](https://github.com/MrrZed0/twitch_viewers_list/blob/main/Untitled.jpg?raw=true)
