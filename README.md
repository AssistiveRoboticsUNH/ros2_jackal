# ros2_jackal

to create a new map run
```
ros2 launch jackal_navigation generate_map.launch.py
```

after the map is done run 
```
ros2 run nav2_map_server map_saver_cli -f ~/map
```


sudo apt-get install -y nlohmann-json3-dev
