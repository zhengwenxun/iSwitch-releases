# iSwitchG Download Page - Cloudflare Pages Configuration

## Quick Setup

This is a static site, no build process needed.

### Cloudflare Pages Settings:

**Framework preset**: None

**Build command**: `echo "Ready"`

**Build output directory**: `docs`

**Environment variables**: (none required)

---

## Auto-deployment

This site auto-updates when:
- GitHub Actions pushes to the `pages` branch
- Triggered by new release tags

The `pages` branch contains only the `docs/` directory with:
- `index.html` - Download page
- `releases.json` - Release metadata
- `build.sh` - Placeholder build script
