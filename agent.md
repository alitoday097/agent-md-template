# agent.md — Project Control File

## 1. Overview
- Type: Web App (MVP)
- Purpose: [One clear sentence — concrete use-case]
- Stack: NextJS (client-side only)
- Dir: ./frontend

---

## 2. Scope (Strict)
Features:
- [Feature 1]
- [Feature 2]
- [Feature 3]

Non-Goals:
- No DB / persistence
- No auth
- No search/filter
- No extra features

---

## 3. Data Model
- In-memory only
- React state (hooks)
- No APIs unless specified

---

## 4. UI Rules
- Clean, modern, minimal
- Desktop-first, mobile-safe
- No emojis

---

## 5. Code Rules
- Keep it simple (no overengineering)
- Use latest stable libs
- Follow existing patterns
- Handle real edge cases only

---

## 6. Agent Rules
- Read this file before changes
- Do not assume beyond scope
- Prefer editing over creating
- Stay consistent with codebase
- Ask if unclear

---

## 7. Execution
1. Plan (with success criteria)
2. Build
3. Test (Jest + Playwright)
4. Fix all issues
5. Verify app runs

---

## 8. Done When
- Features complete
- Tests pass
- No known issues
- App runs
