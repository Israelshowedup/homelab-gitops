# Debugging Journal
## Entry 1: Kubectl Command Not Found
* **Symptom:** Terminal displayed `Command 'kubectl' not found`.
* **Fix:** Added a permanent alias statement `alias kubectl='/usr/local/bin/k3s kubectl'` directly into the `~/.bashrc` profile configuration file.
