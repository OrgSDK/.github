# OrgSDK public brand assets

The navy-and-paper identity used on [orgsdk.ai](https://orgsdk.ai), GitHub and
the [OrgSDK LinkedIn page](https://www.linkedin.com/company/orgsdk/).
Updated 22 October 2026.

## Identity

Use the supplied connected-node mark and OrgSDK wordmark in `source/`. These
are preserved copies of the website artwork. Keep the mark's geometry and the
capitalization **OrgSDK**. The public identity replaces the earlier indigo
Orbit-O imagery.

| Colour | Hex | Use |
| --- | --- | --- |
| Org ink | `#0f1a3d` | Logo, text |
| System blue | `#214e8a` | Accents |
| Slate | `#647085` | Supporting text |
| Off-white | `#faf8f3` | Background |
| Border | `#c9cbd0` | Rules |

Use Arial/Helvetica sans-serif typography, clear hierarchy, generous spacing
and square edges. Supplied logo artwork retains its original lettering.

## Files

Each export has an editable, self-contained SVG source and a PNG for upload.

| Export | Size | Use |
| --- | --- | --- |
| `avatar-512.png` | 512 × 512 | GitHub organization avatar |
| `linkedin-logo-400.png` | 400 × 400 | LinkedIn company logo |
| `linkedin-cover-1512x256.png` | 1512 × 256 | LinkedIn company cover |
| `github-profile-1280x400.png` | 1280 × 400 | GitHub profile README header |
| `github-social-1280x640.png` | 1280 × 640 | OrgSDK repository social preview |
| `github-org-social-1280x640.png` | 1280 × 640 | Organization profile repository preview |
| `github-plugins-social-1280x640.png` | 1280 × 640 | Plugin authoring repository preview |

The avatars use an opaque off-white background so the navy logo remains visible
on light and dark interfaces. Keep essential cover copy away from the edges.

## Copy

**Headline:** A local home for your AI’s actual work.

**Supporting line:** Your AI brings the reasoning. OrgSDK gives its work
somewhere to live.

**Capabilities:** Persistent projects. Tested actions. Scoped execution.

Describe the platform as source-available, matching its current licence. Link
to [the platform](https://github.com/OrgSDK/OrgSDK) and [orgsdk.ai](https://orgsdk.ai).

The workspace's `scripts/render-social-brand.mjs` rebuilds these assets using
the website source artwork and the installed frontend's Sharp renderer.
No generated or redrawn replacement logo is used.
