# LOCORA 🌍

### Discover the City Beyond the Usual

> Personalized local experiences for travelers. Better discovery for local communities.

LOCORA is a modern local-experience discovery platform designed to help travelers discover the authentic side of a city while giving local hosts, artisans, chefs, guides, and creators better visibility.

Instead of showing travelers only the usual tourist attractions, LOCORA focuses on **local food, culture, crafts, hidden gems, community events, and experiences hosted by people who know the city best.**

---

## 📌 Problem Statement

Travelers often discover cities through the same popular attractions, restaurants, and tourist recommendations.

This creates two problems:

### For Travelers

* Difficult to discover authentic local experiences
* Repetitive tourist recommendations
* Limited exposure to local culture and communities
* Difficulty finding hidden gems
* Lack of personalized recommendations
* Local events and independent creators can be difficult to discover

### For Local Communities

* Small local providers have limited digital visibility
* Independent artisans and creators struggle to reach travelers
* Local businesses compete with large tourism platforms
* Many unique experiences remain undiscovered
* Local providers need better ways to showcase their stories and offerings

### LOCORA's Solution

LOCORA connects travelers directly with local experiences and providers.

**Traveler → Discover → Connect → Experience**

At the same time:

**Local Provider → Showcase → Reach Travelers → Grow**

---

## 🎯 Project Objective

The main objective of LOCORA is to create a digital platform that:

* Personalizes travel discovery
* Promotes authentic local experiences
* Helps travelers discover hidden places
* Connects travelers with local people
* Promotes local food and culture
* Gives artisans and independent providers digital visibility
* Encourages community-driven tourism
* Makes discovering a city more meaningful

---

## ✨ Key Features

### 🏠 Modern Home Page

The homepage introduces the LOCORA concept through:

* Large hero section
* Travel-focused search
* Personalized discovery
* Experience categories
* Featured experiences
* Hidden gems
* Local hosts
* Food and culture sections
* Events
* Community impact
* Testimonials
* Newsletter signup

---

### 🔎 Smart Search

Users can search experiences using keywords such as:

* Food
* Craft
* Culture
* Pune
* Mumbai
* Chef
* History

The search system checks experience information such as:

* Experience title
* City
* Category
* Host
* Description
* Tags

Results are dynamically displayed without refreshing the page.

---

### 🎨 Personalized Discovery

Users can select interests such as:

* Food
* Culture
* Art
* Nature
* Music
* Craft
* History
* Nightlife

LOCORA uses these selections to generate personalized recommendations.

Example:

> **Because you love Food + Culture**

The platform then displays experiences matching those interests.

---

### 🧭 Travel Mood Discovery

Users can select travel moods such as:

* Eat like a local
* Meet local makers
* Find hidden gems
* Explore culture
* Learn a craft
* Slow down
* Night owl
* Weekend explorer

The selected mood changes the discovery experience.

---

### 📍 City Selection

The prototype supports multiple cities including:

* Mumbai
* Pune
* Nagpur
* Delhi
* Bengaluru
* Hyderabad
* Jaipur
* Kolkata
* Goa
* Ahmedabad

Changing the city dynamically updates the discovery content.

---

### ❤️ Favorites

Users can save experiences using the heart button.

Favorites are stored using browser `localStorage`, allowing saved experiences to remain available after refreshing the page.

Users can:

* Save experiences
* Remove experiences
* View saved experiences
* Manage their discovery list

---

### 🗺️ Map Discovery

LOCORA includes a map-based discovery interface for finding nearby experiences.

Categories include:

* Food
* Craft
* Culture
* Music
* Markets
* Hidden Gems

The map can display mock experience locations and information popups.

---

### 👩‍🍳 Local Hosts

The platform highlights people behind local experiences.

Example host categories:

* Local Food Guides
* Home Chefs
* Textile Artisans
* Photographers
* Historians
* Artists
* Musicians

Each host has a profile containing:

* Name
* Location
* Role
* Biography
* Rating
* Experience count
* Profile image

---

### 🍜 Local Food Discovery

The food section focuses on authentic local food experiences.

Categories include:

* Street Food
* Home Kitchens
* Local Cafés
* Food Walks
* Traditional Recipes
* Markets

---

### 🎨 Culture & Craft

Travelers can discover experiences such as:

* Pottery workshops
* Block printing
* Warli painting
* Handloom weaving
* Traditional cooking
* Local music sessions

The goal is not simply to observe culture but to **participate in it.**

---

### 📅 Local Events

Users can discover events such as:

