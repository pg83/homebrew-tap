# pg83/tap

```sh
brew install pg83/tap/shitty
brew install pg83/tap/pretty
```

Binary releases of [shitty](https://github.com/pg83/shitty), the fastest
terminal emulator on Earth, and its friendly-branded `pretty` build.

The formulae reconcile themselves: a scheduled workflow compares them
against the latest shitty release twice an hour and regenerates them on a
mismatch, using only this repository's own token - no cross-repo
credentials to expire. A release therefore lands in the tap within half
an hour; `workflow_dispatch` hurries it along when that is too slow.
Note GitHub suspends schedules in repositories with no activity for 60
days; a release cadence slower than that needs the manual dispatch.
