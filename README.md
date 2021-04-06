# npm-run-all-test

- `package.json` has `echo-users` and `echo-workers` scripts that each use `doppler run` to fetch secrets, prints them, and wait
- `local-dev` uses `npm-run-all` to run both of these commands in parallel
