# IT2010-MAD--ASSIGMENT02--Mobile-Application--Mocha-Hub-Online-Coffee-Shop-App
Mocha-Hub is a mobile application for coffee lovers, offering fast and personalized coffee ordering. Features include menu browsing, order customization, secure payments, pre-ordering, loyalty rewards, and exclusive deals, providing a convenient and rewarding digital café experience. using Android Studio. 

# ☕ MochaHub – Online Coffee Shop App

MochaHub is a modern mobile application designed for coffee lovers, offering fast, personalized, and convenient coffee ordering. Users can browse a wide variety of coffee, snacks, and desserts, customize their orders, pre-order to save time, and earn loyalty rewards—all from the comfort of their smartphone.

---

## 🎯 Target Audience
- Coffee enthusiasts (students, professionals, and general customers)  
- Busy individuals who prefer quick mobile ordering  
- Regular café visitors who want loyalty rewards and pre-orders  

---

## 🛠 Problem It Solves
- Saves time with pre-ordering options, avoiding queues  
- Customization for coffee preferences (milk, sugar, flavors)  
- Exclusive deals and loyalty rewards in a centralized app  

---

## 🌟 Core Features
- **Home:** Daily specials, quick order shortcuts  
- **Menu:** Browse coffee, snacks, and combos with detailed descriptions  
- **Deals:** Discounts, happy-hour offers, and seasonal specials  
- **Categories:** Coffee types (Espresso, Latte, Cappuccino, Cold Brew), Snacks, Desserts  
- **Profile:** User info, order history, loyalty points, and rewards  
- **Cart & Checkout:** Secure payments and order tracking  

---

## 🎨 Color Scheme (60-30-10 Rule)

| Role      | Color Code | Usage |
|-----------|------------|-------|
| Primary (60%)   | #6F4E37 (Coffee Brown) | App bar, buttons, key highlights |
| Secondary (30%) | #F5F5F5 (Light Cream) | Backgrounds, card containers |
| Accent (10%)    | #D4A373 (Caramel/Beige) | CTAs like “Order Now” or deals |

> ✔ Colors defined in `colors.xml` for consistent usage across the app.

---

## 🧩 Layouts Used
- **ConstraintLayout:** Home, Menu, Profile screens  
- **LinearLayout (Vertical/Horizontal):** Coffee customization options, onboarding pages  
- **FrameLayout:** Splash/Launch screen (logo + background)  
- **ScrollView:** Menu screen (long product listings)  

> ✔ Adequate margins (8dp) and padding (16dp) maintained for neat UI.

---

## 🖼️ UI Components (Views)
- **TextView:** Coffee names, descriptions, prices  
- **EditText:** Login, delivery instructions  
- **Button:** “Add to Cart”, “Order Now”, “Apply Coupon”  
- **ImageView:** Coffee images, snack thumbnails  
- **RecyclerView/ListView:** Menu listing and order history  
- **CardView:** Display coffee product cards  
- **Navigation Bar:** Tabs for Home, Menu, Deals, Categories, Profile  

> ✔ Strings stored in `strings.xml` for reusability.

---

## 🔗 Interactivity
- Intents used for navigation between screens:  
  `Splash → Onboarding → Login → Home`  
  `Home → Menu → Product Details → Cart → Checkout`  
- Bottom navigation for quick switching: Home, Menu, Deals, Categories, Profile

---

## 🎨 Creativity & Aesthetics
- Warm coffee-inspired theme with brown, cream, and caramel tones  
- Minimalist design using modern rounded cards and icons  
- Personalized touches like `“Good Morning, [UserName] ☕”` greetings  
- Clear product hierarchy with images, prices, and one-click ordering

---

## 📷 Screenshots / PDF Placeholders

### Splash/Launch Screen
![Figure 1 – Splash Screen](./screenshots/figure_01.png)  
![Figure 2 – Splash Screen](./screenshots/figure_02.png)  
![Figure 3 – Splash Screen](./screenshots/figure_03.png)  
*MochaHub logo with coffee cup icon*

---

### Onboarding Screens (3 slides)
![Figure 4 – Onboarding](./screenshots/figure_04.png)  
![Figure 5 – Onboarding](./screenshots/figure_05.png)  
![Figure 6 – Onboarding](./screenshots/figure_06.png)  
*Easy ordering, customization, and rewards*

---

### Login & Sign-Up Screens
![Figure 7 – Login](./screenshots/figure_07.png)  
![Figure 8 – Sign Up](./screenshots/figure_08.png)

---

### Home Screen
![Figure 9 – Home](./screenshots/figure_09.png)  
![Figure 10 – Home](./screenshots/figure_10.png)  
*Specials and recommended coffees*

---

### Menu & Deals Screens
![Figure 11 – Featured](./screenshots/figure_11.png)  
![Figure 12 – Featured](./screenshots/figure_12.png)  
![Figure 13 – Deals](./screenshots/figure_13.png)  
![Figure 14 – Deals](./screenshots/figure_14.png)  
*Coffee list with offers and promotions*

---

### Categories & Profile Screens
![Figure 15 – Categories](./screenshots/figure_15.png)  
![Figure 16 – Categories](./screenshots/figure_16.png)  
![Figure 17 – Profile](./screenshots/figure_17.png)  
![Figure 18 – Profile](./screenshots/figure_18.png)  
*Coffee types, snacks, desserts, and user details*

---

### Cart & Checkout Page
![Figure 19 – Cart](./screenshots/figure_19.png)  
![Figure 20 – Checkout](./screenshots/figure_20.png)  
*Selected items, payment option, and order tracking*



# 🛠 Technologies Used
- Android Studio
- Java / Kotlin
- XML Layouts
- Material Design Components

---


> 💡 Tip: Place your actual screenshots or export pages from your PDF to `./screenshots/` folder, keeping the same file names to display them correctly.

---

> MochaHub delivers a seamless, fast, and personalized coffee shop experience, right from your mobile device! ☕
