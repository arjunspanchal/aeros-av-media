# aeros-av-media

Public image hosting for **@aeros_av** Instagram / Aeros AV Facebook posts.

Each week's slides live in `YYYY-wNN/<post-slug>/NN.jpg`. The Supabase publisher (`ig-publish` edge function, project `smcfbapcsjhxaxigcpjj`) reads approved posts from `public.ig_queue` and passes these raw URLs to the Instagram Graph API.

Do not put anything private here — the repo is public.
