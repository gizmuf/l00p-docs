# Chat & Messaging Tests

Test cases for chat and messaging features.

---

## TEST-C01: View Messages List
**Preconditions:** User has matches
**Steps:**
1. Tap Messages tab (chat icon)
2. Observe conversation list

**Expected:** List of conversations with previews and timestamps
**Priority:** High

---

## TEST-C02: Open Conversation
**Preconditions:** Has at least one match
**Steps:**
1. Go to Messages tab
2. Tap on a conversation
3. Observe chat view

**Expected:** Chat opens showing message history
**Priority:** High

---

## TEST-C03: Send Text Message
**Preconditions:** In active chat
**Steps:**
1. Tap text input field
2. Type "Hello, how are you?"
3. Tap send button

**Expected:** Message appears in chat, shows as sent
**Priority:** High

---

## TEST-C04: Record Voice Note
**Preconditions:** In active chat
**Steps:**
1. Tap microphone icon
2. Hold and speak for 5 seconds
3. Release to send

**Expected:** Voice note sends, playback button visible in chat
**Priority:** High

---

## TEST-C05: Play Voice Note
**Preconditions:** Voice note in chat
**Steps:**
1. Tap play button on voice note
2. Observe playback

**Expected:** Audio plays through speaker, progress bar moves
**Priority:** High

---

## TEST-C06: Send Meeting Invite
**Preconditions:** In active chat
**Steps:**
1. Tap coffee/venue icon
2. Select venue
3. Send invite

**Expected:** Meeting invite card appears in chat
**Priority:** High

---

## TEST-C07: Receive Push Notification
**Preconditions:** App in background, notifications enabled
**Steps:**
1. Have another user send you a message
2. Observe notification

**Expected:** Push notification appears with message preview
**Priority:** High

---

## TEST-C08: Block User from Chat
**Preconditions:** In active chat
**Steps:**
1. Tap menu (three dots)
2. Select "Block User"
3. Confirm

**Expected:** User blocked, chat disappears from list
**Priority:** Medium
