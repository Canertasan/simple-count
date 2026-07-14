# Simple Count — legacy force-update endpoint

This repo exists for exactly one reason: Simple Count app versions 2.0 and
2.0.1 (shipped June–July 2026) fetch their force-update kill switch from

    https://raw.githubusercontent.com/Canertasan/simple-count/main/config.json

which was this repo's name before the app source moved to a different
(private) repository. This public repo keeps that URL serving so those
binaries can still be walled onto newer versions.

Versions 2.0.2+ use https://simplecountdownapp.github.io/config.json —
when changing the floor, update BOTH files.
