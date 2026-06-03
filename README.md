# 3D LoL Models

A collection of 2,091 League of Legends champion skin 3D models in GLB format,
sourced under Riot Games' "Legal Jibber Jabber" fan content policy.

## Contents

- 172 champions
- 2,091 total skins (base skins + all cosmetic skins)
- Format: GLB (GL Transmission Format Binary)
- Models organized across 11 release batches (models-v1 through models-v11)

## Files

- `skins.json` — maps every skin ID to champion name, skin name, and slug
- `batch_lookup.json` — maps every skin ID to its release batch number (1-11)

## Usage

Models are release assets split across 11 batches. Use `batch_lookup.json` to find
which batch a skin is in, then construct the download URL:

```bash
curl -L "https://github.com/nothing17777/3d---lol--models/releases/download/models-v{batch}/{skin_id}.glb" -o "{skin_id}.glb"
```

Example — download base Aatrox (batch 5):
```bash
curl -L "https://github.com/nothing17777/3d---lol--models/releases/download/models-v5/266000.glb" -o "266000.glb"
```

**Note:** GitHub release URLs have CORS restrictions and cannot be loaded
directly in browser web apps. Use a Cloudflare Worker proxy to serve models
to a frontend.

## Skin ID Format

- Base skin: `{champion_id}000` — e.g. `266000` = base Aatrox
- Additional skins increment the last 3 digits: `266001`, `266002`, etc.

## Legal

This project was created under Riot Games' "Legal Jibber Jabber" policy using
assets owned by Riot Games. Riot Games does not endorse or sponsor this project.

Models sourced from [modelviewer.lol](https://modelviewer.lol) (Khada).

## Related Project

Coming soon.
