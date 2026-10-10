# Roblox Avatar for GTA V Legacy — Starter Project

Status: design/specification scaffold only. This is NOT a finished or tested GTA V mod.

## Goal
Create a single-player GTA V Legacy story-mode player-character replacement based on the user's current Roblox avatar reference. Preserve rigid, blocky Roblox proportions.

## Current scope
- GTA V Legacy / RAGE
- Story mode only; do not use in GTA Online
- Replace the player model with a blocky Roblox-style avatar
- Appearance reference: red zip hoodie with white sleeve marks and dark chest graphics; messy black hair; silver spiked head accessory; dark/obscured face; gray distressed jeans with dark markings; dark shoes
- Spawn/intro concept: apartment or safehouse, then free roam
- Keep normal GTA free-roam and vehicle gameplay
- Animation enhancement is secondary; retain the blocky silhouette

## Build status and limitations
No GTA-compatible model, textures, skeleton, or install recipe has been generated or tested yet. The screenshot is a visual reference, not a source asset. A proper implementation still needs a legally usable/creator-authorized model or a recreated model, texture work, a GTA-compatible rig/export, and in-game validation.

## Suggested implementation milestones
1. Inspect Melty's game information and supported install-recipe format for GTA V Legacy.
2. Confirm a supported character-replacement approach for the installed GTA V Legacy build.
3. Create/recreate a blocky model and textures from authorized assets; do not scrape or redistribute Roblox-owned assets without permission.
4. Export and convert to the file formats expected by the chosen GTA modding pipeline.
5. Add a reversible install recipe; preserve original files and document uninstall/rollback.
6. Test in story mode: model loads, materials render, proportions remain blocky, movement and vehicles work, no crash.
7. Capture a gameplay screenshot and run package/recipe validation.
8. Only then upload/publish, after the user explicitly approves the final listing.

## Safety
- Never publish game files, Rockstar assets, or third-party assets without permission.
- Never run the mod in GTA Online.
- Do not put API tokens or credentials in this repository.
