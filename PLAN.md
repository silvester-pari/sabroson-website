# Plan: Website Expansion for ¡SABROSON!

This document outlines the step-by-step plan for extending the minimal landing page into a full-fledged band website based on your requirements. The design will be in German, funny, a bit crazy, colorful, and inspired by both your past `PromotedEvents` style and the reference website (matatu.gruetze.at).

## Phase 1: Asset Transfer & File Organization (✅ DONE)
1. **Create Download Directory:** Create `public/downloads/`. (✅)
2. **Move Press Material:** Copy `20251023_sabroson_kurzinformation.pdf` and `sabroson_presse_information_bilder.zip` from `TEMP_BAND_PROMOTION/` to `public/downloads/`. (✅)
3. **Move Images:** Copy the images `collage posen neu.jpg` and `Sabroson Konzert Musikpavillon Juli 2025.jpeg` from `TEMP_BAND_PROMOTION/pressefotos/` to `public/img/`. (✅)

## Phase 2: Impressum Page Creation (✅ DONE)
1. **Create `src/pages/impressum.astro`**: Use the existing `PageLayout.astro`. (✅)
2. **Add Legal Content**: Integrate the data from `Vereinsregisterauszug_SABROSON.md` as placeholder content (Name, ZVR-Zahl, address, and board members). (✅)

## Phase 3: New Components for Main Page (Single Page Layout) (✅ DONE)
We will expand `src/pages/index.astro` to include the following new sections (similar to the structure of matatu.gruetze.at):

1. **About Section (`src/components/About.astro`)**: (✅)
   - Insert the "Bandvorstellung" and "Biografie" texts.
   - Include the "Pressestimmen" (quote from Tips.at).
   - Use the wide `collage posen neu.jpg` image here to add visual flair.

2. **Band Members (`src/components/Members.astro`)**: (✅)
   - Create a text-based list of the 10 band members and their instruments as provided in the document. (Placeholder for future individual photos).

3. **Media & Press (`src/components/Media.astro`)**: (✅)
   - Include links to download the Kurzinformation (PDF) and the Presse-Bilder (ZIP).
   - Embed or link the SoundCloud track ("Cadera de Madera") and the YouTube videos.
   - Use `Sabroson Konzert Musikpavillon Juli 2025.jpeg` in this section.

4. **Contact & Socials (`src/components/Contact.astro` - if not existing/update)**: (✅)
   - Add Anna's booking contact details (email, phone).
   - Link all social media profiles (Instagram, Facebook, YouTube, SoundCloud).

## Phase 4: Styling and "Crazy" Vibe Restoration (✅ DONE)
1. **Look & Feel Updates**: (✅)
   - Reintroduce the wild animations (`frantic-zoom`, `frantic-shake`) and contrasting borders (orange, yellow, brown, black) from the old `PromotedEvents.astro`.
   - Apply this styling to call-to-action elements, perhaps for booking requests or the upcoming concerts (`Events.astro`).
   - Ensure the typography retains a loud, fun character (e.g., Courier typography, uppercase headers, slight rotations, thick borders).

---

*Please review this plan. Once you confirm, I will begin with Phase 1!*