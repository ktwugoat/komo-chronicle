# Next Steps

## Completed
- New git repo created
- Git author confirmed as Koutian Wu <ktwu01@gmail.com>
- Research dossier created
- Milestone table v1 and v2 created
- Initial timeline / storymap JSON scaffold created
- First landing page prototype created
- SOTA design review added at `research/sota-design-review.md`
- Editorial content schema added:
  - `data/chapters.json`
  - `data/locations.json`
  - `data/validation.json`
  - `data/sources.json`
- Landing page rebuilt into an editorial chronicle with:
  - premium hero + thesis framing
  - phase rail / quick navigation
  - narrative timeline chapters
  - synced geography module
  - curated validation groups
  - source archive

## Next implementation steps
1. Replace the current abstract geography treatment with a real map layer (preferably MapLibre) while preserving the restrained editorial feel.
2. Strengthen the source archive by capturing more direct primary URLs for early academic/founding details and the 2025 Utimaco announcement page.
3. Add a denser secondary archive/reference timeline view using the existing `data/timeline.json` content.
4. Introduce real media/artifact slots (photos, article snippets, conference visuals) only for the strongest source-backed chapters.
5. Consider migrating the static prototype into Astro once the content model stabilizes.
