sdrsharp-bladerf
================

bladeRF driver for SDR#


Installation
============

1. Copy the Release\SDRSharp.BladeRF.dll into SDR# installation directory
2. If required, copy all DLL files from LibBladeRF subdirectory to SDR# installation directory
3. Add the following line in the frontendPlugins sections of SDRSharp.exe.config file:
  <add key="BladeRF" value="SDRSharp.BladeRF.BladeRFIO,SDRSharp.BladeRF" />
4. Launch SDR# and cross fingers :)
