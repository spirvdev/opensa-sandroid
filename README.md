# OpenSA

## Build configuration

- What you will need to configure in your current shell env:

Expose NDK_PATH and CMAKE_ANDROID paths env variable, example:

![Env configuration](assets/envvar.jpeg)

### Create build dir

- Just type at root level folder (OpenSA):

~~~bash
OpenSA> python3 scripts/opensa.py -b
~~~

## Building the plugin

## How to compile

Enter into the build dir and run 'ninja':

~~~bash
OpenSA> cd build
build> ninja
~~~

After this, a library file called **libopensa.so** must be generated

## How to clean

Clean all objected generated by the NDK compiler:

~~~bash
build> ninja clean
~~~



