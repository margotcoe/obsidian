---
tags: 
Links:
  - "[[Home Server]]"
---
- - -
# ping_script.py:
```
python3 ~/Documents/PlexServer_Misc/ping_script.py
```

```
import os

websites = [
    "bazaar.margot.wiki",
    "blog.margot.wiki",
    "docker.margot.wiki",
    "dozzle.margot.wiki",
    "grafana.margot.wiki",
    "hydra.margot.wiki",
    "margot.wiki.margot.wiki",
    "nginx.margot.wiki",
    "ombi.margot.wiki",
    "plex.margot.wiki",
    "prometheus.margot.wiki",
    "radarr.margot.wiki",
    "sabnzbd.margot.wiki",
    "sonarr.margot.wiki",
    "tautulli.margot.wiki",
    "vaultwarden.margot.wiki"
]

status = {}

for website in websites:
    response = os.system(f"ping -c 1 {website}")
    if response == 0:
        status[website] = "up"
    else:
        status[website] = "down"

for website, state in status.items():
    print(f"{website} is {state}")

```

# new_script.py

- - -
6:44 PM - July 21, 2024