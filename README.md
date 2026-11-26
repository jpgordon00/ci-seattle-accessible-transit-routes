# Where do Seattle’s mapped routes to transit leave wheelchair access uncertain?

Audit curb ramps, crossings and slopes on a sample of 20 trips between transit stops and public destinations.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/seattle-accessible-transit-routes/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-seattle-accessible-transit-routes/pulls)

## Why this matters

OpenSidewalks and AccessMap model sidewalk attributes that ordinary shortest-path directions can miss. Missing data can make a crossing’s suitability uncertain.

## What to contribute

Preselect 20 public stop-to-destination pairs in one neighborhood. Generate routes with a specified accessibility profile, review segments with missing data and record dated public-source or field observations.

## How reviewers check it

Publish route GeoJSON, the routing profile and the evidence type for each flagged segment. Tabulate verified barriers, verified passable segments and unknowns. Record the routes that could not be generated.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/seattle-accessible-transit-routes
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/seattle-accessible-transit-routes/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-seattle-accessible-transit-routes/security/advisories/new) for security reports.

## Sources

- [University of Washington’s Taskar Center documentation](<https://taskarcenteratuw.github.io/tcat-wiki/>)
- [AccessMap routing project](<https://github.com/TaskarCenterAtUW/AccessMap>)
