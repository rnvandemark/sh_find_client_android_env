# sh_find_client_android_env

## Build instructions for our select ROS2 repos

```
sudo apt update && sudo apt install -y \
  httpie \
  libjsoncpp-dev

mkdir -p /path/to/your_ws/src
cd /path/to/your_ws
rosinstall src /path/to/sh_find_server_env/sh_find_client.rosinstall
```
