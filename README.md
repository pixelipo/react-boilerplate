# React Docker Boilerplate

Just a boilerplate repository that gives you a working React app inside a Docker container.
No need to install node or yarn/npm locally.
It is using `node:current-alpine` as a base image and eerything is wrapped with a Compose for easier running.

### Usage
1. Just fork and clone :sunglasses:
2. run `sudo -E docker-compose up -d --build`
3. Point your broweser to `localhost:3000` and enjoy :coffee:

Additional containers (like a backend and db engines) can easily be added just by creating a new subfolder and updating `docker-compose.yml` file.
React app is inside the `client` folder, obviously.

All the Yarn commands need to be prefixed with `sudo -E docker-compose exec client `. I suggest creating a bach alias keyword.
