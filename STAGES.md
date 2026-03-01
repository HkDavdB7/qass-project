# Qass — Stage Tracker

## Status Key
- ⬜ Not started
- 🔵 In progress
- ✅ Complete (Sonnet approved)
- 🔴 Blocked / needs fix

---

## MVP Stages

| # | Stage | Status | Notes |
|---|-------|--------|-------|
| 1 | Foundation — Supabase schema + project setup | ✅ | Completed 2026-03-01. All 9 tables + RLS + triggers live. |
| 2 | Auth + Roles — Phone OTP, 4 user roles, protected routes | 🔵 | In progress — test mode OTP, Lovable prompts ready |
| 3 | Customer: Shop Discovery — listing, filters, shop detail | ⬜ | |
| 4 | Customer: Booking Flow — service → barber → time → confirm | ⬜ | |
| 5 | Customer: Profile + My Bookings | ⬜ | |
| 6 | Owner Dashboard — shop setup, services, staff, bookings | ⬜ | MVP complete after this |

---

## Post-MVP Stages

| # | Stage | Status | Notes |
|---|-------|--------|-------|
| 7 | Barber Dashboard — daily schedule, accept/reject, earnings | ⬜ | |
| 8 | Notifications — WhatsApp + SMS (Twilio) | ⬜ | |
| 9 | Reviews & Ratings | ⬜ | |
| 10 | Subscriptions + Loyalty | ⬜ | |
| 11 | Admin Panel | ⬜ | |
| 12 | Arabic + RTL | ⬜ | |
| 13 | QA + Polish | ⬜ | |
| 14 | Deploy — Vercel + Expo EAS | ⬜ | |

---

## Stage Log
| Date | Stage | Summary | Issues |
|------|-------|---------|--------|
| 2026-03-01 | Stage 1 | Schema applied via Monaco JS injection. All 9 tables live, RLS + triggers active. Verified in Table Editor. | None |
| 2026-03-01 | Stage 2 | Started. Phone OTP test mode + Lovable auth prompts prepared. Pending: Supabase phone provider enable + Lovable build. | None yet |
