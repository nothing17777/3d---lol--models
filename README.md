# 3D LoL Models

A collection of 2,091 League of Legends champion skin 3D models in GLB format, 
sourced under Riot Games' "Legal Jibber Jabber" fan content policy.

## Contents

- 172 champions
- 2,091 total skins (base skins + all cosmetic skins)
- Format: GLB (GL Transmission Format Binary)
- Models organized across 11 release batches (models-v1 through models-v11)

## Skin Data

A complete skin metadata file is included: `skins.json`

```json
[
  {
    "skin_id": "266000",
    "champion": "Aatrox", 
    "slug": "aatrox",
    "skin_name": "Aatrox",
    "glb_file": "266000.glb"
  },
  ...
]
```

Use this to look up which skin ID corresponds to which champion and skin name.

## Usage

Models are available as GitHub Release assets. Use `skins.json` to find the 
skin ID, then download from the appropriate batch (models-v1 through models-v11).

To find which batch a skin is in, check the releases page:
https://github.com/nothing17777/3d---lol--models/releases

Example direct URL:
https://github.com/nothing17777/3d---lol--models/releases/download/models-v1/1000.glb

## Skin ID Format

- Base skin: `{champion_id}000` (e.g. `266000` = base Aatrox)
- Additional skins: `{champion_id}001`, `{champion_id}002`, etc.

## Legal

This project was created under Riot Games' "Legal Jibber Jabber" policy using 
assets owned by Riot Games. Riot Games does not endorse or sponsor this project.

Models sourced from [modelviewer.lol](https://modelviewer.lol) (Khada).

## Related Project

will come back later
