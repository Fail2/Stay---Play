# Eagle Creek Golf Club — Stay&Play Technical & Analytical Report

## 1. Executive Summary

This report provides a detailed overview and structured breakdown of the **Eagle Creek Golf Club - Stay&Play** web page interface based on the source code (`index.html` and `style.css`). The application is designed to serve golf enthusiasts, travelers, and event organizers seeking detailed information on golf courses, accommodation options, tee-time availability, and surrounding course recommendations.

---

## 2. Core Functional Modules & Component Architecture

### 2.1 Navigation & Branding Header
- **Brand Identity**: Features the "Stay&Play" logo (`assets/logo.png`) rendered using the Google Font **Comfortaa**.
- **Primary Links**:
  - `HOME`
  - `WHERE TO STAY`
  - `WHERE TO PLAY`
  - `GROUP TRAVEL`
- **Call-To-Action (CTA) & Search**:
  - `BOOK A TEE TIME` CTA button.
  - Interactive search form input with integrated SVG icon.
  - Responsive mobile navigation triggers (golf icon, search icon, hamburger menu).

### 2.2 Golf Course Profile & Gallery
- **Metadata Header**:
  - Breadcrumb navigation: `Golf course > Florida > Orlando > Eagle Creek Golf Club`
  - Star Rating: 5/5 Stars based on **128 reviews**.
  - Operational Hours: Tee Times Daily from **8:00 AM – 8:00 PM**.
- **Media Gallery**:
  - Main hero image (`Eagle creak - 1.webp`) with slider pagination indicators.
  - Secondary thumbnail gallery (`Eagle creak - 2.webp`, `Eagle creak - 3.webp`) with a "VIEW ALL 20 IMAGES" overlay trigger.

---

## 3. Financial & Service Tier Specifications

### 3.1 Pricing & Booking Tiers

| Service Category | Tier / Option | Rate / Details | Features & Inclusions |
| :--- | :--- | :--- | :--- |
| **Stay** | Nearby Accommodations | From $300 / night | 800+ partner properties available |
| **Play** | Peak Tee Time | $100 / round | Prime daily hours |
| **Play** | Off-Peak Tee Time | $75 / round | Mid-day & early morning |
| **Play** | Twilight Tee Time | $60 / round | Late afternoon/evening rounds |
| **Packages** | Special Stay & Play | From $250 / person | Includes 2 rounds of golf, cart, and resort stay |

### 3.2 Course Specifications at a Glance

```
+-----------------------------------------------------------------------+
| EAGLE CREEK GOLF CLUB AT A GLANCE                                     |
+-------------------+--------------------+------------------------------+
| PAR               | TOTAL YARDS        | COURSE TYPE                  |
| 72 (Front 9 / Back 9) | 7,305 Yards        | Public Course (No Stay Req.) |
+-------------------+--------------------+------------------------------+
```

---

## 4. Technical Specifications & Tee Box Breakdown

### 4.1 Course Difficulty Metrics
- **Par**: 72 (Front 9: Par 36 | Back 9: Par 36)
- **Course Rating**: 71.4
- **Course Slope**: 113
- **Architect**: Ron Garl
- **Style**: Parkland Course featuring tree-lined fairways, undulating greens, and strategically placed water hazards and bunkers.

### 4.2 Tee Box Yardage Breakdown
1. **Championship Tees**: 7,198 Yards
2. **Regular Tees**: 6,720 Yards
3. **Forward Tees**: 5,942 Yards
4. **Beginner Tees**: 5,152 Yards

### 4.3 On-Site Amenities & Services
- **18-Hole Championship Layout**
- **Tee Time Flexibility & Online Booking**
- **Luxury Clubhouse**: Premium dining, locker facilities, event spaces.
- **Pro Shop**: Fully stocked with top-tier gear, apparel, and accessories.
- **Instruction**: Expert golf lessons available for all skill levels.
- **Practice Facilities**: Driving range with target greens, putting green, short game area with sand bunkers.
- **Cart & Caddie Services**:
  - Golf Carts: Equipped with GPS ($25 rental fee).
  - Caddie Service: Available upon request ($40/hour).
  - Food & Beverage: Halfway house, multiple snack bars, mobile beverage carts.

