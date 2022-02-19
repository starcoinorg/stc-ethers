# The Starcoin Project

yarn preinstall

yarn install

yarn install

cd packages/providers

> modify src.ts/\*.ts
> change `version` in packages/providers/package.json

cd ../..

yarn build-all

cd packages/providers

npm publish --access public --tag latest --dry-run

npm publish --access public --tag latest
