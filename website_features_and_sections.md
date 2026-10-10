# Snox+ (Taytay Rizal Branch) — Website Features & Sections Specification

> **Project:** Snox+ Snack Warehouse & Refill (Taytay Rizal Branch)  
> **Tech Stack:** Pure HTML & CSS (Fast, responsive static website)  
> **Reference Design:** UI Mockup + Facebook Branch Integration ([Snox Taytay Rizal Branch](https://www.facebook.com/Snoxtaytayrizalbranch))

---

## 1. Executive Summary & Website Goals

The Snox+ website is a lightweight, responsive static web page designed to:
1. **Showcase Categories & Products:** Display available snack categories matching local inventory.
2. **Drive Foot Traffic to Warehouse:** Guide nearby walk-in shoppers directly to the physical warehouse Near Kalayaan Park.
3. **Facilitate Direct Customer Inquiries:** Enable immediate customer contact and bulk orders via Facebook Messenger.

---

## 2. Core Website Layout & Sections

### 📌 1. Announcement Bar (Top Header)
* **Location & Visibility:** Sticky at the very top of the page.
* **Content:** 
  * Operating Hours: `Open 9AM-8PM`
  * Key Landmark: `Taytay Location (Near Kalayaan Park)`
* **Purpose:** Immediately clarifies store hours and physical location.

---

### 🧭 2. Navigation Bar
* **Branding:** Snox+ wordmark / logo.
* **Navigation Links:**
  * `Home`
  * `Collections`
  * `Reels`
  * `About Us`
  * `Inquire on FB` (styled as a button)
* **Utility Actions:**
  * 🔍 **Search Bar:** Clean CSS-styled search input box for browsing snacks.

---

### 🚀 3. Hero Section
* **Headline:** *"Good Finds. Good Times"*
* **Call-to-Action (CTA) Buttons:**
  * `Shop Deals` (Smooth scroll to categories/promos section)
  * `Inquire on Messenger` (Direct external link to Facebook Messenger)

---

### 🏷️ 4. "Explore Our Big Collections" (Category Grid)
Grid of clean, pastel-colored cards based on store inventory categories:

| # | Category Name | Description / Items Included |
| :-: | :--- | :--- |
| 1 | 🥤 **Beverages** | Sodas, juices, bottled drinks, energy drinks, imported teas |
| 2 | 🍪 **Biscuits & Cookies** | Wafers, sandwich cookies, crackers, snack packs |
| 3 | 🍬 **Candies & Sweets** | Gummies, hard candies, marshmallows, lollipops |
| 4 | 🥫 **Canned Goods** | Premium canned meats, fruits, beans, preserved goods |
| 5 | 🍫 **Chocolates** | Chocolate bars, blocks, pralines, chocolate bites |
| 6 | 🥜 **Dried Fruits & Nuts** | Dried mangoes, roasted nuts, trail mixes, seeds |
| 7 | 🎒 **Merchandise & Accessories** | Brand tote bags, snack containers, reusable items |
| 8 | 🍜 **Noodles & Instant Meals** | Ramen bowls, instant noodles, instant soups |
| 9 | 🍙 **Seaweed Snacks** | Crispy seaweed sheets, rolls, seasoned seaweed |
| 10 | 🍞 **Spreads & Breakfast** | Bread spreads, jams, peanut butter, cereals |
| 11 | 🎉 **Store Promotions & Events** | B1T1 bundles, seasonal holiday drops, warehouse specials |

---

### 📱 5. "Follow Us on Facebook & TikTok" (Social Community)
* **Visual Presentation:** Clean CSS-styled media cards and social links (simple responsive card grid without heavy mobile phone frame mockups).
* **Content:**
  * **TikTok Feed Cards:** Video preview thumbnails, snack reviews, and unboxing highlights.
  * **Facebook Page Card:** Direct link to [@Snoxtaytayrizalbranch](https://www.facebook.com/Snoxtaytayrizalbranch) with current store announcements and restock updates.
* **Direct Links:** `Follow on Facebook` and `Follow on TikTok` buttons.

---

### 🦶 6. Footer Section
* **Column 1 (Quick Links):** Home, Menu, Deals, Bulk, Location & Contact.
* **Column 2 (Warehouse Schedule):**
  * `Mon-Sat: 9:00 AM – 8:00 PM`
  * `Sun: 10:00 AM – 6:00 PM`
* **Column 3 (Contact Information):**
  * 📍 Address: Taytay, Rizal (Near Kalayaan Park)
  * 📞 Phone: `+63 9xx xxx xxxx`
  * ✉️ Email: `hello@snox.plus`
* **Bottom Bar:** Copyright notice and accepted payment logos overview (GCash, Maya, COD).

---

## 3. High-Priority Features Included (HTML & CSS Exclusively)

### 📍 A. Interactive Store Locator & Google Maps Integration
* **Embedded Map:** Responsive `<iframe>` Google Maps embed with the exact warehouse location in Taytay.
* **Landmark & Arrival Guide:**
  * Note: *"Located Near Kalayaan Park along Manila East Road"*
  * Parking & pickup bay notes.
* **Navigation Buttons:**
  * 📍 `Open in Google Maps` link (`target="_blank"`).
  * 🚗 `Navigate with Waze` link (`target="_blank"`).
* **Store Pickup Guide:** Simple static steps on messaging the store to reserve orders for counter pick-up.

---

### 💬 B. Live Chat & Direct Messenger Integration
* **Floating Contact Button (Pure CSS Fixed Widget):** Fixed at the bottom-right corner of the screen.
* **Direct Action Links:**
  * 💬 **Facebook Messenger:** Direct `https://m.me/Snoxtaytayrizalbranch` link.
  * 📱 **Phone / Viber:** Direct `tel:` link for quick warehouse hotline access.

---

## 4. Supplementary Trust & Information Badges

1. **Accepted Payment Badges (Static CSS Grid):**
   * Badges for **GCash, Maya, Cash on Delivery (COD)**, and Bank Transfer.
2. **Courier & Dispatch Badges:**
   * Badges indicating support for **Lalamove, GrabExpress, and Borzo** same-day booking.
3. **Freshness & Expiry Date Assurance:**
   * Trust badge: *"100% Authentic & Fresh Stock Guarantee with Clear Expiration Labels."*

---

## 5. Summary Architecture Matrix

| Section / Feature | Primary Target User | Key Implementation (HTML/CSS) |
| :--- | :--- | :--- |
| **Top Bar & Announcement** | Walk-in / Local Shoppers | Fixed top strip with store hours and landmark |
| **Hero Section** | All Visitors | Short headline and `Inquire on Messenger` CTA |
| **Category Cards (11 Categories)** | Snack Browsers | CSS grid of 11 pastel cards mapped directly to store product categories |
| **Social Proof / Community** | Social Shoppers | Clean preview cards linking to Facebook and TikTok |
| **Interactive Map & Waze** | In-person warehouse visitors | Embedded Google Maps `<iframe>` + Waze navigation links |
| **Floating Messenger Widget** | Inquiring customers | Fixed pure-CSS floating button linking to Facebook Messenger |
| **Footer & Schedule** | All visitors | 3-column footer with quick links, operating hours, and contact details |
