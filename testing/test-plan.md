# l00p Test Plan

Manual testing guide for QA testers.

---

## Test Environment

**Device Requirements:**
- iPhone running iOS 15+
- Internet connection
- Location services enabled

**Test Account:**
- Create a fresh account via Apple/Google sign-in
- Or use provided test credentials

---

## Test Categories

| Category | Priority | Pages |
|----------|----------|-------|
| Feed & Discovery | High | [Feed Tests](./feed-tests.md) |
| Profile Management | High | [Profile Tests](./profile-tests.md) |
| Chat & Messaging | High | [Chat Tests](./chat-tests.md) |
| Map & Location | Medium | [Map Tests](./map-tests.md) |
| Matching Flow | High | [Matching Tests](./matching-tests.md) |

---

## Test Case Format

Each test follows this structure:

```
TEST-XXX: Test Name
─────────────────────
Preconditions: What must be true before testing
Steps:
1. Step one
2. Step two
3. Step three
Expected: What should happen
Priority: High/Medium/Low
```

---

## Quick Smoke Test

Run these 5 tests to verify basic app functionality:

1. **Login** - Can sign in with Apple/Google
2. **Feed** - Can see and swipe profiles
3. **Messages** - Can open chat with a match
4. **Profile** - Can edit bio and save
5. **Map** - Can see map with pins

---

## Bug Reporting

When reporting bugs, include:

- **Device:** iPhone model and iOS version
- **Steps:** Exact steps to reproduce
- **Expected:** What should happen
- **Actual:** What actually happened
- **Screenshot/Video:** If applicable

---

## Test Tracking

Use this checklist to track testing progress:

- [ ] Feed Tests (12 cases)
- [ ] Profile Tests (10 cases)
- [ ] Chat Tests (8 cases)
- [ ] Map Tests (6 cases)
- [ ] Matching Tests (5 cases)
