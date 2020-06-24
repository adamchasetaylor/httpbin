# httpbin-ngrok: HTTP Request & Response Service with Ngrok


Pre-Requisites
- Docker
- git
- No running service on Ports 3030, 4040

Run locally:
```sh
git clone git@github.com:adamchasetaylor/httpbin.git
cd httpbin-ngrok
docker-compose up
```

Load up the Launchpad to find your Ngrok and HTTPBin URLs http://localhost:3030

To exit:
```sh
ctrl+c
```

See http://httpbin.org and https://ngrok.com for more information.

## SEE ALSO
- https://hub.docker.com/r/kennethreitz/httpbin/
- https://hub.docker.com/r/wernight/ngrok/

## Credits
- [kennethreitz](https://github.com/postmanlabs/httpbin)
- [wernight](https://github.com/wernight/docker-ngrok)
