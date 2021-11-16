# deploy-checker
Twisto Github Action for checking (according to preconfigured deploy rules), if PR can be deployed.

## Usage
Add this action to your flow .yaml:
```
      - name: Twisto deploy checker
        uses: twistopayments/deploy-checker@v*.*.*
```

[Dockerhub image](https://hub.docker.com/repository/docker/twistopayments/deploy-checker-base)