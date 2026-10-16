# stevestuff.app

Maintenance records and live gauges for Bounty Hunter.

## Live data

Ship Monitor (boat laptop) updates `data.json` every few minutes.

The home page fetches it and shows fuel/water gauges with last-updated time.

To update data from the boat:
```bash
# Example: commit new readings
# (or use GitHub API / curl with token)
```

Deploy: Connect this repo to Cloudflare Pages (or wherever stevestuff.app is hosted) for automatic deploys on push.
