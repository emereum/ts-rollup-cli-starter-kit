# ts-rollup-cli-starter-kit


## Setup

* rename all `ts-rollup-cli-starter-kit` to your product name

```sh
# (once)
yarn && yarn prepack
sudo ln -s $PWD/bin/ts-rollup-cli-starter-kit /usr/local/bin

# (every time)
ts-rollup-cli-starter-kit
```

## Development

```sh
yarn format # runs prettier
yarn start # builds and runs using node directly
yarn prepack # builds and packages an executable into bin/ts-rollup-cli-starter-kit
```