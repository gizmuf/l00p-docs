# Profile Tests

Test cases for Profile management.

---

## TEST-P01: View Own Profile
**Preconditions:** User logged in
**Steps:**
1. Tap Profile tab (person icon)
2. Observe profile screen

**Expected:** Own profile details visible with edit options
**Priority:** High

---

## TEST-P02: Edit Profile Photo
**Preconditions:** On Profile screen
**Steps:**
1. Tap on photo slot in 3x3 grid
2. Select "Choose from Library" or "Take Photo"
3. Select/capture image
4. Confirm

**Expected:** Photo uploads and appears in grid with position badge
**Priority:** High

---

## TEST-P03: Edit Bio
**Preconditions:** On Profile screen
**Steps:**
1. Tap on Bio section
2. Edit text
3. Tap outside to save

**Expected:** Bio saves automatically, changes visible
**Priority:** High

---

## TEST-P04: Change Location
**Preconditions:** On Profile screen
**Steps:**
1. Tap Location section
2. Search for city OR tap on map
3. Tap "Set Location"

**Expected:** Location updates, confirmation shown
**Priority:** High

---

## TEST-P05: Edit Themes/Interests
**Preconditions:** On Profile screen
**Steps:**
1. Scroll to Themes section
2. Tap to add/remove interest chips
3. Observe changes

**Expected:** Selected themes highlighted, unselected dimmed
**Priority:** Medium

---

## TEST-P06: Preview Profile
**Preconditions:** On Profile screen
**Steps:**
1. Tap "Preview Profile" button
2. Observe preview modal

**Expected:** Full-screen preview shows how others see you
**Priority:** Medium

---

## TEST-P07: Change Gender
**Preconditions:** On Profile screen
**Steps:**
1. Tap Gender section
2. Select different option
3. Confirm

**Expected:** Gender updates and saves
**Priority:** Medium

---

## TEST-P08: Edit Birthday
**Preconditions:** On Profile screen
**Steps:**
1. Tap Birthday section
2. Use date picker to change
3. Confirm

**Expected:** Age updates based on new birthday
**Priority:** Low

---

## TEST-P09: Access Settings
**Preconditions:** On Profile screen
**Steps:**
1. Tap gear/settings icon
2. Observe settings menu

**Expected:** Settings options appear (Blocked, Privacy, Delete, Sign Out)
**Priority:** Medium

---

## TEST-P10: Sign Out
**Preconditions:** In Settings
**Steps:**
1. Tap "Sign Out"
2. Confirm action

**Expected:** Returns to login screen, session cleared
**Priority:** High