---

## 5. Accommodation & Interactive Search Module

The page features an interactive accommodation lookup tool paired with an embedded Google Map.

### 5.1 Nearby Featured Properties

- **Fairway Greens Resort** (Booking.com) | Rating: 10.0 Exceptional (12 Reviews) | From $295/night
  - *Amenities*: Shuttle service to course, club storage, pet-friendly, on-site dining, sleeps 8.
- **The Par View Lodge** (Booking.com) | Rating: 10.0 Exceptional (12 Reviews) | From $295/night
- **Coastal Links Retreat** (Booking.com) | Rating: 10.0 Exceptional (12 Reviews) | From $295/night
- **Eagle's Nest Golf Resort** (Booking.com) | Rating: 10.0 Exceptional (12 Reviews) | From $295/night
- **Parview Lakeside Hotel** (Booking.com) | Rating: 10.0 Exceptional (12 Reviews) | From $295/night
- **Bunker Bay Retreat** (Booking.com) | Rating: 10.0 Exceptional (12 Reviews) | From $295/night

### 5.2 Real-time Availability Widget Features
- **Average Nightly Rate**: $600 USD
- **Check-In / Check-Out Selector**: Pre-configured defaults (e.g., 19 SEP 2025 – 21 SEP 2025).
- **Guest Breakdown Selector**: Adult, Infant, and Pet settings.
- **Real-Time Status Indicator**: Verified availability badge.
- **Partner Redirect**: Redirects to Booking.com partner checkout.

---

## 6. Seasonal Climate & Playability Index

The best time of year to play at Eagle Creek Golf Club is **Fall and Spring**, offering mild weather and minimal rainfall.

| Season | Months | Daytime Temp | Nighttime Temp | Playability & Conditions |
| :--- | :--- | :--- | :--- | :--- |
| **Spring** | March – May | 60°F – 80°F | 40°F – 55°F | **Optimal**: Wildflowers in bloom, ideal course conditions. High demand. |
| **Summer** | June – August | 85°F – 95°F | 70°F – 78°F | **Moderate**: Warm & humid, afternoon rain showers. Twilight play recommended. |
| **Fall** | Sept – Nov | 60°F – 80°F | 40°F – 55°F | **Optimal**: Comfortable temperatures, clear skies, excelente turf condition. |
| **Winter** | Dec – Feb | 55°F – 72°F | 40°F – 50°F | **Good**: Mild year-round play alternative for winter travelers. |

---

## 7. Neighboring Golf Recommendations

| Course Name | Distance from Eagle Creek | Yards | Par | Highlights / Pro Notes |
| :--- | :--- | :--- | :--- | :--- |
| **Providence Golf Club** | 6 Miles | 7,305 Yds | Par 72 | Tour-grade layout, challenging water hazards. |
| **ChampionsGate Golf Club** | 6 Miles | 7,305 Yds | Par 72 | World-class facility designed by Greg Norman. |
| **Nicklaus Course at Reunion Resort** | 6 Miles | 7,305 Yds | Par 72 | Signature Jack Nicklaus parkland design. |

---

## 8. Footer & Localization Settings

- **Navigation Columns**: Global destinations across North America, Europe, Asia, and Oceania (USA, Scotland, Portugal, Spain, Ireland, Australia, Thailand, Mexico, Canada, etc.).
- **Localization Controls**:
  - Currencies Supported: `USD`, `EUR`, `GBP`
  - Regions Supported: `UNITED STATES`, `UNITED KINGDOM`, `CANADA`
- **Branding Partnership**: Stay&Play Powered by **TravelAi**.
- **Copyright**: © 2026 StayAndPlay. All Rights Reserved.
