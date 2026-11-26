# PRMX.in — Personal Software & Systems Lab

This repository powers **[PRMX.in](https://prmx.in)** via Cloudflare Pages.

Currently, it features **Ujan Chakraborty's** personal software engineering & tools portfolio:
- **FlyOverhead**: High-precision ADS-B flight overhead tracking with predictive Telegram alerts.
- **DeskGlide**: Cross-machine input and clipboard multiplexer.
- **MINUTES**: Automated 5-city news intelligence and Telegram publishing pipeline.
- **StreamDVR & ClipDeck**: Headless 24/7 stream monitor and circular ring-buffer clip engine.
- **PRMX API Gateways & Clipping Tools**.

---

## Restoring DJ Dev Site

The previous DJ Dev site is backed up in two safe places:
1. **Local backup file**: `index.djdev.html` in this repository.
2. **Git branch**: `backup/dj-dev`

### To switch back to DJ Dev:
```bash
# Method A: Copy the backup file
cp index.djdev.html index.html
git add index.html
git commit -m "Restore DJ Dev website"
git push origin main
```
or
```bash
# Method B: Checkout from backup branch
git checkout backup/dj-dev -- index.html robots.txt sitemap.xml
git commit -m "Restore DJ Dev website from backup branch"
git push origin main
```