* Indie music evenings
* Artisan markets
* Open mic nights
* Traditional dance workshops
* Photography walks

Events can be filtered by:

* Today
* This Weekend
* This Month

---

### 📖 Local Stories

LOCORA includes editorial-style stories about local communities.

Example topics:

* Morning markets
* Traditional workshops
* Neighborhood food trails
* Local artists
* Family-run businesses

This helps users understand the people and history behind the places they visit.

---

### 🧠 Discovery Quiz

A short quiz helps users identify their travel personality.

Example result:

> **Culture & Craft Explorer**

The quiz then recommends experiences based on the user's answers.

---

### 🧳 Experience Details

Each experience can be opened in a detailed modal containing:

* Experience image
* Title
* Location
* Rating
* Reviews
* Host
* Description
* Duration
* Group size
* Meeting point
* Price
* Activities
* What's included
* Reviews

---

### 📅 Booking Prototype

Users can select:

* Date
* Time
* Number of guests

The system automatically calculates:

**Experience Price × Guests + Service Fee = Total**

The booking is simulated because the project is a frontend prototype.

After confirmation, a demo booking reference is generated.

---

### 🏡 Become a Host

Local providers can explore a host onboarding flow.

They can submit:

* Name
* Email
* City
* Category
* Experience title
* Description
* Price
* Duration

The prototype generates a confirmation message after submission.

---

### 🔐 Login & Signup UI

The project includes a frontend authentication interface with:

* Login
* Signup
* Email
* Password
* Travel interests
* Google login UI
* Apple login UI

Authentication is simulated and does not connect to a real backend.

---

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* Responsive Web Design

### Libraries / External Resources

Depending on the implementation:

* Google Fonts
* Lucide Icons / Font Awesome
* Leaflet.js
* OpenStreetMap
* Unsplash images

### Browser Storage

`localStorage` is used for frontend persistence such as:

* Favorites
* Selected city
* Preferences
* Demo user state
* Theme preference, if enabled

---

## 🏗️ Project Architecture

LOCORA is intentionally designed as a **single-file frontend prototype**.

```text
LOCORA/
│
└── LOCORA.html
```

The single HTML file contains:

```text
LOCORA.html
│
├── HTML
│   ├── Navbar
│   ├── Hero
│   ├── Search
│   ├── Experiences
│   ├── Hosts
│   ├── Food
│   ├── Culture & Craft
│   ├── Events
│   ├── Stories
│   ├── Map
│   ├── Impact
│   ├── Testimonials
│   └── Footer
│
├── CSS
│   ├── Design System
│   ├── Responsive Layout
│   ├── Cards
│   ├── Modals
│   ├── Animations
│   └── Mobile Styles
│
└── JavaScript
    ├── Search
    ├── Filters
    ├── Sorting
    ├── Favorites
    ├── Booking
    ├── Authentication UI
    ├── Personalization
    ├── Quiz
    ├── Map
    ├── Modals
    ├── Toast Notifications
    └── Local Storage
```

---

## 🚀 How to Run

No installation or backend server is required.

### Step 1

Download or clone the project.

### Step 2

Locate:

```text
LOCORA.html
```

### Step 3

Double-click the file.

Or open it using:

```text
Google Chrome
Microsoft Edge
Mozilla Firefox
Safari
```

That's it.

---

## 💻 Running with VS Code

If using Visual Studio Code:

1. Open the LOCORA project folder.
2. Open `LOCORA.html`.
3. Install the **Live Server** extension if desired.
4. Right-click the HTML file.
5. Select:

```text
Open with Live Server
```

The website will open in the browser.

---

## 📱 Responsive Design

LOCORA is designed to work across:

| Device        | Supported |
| ------------- | --------- |
| Mobile        | ✅         |
| Tablet        | ✅         |
| Laptop        | ✅         |
| Desktop       | ✅         |
| Large Desktop | ✅         |

The interface adapts to different screen sizes using CSS media queries.

---

## 🎨 Design Highlights

The visual language combines:

* Modern travel technology
* Editorial storytelling
* Local community aesthetics
* Premium marketplace UI
* Warm natural colors
* Large photography
* Clean typography
* Subtle animations

The design avoids the appearance of a generic tourism website.

---

## 🔄 User Journey

A typical traveler journey looks like:

```text
LAND ON LOCORA
       ↓
Choose City
       ↓
Select Travel Mood
       ↓
Search / Explore
       ↓
Filter Experiences
       ↓
View Local Experience
       ↓
Meet the Host
       ↓
Save or Book
       ↓
Experience the City
       ↓
Leave a Review
```

---

