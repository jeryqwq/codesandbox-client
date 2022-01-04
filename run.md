yarn run build:deps
cd packages/app
yarn run build:sandpack-sandbox
cp -rf ../../www/static/* ./www/static