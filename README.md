# docker-compose-cli-install

Fixes the RELEASE_URL set in the Docker Compose CLI install script for linux archived on Github

Since the repo was archived the latest releast returns a JSON object with a permanently moved URL, which the install script does not account for.
