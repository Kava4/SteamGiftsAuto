<h1 align="center" id="title">SteamGifts.com bot for Heroku</h1>

<p align="center"><img src="https://www.userlogos.org/files/logos/Deva/steamgifts1.png" alt="project-image"></p>

  
  
<h2>🧐 Features</h2>


*   SteamGifts auto giveaway
*   Runs 24/7
*   Deployable on Heroku



<h2>🛠️ Installation Steps:</h2>

<p>1. Sign in on SteamGifts.com</p>

<p>2. Find PHPSESSID cookie in your browser.</p>

```
Use Cookie-Editor extension
```

<p>3. Create new app on Heroku.</p>

<p>4. Copy this repo to your new app.</p>

<p>5. In app settings create Config Vars:</p>

cookie
```
With the value of your PHPSESSID cookie
```
pages
```
With the number of the pages you want to go through
```

<p>8. Use Heroku Scheduler Add-on to run following command on your preferred schedule:</p>

```
python3 main.py
```