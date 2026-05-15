# Affiliate Creatives Setup Guide for Admin

## Overview

This guide explains how to set up embedded instructions so affiliates know exactly how, where, and why to use each marketing creative. No coding required — just paste text into the built-in fields.

---

## How Embedded Instructions Work

AffiliateWP has two built-in fields that affiliates can see:

| Field | What Affiliates See | Best For |
|-------|---------------------|----------|
| **Description** | Shown ABOVE the creative card | What this creative is, where to use it |
| **Notes** | Shown BELOW the creative card | Pro tips, size info, usage warnings |

Both fields appear automatically on the affiliate's Creatives page. No code needed.

---

## Step-by-Step: Adding Instructions to Each Creative

### 1. Edit the Creative
- Go to **WordPress Admin → AffiliateWP → Creatives**
- Click the creative name to edit

### 2. Fill in Description (shown above the creative)

**Example for a Logo Banner:**
```
Your microDOS(2) Logo — Use this on your profile, website sidebar, or social media bio.
Perfect for: Instagram bio, website header, email signature, business cards.
Your referral link is already embedded — just download and use!
```

**Example for a Product Banner:**
```
Product Showcase Banner — Use this in social posts, blog articles, or email newsletters.
Perfect for: Facebook posts, Reddit threads, blog sidebars, email campaigns.
Click "Copy Link" to get the code with your referral URL already inside.
```

### 3. Fill in Notes (shown below the creative)

**Example:**
```
TIP: Add a personal recommendation above this banner when posting — it increases clicks by 300%!
Banner size: 300x250px (standard web ad size)
Best posting times: Weekday evenings (6-9pm) for highest engagement
```

### 4. Save the Creative
- Click **Save** — instructions appear immediately for all affiliates

---

## Description Templates You Can Copy/Paste

### Logo / Brand Creative
```
Your Official microDOS(2) Brand Asset

WHAT: This is your official logo file for promoting microDOS(2).
WHERE TO USE: Website sidebar, social media profile picture, email signature, business cards, flyer designs.
HOW: Download the image and upload it anywhere you promote. Your referral link tracks all clicks automatically.
```

### Social Media Banner
```
Social Media Ready Banner

WHAT: Pre-sized banner optimized for social media posts.
WHERE TO USE: Facebook posts, Instagram stories/feeds, Twitter/X posts, Reddit threads.
HOW: Click "View" to see full size, save the image, then upload directly to your social platform. Your referral link is embedded — every click tracks to your account.
WHY: Posts with images get 2.3x more engagement than text-only posts.
```

### Email Newsletter Banner
```
Email Newsletter Banner

WHAT: Banner designed for email marketing campaigns.
WHERE TO USE: Mailchimp, Gmail newsletters, Constant Contact, or any email platform.
HOW: Click "Copy Link" to copy the HTML code, then paste it into your email editor. Your referral link is pre-embedded.
WHY: Email marketing has the highest conversion rate of any channel (average 15-20% click-through).
```

### Text Link
```
Ready-to-Share Text Link

WHAT: Pre-written promotional text with your referral link built in.
WHERE TO USE: Social media captions, forum posts, text messages, chat apps (Telegram, Discord, WhatsApp).
HOW: Click "Copy Link" and paste directly — no editing needed.
WHY: Personal recommendations with your own comment convert 3-5x better than generic ads.
```

---

## Recommended Categories to Create

Go to **AffiliateWP → Creatives → Manage Categories** and add:

| Category | Purpose |
|----------|---------|
| **Logos & Branding** | Official logos for profile/website use |
| **Social Media** | Banners sized for Instagram, Facebook, X, TikTok |
| **Email Marketing** | Banners optimized for email newsletters |
| **Website Banners** | Standard ad sizes (300x250, 728x90, 160x600) |
| **Product Photos** | Individual product images for direct promotion |
| **Text Links** | Pre-written copy for quick sharing |
| **Seasonal/Promo** | Limited-time offers and sale banners |

---

## Setting Up the Marketing Guide Page

After uploading the theme files:

1. **Pages → Add New**
2. **Title:** Marketing Guide
3. **Page Template:** Affiliate Marketing Guide (dropdown in right sidebar)
4. **Permalink:** `/marketing-guide/`
5. **Publish**

The page will show step-by-step instructions for every platform (Instagram, Facebook, X, TikTok, Reddit, Email, Website).

The Creatives page automatically links to this guide with:  
"Need help? Read the full Marketing Guide for step-by-step instructions"

---

## What Affiliates See (After Setup)

```
+---------------------------------------------------+
| HOW TO USE YOUR MARKETING MATERIALS (instruction   |
| banner with steps 1-4)                            |
+---------------------------------------------------+
                                                    
+---------------------------------------------------+
| Your Official microDOS(2) Brand Asset             |  <-- DESCRIPTION
|                                                   |
| WHAT: This is your official logo file...          |
| WHERE TO USE: Website sidebar, social media...    |
| HOW: Download the image and upload...             |
+---------------------------------------------------+
|                                                   |
|              [IMAGE CREATIVE]                     |
|                                                   |
|  [View]              [Copy Link]                  |
+---------------------------------------------------+
| TIP: Add a personal recommendation above this     |  <-- NOTES
| banner when posting — it increases clicks by 300%!|
+---------------------------------------------------+
```

---

## Quick Checklist

- [ ] Upload theme files (style.css, functions.php, JS, marketing guide template)
- [ ] Edit each creative and add Description text
- [ ] Edit each creative and add Notes with pro tips
- [ ] Create categories (Logos, Social Media, Email, etc.)
- [ ] Create Marketing Guide WordPress page
- [ ] Test by viewing Creatives tab as an affiliate

Done! Affiliates now see embedded instructions on every creative.