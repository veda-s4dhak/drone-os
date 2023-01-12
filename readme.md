<h2> Development Environment Setup (macOS) </h2>

1) Download the Epic Games Launcher from https://www.unrealengine.com/en-US/download

2) Run the following commands to setup AirSim

```
cd git
git clone https://github.com/Microsoft/AirSim.git
cd AirSim
./setup.sh
./build.sh
```

3) Generate shared wrapper libraries

```
cd AirSim/Unity
./build.sh
```

cd AirSim/Unreal/Environments/Blocks
./GenerateProjectFiles.sh /Users/Shared/Epic\ Games/UE_4.27/
```

<h2> Install Python Dependencies </h2>

1) Run the following command to install 

```
python3 -m pip install msgpack-rpc-python
python3 -m pip install airsim
```

<h2> Setup drone-os </h2>

1) Clone this repo beside the AirSim repo cloned above.

<h2> Reference </h2>

https://microsoft.github.io/AirSim/build_macos/
