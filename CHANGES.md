# Basai - Student Hostel Transformation

## What Changed?

The website has been transformed from a **hotel/traveler-style** booking site to a proper **student hostel finder** platform.

### Key Differences: Before vs After

| Aspect | ❌ Before (Hotel-style) | ✅ After (Student Hostel) |
|--------|------------------------|--------------------------|
| **Target Users** | Travelers, tourists | Students attending colleges |
| **Duration** | Nightly stays (1-3 days) | Monthly/yearly (3-12 months) |
| **Pricing** | NPR 500-1200/night | NPR 10,000-18,000/month |
| **Location Focus** | Tourist areas (Thamel, Durbar Square) | Near universities (TU, KU, Patan Campus) |
| **Search Fields** | Check-in/Check-out dates | Move-in date + Duration |
| **Room Selection** | "Guests" | "Room Type" (Single/Shared) |
| **Amenities** | Swimming pool, gym, yoga, breakfast | Study rooms, mess, WiFi, library |
| **Reviews From** | International travelers | Current students |
| **Language** | "Guests", "travelers", "stay" | "Students", "hostel", "living" |

## Specific Changes Made

### 1. Homepage (index.html)

#### Hero Section
- **Title**: "Find Your Perfect Stay" → "Find Your Student Hostel Near Campus"
- **Subtitle**: Tourism focus → Student accommodation focus
- **Search Bar**:
  - Location: "Location in Kathmandu" → "Near your college (e.g., TU, Patan Campus)"
  - Icon changed from map to university icon
  - Removed: Check-in/Check-out dates
  - Added: Move-in date + Duration dropdown (3 months, 6 months, 1 year, 2 years)
  - Guests selector → Room Type (Single, Shared 2 beds, Shared 3+ beds)

#### Features Section
- Changed amenities to student-focused:
  - Added: Student-Friendly (graduation cap icon)
  - Changed "Delicious Meals" → "Mess Facility" (hostel mess)
  - Changed "Prime Locations" → "Study Rooms" (study areas)

#### Hostel Cards (4 properties updated)
1. **Thamel Heights** → **Thamel Student House**
   - NPR 800/night → NPR 15,000/month
   - Location: "Thamel" → "5 min walk to TU, Thamel"
   - Amenities: Parking, Breakfast → Study Room, Mess
   - Reviews: "234 reviews" → "234 students"

2. **Himalayan Retreat** → **Patan Girls Hostel**
   - NPR 1200/night → NPR 18,000/month
   - Badge: "Featured" → "Girls Only"
   - Location: "Lazimpat" → "Near Patan Campus, Lalitpur"
   - Amenities: Gym, Pool → 24/7 Security, Library, Meals

3. **Durbar Square Inn** → **Boudha Student Residence**
   - NPR 500/night → NPR 10,000/month
   - Badge: "Budget" → "Affordable"
   - Location: "Basantapur" → "10 min to TU, Boudha"
   - Amenities: Breakfast, Library → Food included, Study Area

4. **Swayambhu Vista** → **KU Boys Hostel**
   - NPR 950/night → NPR 14,000/month
   - Badge: "New" → "Boys Only"
   - Location: "Swayambhu" → "Near KU, Dhulikhel"
   - Amenities: View, Yoga → Computer Lab, Sports

#### Why Choose Section
- Title: "Why Choose Basai?" → "Why Students Choose Basai?"
- Updated all 4 points to student-focused:
  1. Verified Properties → **Near Your College** (walking distance)
  2. Best Price Guarantee → **Student-Friendly Prices** (NPR 10,000+, long-term)
  3. 24/7 Support → **Study Environment** (quiet hours, WiFi)
  4. (Kept support, added student context)

#### Testimonials
All 3 testimonials changed from tourists to students:

1. **Sarah Johnson (Australia)** → **Rajesh Kumar**
   - "Amazing experience exploring Kathmandu"
   - → "I've been staying for 8 months, 10 min walk to college, study room is quiet"
   - Country → "Engineering Student, TU"

2. **David Chen (Singapore)** → **Sita Sharma**
   - "Great value, met people from all over the world"
   - → "Girls hostel near Patan Campus, safe, NPR 16,000/month, living for 1 year"
   - Country → "BBS Student, Patan Campus"

3. **Emma Wilson (UK)** → **Bikash Thapa**
   - "Best hostel experience in Nepal"
   - → "Hostel has study room, fast WiFi, near KU, been 6 months, extending to whole year"
   - Country → "MBA Student, Kathmandu University"

#### Call-to-Action
- "Book your perfect hostel today and save 30%"
- → "Join thousands of students living in affordable hostels near their college"
- Button: "Browse Hostels" → "Find Student Hostels"

#### Footer
- Icon: Hotel → Home
- Description: "travelers", "accommodations since 2020"
  - → "student hostel finder", "safe verified hostels for long-term stay"
- "Popular Areas" section → **"Near Colleges"**
  - Tourist spots → University names (TU, KU, Patan Campus, Pulchowk)

### 2. Throughout Site

Similar changes will be applied to:
- `hostels.html` - Browse page filters
- `hostel-detail.html` - Property details
- `booking.html` - Booking form
- `about.html` - Company description
- `dashboard.html` - User dashboard
- All other pages

### Language Changes

**Removed Terms:**
- ❌ Travelers, tourists, guests
- ❌ Night stays, check-in/check-out
- ❌ Exploring, sightseeing
- ❌ Hotel amenities (pool, spa, luxury)

**Added Terms:**
- ✅ Students, hostelers
- ✅ Monthly rent, long-term stay
- ✅ Study, college, university
- ✅ Student amenities (study room, mess, library)

## Why This Matters

### For Students:
- **Clear Focus**: They know this is FOR them
- **Realistic Pricing**: Monthly rates, not confusing nightly rates
- **Relevant Locations**: Near their actual colleges
- **Student Amenities**: Study rooms, not tourist attractions
- **Long-term**: Can stay for semester/year, not just days

### For the Platform:
- **Differentiation**: Not competing with hotels/tourism sites
- **Target Market**: Clear niche (students near colleges)
- **Search Experience**: Filters match student needs
- **Trust**: Reviews from fellow students, not tourists

## Next Steps

The transformation is complete for the homepage. The same student-centric approach should continue across all pages to maintain consistency.

---

**Status**: ✅ Homepage transformed to student hostel finder  
**Date**: January 2, 2026  
**Version**: 2.0 (Student-Focused)
