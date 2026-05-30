# 🎮 Hyper Shivaa's Website Editing Guide (No Coding Needed!)
Welcome, Shivaa! This guide was made specifically for you so you can easily update, change, and manage everything on your link-tree website while your friend is away.
You **do not need any coding experience** to do this. All you need to know is how to use **Find (Ctrl + F)** to look for specific words and replace them.
## ⚠️ THE GOLDEN RULES (Read this first!)
 * **CRITICAL FILE NAME RULE:** If you ever replace, rename, or upload a new main website file, it **STRICTLY** must be named exactly **index.html** (with a small lowercase **i**). If you capitalize it as Index.html or change the name, your website will instantly break and show a *404 Not Found* error.
 * **📦 FILE BACKUP LOCATION:** A complete backup copy of your original website (which still includes the original live sponsor menu) is safely stored inside the **backups** folder in your repository.
## 🛠️ How to Edit Your File on GitHub
 1. Open your repository on **GitHub**.
 2. Click on your main website file: **index.html**.
 3. Click the **Pencil Icon (Edit this file)** in the top right corner.
 4. Press **Ctrl + F** (or **Cmd + F** on Mac) to open the search bar. Use this to find the exact lines listed below!
 5. After making your updates, scroll down, click the green **Commit changes** button, and your website will update live!
## 🎨 1. Changing the Default Background Theme
When someone opens your website, it loads a default color theme. Right now, it is set to arctic-ice. You can change this to any of the 15 custom themes built right into your code.
**How to change it:**
 1. Press **Ctrl + F** and search for: data-theme=
 2. You will find this line near the top of the body section:
```html
<body data-theme="arctic-ice">

```
 3. Change "arctic-ice" to any theme name from the list below. **Make sure to keep the quotation marks ""!**
### Available Theme Names to Choose From:
 * cyber-red *(Futuristic neon red & dark purple)*
 * neon-blue *(Clean sci-fi blue)*
 * gaming-green *(Razer-style gaming green)*
 * golden-king *(Luxury gold and dark stealth tones)*
 * galaxy-purple *(Deep space cosmic purple & pink)*
 * fire-orange *(Hot streaming flame orange)*
 * arctic-ice *(Bright, clean glacial light blue)*
 * sakura-pink *(Light aesthetic Japanese anime pink)*
 * midnight-teal *(Deep ocean neon teal)*
 * blood-moon *(Aggressive dark vampire red)*
 * emerald *(Bright Matrix-style cyberpunk green)*
 * solar-white *(Clean minimalist white with red accents)*
 * phantom-black *(Pure stealth obsidian black and white)*
 * indian-saffron *(Saffron, white, and emerald green accents)*
 * neon-pink *(Vibrant electric arcade pink)*
*Example: To switch to the aggressive dark red theme, change the line to:* <body data-theme="blood-moon">
## 👤 2. Changing Profile Picture, Name, and Bio
### Changing your Profile Picture
 1. Search for: class="avatar-img"
 2. Look at the link inside the src="..." right next to it:
```html
<img class="avatar-img" src="https://cdn.discordapp.com/attachments/..."

```
 3. Replace that long URL inside the quotation marks with your new image link. *(Tip: You can upload an image to a private Discord channel, right-click it, and click **Copy Link** to get a working image URL!)*
### Changing your Name & Handle
 1. Search for: class="name" and change the text inside the brackets:
```html
<h1 class="name">HYPER SHIVAA</h1>

```
 2. Search for: class="handle" and update your username handle:
```html
<p class="handle">@hypershivaa</p>

```
### Changing your Bio Text & Stream Schedule
 1. Search for: class="bio"
 2. Change your status text safely:
```html
<p class="bio">🎮 Content Creator &amp; Gamer · Mobile Legends · West Bengal, India<br>live at 4:45 Indian TZ 🔥</p>

```
*Note: Do not delete the <br> code. It simply tells the browser to start a new line of text.*
## 🔗 3. Updating and Changing Social Media Links
All your standard social media buttons (YouTube, Instagram, Facebook, Discord) share this exact layout in the code:
```html
<a class="link-btn" href="YOUR_SOCIAL_LINK_HERE" target="_blank" rel="noopener">
  <div class="link-icon">ICON</div>
  <div class="link-label">
    MAIN TITLE
    <span class="link-sub">SUBTITLE TEXT</span>
  </div>
  <span class="link-arrow">→</span>
</a>

```
### How to update them:
 1. Search for the name of the app you want to update (e.g., Instagram or YouTube).
 2. Swap out the URL inside the href="..." quotation marks with your updated link.
 3. You can freely change the **MAIN TITLE** or **SUBTITLE TEXT** lines to say whatever you like!
## 💎 4. The Sponsor Menu (Dab Arcade)
Your sponsor button features special animated glow and jitter styles to stand out from regular buttons.
> ### ⚠️ IMPORTANT NOTE ON THE SPONSOR MENU:
> The active sponsor menu block has been **temporarily removed** from your live homepage file. If a new sponsor comes on board or you want your original layout back, you have **two easy ways** to restore it:
> 
### Method A: Manually Paste the Code Back In
 1. Open your index.html file to edit.
 2. Search for the phrase: </div> *(or simply find your very last social link button, like Discord)*.
 3. Copy the clean code block below and paste it **directly above that final closing </div>** tag:
```html
    <a class="link-btn sponsor-btn" href="https://dabarcade.in/" target="_blank" rel="noopener">
      <span class="sponsor-badge">🔥 SPONSOR</span>
      <div class="link-icon">💎</div>
      <div class="link-label">
        Dab Arcade — Top Up Diamonds
        <span class="link-sub">Mobile Legends · Cheapest ML Diamonds!</span>
      </div>
      <span class="link-arrow">→</span>
    </a>

```
 4. If you get a new sponsor, just change https://dabarcade.in/ to your new sponsor's link, and update Dab Arcade to their company name!
### Method B: Use the Backup File
If you get confused pasting code, you can completely replace your main file using the backup folder:
 1. Go into the backups folder in your repository.
 2. Copy its contents.
 3. Paste it over everything in your main directory.
 4. **STRICTLY** make sure the final saved file is named exactly **index.html** (all lowercase letters!).
## 📍 5. Changing Footer Text
At the very bottom of your screen, you can change your location details and copyright info.
 1. Search for: class="footer"
 2. Modify the text inside the element:
```html
<p class="footer">© 2026 Hyper Shivaa · Kolkata, West Bengal, India</p>

```
### 💡 Final Pro-Tip
Take your time! As long as you don't accidentally delete code characters like < or >, your site will work beautifully. Good luck with the streams! 🔥🕹️
