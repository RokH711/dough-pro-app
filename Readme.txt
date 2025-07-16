Dough Pro: Your Baking Companion
=================================

A simple, intuitive web application designed to help home bakers manage their sourdough and other bread-making processes, from recipe formulation to timing and bake logging.

Features:
---------
* **Recipe Calculator:** Input your ingredients (flour, water, salt, starter, other) and instantly see hydration and salt percentages.
* **Ingredient Scaling:** Easily scale your recipe to a desired total flour weight.
* **Smart Timers:** Dedicated timers for Bulk Fermentation, Stretch & Folds (up to 4), and Final Proof.
* **Repeating Alarms:** Timers will provide a voice alert followed by a continuous audible alarm until manually paused or reset.
* **Temperature Conversion:** Seamlessly convert temperatures between Celsius (°C) and Fahrenheit (°F) across all relevant input fields.
* **Proofing Suggestions:** Get suggested final proof times based on ambient temperature and cold proofing preference.
* **Bake Log & Notes:** Record your oven settings, internal dough temperature, and detailed notes for each bake.
* **Photo Upload:** Attach a photo of your baked bread to your bake log for visual reference.
* **Saved Bakes:** All your bake details, including recipes, notes, and photos, are saved locally in your browser for future reference. You can view, load, and delete past bakes.
* **User-Friendly Interface:** Clean and responsive design using Tailwind CSS, optimized for both desktop and mobile.

How to Use:
-----------
1.  **Recipe Tab:** Enter your ingredient weights. The hydration and salt percentages will update automatically. You can also use the "Scale Recipe" feature to adjust quantities.
2.  **Timers Tab:** Set durations for your bulk fermentation, stretch & folds, and final proof. Click "Start" to begin a timer. "Pause" will temporarily stop it, and "Reset" will clear it. Alarms will repeat until paused or reset.
3.  **Oven & Notes Tab:** Record your oven preheat, covered/uncovered bake temperatures and times, and final internal dough temperature. Add detailed notes about your bake and upload a photo. Don't forget to give your recipe a name and click "Save Bake Details & Recipe"!
4.  **Saved Bakes Tab:** View a list of all your saved bakes. Click "View Details" to load a past bake's information into the Recipe and Oven & Notes tabs. Click "Delete" to remove a bake log.

Local Setup (Running the App on Your Computer):
----------------------------------------------
1.  **Save the file:** Save the entire HTML code (e.g., `index.html`) to a file on your computer.
2.  **Open in Browser:** Double-click the `index.html` file. It will open in your default web browser, and the app will be fully functional.

Deployment (Making the App Live on the Web):
-------------------------------------------
This app is a static site (HTML, CSS, JavaScript). The easiest way to deploy it is using a static site hosting service.

**Recommended: GitHub Pages**
1.  **Create a GitHub Repository:** Create a new **public** repository on GitHub (e.g., `dough-pro-app`).
2.  **Upload `index.html`:** Upload your `index.html` file directly to the `main` (or `master`) branch of this repository.
3.  **Enable GitHub Pages:**
    * Go to your repository on GitHub.
    * Click **"Settings"** -> **"Pages"**.
    * Under "Source," select **"Deploy from a branch"**.
    * Choose your `main` branch and select the `/root` folder.
    * Click **"Save"**.
4.  **Access Your App:** GitHub will provide a URL (e.g., `https://yourusername.github.io/dough-pro-app/`) where your app will be live within a few minutes.

**Alternatives:** Netlify, Vercel, or other static site hosting providers offer similar easy deployment processes by connecting to your GitHub repository.

Support Dough Pro:
-----------------
If you find Dough Pro useful and would like to support its development, you can make a donation here:

❤️ **[https://ko-fi.com/rokh321836](https://ko-fi.com/rokh321836)**

Acknowledgements:
----------------
* **Tailwind CSS:** For the utility-first CSS framework.
* **Mixkit:** For the free alarm clock sound effect (mixkit-analog-alarm-clock-bell-1456.mp3).
* **Web Speech API:** For the text-to-speech functionality.
* **Local Storage API:** For saving bake logs directly in the browser.

Enjoy your baking with Dough Pro!
```