# Qass — Database Schema
_Updated after Stage 1 completes. Placeholder for now._

## Tables Needed (MVP)
- users (id, phone, email, name, role, preferred_barber_id, preferred_branch_id, notes)
- shops (id, owner_id, name, description, photos, location, working_hours, is_approved)
- branches (id, shop_id, name, address, location, working_hours)
- barbers (id, shop_id, user_id, name, skills, working_hours, days_off, commission_pct)
- services (id, shop_id, name, description, duration_min, price, category)
- bookings (id, customer_id, shop_id, barber_id, service_id, branch_id, start_time, end_time, status, notes, type)
- time_slots (id, barber_id, date, start_time, end_time, is_available)

## Tables Needed (Post-MVP)
- subscriptions (id, customer_id, shop_id, plan, price, start_date, end_date, status)
- payments (id, booking_id, amount, method, status, reference)
- reviews (id, customer_id, barber_id, shop_id, rating, comment, created_at)
- promotions (id, shop_id, code, discount_pct, valid_from, valid_to, max_uses)
- loyalty_points (id, customer_id, shop_id, points, last_updated)

## Booking Status Values
pending → confirmed → completed → cancelled → no_show

## Booking Types
immediate | scheduled | recurring | preferred_weekly
