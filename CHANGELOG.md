# Changelog

What changed in WittyCouchHost, newest first. What changed before it had a repository of its own is in the
[WittyMediaServer changelog](https://github.com/wittywilla/WittyMediaServer/blob/master/CHANGELOG.md).

## 0.4.1

- The README's pictures are retaken from WittyMediaServer 0.8.0-alpha.

## 0.4.0

- **Module API 5** (0.4.0): carries `integration.json`, which says it adds nothing to a server of its own: WittyCouch and WittyRigs run it (the host API's `/programs/wittycouchhost`). A server takes module API 5 only, so this is the version WittyMediaServer runs. Built on WittyModule 0.5.4 and module API 5: its workflows use WittyModule 0.5.4.
- **Module API 4:** carries `sdui.json`, its theme scope (the games accent), and needs WittyMediaServer 0.8.0-alpha or later. It adds no pages of its own: its screens are the server's.
- Fits servers up to 0.8.x, so WittyMediaServer 0.8.0-alpha accepts it; it was limited to 0.6.x.
- A release is a module again: each system's native build is packed and signed as any module's is, with the source beside it.
- Module API 3 and WittyMediaServer 0.6.0-alpha: this is how a server gets it now, with no copy compiled in.
- WittyCouchHost is now a project of its own, developed and released from this repository.
