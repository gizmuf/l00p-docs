# Matching Flow Tests

Test cases for the complete matching journey.

---

## TEST-MT01: Like Creates Pending
**Preconditions:** Viewing profile that hasn't liked you
**Steps:**
1. Swipe right to Like
2. Check if match popup appears

**Expected:** No match popup (one-sided like), next profile shows
**Priority:** High

---

## TEST-MT02: Mutual Like Creates Match
**Preconditions:** Someone has already liked you
**Steps:**
1. Find their profile in Feed
2. Swipe right to Like

**Expected:** "It's a Match!" popup appears
**Priority:** High

---

## TEST-MT03: Match Opens Chat
**Preconditions:** Just matched with someone
**Steps:**
1. On match popup, tap "Send Message"
2. Observe navigation

**Expected:** Chat opens with new match
**Priority:** High

---

## TEST-MT04: Like from Likes Tab
**Preconditions:** Premium user, people in Likes tab
**Steps:**
1. Go to Likes tab
2. Swipe right on a profile

**Expected:** Instant match, chat becomes available
**Priority:** High

---

## TEST-MT05: Pass from Likes Tab
**Preconditions:** Premium user, people in Likes tab
**Steps:**
1. Go to Likes tab
2. Swipe left on a profile

**Expected:** Profile removed from Likes list
**Priority:** Medium
