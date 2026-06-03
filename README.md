# 3D LoL Models

A collection of 2,091 League of Legends champion skin 3D models in GLB format,
sourced under Riot Games' "Legal Jibber Jabber" fan content policy.

## Contents

- 172 champions
- 2,091 total skins (base skins + all cosmetic skins)
- Format: GLB (GL Transmission Format Binary)
- Models organized across 11 release batches (models-v1 through models-v11)

## Skin Data

`skins.json` is included in this repo and maps every skin ID to its champion and skin name.

```json
[
  {
    "skin_id": "266000",
    "champion": "Aatrox",
    "slug": "aatrox",
    "skin_name": "Aatrox",
    "glb_file": "266000.glb"
  }
]
```

## Usage

Models are release assets split across 11 batches (models-v1 to models-v11).
Check the [releases page](https://github.com/nothing17777/3d---lol--models/releases)
to find which batch contains your skin.

**Download via terminal:**
```bash
curl -L "https://github.com/nothing17777/3d---lol--models/releases/download/models-v1/1000.glb" -o "1000.glb"
```

**Note:** GitHub release URLs have CORS restrictions and cannot be loaded
directly in web apps. Use a proxy such as a Cloudflare Worker.

## Skin ID Format

- Base skin: `{champion_id}000` — e.g. `266000` = base Aatrox
- Additional skins increment the last 3 digits: `266001`, `266002`, etc.

## Legal

This project was created under Riot Games' "Legal Jibber Jabber" policy using
assets owned by Riot Games. Riot Games does not endorse or sponsor this project.

Models sourced from [modelviewer.lol](https://modelviewer.lol) (Khada).

## Related Project

Coming soon.
