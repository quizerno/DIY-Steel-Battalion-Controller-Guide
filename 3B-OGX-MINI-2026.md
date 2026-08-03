# 3B. OGX-MINI-2026
Based off

Build in Linux or WSL, using these instructions.

```
git clone --recurse-submodules https://github.com/MegaCadeDev/OGX-Mini-2026
cd OXG-Mini-2026/Firmware/external
git clone --recurse-submodules https://github.com/RaspberryPi/pico-sdk
mkdir ../RP2040/build
cd ../RP2040/build
cmake -DOGXM_BOARD=[BOARD OPTION] -DOGXM_FIXED_DRIVER=[CONTROLLER OPTION] -DCMAKE_BUILD_TYPE=[Debug or Release] ..
make 
```


# Default Configuration
By default, OGX-MINI's configuration defaults to this control scheme using the Xbox 360+Chatpad
<img width="975" height="965" alt="image" src="https://github.com/user-attachments/assets/7d95fc88-7829-45cb-86cd-088762b4ac45" />
