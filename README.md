# IDEA Run Configurations

Copy files to .run


Simple usage

```sh
cd project
git clone git@github.com:samovar/idea-run-configurations.git /tmp/idea \
    && rm -rf /tmp/idea/.git \
    && rm -rf /tmp/idea/README.md \
    && cp -rT /tmp/idea .run \
    && rm -rf /tmp/idea
```
