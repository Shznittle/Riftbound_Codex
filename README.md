# Riftbound Codex

- `riftbound-codex.html`: the app. Download it and open it in Chrome or Edge.
- `data/codex-data.json`: the meta data the app's **Update Meta** button pulls (decklists, guides, ban list, matchups, computer playbooks, card data).

## Updating the meta
1. Replace `data/codex-data.json` with a newer copy (Claude can make one).
2. Make sure its `"version"` number is higher than the last one (it's a date: 20261115, then 20261123 and so on).
3. Commit to the `main` branch.
4. In the Codex, press **Update Meta**, then **Reload to apply**.

The repo has to be public for the button to read it.
