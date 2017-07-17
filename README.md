# Argus Panoptes
Distributed cameras

## Getting started

### Setting up a new Jetson TX\*
- Install the latest [JetPack](https://developer.nvidia.com/embedded/jetpack) (requires a host Ubuntu machine to prepare to flash the Jetson). Instructions [here](http://docs.nvidia.com/jetpack-l4t/2_3/content/developertools/mobile/jetpack/l4t/2.3/jetpack_l4t_install.htm) if needed. Video of how to put the Jetson TX\* into recovery mode [here](https://www.youtube.com/watch?v=4JUWS9i_FCQ). If you're _still_ struggling, check out [this](https://www.slothparadise.com/setup-cuda-7-0-nvidia-jetson-tx1-jetpack-detailed/) guide.
```
# Run from host machine (x86_64) with TX* in recovery mode
./bin/flash
```
- Run install script
```
# Run from TX*
./bin/install
```
