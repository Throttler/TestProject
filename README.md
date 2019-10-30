[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/IT-Beard/GitForUniver.git/master)
# GitForUniver
export GITHUB_CLIENT_ID=github_id
export GITHUB_CLIENT_SECRET=github_secret
export OAUTH_CALLBACK_URL=https://example.com/hub/oauth_callback
export CONFIGPROXY_AUTH_TOKEN=super-secret
# append log output to log file /var/log/jupyterhub.log
jupyterhub -f /etc/jupyterhub/jupyterhub_config.py &>> /var/log/jupyterhub.log
