# XLQP Gen1

![XLQP Gen1 documentation preview](https://xlqp-docs.vercel.app/og.png)

[![Documentation](https://img.shields.io/badge/Documentation-XLQP%20Gen1-8b5cf6?style=for-the-badge)](https://xlqp-docs.vercel.app/docs)
[![Website](https://img.shields.io/badge/Website-xlqp.lol-22c55e?style=for-the-badge)](https://xlqp.lol/)
[![Discord](https://img.shields.io/badge/Discord-Verbal-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/verbal)

XLQP Gen1 is a complete Roblox Luau interface library for building polished hubs, tools, dashboards, menus, and interactive experiences from one configurable window API. It includes flexible navigation, a large element collection, themes, media tools, data views, notifications, key systems, configuration persistence, and advanced window controls.

Created by [Sirus](https://www.sentivel.com) and Itsjose4.

## Quick start

```luau
local Library = loadstring(game:HttpGet("https://raw.githubusercontent.com/josediaz765/XLQP-UIS/main/xlqp%20gen1"))()

local Window = Library:MakeWindow({
    Branding = {
        Name = "My Hub",
        Subtitle = "XLQP Gen1",
        Icon = "home",
    },
})
```

## Repository files

| File | Description |
| --- | --- |
| [`xlqp gen1`](./xlqp%20gen1) | Current XLQP Gen1 UI source used by the public loader. |
| [`xlqp example full`](./xlqp%20example%20full) | Complete, comment-free example covering the available XLQP Gen1 APIs and elements. |
| [`LICENSE`](./LICENSE) | License and usage terms for XLQP Gen1. |

## Resources

- [Documentation](https://xlqp-docs.vercel.app/docs)
- [XLQP website](https://xlqp.lol/)
- [Verbal Discord](https://discord.com/invite/verbal)
- [Sentivel](https://www.sentivel.com)

## License

XLQP Gen1 is distributed under the terms in [LICENSE](./LICENSE). Read the license before using or distributing the source.
