# Examples

YAML sketches for Home Assistant. **Adapt entity IDs** before use. These are not drop-in production packages.

| File | Purpose |
|------|---------|
| [`helpers.yaml`](helpers.yaml) | Kill switch + offset setpoints |
| [`tado-demand-template.yaml`](tado-demand-template.yaml) | Aggregate valve demand ≥ 20% |
| [`offset-stepped-set-script.yaml`](offset-stepped-set-script.yaml) | ±5 K stepped EMS writes |
| [`offset-bump-automation.yaml`](offset-bump-automation.yaml) | Demand on/off → bump / idle |

Recommended order: helpers → demand template → stepped script → automation.
