# Gazebo Install



```
sudo apt update
sudo apt upgrade
```

## ArduPilot
Next, we will begin by installing ArduPilot:

```
git clone https://github.com/ArduPilot/ardupilot.git
cd ardupilot
git checkout Copter-3.6
git submodule update --init --recursive
```

