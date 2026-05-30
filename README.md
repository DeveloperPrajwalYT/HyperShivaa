File backup: In the backups folder
# 🎮 Hyper Shivaa's Website Editing Guide (No Coding Needed!)

Welcome, Shivaa! This guide is created specifically for you so you can easily manage, update, and change everything on your link tree website while your friend is away. 

You **do not need any coding experience** to do this. All you need to know is how to use **Find (Ctrl + F)** to look for specific words and replace them.

---

## 🛠️ How to Edit Your File
1. Open your repository on **GitHub**.
2. Click on your website file (usually named `index.html`).
3. Click the **Pencil Icon (Edit this file)** in the top right corner.
4. Press **Ctrl + F** (or **Cmd + F** on Mac) to open the search bar. This is how you will find the exact lines to change!
5. After making changes, scroll to the bottom, click **Commit changes**, and your website updates instantly!

---

## 🎨 1. Changing the Default Background Theme
When someone opens your website, it loads a default theme. Right now, it is set to `arctic-ice`. You can change this to any of the 15 custom themes built into your site.

**How to change it:**
1. Press **Ctrl + F** and search for: `data-theme=`
2. You will find this line:
   ```html
   <body data-theme="arctic-ice">

 3. Change "arctic-ice" to any theme name from the list below. Make sure to keep the quotation marks ""!
### Available Theme Names to Choose From:
 * cyber-red (Futuristic neon red/dark purple)
 * neon-blue (Clean sci-fi blue)
 * gaming-green (Razer style green)
 * golden-king (Luxury gold and dark tones)
 * galaxy-purple (Deep space purple and pink)
 * fire-orange (Hot flame orange)
 * arctic-ice (Bright, clean light blue)
 * sakura-pink (Light aesthetic Japanese pink)
 * midnight-teal (Deep ocean neon teal)
 * blood-moon (Aggressive dark vampire red)
 * emerald (Bright matrix green)
 * solar-white (Clean minimalist white and red)
 * phantom-black (Pure stealth black and white)
 * indian-saffron (Saffron, white, and green accents)
 * neon-pink (Vibrant electric pink)
*Example: To change your site to the aggressive red theme, change it to <body data-theme="blood-moon">.*
## 👤 2. Changing Profile Picture, Name, and Bio
### Changing your Profile Picture
 1. Search for: class="avatar-img"
 2. Look at the src="..." part right next to it:
   ```html
   <img class="avatar-img" src="[https://cdn.discordapp.com/attachments/](https://cdn.discordapp.com/attachments/)..."
   
   ```
 3. Replace the long URL inside the quotation marks with your new image link (you can upload an image to Discord, right-click it, and click **Copy Link** to get a URL).
### Changing your Name & Handle
 1. Search for: class="name"
 2. Change the text between the brackets:
   ```html
   <h1 class="name">HYPER SHIVAA</h1>
   
   ```
 3. Search for: class="handle" and change your username:
   ```html
   <p class="handle">@hypershivaa</p>
   
   ```
### Changing your Bio Text & Live Timing
 1. Search for: class="bio"
 2. Change the text inside it:
   ```html
   <p class="bio">🎮 Content Creator &amp; Gamer · Mobile Legends · West Bengal, India<br>live at 4:45 Indian TZ 🔥</p>
   
   ```
   *Note: Leave the <br> as it is—it just means "start a new line".*
## 🔗 3. Updating and Changing Social Media Links
All your standard social buttons (YouTube, Instagram, Facebook, Discord) look exactly like this block of code:
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
### How to change an existing social link:
 1. Search for the name of the social platform (e.g., Instagram or YouTube).
 2. Change the link inside href="..." to your new profile link.
 3. Change the **MAIN TITLE** or **SUBTITLE TEXT** to whatever you want.
## 💎 4. The Sponsor Menu (Dab Arcade)
Your sponsor menu has special animations (glow and jitter) to make it stand out.
### How to change the Sponsor Link or Details:
 1. Search for: SPONSOR — Dab Arcade
 2. You will see this block of code:
   ```html
   <a class="link-btn sponsor-btn" href="[https://dabarcade.in/](https://dabarcade.in/)" target="_blank" rel="noopener">
     <span class="sponsor-badge">🔥 SPONSOR</span>
     <div class="link-icon">💎</div>
     <div class="link-label">
       Dab Arcade — Top Up Diamonds
       <span class="link-sub">Mobile Legends · Cheapest ML Diamonds!</span>
     </div>
     <span class="link-arrow">→</span>
   </a>
   
   ```
 3. Change href="https://dabarcade.in/" to your new sponsor's link if you get a new one.
 4. Replace Dab Arcade — Top Up Diamonds with the new sponsor's name, and update the subtitle message below it.
### 🔄 How to Bring Back the Sponsor Menu if it gets deleted:
If you accidentally delete your sponsor container or want to add a brand new one back later, follow these steps:
 1. Search for: </div> right above the footer section, or just find the end of your links-section.
 2. Look for the closing </div> that ends the links block.
 3. Copy the clean code block below and paste it **right above that final closing </div>** (just before the footer section):
```html
    <a class="link-btn sponsor-btn" href="PUT_NEW_SPONSOR_LINK_HERE" target="_blank" rel="noopener">
      <span class="sponsor-badge">🔥 SPONSOR</span>
      <div class="link-icon">💎</div>
      <div class="link-label">
        SPONSOR NAME HERE
        <span class="link-sub">Sponsor descriptive text or promotion goes here!</span>
      </div>
      <span class="link-arrow">→</span>
    </a>

```
## 📍 5. Changing Footer Text
At the very bottom of the file, you can change your copyright and location info.
 1. Search for: class="footer"
 2. Modify the text inside:
   ```html
   <p class="footer">© 2026 Hyper Shivaa · Kolkata, West Bengal, India</p>
   
   ```
That's it! Take your time, don't delete any characters like < or >, and your site will look good👍 
