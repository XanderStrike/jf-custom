# Jellyfin Custom for Home Assistant

A custom Jellyfin integration for Home Assistant that overrides the built-in version.

The only difference is it makes the friendly_name look more like what the plex integration produces, for consistency in my [now-playing](https://github.com/XanderStrike/now-playing) card:

<img width="397" height="699" alt="image" src="https://github.com/user-attachments/assets/20d75954-010b-44b6-ba2a-761e8bc30a1d" />

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
