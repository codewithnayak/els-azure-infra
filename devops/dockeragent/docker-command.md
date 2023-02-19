# Dockercommand

docker run -v /var/run/docker.sock:/var/run/docker.sock -v /usr/bin/docker:/usr/bin/docker -e AZP_URL=https://dev.azure.com/codewithnayak -e AZP_TOKEN="your token" -e AZP_AGENT_NAME=mydockeragent dockeragent:latest
