# ubuntu_zshrc

## Tool Installation
* kubectl - https://kubernetes.io/docs/tasks/tools/install-kubectl/
  * release version - https://github.com/kubernetes/kubernetes/tags
* Ibmcloud - https://cloud.ibm.com/docs/cli?topic=cloud-cli-install-ibmcloud-cli
* Azure CLI - https://docs.microsoft.com/ko-kr/cli/azure/install-azure-cli?view=azure-cli-latest
* aws cli - https://docs.aws.amazon.com/ko_kr/cli/latest/userguide/install-cliv2.html
* jq - https://stedolan.github.io/jq/download/
* k9s - https://github.com/derailed/k9s/releases
* tkn cli
* argocd cli

## Init
```
cp conf/vimrc ~/.vimrc

sudo cp conf/setkubeconfig /usr/local/bin/setkubeconfig
sudo chmod a+x /usr/local/bin/setkubeconfig

sudo cp conf/bug /usr/local/bin/bug
sudo chmod a+x /usr/local/bin/bug

sudo cp conf/getkubeconfig /usr/local/bin/getkubeconfig
sudo chmod a+x /usr/local/bin/getkubeconfig 
# TODO zshrc 
```

