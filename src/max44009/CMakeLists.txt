set (libname "max44009")
set (libdescription "I2C Low-power Digital Ambient Light Sensor")
set (module_src ${libname}.cxx)
set (module_hpp ${libname}.hpp)
set (module_iface iLight.hpp)
upm_module_init(mraa)
