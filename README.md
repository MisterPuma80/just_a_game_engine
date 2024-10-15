# Just a Game Engine

<p align="center">
  <a href="https://github.com/MisterPuma80/just_a_game_engine">
    <img src="logo_outlined.svg" width="400" alt="Just a Game Engine">
  </a>
</p>

# Based on Godot 4.3 but with changes
* [x] Expose Engine.get_frame_ticks to GDScript

# Get code

```sh
git clone https://github.com/MisterPuma80/just_a_game_engine
```


# Build

```sh
scons platform=linuxbsd target=editor dev_build=no dev_mode=no use_llvm=yes linker=mold tests=yes -j 16
```

# Build export templates

```sh
scons platform=linuxbsd target=template_release dev_build=no dev_mode=no use_llvm=yes linker=mold -j 16
```


# Clean

```sh
scons -c
git clean -fixd
```
