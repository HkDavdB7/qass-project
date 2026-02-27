# Qass — Barbershop Booking Platform (Kuwait)

## What It Is
Mobile + web platform for barbershops in Kuwait.
Customers book barbers by time slot. Shops manage staff, services, and schedules.

## Stack
- Frontend: React + Vite + Tailwind (via Lovable)
- Backend: Supabase (DB + Auth + Edge Functions + Realtime)
- Mobile: Expo / React Native (future)
- Auth: Supabase Phone OTP
- SMS: Twilio
- Payments: MyFatoorah (KNET)
- Hosting: Vercel
- Repo: github.com/HkDavdB7/qass-project (this repo)
- App code: github.com/HkDavdB7/Qassap

## User Roles
1. Customer — books services
2. Barber — manages daily schedule
3. Shop Owner — manages shop, staff, bookings
4. Platform Admin — approves shops, manages platform

## MVP Scope (Launch First)
- Shop discovery + detail page
- Booking flow (service → barber → date/time → confirm)
- Customer profile + my bookings
- Basic owner dashboard

## Full Scope (Post-MVP)
- Subscriptions + loyalty
- Notifications (WhatsApp + SMS)
- Reviews & ratings
- Queue system
- Analytics dashboard
- Admin panel
- Arabic/RTL support
- Home service booking

## Kuwait Market Priorities
- Preferred weekly time booking
- Arabic + English
- WhatsApp notifications (not email)
- Residential area targeting
- KNET payment support

## Agent Roles
- Gemini (free): Architecture decisions + stage specs
- Lovable ($25/mo): UI building (primary builder)
- Claude Sonnet ($20/mo): Project manager + QA reviewer
- GPT ($10/mo): Complex logic, edge functions, Supabase RPC
