# pg83/tap

```sh
brew install pg83/tap/shitty
```

Binary releases of [shitty](https://github.com/pg83/shitty), the fastest
terminal emulator on Earth.

The formula reconciles itself: a scheduled workflow compares it against
the latest shitty release twice an hour and regenerates it on a
mismatch, using only this repository's own token - no cross-repo
credentials to expire. A release therefore lands in the tap within half
an hour; `workflow_dispatch` hurries it along when that is too slow.
Note GitHub suspends schedules in repositories with no activity for 60
days; a release cadence slower than that needs the manual dispatch.
