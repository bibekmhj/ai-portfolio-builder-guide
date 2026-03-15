# Full Guide: Build a Free Portfolio Website with Claude AI + Netlify

> Complete step-by-step instructions for students of any major.
> No coding experience required. Takes 30 minutes. 100% free.

---

## Table of Contents

1. [Why You Need a Portfolio Website](#why)
2. [What You Need](#what-you-need)
3. [Step 1: Sign Up for Claude](#step-1)
4. [Step 2: Generate Your Portfolio](#step-2)
5. [Step 3: Save Your HTML File](#step-3)
6. [Step 4: Deploy to Netlify](#step-4)
7. [Step 5: Customize Your URL](#step-5)
8. [Step 6: Update Your Resume & LinkedIn](#step-6)
9. [Customization Tips](#customization)
10. [FAQ](#faq)
11. [Troubleshooting](#troubleshooting)

---

## 1. Why You Need a Portfolio Website {#why}

- Recruiters spend **6 seconds** on an average resume
- A portfolio website gives you a **permanent, shareable link** to your work
- It works for **every major** — not just CS students
- It takes **30 minutes** to build and costs **$0**
- Less than **5% of students** have one — instant competitive advantage

---

## 2. What You Need {#what-you-need}

| Tool | Cost | Link |
|------|------|------|
| Claude AI | Free | https://claude.ai |
| Netlify | Free | https://netlify.com |
| GitHub (optional) | Free | https://github.com |
| Your resume | Already have it | — |
| 30 minutes | Free | — |

---

## 3. Step 1: Sign Up for Claude {#step-1}

1. Go to **https://claude.ai**
2. Click **"Sign up"**
3. Create a free account with your email
4. Verify your email address
5. You're ready!

**Time: 5 minutes**

---

## 4. Step 2: Generate Your Portfolio {#step-2}

1. Start a new Claude conversation
2. Click the **paperclip icon** and upload your resume (PDF or Word)
3. Copy and paste the Master Prompt from `prompts/master-prompt.txt`
4. Press Enter and watch Claude build your website
5. **Copy all the HTML code** Claude generates

**Customization:** Use prompts from `prompts/customization-prompts.txt` to refine the design.

**Non-CS students:** Use your field-specific prompt from `prompts/field-specific-prompts.txt`

**Time: 10 minutes**

---

## 5. Step 3: Save Your HTML File {#step-3}

### On Windows:
1. Open **Notepad**
2. Paste the HTML code
3. Click **File → Save As**
4. Change "Save as type" to **All Files**
5. Name the file **`index.html`**
6. Click Save

### On Mac:
1. Open **TextEdit**
2. Click **Format → Make Plain Text**
3. Paste the HTML code
4. Click **File → Save**
5. Name the file **`index.html`**
6. Make sure it doesn't save as `.html.txt` — check the extension

**Time: 2 minutes**

---

## 6. Step 4: Deploy to Netlify {#step-4}

1. Go to **https://netlify.com**
2. Click **"Sign up"** and create a free account (no credit card needed)
3. After logging in, click **"Add new site"**
4. Select **"Deploy manually"**
5. You'll see a drag-and-drop area
6. **Drag your `index.html` file** into the box
7. Wait 10–15 seconds
8. 🎉 Your site is live!

You'll get a URL like: `https://random-name-abc123.netlify.app`

**Time: 5 minutes**

---

## 7. Step 5: Customize Your URL {#step-5}

1. In your Netlify dashboard, click on your site
2. Click **"Site configuration"**
3. Click **"Change site name"**
4. Type something like `firstname-lastname` or `firstname-portfolio`
5. Click **Save**

Your new URL: **`https://yourname.netlify.app`**

This is what you'll add to your resume and LinkedIn.

**Time: 3 minutes**

---

## 8. Step 6: Update Your Resume & LinkedIn {#step-6}

### On your resume (at the top):
```
Your Name | yourname.netlify.app | linkedin.com/in/yourname
```

### On LinkedIn:
1. Go to your profile
2. Click **"Edit intro"**
3. Add your URL in the **Website** field
4. Save

### In your email signature:
```
Your Name
Portfolio: yourname.netlify.app
LinkedIn: linkedin.com/in/yourname
```

**Time: 5 minutes**

---

## 9. Customization Tips {#customization}

See `prompts/customization-prompts.txt` for the full list. Quick examples:

**Change colors:**
> "Change the color scheme to dark mode with green accents"

**Add a section:**
> "Add a Certifications section after Skills"

**Improve content:**
> "Rewrite my experience bullets to be more results-oriented"

**Add interactivity:**
> "Add a working contact form using Netlify Forms"

**To update your site after changes:**
1. Ask Claude to update the HTML
2. Save the new file as `index.html`
3. Go to Netlify → your site → **Deploys** tab
4. Drag the new file — updates instantly

---

## 10. FAQ {#faq}

**Q: Do I need to know how to code?**
No. Claude handles all the code. You just copy, paste, and upload.

**Q: Is Netlify really free forever?**
Yes. The free tier includes everything you need — hosting, HTTPS, custom subdomain, and form handling. No credit card required.

**Q: What if I don't like the design?**
Keep asking Claude to change it! Try: "Make it more modern", "Change to dark mode", "Make it more minimal". Iterate until you love it.

**Q: Can I use my own domain name (like myname.com)?**
Yes! Buy a domain from Namecheap (~$10/year) and connect it to Netlify for free in their dashboard under "Domain management".

**Q: My major isn't tech-related. Does this still work for me?**
Absolutely. See `prompts/field-specific-prompts.txt` for prompts designed for Business, Psychology, Design, Education, Pre-Med, Engineering, and Humanities students.

**Q: Can I update my portfolio later?**
Yes, easily. Update your resume → re-upload to Claude → regenerate HTML → drag new file to Netlify. Done in minutes.

**Q: Can I add my own photos or images?**
Yes. Ask Claude to add an `<img>` tag with a placeholder, then either host your image on a free service like Imgur or upload it alongside `index.html` in Netlify.

---

## 11. Troubleshooting {#troubleshooting}

**Problem: File saved as `index.html.txt` on Mac**
Solution: In TextEdit, go to Preferences → uncheck "Add .txt extension to plain text files". Then re-save.

**Problem: Website looks broken / unstyled**
Solution: Make sure you copied ALL the HTML, including the `<style>` section. Re-copy from Claude and make sure nothing was cut off.

**Problem: Netlify says "no HTML found"**
Solution: Make sure your file is named exactly `index.html` (lowercase, no spaces).

**Problem: Changes not showing after update**
Solution: Hard refresh your browser: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac). Or try opening in a new incognito window.

**Problem: Claude's output got cut off**
Solution: Ask Claude: "Please continue from where you left off" or "Please regenerate the complete HTML file again."

---

*Created by Bibek Maharjan | [INSERT LINKEDIN] | [INSERT MEDIUM]*
*Star this repo if it helped you! ⭐*
