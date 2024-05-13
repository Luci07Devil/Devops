brew install fluxcd/tap/flux
#To configure your shell to load flux bash completions add to your profile:
. <(flux completion bash)
flux bootstrap github --owner=vraja253 --repository=DevOps- --hostname=github.comcast.com --token-auth --path=flux-cd/
#you will be asked for PAT 
