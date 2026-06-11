# GS-Paracosm Profile Visual System

This profile uses a light cyber embedded-console style. The goal is clean engineering presentation, not decorative overload.

## Color Tokens

| Token | Hex | Usage |
| --- | --- | --- |
| `sky` | `#60A5FA` | primary signal, boot, build flow |
| `violet` | `#A78BFA` | control, servo, roadmap branch |
| `cyan` | `#22D3EE` | debug, data path, realtime motion |
| `teal` | `#2DD4BF` | online state, robotics, completion |
| `ink` | `#1E293B` | title text |
| `muted` | `#64748B` | secondary text |
| `panel` | `rgba(255,255,255,.84)` | card fill |
| `line` | `#DBEAFE` | card border and soft grid |

## Typography

| Role | Size | Weight |
| --- | --- | --- |
| Page visual title | 24-28 | 800 |
| Primary node | 15-18 | 800 |
| Metadata | 10.5-12 | 600 |
| Center brand | 52-60 | 800-900 |

Use `Segoe UI`, `Microsoft YaHei`, `Arial`, sans-serif fallback.

## Shape System

- Outer panels: `rx=24` to `rx=28`.
- Cards: `rx=16` to `rx=20`.
- Chips: `rx=13`.
- Prefer one panel per section. Avoid nested heavy cards.
- Keep image width at `96%` in README except full-bleed header/footer.

## Animation Rules

| Motion | Duration | Use |
| --- | --- | --- |
| `flow` | 4.2s-5.2s | rails, data paths |
| `float` | 3.0s-3.6s | cards and nodes |
| `pulse` | 2.2s-2.8s | online dots, core nodes |
| `scan` | 3.0s-4.5s | vertical/horizontal scan beams |
| `spin` | 18s-30s | background rings only |

Keep opacity transitions subtle. Motion should feel like instrumentation, not noise.

## Section Roles

| Section | Role |
| --- | --- |
| Hero | identity and current engineering direction |
| Runtime Window | boot/debug/build/standby operational feel |
| Current Coordinate | current, next, later, tools |
| MCU Radar | cross-vendor MCU ecosystem |
| Roadmaps | learning and engineering progression |
| Tech Stack | capability map, not a long list |
| Project Matrix | repository topology and ownership |
| Dynamic Track | GitHub activity framed as runtime telemetry |
| Code Habits | engineering rules and maintenance taste |

## Copy Style

- Prefer concrete engineering words: boot, OTA, RTOS, EtherCAT, FOC, CiA402, BSP, OSAL.
- Avoid overclaiming. Use `current`, `next`, `later` for learning status.
- Keep self-description short; let project structure speak.
