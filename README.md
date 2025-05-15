# `garethgeorge/backrest` with `rsync`

Adds rsync binary to [backrest-docker](https://hub.docker.com/r/garethgeorge/backrest). That's it!

Needed it for a [rsync centralized backup script](https://github.com/dpi0/scripts/blob/main/rsync-central-backup.sh).

Checks every 48h for a newer release of backrest, and rebuilds the image.

Note to self:

- In order for `github-actions` commit to work **Settings → Actions → General**
- Scroll to the "Workflow permissions" section
- Select: "Read and write permissions"
- This will allow github-actions[bot] to: Push commits and Trigger workflows.
- Better way might be to use a fine grained PAT, but this works for now.
