# PadFlow status

Public status page for [padflow.io](https://padflow.io).

A GitHub Actions probe checks https://padflow.io every five minutes from GitHub's infrastructure — deliberately independent of the environment PadFlow runs in — and appends the result to `docs/data/history.csv`. GitHub Pages serves `docs/` as the status page. History is kept for ~90 days.

This repository contains no PadFlow source code and no customer data.
