# my-ros2-template
repo for setup ros2 workspace and generate copmile_commands.json


# commands

```
git clone https://github.com/juicyideas/my-ros2-template src
colcon build --cmake-args -DCMAKE_EXPORT_COMPILE_COMMANDS=ON -G Ninja
```
