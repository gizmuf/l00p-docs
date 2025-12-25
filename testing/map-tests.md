# Map & Location Tests

Test cases for Map discovery features.

---

## TEST-M01: View Map Screen
**Preconditions:** User logged in, location enabled
**Steps:**
1. Tap Map tab (map icon)
2. Observe map view

**Expected:** Map loads centered on user location or default city
**Priority:** High

---

## TEST-M02: See User Pins
**Preconditions:** On Map screen
**Steps:**
1. Look at map
2. Observe pins/markers

**Expected:** Pins showing nearby users appear on map
**Priority:** High

---

## TEST-M03: Tap Profile Pin
**Preconditions:** Map has user pins
**Steps:**
1. Tap on a user pin
2. Observe carousel

**Expected:** Carousel scrolls to that user's profile card
**Priority:** Medium

---

## TEST-M04: Swipe Through Carousel
**Preconditions:** Map carousel visible
**Steps:**
1. Swipe left/right on carousel
2. Observe changes

**Expected:** Different profiles show, map may pan to them
**Priority:** Medium

---

## TEST-M05: View Meeting Alert
**Preconditions:** Have pending meeting invitation
**Steps:**
1. Open Map screen
2. Look at top banner

**Expected:** Meeting alert shows with "View" button
**Priority:** High

---

## TEST-M06: Navigate to Accepted Meeting
**Preconditions:** Have accepted meeting invite
**Steps:**
1. Open Map screen
2. Tap "Navigate" on accepted invite

**Expected:** Apple Maps opens with directions to venue
**Priority:** High
