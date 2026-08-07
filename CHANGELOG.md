# Change Log

The format is based on [Keep a Changelog](http://keepachangelog.com/) and this
project adheres to [Semantic Versioning](http://semver.org/).

## [0.1.0] - 2026-08-06

First release.

- Monthly mapping leaderboard for a Wanderer map, read live from its audit API
- Alt characters rolled up to their Alliance Auth main; characters Auth does
  not know show individually, marked unlinked
- Systems, connections and signatures, each split into created, updated and
  deleted, plus a total
- One map and one month at a time, with a clear notice for months older than
  the API's three month window
- Audit responses and finished leaderboards both cached, keyed by the base URL
  and API key they were fetched with
- Per map API keys managed in the admin, with an action that tests a key
  against Wanderer
- Menu entry and page gated behind the `basic_access` permission
