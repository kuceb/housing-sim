# Housing-sim :house:
clone this repo using git:
```
git clone https://github.com/Bkucera/housing-sim.git && cd housing-sim
```

install [nodejs version manager](https://github.com/creationix/nvm):
```
curl -o- https://raw.githubusercontent.com/creationix/nvm/v0.33.8/install.sh | bash
```

then reload your bashrc:
```
. ~/.bashrc
```

then activate the LTS version of nodejs:
```
nvm install --lts
```
```
nvm alias default node
```

finally, install my dependencies:
```
npm install
```
and run the simulation:
```
npm start
```
**Note:** Don't worry, none of the dependencies actually affect the running of the code, they just enable the compiling of TypeScript `.ts` files to run with `Nodejs`

to run the simulation again, just use `npm start`

If for some reason these steps are not working for you, just run my setup script by running:
```shell
chmod +x quick-setup.sh
bash ./quick-setup.sh
```