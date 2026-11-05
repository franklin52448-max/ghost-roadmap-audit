# GHOST Roadmap Link Audit Report (Bounty #8)

**Audit Target:** gh0st.fyi roadmap links
**Date:** November 5, 2026
**Auditor:** Franklin (franklin52448-max)

## Live Status of Roadmap Links

| # | Roadmap Link | URL | HTTP Status | Observed Content |
|---|---|---|---|---|
| 1 | Inspect checker | https://gh0st.fyi/checker | 404 Not Found | None |
| 2 | Read the thoughts | https://gh0st.fyi/thoughts | 404 Not Found | None |
| 3 | Open Watcher | https://gh0st.fyi/watcher | 200 OK | GH0ST Watch "Coin Observatory" page |
| 4 | See recent scans | https://gh0st.fyi/scans | 404 Not Found | None |
| 5 | Spawn an agent | https://gh0st.fyi/spawn | 404 Not Found | None |
| 6 | Explore AgentKit | https://gh0st.fyi/agentkit | 200 OK | GH0ST Developer Kit, developer preview, paid access in preparation |

## Details

- **/watcher (200 OK):** Titled "GH0ST Watch — The Coin Observatory". Provides a coin inspection lookup, a recent scans section, and a market atlas. It is a coin investigation tool, not a generic system monitoring dashboard.
- **/agentkit (200 OK):** Titled "GH0ST Developer Kit". Labeled developer preview. Paid access is in preparation and no transactions are currently available. Public request access is not active yet.

## Conclusion

Of the six roadmap links on gh0st.fyi, two return 200 OK (/watcher and /agentkit) and four return 404 Not Found (/checker, /thoughts, /scans, /spawn). The roadmap links are therefore not all functional. Each 404 path is listed above so it can be verified independently.
