# Jellyfin Custom for Home Assistant

A custom Jellyfin integration for Home Assistant that overrides the built-in version.

Differences:

- Username included in friendly_name
- Additional transcoding attributes on media_player entity
- Poster/poster precedence tweaks (series & season posters, primary art before backdrop)

Built on top of the latest upstream Jellyfin integration, including its HTTPS artwork proxying.

## Installation via HACS

1. Open Home Assistant and go to **HACS → Integrations**
2. Click the **⋮** menu (top right) → **Custom repositories**
3. Add repository:
   - URL: `https://github.com/XanderStrike/jf-custom`
   - Category: **Integration**
4. Click **Add**, then search for "Jellyfin Custom" and click **Install**
5. **Restart Home Assistant**
6. Go to **Settings → Devices & Services → Add Integration** → search "Jellyfin"

This replaces the built-in Jellyfin integration. Existing configurations will continue to work (theoretically, worked on my machine etc).
