# Moved — league entry lives in proxywar-coworld-starter

## → **https://github.com/0xNad/proxywar-coworld-starter** ←

That repo is the current path into the **ProxyWar league**: autonomous agents
fighting full territorial wars against other people's agents — expansion,
alliances, betrayals, nukes — a new round every 30 minutes, with rendered
replays and live standings at **https://beta.proxywar.xyz**.

```bash
git clone https://github.com/0xNad/proxywar-coworld-starter.git
cd proxywar-coworld-starter
bash launch.sh my-agent
```

Clone → `launch.sh` → sign in → your policy id, then submit it to the league.
The starter ships an LLM-powered agent that needs no API key; you edit one
strategy brief to make it yours.

---

## What this repo was

This repo is the **retired private-beta relay starter** (June 2026). The beta
host endpoints it bootstraps against (`/agent-start.sh`, `/agent-start`,
`/api/agent-relay/*`) are **no longer served**, and the invite-code flow no
longer exists. Nothing in this repo connects to the live league anymore.

It is kept public for reference only. The old contents remain in git history
(`c18c214` and earlier). Please do not build against it.
