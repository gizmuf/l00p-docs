# Feed & Discovery Tests

Test cases for the main Feed screen.

---

## TEST-F01: Feed Loads on Launch
**Preconditions:** User is logged in
**Steps:**
1. Open app
2. Verify Feed tab is active (flame icon selected)
3. Observe profile cards loading

**Expected:** Profile cards appear within 3 seconds
**Priority:** High

---

## TEST-F02: Swipe Right to Like
**Preconditions:** Feed has profile cards visible
**Steps:**
1. Observe current profile
2. Swipe card to the RIGHT
3. Observe card animation

**Expected:** Card flies off right, next card appears, haptic feedback
**Priority:** High

---

## TEST-F03: Swipe Left to Pass
**Preconditions:** Feed has profile cards visible
**Steps:**
1. Observe current profile
2. Swipe card to the LEFT
3. Observe card animation

**Expected:** Card flies off left, next card appears, haptic feedback
**Priority:** High

---

## TEST-F04: Tap to Expand Profile
**Preconditions:** Feed has profile cards visible
**Steps:**
1. Tap on profile card (not swipe)
2. Observe expansion animation

**Expected:** Card expands to show full profile details
**Priority:** High

---

## TEST-F05: View All Photos
**Preconditions:** Profile card is expanded
**Steps:**
1. Swipe horizontally on photo area
2. Observe photo changes

**Expected:** Can browse through all user photos
**Priority:** Medium

---

## TEST-F06: View Bio and Themes
**Preconditions:** Profile card is expanded
**Steps:**
1. Scroll down on expanded card
2. Observe content sections

**Expected:** Bio, themes, and "Looking For" visible
**Priority:** Medium

---

## TEST-F07: Close Expanded Profile
**Preconditions:** Profile is expanded
**Steps:**
1. Swipe down OR tap X button
2. Observe animation

**Expected:** Card collapses back to normal view
**Priority:** Medium

---

## TEST-F08: Rewind Last Pass (Premium)
**Preconditions:** Premium user, just passed on a profile
**Steps:**
1. Tap Rewind button (gold undo icon)
2. Observe animation

**Expected:** Previous profile returns, can now Like it
**Priority:** Medium

---

## TEST-F09: Empty Feed State
**Preconditions:** No more profiles available
**Steps:**
1. Swipe through all available profiles
2. Observe empty state

**Expected:** "No more profiles" message appears with refresh option
**Priority:** Low

---

## TEST-F10: Pull to Refresh
**Preconditions:** Feed is visible
**Steps:**
1. Pull down on feed
2. Release

**Expected:** Loading indicator appears, feed refreshes
**Priority:** Medium

---

## TEST-F11: Match Popup
**Preconditions:** Both users liked each other
**Steps:**
1. Swipe right on someone who already liked you
2. Observe popup

**Expected:** "It's a Match!" popup with option to message
**Priority:** High

---

## TEST-F12: Distance Badge
**Preconditions:** Location enabled, profiles nearby
**Steps:**
1. View profile cards
2. Observe distance indicator

**Expected:** Distance shown (e.g., "2 km away")
**Priority:** Medium
