# Improvado Assignment — Multi-Channel Ad Performance

## Stack
- **Snowflake** — cloud data warehouse
- **dbt** — data transformation and modeling  
- **Looker Studio** — dashboard and visualization

## Data Model
Three raw tables loaded into Snowflake: FACEBOOK_ADS, GOOGLE_ADS, TIKTOK_ADS. Unified into UNIFIED_AD_PERFORMANCE via dbt UNION ALL model, normalizing field names and calculating CTR, CPC, CPM.

## Dashboard
[Live Dashboard](https://datastudio.google.com/reporting/b8c2dbaf-d7e0-4daa-952e-3928957e67ee)

## Key Insights
- TikTok = 57% of spend but lowest CTR — awareness play
- Google = highest CTR — best for intent capture
- Influencer_Collab = top converter at $3.99 CPC
- Search_Generic_Terms = $17 CPC — budget risk, needs optimization
