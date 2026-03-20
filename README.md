# ai-gallery-system
Great — here is a **clear, practical step-by-step guide** to turn the pieces you downloaded into a working **AI chat storefront for your stained glass gallery**. I designed it so someone with **basic computer skills can set it up in a few hours.** 🌞🪟

---

# Step-by-Step Setup Guide

## AI Gallery System for Selling Handmade Stained Glass

This guide connects the three things you downloaded:

1. Inventory spreadsheet
2. AI gallery assistant prompt
3. Gallery webpage

And links them to **PayPal payments**.

---

# STEP 1 — Prepare Your Inventory Spreadsheet

Open the file you downloaded:

```
stained_glass_inventory_template.xlsx
```

You can open it in:

* Microsoft Excel
* LibreOffice Calc
* Google Sheets

---

### Add your pieces

Fill in one row for each suncatcher.

Example:

| ID    | Title          | Price | Size | Description            | Image URL  | PayPal Link | Tags            | Available |
| ----- | -------------- | ----- | ---- | ---------------------- | ---------- | ----------- | --------------- | --------- |
| SG001 | Blue Dragonfly | 32    | 5 in | cobalt glass dragonfly | image link | PayPal link | blue, dragonfly | Yes       |

---

### Important columns

**Image URL**

Link to the photo.

Example:

```
https://yourwebsite.com/images/dragonfly.jpg
```

---

**Tags**

Example:

```
blue, dragonfly, nature
```

These help the AI recommend pieces.

---

**Available**

```
Yes
```

When something sells:

```
No
```

The AI stops offering it.

---

# STEP 2 — Upload Your Images

Each item needs a public image link.

Easy options:

* your website
* Google Drive public link
* Imgur

Example link:

```
https://i.imgur.com/dragonfly.jpg
```

Paste this into the **Image URL column**.

---

# STEP 3 — Create PayPal Payment Links

Log into **PayPal**.

Go to:

```
Pay & Get Paid
↓
PayPal Buttons
↓
Buy Now
```

Fill in:

* item name
* price
* shipping

PayPal generates a purchase link.

Example:

```
https://paypal.com/pay/dragonfly
```

Paste this into the **PayPal Link column**.

---

# STEP 4 — Create the AI Gallery Assistant

Open the file you downloaded:

```
ai_gallery_assistant_prompt.md
```

Copy the entire prompt.

---

### Create the assistant

Go to **OpenAI ChatGPT:

```
Explore GPTs
↓
Create GPT
```

Paste the prompt into the **instructions section**.

---

### Upload your inventory

Upload your spreadsheet file.

The AI can now read your inventory.

It will:

* show pieces
* recommend pieces
* send PayPal links

---

# STEP 5 — Test the AI Gallery

Ask the assistant questions like:

```
show blue stained glass
```

```
what bird designs do you have
```

```
what is under $40
```

It should respond with your pieces.

---

# STEP 6 — Publish Your Chat Link

When the assistant works, click:

```
Share GPT
```

Copy the link.

Example:

```
https://chat.openai.com/g/g-stained-glass-gallery
```

This is now your **AI storefront**.

---

# STEP 7 — Use the Gallery Webpage

Open the file:

```
stained_glass_gallery_layout.html
```

You can edit it in:

* Notepad
* VS Code
* any text editor

---

### Insert your chat link

Replace this section:

```
CHAT LINK HERE
```

With your assistant URL.

Example:

```
https://chat.openai.com/g/g-stained-glass-gallery
```

---

# STEP 8 — Put the Site Online

Upload the webpage to:

* your website
* GitHub Pages
* Netlify

Now visitors see:

```
Chat with the stained glass gallery assistant
```

---

# STEP 9 — Add New Suncatchers

Whenever you make a new piece:

1. upload photo
2. add row to spreadsheet
3. add PayPal link
4. add tags

That's it.

The AI will now sell it.

---

# STEP 10 — When Something Sells

Change:

```
Available → No
```

The AI immediately stops offering it.

---

# Example Customer Conversation

Customer

```
show bird designs
```

AI

```
I currently have a Cardinal stained glass panel available.
```

Customer

```
show it
```

AI shows image.

Customer

```
I want it
```

AI sends PayPal link.

---

# Weekly Maintenance

You only need to do:

```
add new pieces
mark sold pieces
```

Everything else runs automatically.

---

# Optional Improvements (Later)

You can later add:

* Facebook Messenger AI replies
* Pinterest auto-posting
* AI posting new pieces
* collector email list

But none of that is required to start.

---

# What You Now Have

You now have a **complete AI gallery system** that:

✔ shows your stained glass
✔ recommends pieces
✔ chats with buyers
✔ sends PayPal checkout links
✔ updates inventory

And it works **24/7**.

---

If you'd like in the future, I can also show you **one advanced improvement that dramatically increases sales** for systems like this:

👉 an **AI “gallery discovery” system that brings buyers to the chat automatically** (without Etsy or paid ads).

But for now you have everything needed to **launch your AI stained glass storefront.** 🌞🪟
