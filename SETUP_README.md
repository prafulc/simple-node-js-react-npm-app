docker run \
  --rm \
  -u root \
  -p 8080:8080 \
  -v jenkins-data:/var/jenkins_home \
  -v /var/run/docker.sock:/var/run/docker.sock \
  -v "$HOME/myApp/jenkins-docker-node-react":/home \
  jenkinsci/blueocean


Generated admin Password: 6743000fddee496ea7871b61b1c3f781
User Setup: username: praful password: praful email: pchandekar10@gmail.com
