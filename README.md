# Speed-to-Lead dashboard

Owner dashboard for the Speed-to-Lead Revenue Engine (n8n + GoHighLevel + Supabase).
Shows, per lead source (Meta, website, referral), the funnel, speed to first reply, cost per lead / booked call / show and no-show rate.
Live mode reads the number-only Supabase view `dashboard_daily` with the public publishable key; Demo mode uses real ad spend with generated leads.
