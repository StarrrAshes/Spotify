# Spotify
  ╔══════════════════════════════════════════════════════════════════╗
  ║  Spotify Stats — Editorial Listening Dashboard                  ║
  ║  Version: 2.0.0                                                 ║
  ║  Author:  Bat                                 ║
  ║  Date:    2026-03-17                                             ║
  ║  License: MIT                                                    ║
  ║                                                                  ║
  ║  A self-contained Spotify analytics dashboard using PKCE OAuth. ║
  ║  Displays top tracks, artists, genre maps, audio DNA radar,     ║
  ║  and recent listening history across configurable time ranges.   ║
  ║                                                                  ║
  ║  Keyboard shortcuts:                                             ║
  ║    1–5       Navigate between pages                              ║
  ║    D         Toggle dark/light mode                              ║
  ║    Escape    Close any open modal/toast                          ║
  ║                                                                  ║
  ║  State flow:                                                     ║
  ║    LOGIN → (PKCE auth) → CODE_EXCHANGE → LOADING → DASHBOARD    ║
  ║    DASHBOARD: pages { tracks | artists | genres | audio | recent }║
  ║    Each page supports time range switching with in-memory cache. ║
  ╚══════════════════════════════════════════════════════════════════╝
