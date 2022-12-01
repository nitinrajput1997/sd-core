# sd-core

Clone Repo
```
cd ~
git clone "https://gerrit.opencord.org/aether-in-a-box"

mkdir -p ~/cord
cd ~/cord
git clone "https://gerrit.opencord.org/sdcore-helm-charts"
```

To deploy 5G SD-CORE using local helm charts:
```
make 5g-core
```

To deploy and test 5G SD-CORE using local helm charts:
```
make 5g-test
```

