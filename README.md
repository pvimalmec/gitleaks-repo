# gitleaks-repo

gitleaks detect  -c .\gitleaks.toml - --log-level=debug                                   

11:06AM DBG using gitleaks config .\gitleaks.toml from `--config`

11:06AM DBG executing: C:\Program Files\Git\cmd\git.exe -C . log -p -U0 --full-history --all

11:06AM INF 2 commits scanned.

11:06AM DBG Note: this number might be smaller than expected due to commits with no additions

11:06AM INF scan completed in 107ms

11:06AM WRN leaks found: 3

### With this config, i couldnt able to scan the secerts in propetries file
