Arduino CMake
=============

Arduino is a great development platform, which is easy to use. It has everything a beginner should need. The *Arduino IDE* simplifies a lot of things for the standard user, but if you are a professional programmer the IDE can feel simplistic and restrictive.

One major drawback of the *Arduino IDE* is that you cannot do anything without it, which for me is a **complete buzz kill** . Thats why I created an alternative build system for the Arduino using CMake.

CMake is great cross-platform build system that works on practically any operating system. With it you are not constrained to a single build system. CMake lets you generate the build system that fits your needs, using the tools you like. It can generate any type of build system, from simple Makefiles, to complete projects for Eclipse, Visual Studio, XCode, etc.

The **Arduino CMake** build system integrates tightly with the *Arduino SDK* .

*Arduino SDK* version **0.19** or higher is required.

So if you like to do things from the command line (using make), or to build your firmware where you're in control, or if you would like to use an IDE such as Eclipse, KDevelop, XCode, CodeBlocks or something similar, then **Arduino CMake** is the system for you.
{#user-content-features}

Features
--------

* Integrates with *Arduino SDK*
* Supports all Arduino boards.
* Supports Arduino type libraries
* Automatic detection of Arduino libraries.
* Generates firmware images.
* Generates libraries.
* Sketch support.
* Upload support.
* Hardware Platform support.
* Programmer support (with bootloader upload).
* Supports multiple build system types (Makefiles, Eclipse, KDevelop, CodeBlocks, XCode, etc).
* Cross-platform: Windows, Linux, Mac
* Extensible build system, thanks to CMake

{#user-content-feedback}

Feedback
--------

**Arduino CMake** is hosted on GitHub and is available at:

https://github.com/queezythegreat/arduino-cmake

Did you find a bug or would like a specific feature, please report it at:

https://github.com/queezythegreat/arduino-cmake/issues

If you would like to hack on this project, don't hesitate to fork it on GitHub. I will be glad to integrate your changes if you send me a `Pull Request`.
{#user-content-requirements}

Requirements
------------

* Base requirements:
  * `CMake` - http://www.cmake.org/cmake/resources/software.html
  * `Arduino SDK` - http://www.arduino.cc/en/Main/Software

* Linux requirements:
  * `gcc-avr` - AVR GNU GCC compiler
  * `binutils-avr` - AVR binary tools
  * `avr-libc` - AVR C library
  * `avrdude` - Firmware uploader

{#user-content-contributors}

Contributors
------------

I would like to thank the following people for contributing to **Arduino CMake** :

* Marc Plano-Lesay ([Kernald](https://github.com/Kernald))
* James Goppert ([jgoppert](https://github.com/jgoppert))
* Matt Tyler ([matt-tyler](https://github.com/matt-tyler))
* Andrew Stromme ([astromme](https://github.com/astromme))
* [johnyb](https://github.com/johnyb)
* [arunh](https://github.com/arunh)
* Sebastian Herp ([sebastianherp](https://github.com/sebastianherp))
* Michael Daffin ([james147](https://github.com/james147))
* Pavel Ilin ([PIlin](https://github.com/PIlin))
* Igor Mikolic-Torreira ([igormiktor](https://github.com/igormiktor))
* Claudio Henrique Fortes Felix ([chffelix](https://github.com/chffelix))
* Alexandre Tuleu ([atuleu](https://github.com/atuleu))
* [getSurreal](https://github.com/getSurreal)
* Sebastian Zaffarano ([szaffarano](https://github.com/szaffarano))
* [cheshirekow](https://github.com/cheshirekow)
* Logan Engstrom ([meadowstream](https://github.com/meadowstream))
* Francisco Ramírez ([franramirez688](https://github.com/franramirez688))
* Brendan Shillingford ([bshillingford](https://github.com/bshillingford))
* Mike Purvis ([mikepurvis](https://github.com/mikepurvis))
* Steffen Hanikel ([hanikesn](https://github.com/hanikesn))

{#user-content-license}

License
-------

This Source Code Form is subject to the terms of the Mozilla Public License, v. 2.0. If a copy of the MPL was not distributed with this file, You can obtain one at http://mozilla.org/MPL/2.0/.
{#user-content-todo}

TODO
----

* Test more complex configurations and error handling

{#user-content-contents}

Contents
--------

1. [Getting Started](http://www.arduino.cc/en/Guide/HomePage)
2. [Using Arduino CMake](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#using-arduino-cmake)
   1. [Creating firmware images](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#creating-firmware-images)
   2. [Creating libraries](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#creating-libraries)
   3. [Arduino Sketches](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-sketches)
   4. [Arduino Libraries](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-libraries)
   5. [Arduino Library Examples](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-library-examples)
   6. [Compiler and Linker Flags](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#compiler-and-linker-flags)
   7. [Programmers](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#programmers)
   8. [Pure AVR Development](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#pure-avr-development)
   9. [Advanced Options](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#advanced-options)
   10. [Miscellaneous Functions](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#miscellaneous-functions)
   11. [Bundling Arduino CMake](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#bundling-arduino-cmake)

3. [Linux Environment](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#linux-environment)
   1. [Linux Serial Naming](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#linux-serial-naming)
   2. [Linux Serial Terminals](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#linux-serial-terminals)

4. [Mac OS X Environment](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#mac-os-x-environment)
   1. [Mac Serial Naming](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#mac-serial-naming)
   2. [Mac Serial Terminals](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#mac-serial-terminals)

5. [Windows Environment](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#windows-environment)
   1. [CMake Generators](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#cmake-generators)
   2. [Windows Serial Naming](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#windows-serial-naming)
   3. [Windows Serial Terminals](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#windows-serial-terminals)

6. [Eclipse Environment](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#eclipse-environment)
7. [Troubleshooting](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#troubleshooting)
   1. [undefined reference to \`__cxa_pure_virtual'](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#undefined-reference-to-cxa-pure-virtual)
   2. [Arduino Mega 2560 image does not work](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-mega-2560-image-does-not-work)
   3. [Library not detected automatically](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#library-not-detected-automatically)
   4. [error: attempt to use poisoned "SIG_USART0_RECV"](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#error-attempt-to-use-poisoned-sig-usart0-recv)

8. [Resources](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#resources)

{#user-content-getting-started}

Getting Started
---------------

The following instructions are for ***nix** type systems, specifically this is a Linux example.

In short you can get up and running using the following commands:

```
mkdir build
cd build
cmake ..
make
make upload              # to upload all firmware images             [optional]
make blink-serial  # to get a serial terminal to wire_serial   [optional]
```

For a more detailed explanation, please read on...

1. Toolchain file

   In order to build firmware for the Arduino you have to specify a toolchain file to enable cross-compilation. There are two ways of specifying the file, either at the command line or from within the *CMakeLists.txt* configuration files. The bundled example uses the second approach like so:

   ```
   set(CMAKE_TOOLCHAIN_FILE ${CMAKE_SOURCE_DIR}/cmake/ArduinoToolchain.cmake)
   ```

   Please note that this must be before the `project(...)` command.

   If you would like to specify it from the command line, heres how:

   ```
   cmake -DCMAKE_TOOLCHAIN_FILE=../path/to/toolchain/file.cmake PATH_TO_SOURCE_DIR
   ```

2. Creating a build directory

   The second order of business is creating a build directory. CMake has a great feature called out-of-source builds, what this means is the building is done in a completely separate directory from where the sources are. The benefit of this is you don't have any clutter in you source directory and you won't accidentally commit something that is auto-generated.

   So let's create that build directory:

   ```
   mkdir build
   cd build
   ```

3. Creating the build system

   Now let's create the build system that will create our firmware:

   ```
   cmake ..
   ```

   To specify the build system type, use the `-G` option, for example:

   ```
   cmake -G"Eclipse CDT4 - Unix Makefiles" ..
   ```

   If you rather use a GUI, use:

   ```
   cmake-gui ..
   ```

4. Building

   Next we will build everything:

   ```
   make
   ```

5. Uploading

   Once everything built correctly we can upload. Depending on your Arduino you will have to update the serial port used for uploading the firmware. To change the port please edit the following variable in *CMakeLists.txt* :

   ```
   set(${FIRMWARE_NAME}_PORT /path/to/device)
   ```

   Ok lets do a upload of all firmware images:

   ```
   make upload
   ```

   If you have an upload sync error then try resetting/ power cycling the board before starting the upload process.
6. Serial output

   If you have some serial output, you can launch a serial terminal from the build system. The command used for executing the serial terminal is user configurable by the following setting:

   ```
   set(${FIRMWARE_NAME}_SERIAL serial command goes here)
   ```

   In order to get access to the serial port use the following in your command:

   ```
   @SERIAL_PORT@
   ```

   That constant will get replaced with the actual serial port used (see uploading). In the case of our example configuration we can get the serial terminal by executing the following:

   ```
   make blink-serial
   ```

{#user-content-using-arduino-cmake}

Using Arduino CMake
-------------------

In order to use **Arduino CMake** just include the toolchain file, everything will get set up for building. You can set the toolchain in CMakeList.txt like so:

```
set(CMAKE_TOOLCHAIN_FILE ${CMAKE_SOURCE_DIR}/cmake/ArduinoToolchain.cmake)
```

Please note that this must be before the `project(...)` command.

You can also specify it at build configuration time:

```
cmake -DCMAKE_TOOLCHAIN_FILE=../path/to/toolchain/file.cmake PATH_TO_SOURCE_DIR
```

{#user-content-creating-firmware-images}

### Creating firmware images

Once you have the **Arduino CMake** loaded you can start defining firmware images.

To create Arduino firmware in CMake you use the `generate_arduino_firmware` command. The full syntax of the command is:

```
generate_arduino_firmware(target_name
     [BOARD board_id]
     [SKETCH sketch_path | SRCS  src1 src2 ... srcN]
     [HDRS  hdr1 hdr2 ... hdrN]
     [LIBS  lib1 lib2 ... libN]
     [PORT  port]
     [SERIAL serial_cmd]
     [PROGRAMMER programmer_id]
     [AFLAGS flags]
     [NO_AUTOLIBS])
```

The options are:

|-----------------|-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|---------------------------------|
| **Name**        | **Description**                                                                                                                                                                                             | **Required**                    |
| **BOARD**       | Board ID *(such as uno, mega2560, ...)*                                                                                                                                                                     | **REQUIRED**                    |
| **SKETCH**      | Sketch path (see [Arduino Sketches](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-sketches))                                                                    | **SKETCH or SRCS are REQUIRED** |
| **SRCS**        | Source files                                                                                                                                                                                                | **SKETCH or SRCS are REQUIRED** |
| **HDRS**        | Headers files *(for project based build systems)*                                                                                                                                                           |                                 |
| **LIBS**        | Libraries to link (see [Creating libraries](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#creating-libraries))                                                          |                                 |
| **PORT**        | Serial port, for upload and serial targets (see [Upload Firmware](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#upload-firmware))                                       |                                 |
| **SERIAL**      | Serial command for serial target (see [Serial Terminal](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#serial-terminal))                                                 |                                 |
| **PROGRAMMER**  | Programmer ID, enables programmer burning (see [Programmers](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#programmers)).                                               |                                 |
| **ARDLIBS**     | Manual list of Arduino type libraries, common use case is when the library header name does not match the librarie's directory name. **ADVANCED OPTION!**  Can be used in conjuction with **NO_AUTOLIBS** . |                                 |
| **AFLAGS**      | avrdude flags for target                                                                                                                                                                                    |                                 |
| **NO_AUTOLIBS** | Disable Arduino library detection *(default On)*                                                                                                                                                            |                                 |
| **MANUAL**      | Disable Arduino Core (enables pure AVR development)                                                                                                                                                         |                                 |

You can specify the options in two ways, either as the command arguments or as variables. When specifying the options as variables they must be named:

```
${TARGET_NAME}_${OPTION_NAME}
```

Where **${TARGET_NAME}** is the name of you target and **${OPTION_NAME}** is the name of the option.

So to create a target (firmware image) called `blink`, composed of `blink.h` and `blink.cpp` source files for the *Arduino Uno* , you write the following:

```
set(blink_SRCS  blink.cpp)
set(blink_HDRS  blink.h)
set(blink_BOARD uno)

generate_arduino_firmware(blink)
```

The previous example can be rewritten as:

```
generate_arduino_firmware(blink
      SRCS  blink.cpp
      HDRS  blink.h
      BOARD uno)
```

{#user-content-upload-firmware}

#### Upload Firmware

To enable firmware upload functionality, you need to add the `PORT` option:

```
set(blink_SRCS  blink.cpp)
set(blink_HDRS  blink.h)
set(blink_PORT /dev/ttyUSB0)
set(blink_BOARD uno)

generate_arduino_firmware(blink)
```

Or:

```
generate_arduino_firmware(blink
      SRCS  blink.cpp
      HDRS  blink.h
      PORT  /dev/ttyUSB0
      BOARD uno)
```

Once defined there will be two targets available for uploading, `${TARGET_NAME}-upload` and a global `upload` target (which will depend on all other upload targets defined in the build):

* `blink-upload` - will upload just the `blink` firmware
* `upload` - upload all firmware images registered for uploading

{#user-content-serial-terminal}

#### Serial Terminal

To enable serial terminal, use the `SERIAL` option (`@SERIAL_PORT@` will be replaced with the `PORT` option):

```
set(blink_SRCS  blink.cpp)
set(blink_HDRS  blink.h)
set(blink_PORT  /dev/ttyUSB0)
set(blink_SERIAL picocom @SERIAL_PORT@ -b 9600 -l)
set(blink_BOARD uno)

generate_arduino_firmware(blink)
```

Alternatively:

```
generate_arduino_firmware(blink
      SRCS  blink.cpp
      HDRS  blink.h
      PORT  /dev/ttyUSB0
      SERIAL picocom @SERIAL_PORT@ -b 9600 -l
      BOARD uno)
```

This will create a target named `${TARGET_NAME}-serial` (in this example: blink-serial).
{#user-content-creating-libraries}

### Creating libraries

Creating libraries is very similar to defining a firmware image, except we use the `generate_arduino_library` command. This command creates static libraries, and are not to be confused with [Arduino Libraries](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-libraries). The full command syntax:

```
generate_arduino_library(name
     [BOARD board_id]
     [SRCS  src1 src2 ... srcN]
     [HDRS  hdr1 hdr2 ... hdrN]
     [LIBS  lib1 lib2 ... libN]
     [NO_AUTOLIBS])
```

The options are:

|-----------------|-----------------------------------------------------|--------------|
| **Name**        | **Description**                                     | **Required** |
| **BOARD**       | Board ID *(such as uno, mega2560, ...)*             | **REQUIRED** |
| **SRCS**        | Source files                                        | **REQUIRED** |
| **HDRS**        | Headers files *(for project based build systems)*   |              |
| **LIBS**        | Libraries to link *(sets up dependency tracking)*   |              |
| **NO_AUTOLIBS** | Disable Arduino library detection *(default On)*    |              |
| **MANUAL**      | Disable Arduino Core (enables pure AVR development) |              |

You can specify the options in two ways, either as the command arguments or as variables. When specifying the options as variables they must be named:

```
${TARGET_NAME}_${OPTION_NAME}
```

Where **${TARGET_NAME}** is the name of you target and **${OPTION_NAME}** is the name of the option.

Let's define a simple library called `blink_lib` with two sources files for the *Arduino Uno* :

```
set(blink_lib_SRCS  blink_lib.cpp)
set(blink_lib_HDRS  blink_lib.h)
set(blink_lib_BOARD uno)

generate_arduino_library(blink_lib)
```

The other way of defining the same thing is:

```
generate_arduino_library(blink_lib
    SRCS  blink_lib.cpp
    HDRS  blink_lib.h
    BOARD uno)
```

Once that library is defined we can use it in our other firmware images... Let's add `blink_lib` to the `blink` firmware:

```
set(blink_SRCS  blink.cpp)
set(blink_HDRS  blink.h)
set(blink_LIBS  blink_lib)
set(blink_BOARD uno)

generate_arduino_firmware(blink)
```

CMake has automatic dependency tracking, so when you build the `blink` target, `blink_lib` will automatically get built, in the right order.
{#user-content-arduino-sketches}

### Arduino Sketches

To build a Arduino sketch use the **SKETCH** option (see [Creating firmware images](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#creating-firmware-images)). For example:

```
set(blink_SKETCH  ${ARDUINO_SDK_PATH}/examples/1.Basics/Blink) # Path to sketch directory
set(blink_BOARD   uno)

generate_arduino_firmware(blink)
```

This will build the **blink** example from the **Arduino SDK** .

Note: When specifying the sketch directory path, arduino-cmake is expecting to find a sketch file named after the directory (with a extension of .pde or .ino).

You can also specify the path to the main sketch file, then the parent directory of that sketch will be search for additional sketch files.
{#user-content-arduino-libraries}

### Arduino Libraries

Libraries are one of the more powerful features which the Arduino offers to users. Instead of rewriting code, people bundle their code in libraries and share them with others. The structure of these libraries is very simple, which makes them easy to create.

An Arduino library is **any directory which contains a header named after the directory** , simple. Any source files contained within that directory are part of the library. Here is a example of library a called ExampleLib:

```
ExampleLib/
  |-- ExampleLib.h
  |-- ExampleLib.cpp
  `-- OtherLibSource.cpp
```

Now because the power of Arduino lies within those user-created libraries, support for them is built right into **Arduino CMake** . The **Arduino SDK** comes with a large number of default libraries and adding new libraries is simple.

To incorporate a library into your firmware, you can do one of three things:

1. Place the library next to the default Arduino libraries (located at **${ARDUINO_SDK}/libraries** )

2. Place the library next to the firmware configuration file (same directory as the **CMakeLists.txt** )

3. Place the library in a separate folder and tell **Arduino CMake** the path to that directory.

   To tell CMake where to search for libraries use the link_directories command. The command has to be used before defining any firmware or libraries requiring those libraries.

   For example:

   ```
   link_directories(${CMAKE_CURRENT_SOURCE_DIR}/libraries)
   link_directories(/home/username/arduino_libraries)
   ```

If a library contains nested sources, a special option must be defined to enable recursion. For example to enable recursion for the Arduino Wire library use:

```
set(Wire_RECURSE True)
```

The option name should be **${LIBRARY_NAME}_RECURSE** , where in this case **LIBRARY_NAME** is equal to *Wire* .

Arduino Libraries are not to be confused with normal static libraries (for exmaple *system libraries* or libraries created using generate_arduino_library). The **LIBS** option only accepts static libraries, so do not list the Arduino Libraries in that option (as you will get an error).
{#user-content-arduino-library-examples}

### Arduino Library Examples

Most Arduino libraries have examples bundled with them. If you would like to generate and upload some of those examples you can use the generate_arduino_example command. The syntax of the command is:

```
generate_arduino_example(target_name
                         LIBRARY library_name
                         EXAMPLE example_name
                         [BOARD  board_id]
                         [PORT port]
                         [SERIAL serial command]
                         [PORGRAMMER programmer_id]
                         [AFLAGS avrdude_flags])
```

The options are:

|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| **Name**       | **Description**                                                                                                                                                       | **Required** |
| **LIBRARY**    | Library name.                                                                                                                                                         | **REQUIRED** |
| **EXAMPLE**    | Example name.                                                                                                                                                         | **REQUIRED** |
| **BOARD**      | Board ID *(such as uno, mega2560, ...)*                                                                                                                               | **REQUIRED** |
| **PORT**       | Serial port, for upload and serial targets (see [Upload Firmware](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#upload-firmware)) |              |
| **SERIAL**     | Serial command for serial target (see [Serial Terminal](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#serial-terminal))           |              |
| **PROGRAMMER** | Programmer ID, enables programmer burning (see [Programmers](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#programmers)).         |              |
| **AFLAGS**     | avrdude flags for target                                                                                                                                              |              |

To generate a target for the **master_writer** example from the **Wire** library for the **Uno** :

```
generate_arduino_example(wire_example
                         LIBRARY Wire
                         EXAMPLE master_writer
                         BOARD uno
                         PORT  /dev/ttyUSB0)
```

You can also rewrite the previous like so:

```
set(wire_example_LIBRARY Wire)
set(wire_example_EXAMPLE master_writer)
set(wire_example_BOARD uno)
set(wire_example_PORT /dev/ttyUSB0)

generate_arduino_example(wire_example)
```

The previous example will generate the following two target:

```
wire_example
wire_example-upload
```

{#user-content-compiler-and-linker-flags}

### Compiler and Linker Flags

The default compiler and linker flags should be fine for most projects. If you required specific compiler/linker flags, use the following options to change them:

|--------------------------|--------------------|
| **Name**                 | **Description**    |
| **ARDUINO_C_FLAGS**      | C compiler flags   |
| **ARDUINO_CXX_FLAGS**    | C++ compiler flags |
| **ARDUINO_LINKER_FLAGS** | Linker flags       |

Set these option either before the project() like so:

```
set(ARDUINO_C_FLAGS      "-ffunction-sections -fdata-sections")
set(ARDUINO_CXX_FLAGS    "${ARDUINO_C_FLAGS} -fno-exceptions")
set(ARDUINO_LINKER_FLAGS "-Wl,--gc-sections")

project(ArduinoExample C CXX)
```

or when configuring the project:

```
cmake -D"ARDUINO_C_FLAGS=-ffunction-sections -fdata-sections" ../path/to/sources/
```

{#user-content-programmers}

### Programmers

**Arduino CMake** fully supports programmers for burning firmware and bootloader images directly onto the Arduino. If you have a programmer that is supported by the *Arduino SDK* , everything should work out of the box. As of version 1.0 of the *Arduino SDK* , the following programmers are supported:

|-------------------|---------------------|
| **Programmer ID** | **Description**     |
| **avrisp**        | AVR ISP             |
| **avrispmkii**    | AVRISP mkII         |
| **usbtinyisp**    | USBtinyISP          |
| **parallel**      | Parallel Programmer |
| **arduinoisp**    | Arduino as ISP      |

The programmers.txt file located in ${ARDUINO_SDK_PATH}/hardware/arduino/ lists all supported programmers by the *Arduino SDK* .

In order to enable programmer support, you have to use the **PROGRAMMER** option (see [Creating firmware images](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#creating-firmware-images)):

```
set(${TARGET_NAME}_PROGRAMMER programmer_id)
```

where programmer_id is the name of the programmer supported by the *Arduino SDK* .

Once you have enabled programmer support, two new targets are available in the build system:

* **${TARGET_NAME}-burn** - burns the firmware image via the programmer
* **${TARGET_NAME}-burn-bootloader** - burns the original **Arduino bootloader** image via the programmer

If you need to restore the original **Arduino bootloader** onto your Arduino, so that you can use the traditional way of uploading firmware images via the bootloader, use **${TARGET_NAME}-burn-bootloader** to restore it.
{#user-content-pure-avr-development}

### Pure AVR Development

For those developers who don't want any Arduino magic, but still want to utilize the hardware platform you are in luck. This section will outline the generate_avr_firmware() and generate_avr_library() commands, which enables you to compile sources for the given Arduino board.

No Arduino Core or Arduino libraries will get generated, this is for manual compilation of sources. These commands are for people that know what they are doing, or have done pure AVR development. People starting out, or just familiar with Arduino should not use these commands.

The generate_avr_firmware() command:

```
generate_avr_firmware(name
     [BOARD board_id]
     [SRCS  src1 src2 ... srcN]
     [HDRS  hdr1 hdr2 ... hdrN]
     [LIBS  lib1 lib2 ... libN]
     [PORT  port]
     [SERIAL serial_cmd]
     [PROGRAMMER programmer_id]
     [AFLAGS flags])
```

This will compile the sources for the specified Arduino board type.

The options:

|----------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------|
| **Name**       | **Description**                                                                                                                                                       | **Required** |
| **BOARD**      | Board ID *(such as uno, mega2560, ...)*                                                                                                                               | **REQUIRED** |
| **SRCS**       | Source files                                                                                                                                                          | **REQUIRED** |
| **HDRS**       | Headers files *(for project based build systems)*                                                                                                                     |              |
| **LIBS**       | Libraries to link *(sets up dependency tracking)*                                                                                                                     |              |
| **BOARD**      | Board ID *(such as uno, mega2560, ...)*                                                                                                                               | **REQUIRED** |
| **PORT**       | Serial port, for upload and serial targets (see [Upload Firmware](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#upload-firmware)) |              |
| **SERIAL**     | Serial command for serial target (see [Serial Terminal](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#serial-terminal))           |              |
| **PROGRAMMER** | Programmer ID, enables programmer burning (see [Programmers](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#programmers)).         |              |
| **AFLAGS**     | avrdude flags for target                                                                                                                                              |              |

You can specify the options in two ways, either as the command arguments or as variables. When specifying the options as variables they must be named:

```
${TARGET_NAME}_${OPTION_NAME}
```

Where **${TARGET_NAME}** is the name of you target and **${OPTION_NAME}** is the name of the option.

The generate_avr_library() command:

```
generate_avr_library(name
     [BOARD board_id]
     [SRCS  src1 src2 ... srcN]
     [HDRS  hdr1 hdr2 ... hdrN]
     [LIBS  lib1 lib2 ... libN])
```

This will compile a static library for the specified Arduino board type.

The options:

|-----------|---------------------------------------------------|--------------|
| **Name**  | **Description**                                   | **Required** |
| **BOARD** | Board ID *(such as uno, mega2560, ...)*           | **REQUIRED** |
| **SRCS**  | Source files                                      | **REQUIRED** |
| **HDRS**  | Headers files *(for project based build systems)* |              |
| **LIBS**  | Libraries to link *(sets up dependency tracking)* |              |

You can specify the options in two ways, either as the command arguments or as variables. When specifying the options as variables they must be named:

```
${TARGET_NAME}_${OPTION_NAME}
```

Where **${TARGET_NAME}** is the name of you target and **${OPTION_NAME}** is the name of the option.
{#user-content-advanced-options}

### Advanced Options

The following options control how **Arduino CMake** is configured:

|---------------------------------|---------------------------------------------------------------------------------------------------------------------------------------|
| **Name**                        | **Description**                                                                                                                       |
| **ARDUINO_SDK_PATH**            | Full path to the **Arduino SDK**                                                                                                      |
| **ARDUINO_AVRDUDE_PROGRAM**     | Full path to avrdude programmer                                                                                                       |
| **ARDUINO_AVRDUDE_CONFIG_PATH** | Full path to avrdude configuration file                                                                                               |
| **ARDUINO_DEFAULT_BOARD**       | Default Arduino Board ID, when not specified.                                                                                         |
| **ARDUINO_CPU**                 | Selected CPU from Arduino 1.5 menu boards. For mega board, for example, you have to set atmega2560 before including ARDUINO ToolChain |
| **ARDUINO_DEFAULT_PORT**        | Default Arduino port, when not specified.                                                                                             |
| **ARDUINO_DEFAULT_SERIAL**      | Default Arduino Serial command, when not specified.                                                                                   |
| **ARDUINO_DEFAULT_PROGRAMMER**  | Default Arduino Programmer ID, when not specified.                                                                                    |

To force a specific version of **Arduino SDK** , configure the project like so:

```
cmake -DARDUINO_SDK_PATH=/path/to/arduino_sdk ../path/to/sources
```

Note: You must create a new build system if you change **ARDUINO_SDK_PATH** .

When **Arduino CMake** is configured properly, these options are defined:

|-------------------------------|-------------------------------------------------------------------|
| **Name**                      | **Description**                                                   |
| **ARDUINO_FOUND**             | Set to True when the **Arduino SDK**  is detected and configured. |
| **ARDUINO_SDK_VERSION**       | Full version of the **Arduino SDK**  (ex: 1.0.0)                  |
| **ARDUINO_SDK_VERSION_MAJOR** | Major version of the **Arduino SDK**  (ex: 1)                     |
| **ARDUINO_SDK_VERSION_MINOR** | Minor version of the **Arduino SDK**  (ex: 0)                     |
| **ARDUINO_SDK_VERSION_PATCH** | Patch version of the **Arduino SDK**  (ex: 0)                     |

During compilation, you can enable the following environment variables.

|------------------|----------------------------------------------------------------------------------|
| **Name**         | **Description**                                                                  |
| **VERBOSE**      | Enables verbose compilation, displays commands being executed. (Non empty value) |
| **VERBOSE_SIZE** | Enables full/verbose output from avr-size. (Non empty value)                     |

{#user-content-miscellaneous-functions}

### Miscellaneous Functions

This section will outlines some of the additional miscellaneous functions available to the user.

* **print_board_list()** :

  Print list of detected Arduino Boards.
* **print_programmer_list()** :

  Print list of detected Programmers.
* **print_programmer_settings(PROGRAMMER)** :
  >
  > *PROGRAMMER* - programmer id

  Print the detected Programmer settings.
* **print_board_settings(BOARD_ID)** :
  >
  > *BOARD_ID* - Board ID

  Print the detected Arduino board settings.
* **register_hardware_platform(HARDWARE_PLATFORM_PATH)** :
  >
  > *HARDWARE_PLATFORM_PATH* - Hardware platform path

  Registers a `Hardware Platform` path. See: [Arduino Platforms PRE 1.5](http://code.google.com/p/arduino/wiki/Platforms) and [Arduino Platforms 1.5](http://code.google.com/p/arduino/wiki/Platforms1).

  A Hardware Platform is a directory containing the following:

  ```
  HARDWARE_PLATFORM_PATH/
      |-- bootloaders/
      |-- cores/
      |-- variants/
      |-- boards.txt
      `-- programmers.txt
  ```

  This enables you to register new types of hardware platforms such as the Sagnuino, without having to copy the files into your Arduino SDK.

  The `board.txt` describes the target boards and bootloaders. While `programmers.txt` the programmer defintions.

  A good example of a *Hardware Platform* is in the Arduino SDK: `${ARDUINO_SDK_PATH}/hardware/arduino/`

{#user-content-bundling-arduino-cmake}

### Bundling Arduino CMake

Using **Arduino CMake** in your own project is simple, you just need a single directory called **cmake** . Just copy that entire directory into you project and you are set.

Copying the **cmake** directory, although simple is not the best solution. If you are using GIT for source code versioning, the best solution is using a submodule. The submodule gives you the power of updating to the latest version of **Arduino CMake** without any effort. To add a submodule do:

```
git submodule add git://github.com/queezythegreat/arduino-cmake.git arduino-cmake
```

Then just set the CMAKE_TOOLCHAIN_FILE variable:

```
set(CMAKE_TOOLCHAIN_FILE ${CMAKE_SOURCE_DIR}/arduino-cmake/cmake/ArduinoToolchain.cmake)
```

For more information on GIT submodules please read: [GIT Book - Submodules](http://book.git-scm.com/5_submodules.html)
{#user-content-linux-environment}

Linux Environment
-----------------

Running the *Arduino SDK* on Linux is a little bit more involved, because not everything is bundled with the SDK. The AVR GCC toolchain is not distributed alongside the Arduino SDK, so it has to be installed seperately.

To get **Arduino CMake** up and running follow these steps:

1. Install the following packages using your package manager:

   * `gcc-avr` - AVR GNU GCC compiler
   * `binutils-avr` - AVR binary tools
   * `avr-libc` - AVR C library
   * `avrdude` - Firmware uploader

2. Install the *Arduino SDK* .

   Depending on your distribution, the *Arduino SDK* may or may not be available.

   If it is available please install it using your packages manager otherwise do:
   1. Download the [Arduino SDK](http://www.arduino.cc/en/Main/Software)
   2. Extract it into `/usr/share`

   NOTE: Arduino version **0.19** or newer is required!
3. Install CMake:

   * Using the package manager or
   * Using the [CMake installer](http://www.cmake.org/cmake/resources/software.html)

   NOTE: CMake version 2.8 or newer is required!

{#user-content-linux-serial-naming}

### Linux Serial Naming

On Linux the Arduino serial device is named as follows (where **X** is the device number):

```
/dev/ttyUSBX
/dev/ttyACMX
```

Where `/dev/ttyACMX` is for the new **Uno** and **Mega** Arduino's, while `/dev/ttyUSBX` is for the old ones.

CMake configuration example:

```
set(${FIRMWARE_NAME}_PORT /dev/ttyUSB0)
```

{#user-content-linux-serial-terminals}

### Linux Serial Terminals

On Linux a wide range on serial terminal are availabe. Here is a list of a couple:

* `minicom`
* `picocom`
* `gtkterm`
* `screen`

{#user-content-mac-os-x-environment}

Mac OS X Environment
--------------------

The *Arduino SDK* , as on Windows, is self contained and has everything needed for building. To get started do the following:

1. Install the *Arduino SDK*

   1. Download [Arduino SDK](http://www.arduino.cc/en/Main/Software)
   2. Copy `Arduino` into `Applications`
   3. Install `FTDIUSBSerialDrviver*` (for FTDI USB Serial)

2. Install CMake

   1. Download [CMake](http://www.cmake.org/cmake/resources/software.html)

   2. Install `cmake-*.pkg`

      NOTE: Make sure to click on **\`Install Command Line Links\`**

{#user-content-mac-serial-naming}

### Mac Serial Naming

When specifying the serial port name on Mac OS X, use the following names (where XXX is a unique ID):

```
/dev/tty.usbmodemXXX
/dev/tty.usbserialXXX
```

Where `tty.usbmodemXXX` is for new **Uno** and **Mega** Arduino's, while `tty.usbserialXXX` are the older ones.

CMake configuration example:

```
set(${FIRMWARE_NAME}_PORT /dev/tty.usbmodem1d11)
```

{#user-content-mac-serial-terminals}

### Mac Serial Terminals

On Mac the easiest way to get a Serial Terminal is to use the `screen` terminal emulator. To start a `screen` serial session:

```
screen /dev/tty.usbmodemXXX
```

Where `/dev/tty.usbmodemXXX` is the terminal device. To exit press `C-a C-\`.

CMake configuration example:

```
set(${FIRMWARE_NAME}_SERIAL screen @SERIAL_PORT@)
```

{#user-content-windows-environment}

Windows Environment
-------------------

On Windows the *Arduino SDK* is self contained and has everything needed for building. To setup the environment do the following:

1. Place the [Arduino SDK](http://www.arduino.cc/en/Main/Software) either

   * into **Program Files** , or
   * onto the **System Path**

   NOTE: Don't change the default *Arduino SDK* directory name, otherwise auto detection will no work properly!
2. Add to the **System Path** : `${ARDUINO_SDK_PATH}/hardware/tools/avr/utils/bin`

3. Install [CMake 2.8](http://www.cmake.org/cmake/resources/software.html)

   NOTE: Make sure you check the option to add CMake to the **System Path** .

{#user-content-cmake-generators}

### CMake Generators

Once installed, you can start using CMake the usual way, just make sure to chose either a **MSYS Makefiles** or **Unix Makefiles** type generator:

```
MSYS Makefiles              = Generates MSYS makefiles.
Unix Makefiles              = Generates standard UNIX makefiles.
CodeBlocks - Unix Makefiles = Generates CodeBlocks project files.
Eclipse CDT4 - Unix Makefiles
                            = Generates Eclipse CDT 4.0 project files.
```

If you want to use a **MinGW Makefiles** type generator, you must generate the build system the following way:

1. Remove `${ARDUINO_SDK_PATH}/hardware/tools/avr/utils/bin` from the **System Path**

2. Generate the build system using CMake with the following option set (either through the GUI or from the command line):

   ```
   CMAKE_MAKE_PROGRAM=${ARDIUNO_SDK_PATH}/hardware/tools/avr/utils/bin/make.exe
   ```

3. Then build the normal way

The reason for doing this is the MinGW generator cannot have the `sh.exe` binary on the **System Path** during generation, otherwise you get an error.
{#user-content-windows-serial-naming}

### Windows Serial Naming

When specifying the serial port name on Windows, use the following names:

```
com1 com2 ... comN
```

CMake configuration example:

```
set(${FIRMWARE_NAME}_PORT com3)
```

{#user-content-windows-serial-terminals}

### Windows Serial Terminals

Putty is a great multi-protocol terminal, which supports SSH, Telnet, Serial, and many more... The latest development snapshot supports command line options for launching a serial terminal, for example:

```
putty -serial COM3 -sercfg 9600,8,n,1,X
```

CMake configuration example (assuming putty is on the **System Path** ):

```
set(${FIRMWARE_NAME}_SERIAL putty -serial @SERIAL_PORT@)
```

Putty - http://tartarus.org/~simon/putty-snapshots/x86/putty-installer.exe
{#user-content-eclipse-environment}

Eclipse Environment
-------------------

Eclipse is a great IDE which has a lot of functionality and is much more powerful than the *Arduino IDE* . In order to use Eclipse you will need the following:

1. Eclipse
2. Eclipse CDT extension (for C/C++ development)

On most Linux distribution you can install Eclipse + CDT using your package manager, otherwise you can download the [Eclipse IDE for C/C++ Developers](http://www.eclipse.org/downloads/packages/eclipse-ide-cc-developers/heliossr2) bundle.

Once you have Eclipse, here is how to generate a project using CMake:

1. Create a build directory that is next to your source directory, like this:

   ```
   build_directory/
   source_directory/
   ```

2. Run CMake with the Eclipse CDT4 - Unix Makefiles generator, inside the build directory:

   ```
   cd build_directory/
   cmake -G"Eclipse CDT4 - Unix Makefiles" ../source_directory
   ```

3. Open Eclipse and import the project from the build directory.

   1. **File \> Import**
   2. Select Existing Project into Workspace, and click **Next**
   3. Select *Browse* , and select the build directoy.
   4. Select the project in the **Projects:** list
   5. Click **Finish**

{#user-content-troubleshooting}

Troubleshooting
---------------

The following section will outline some solutions to common problems that you may encounter.
{#user-content-undefined-reference-to-cxa-pure-virtual}

### undefined reference to [\`](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#id1)__cxa_pure_virtual'

When linking you'r firmware image you may encounter this error on some systems. An easy fix is to add the following to your firmware source code:

```
extern "C" void __cxa_pure_virtual(void);
void __cxa_pure_virtual(void) { while(1); }
```

The contents of the `__cxa_pure_virtual` function can be any error handling code; this function will be called whenever a pure virtual function is called.

* [What is the purpose of \`cxa_pure_virtual\`](http://stackoverflow.com/questions/920500/what-is-the-purpose-of-cxa-pure-virtual)

{#user-content-arduino-mega-2560-image-does-not-work}

### Arduino Mega 2560 image does not work

If you are working on Linux, and have `avr-gcc` \>= 4.5 you might have a unpatched version gcc which has the C++ constructor bug. This bug affects the **Atmega2560** when using classes which causes the Arduino firmware to crash.

If you encounter this problem either downgrade `avr-gcc` to **4.3** or rebuild gcc with the following patch:

```
--- gcc-4.5.1.orig/gcc/config/avr/libgcc.S  2009-05-23 17:16:07 +1000
+++ gcc-4.5.1/gcc/config/avr/libgcc.S   2010-08-12 09:38:05 +1000
@@ -802,7 +802,9 @@
    mov_h   r31, r29
    mov_l   r30, r28
    out     __RAMPZ__, r20
+   push    r20
    XCALL   __tablejump_elpm__
+   pop r20
 .L__do_global_ctors_start:
    cpi r28, lo8(__ctors_start)
    cpc r29, r17
@@ -843,7 +845,9 @@
    mov_h   r31, r29
    mov_l   r30, r28
    out     __RAMPZ__, r20
+   push    r20
    XCALL   __tablejump_elpm__
+   pop r20
 .L__do_global_dtors_start:
    cpi r28, lo8(__dtors_end)
    cpc r29, r17
```

* [AVR GCC Bug 45263 Report](http://gcc.gnu.org/bugzilla/show_bug.cgi?id=45263)
* [The global constructor bug in avr-gcc](http://andybrown.me.uk/ws/2010/10/24/the-major-global-constructor-bug-in-avr-gcc/)

{#user-content-library-not-detected-automatically}

### Library not detected automatically

When a Arduino library does not get detected automatically, it usually means CMake cannot find it (obvious).

One common reason why the library is not detected, is because the directory name of the library does not match the header. If I'm including a library header like so:

```
#include "my_library.h"
```

Based on this include, **Arduino CMake** is expecting to find a library that has a directory name **my_libray** . If the directory name does not match the header, it won't be consider a Arduino Library (see [Arduino Libraries](https://github.com/francoiscampbell/arduino-cmake/blob/master/README.original.rst#arduino-libraries)).

When a library being used is located in a non-standard location (not in the **Arduino SDK** or next to the firmware), then that directory must be registered. To register a non-standard directory containing Arduino libraries, use the following:

```
link_directories(path_to_directory_containing_libraries)
```

Remember to **use this command before defining the firmware** , which requires the library from that directory.
{#user-content-error-attempt-to-use-poisoned-sig-usart0-recv}

### error: attempt to use poisoned "SIG_USART0_RECV"

If you get the following error:

```
/usr/share/arduino/hardware/arduino/cores/arduino/HardwareSerial.cpp:91:41: error: attempt to use poisoned "SIG_USART0_RECV"
/usr/share/arduino/hardware/arduino/cores/arduino/HardwareSerial.cpp:101:15: error: attempt to use poisoned "SIG_USART0_RECV"
/usr/share/arduino/hardware/arduino/cores/arduino/HardwareSerial.cpp:132:15: error: attempt to use poisoned "SIG_USART1_RECV"
/usr/share/arduino/hardware/arduino/cores/arduino/HardwareSerial.cpp:145:15: error: attempt to use poisoned "SIG_USART2_RECV"
/usr/share/arduino/hardware/arduino/cores/arduino/HardwareSerial.cpp:158:15: error: attempt to use poisoned "SIG_USART3_RECV"
```

You probably recently upgraded avr-libc to the latest version, which has deperecated the use of these symbols. There is a [Arduino Patch](http://arduino.googlecode.com/issues/attachment?aid=9550004000&name=sig-patch.diff&token=R2RWB0LZXQi8OpPLsyAdnMATDNU%3A1351021269609) which fixes these error, you can read more about this bug here: [Arduino Bug ISSUE 955](http://code.google.com/p/arduino/issues/detail?id=955).
{#user-content-resources}

Resources
---------

Here are some resources you might find useful in getting started.

1. CMake:
   * [Offical CMake Tutorial](http://www.cmake.org/cmake/help/cmake_tutorial.html)
   * [CMake Tutorial](http://mathnathan.com/2010/07/11/getting-started-with-cmake/)
   * [CMake Reference](http://www.cmake.org/cmake/help/cmake-2-8-docs.html)

1. Arduino:
   * [Getting Started](http://www.arduino.cc/en/Guide/HomePage) - Introduction to Arduino
   * [Playground](http://www.arduino.cc/playground/) - User contributed documentation and help
   * [Arduino Forums](http://www.arduino.cc/forum/) - Official forums
   * [Arduino Reference](http://www.arduino.cc/en/Reference/HomePage) - Official reference manual
