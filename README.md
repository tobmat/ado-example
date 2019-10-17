
* Create agent pool
* update Dockerfile as needed
* run build.sh initially and after every Dockerfile change

*** RUN THIS COMMAND ***

```docker run -e AZP_URL=https://dev.azure.com/<site> -e AZP_TOKEN=<agent token> -e AZP_AGENT_NAME=infra-test-container -e AZP_POOL=infra-test-agent-pool dockeragent:latest &```

* This runs in background to exit, fg and cntl+c
