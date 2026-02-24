# ha-blueprints

Custom Home Assistant blueprints.

## Blueprints

### `motion_light_standard.yaml` — Motion Light (Standard)
Einheitlicher Blueprint für alle Bewegungsmelder-Automationen.

**Inputs:**
| Parameter | Default | Beschreibung |
|---|---|---|
| Bewegungsmelder | — | Binary sensor (motion) |
| Licht(er) | — | Zu steuernde Lichter |
| Wartezeit | 30 min | Wie lange Licht nach letzter Bewegung an bleibt |
| Einblend-Zeit | 5s | Transition beim Einschalten |
| Ausblend-Zeit | 10s | Transition beim Ausschalten |

**Import in HA:**
Settings → Automations & Scenes → Blueprints → Import Blueprint
→ URL: `https://raw.githubusercontent.com/mindrunner/ha-blueprints/main/motion_light_standard.yaml`
