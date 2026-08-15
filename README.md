# DealForge

Utah-first real-estate acquisition and underwriting platform.

## Run

Install Node.js 20+, then:

```bash
npm install
npm run dev
```

Open http://localhost:3000.

## Supabase

Create a free project at https://supabase.com, copy `.env.example` to `.env.local`, add your URL and anon key, then run `supabase/schema.sql` in the SQL editor.

## Current foundation

- Flip / rental / BRRRR underwriting
- Maximum offer
- Deal and risk scores
- Utah / Other Markets split
- Deal Hunter foundation
- Supabase schema for properties, comps, markets and underwriting snapshots
- Server-side underwriting endpoint

Next: Supabase persistence, listing-data adapters, comparable sales/rents, Utah GIS, Census, BLS, HUD and university enrichment, then automated Deal Hunter sources.

Do not scrape commercial listing sites unless their terms/API permit it.