# knsk - Kubernetes namespace killer

This tool is aimed to kill namespaces that stuck in Terminating mode after you try to delete it.

It automate the tips by https://github.com/alvaroaleman in https://github.com/kubernetes/kubernetes/issues/60807#issuecomment-524772920

If it doesn't work for you, please, let me know. It is hard to force namespace in Terminating mode just to test it.

### Just call the script on a host that manage your Kubernetes (kubectl configured)

#### with CURL
     curl -s https://raw.githubusercontent.com/thyarles/knsk/master/knsk.sh | bash 

#### with WGET
     wget -q https://raw.githubusercontent.com/thyarles/knsk/master/knsk.sh -O - | bash 
