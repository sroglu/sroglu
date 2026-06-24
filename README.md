# Hi, I'm Mehmet Sarıoğlu 👋

![banner](https://github.com/sroglu/sroglu/blob/main/Resources/Img/mossWorking.gif)

**Senior Unity / C# Engineer — gameplay systems, frameworks & simulation.**

I build reusable Unity systems and the framework plumbing — data stores, MVC, DI,
caching, navigation — that games and simulators are built on, plus offline content
pipelines for geospatial / simulation data. I care about clean architecture,
zero-allocation hot paths, and code other engineers can actually reuse.

- 🔭 **Currently:** building reusable Unity 6 gameplay & framework modules
- 🧰 **Core stack:** Unity 6 · C# · Burst / Jobs / Mathematics · URP (post-processing / LUT / blur) · XR/VR · Python
- 🛰️ **Domains:** gameplay & framework engineering · digital-twin & training simulation · geospatial terrain · eye/head-tracking XR
- 📫 **Reach me:** [LinkedIn](https://www.linkedin.com/in/mehmetsrl)

---

### 📌 Pinned work

| Repo | What it is |
|---|---|
| **[GameDataStore](https://github.com/sroglu/GameDataStore)** | `StructLayout.Explicit` tagged-union value type (20+ types, zero-alloc `ToString`) + self-registering typed DB via C# 11 static interface members. |
| **[FoodMatch3D](https://github.com/sroglu/FoodMatch3D)** | Finished, playable 3D match-3 (Unity 6) — data-driven JSON levels, custom `LevelEditor` tooling, full game loop, Android build. |
| **[TerrainPreprocessing](https://github.com/sroglu/TerrainPreprocessing)** | Offline toolchain: military **DTED** elevation + **OSM** → engine-ready 3D terrain / buildings / vegetation. Custom DTED parser + Blender (`bpy`). |

Also building a set of reusable Unity framework modules (`mehmetsrl.*`): **MVC**,
**RemoteResourceCache** (tiered cache + async loader), **Render** (URP 17 post-processing),
**Navigation**, **ServiceRegistry**, **DataStructures**, **Utilities**.
