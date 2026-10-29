# Superfluid Jiu-Jitsu

superfluidjiujitsu.com: home of the fitWrench Suite for hobbyist grapplers.
Jekyll, served by GitHub Pages (legacy build, `main` branch, `CNAME`).

Design system is copied from sphericalwave.com (`_sass/_variables`, `_base`,
`_type`, `_navbar`, `_socialNetworks`, `_home`). Site-only rules live in
`_sass/_superfluid.scss`.

## Local preview

    bundle config set --local path vendor/bundle
    bundle install
    bundle exec jekyll serve   # http://127.0.0.1:4000

## Waitlist

No third-party scripts. `_config.yml` → `waitlist_email` (mailto form) until
the Kit form exists; then set `waitlist_action` (see `_includes/waitlist.html`).
