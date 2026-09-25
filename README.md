# RAVENET Design Log

Design log website for the MTE 481 capstone project (Fall 2026): a low-cost mesh
network device that keeps texting and location sharing working in crowds dense
enough to saturate cell towers.

**Live site:** https://baconomist.github.io/relay-design-log/

## Structure

The whole site is a single static file, `index.html`. No build step, no
dependencies. GitHub Pages serves it from the `main` branch root and rebuilds
automatically on every push.

## Adding a design log entry

Entries are stored in the `ENTRIES` array inside the `<script>` tag at the
bottom of `index.html`. Add a new object at the top of the array:

```js
{
  date: "2026-10-03",
  title: "LoRa range testing in E7 parking lot",
  members: [
    { name: "Jane Doe", contribution: "Ran range tests at 100 m intervals, logged RSSI" },
    { name: "John Smith", contribution: "Built the test firmware and serial logger" }
  ],
  notes: "Measured usable range at 380 m line-of-sight before packet loss exceeded 5%..."
}
```

Then commit and push:

```bash
git add index.html
git commit -m "Log entry: LoRa range testing"
git push
```

The live site updates within about a minute.

Entries sort themselves by date (newest first), so the position in the array
doesn't strictly matter. Drop the `template: true` flag from the seed entry once
you replace it with a real one — it's what draws the dashed border and the
"Example" badge.
