# ThingTrackNano

My own twist on SlimeVR Full body trackers.
My trackers are based on the ESP32C3 and support BMI160/270/323 or LSM6DSV16X IMUs.

These files only contain the PCB project file, Schematics, Gerbers and BOMs but there is no official case yet as I'm working on it.
The case will be added as soon as I finish it and am satisfied with the result.

The defines.h for SlimeVR firmware are included and are configured for the BMI270 but can be easily changed to accomodate the LSM and other BMI chips.
The WIFI settings will need to be hard coded into platformio.ini as the SlimeVR server does not want to pass these settings over automatically.

![ThingTrackNano pic](https://github.com/JuliThing/ThingTrackNano/assets/63885704/58f98e0d-feac-4169-8683-6a659f19fde7)