## 🏘️ Local Provider Journey

A local provider can follow:

```text
BECOME A HOST
       ↓
Create Profile
       ↓
Add Experience
       ↓
Set Price & Duration
       ↓
Showcase Story
       ↓
Reach Travelers
       ↓
Receive Bookings
       ↓
Grow Local Business
```

---

## 📊 Demo Platform Metrics

The interface contains sample/demo metrics such as:

```text
2,400+
Local Hosts

18,000+
Experiences

72%
Revenue Retained Locally

45+
Cities & Neighborhoods
```

> **Note:** These figures are demonstration data for the prototype and do not represent actual LOCORA platform statistics.

---

## 🔮 Future Scope

LOCORA can be extended into a complete production platform by adding a backend and real-world integrations.

Possible future features include:

### Backend

* Node.js / Express
* Python / Django
* REST API
* Database integration

### Database

Potential technologies:

* PostgreSQL
* MySQL
* MongoDB

### Authentication

* Google OAuth
* Apple Sign-In
* Email authentication
* OTP login

### Payments

Integration with payment gateways such as:

* Razorpay
* Stripe

### Advanced Personalization

A future recommendation engine could use:

* User interests
* Previous bookings
* Search history
* Location
* Ratings
* Travel style
* Budget
* Duration

to provide more personalized recommendations.

### Local Provider Dashboard

Providers could receive:

* Booking management
* Revenue analytics
* Customer reviews
* Availability management
* Experience management
* Profile analytics

### AI Features

Future versions could include:

* AI travel planner
* AI local guide
* Personalized city itineraries
* Conversational discovery
* AI-generated recommendations
* Smart trip planning

---

## 🌱 Social Impact

LOCORA is designed around a local-first travel philosophy.

The platform aims to encourage travelers to:

* Explore beyond famous landmarks
* Spend more time in local neighborhoods
* Discover independent providers
* Learn from local communities
* Support local creators
* Experience culture more meaningfully

The core idea is:

> **Travel should not only take you somewhere. It should help you connect with somewhere.**

---

## 🔒 Current Limitations

This project is currently a frontend prototype.

Therefore:

* No real user authentication
* No real payment processing
* No production database
* No real booking system
* No real provider verification
* Map data is primarily demonstration data
* Experience data is mock data
* Statistics are demonstration values

These can be implemented in a future full-stack version.

---

## 📂 Suggested Repository Structure

If this project is uploaded to GitHub:

```text
LOCORA/
│
├── LOCORA.html
│
├── README.md
│
└── screenshots/
    ├── home.png
    ├── explore.png
    ├── experience.png
    └── mobile.png
```

The current implementation intentionally keeps the website itself inside a **single HTML file containing HTML, CSS, and JavaScript**.

---

## 🧪 Testing Checklist

Before presenting the project, verify:

* [x] Homepage loads
* [x] Navbar works
* [x] Mobile menu works
* [x] Search works
* [x] City selector works
* [x] Experience filtering works
* [x] Experience sorting works
* [x] Favorite button works
* [x] Favorites persist using localStorage
* [x] Experience details open
* [x] Booking modal works
* [x] Booking price calculation works
* [x] Login modal works
* [x] Signup interface works
* [x] Host registration works
* [x] Newsletter validation works
* [x] Testimonials work
* [x] Discovery quiz works
* [x] Personalized recommendations work
* [x] Story modal works
* [x] Host profile works
* [x] Responsive layout works
* [x] No horizontal scrolling on mobile

---

## 👥 Target Users

### Travelers

People looking for:

* Authentic experiences
* Local food
* Hidden places
* Cultural activities
* Workshops
* Events
* Community experiences

### Local Providers

Including:

* Guides
* Chefs
* Artisans
* Artists
* Photographers
* Musicians
* Historians
* Home businesses
* Independent cafés
* Local creators

---

## 💡 Core Value Proposition

### For Travelers

**Discover more authentic experiences.**

### For Local Communities

**Become easier to discover.**

### For Both

**Create meaningful connections through travel.**

---

## 🏆 Project Vision

LOCORA aims to move travel discovery from:

```text
“What's popular?”
```

to:

```text
“What feels meaningful to me?”
```

And from:

```text
“Visit the landmark.”
```

to:

```text
“Meet the people who make the place.”
```

---

## 📜 License

This project is created as a frontend prototype/project.

You may modify and extend it for educational, demonstration, and portfolio purposes.

---

## ❤️ Built Around One Simple Idea

### **Don't just visit a city. Discover it.**

**LOCORA**

*Discover the city beyond the usual.*
