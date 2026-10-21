# Orvix Central Hub (orvixcentralhub.com)

Admin-only site: sign in → Orvix Aero / Orvix Grid. Orvix Aero has Bug reports
(status + reply the pilot sees, screenshots) and Testers & admins (admins,
members, Android sign-ups, paywall preview). Static page, Supabase auth; every
read/write goes through the hub_* functions (migration
20261021060000_central_hub.sql), which refuse non-admins.

Published from its own repo jgdeleon22/orvixcentralhub (GitHub Pages, custom
domain). This folder is the source copy; keep both in sync.
Supabase Auth needs https://orvixcentralhub.com/** in Redirect URLs for Google sign-in.
