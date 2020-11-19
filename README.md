## Some Tutorial Notes

* insert the new value into the system config due to Linux file tracking mechanism

`echo fs.inotify.max_user_watches=524288 | sudo tee -a /etc/sysctl.conf && sudo sysctl -p`

* Prepare `expo`

`npm install --global exp expo expo-cli --registry=https://registry.npm.taobao.org` (for CN Mainland users)

`npm install --global exp expo expo-cli` (for global users)

`npm install` (don't forget to install dependecies according to package.json)

`expo start --web` (to start the app)