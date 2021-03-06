# ChangeLlog

# Version 0.8.10

### Kai-Uwe Behrmann (22):
* [core]: update on geomentry changes
* [core]: switch only single monitor for _ICC_PROFILE_xxx event
* [core]: check for the need of a update
* [core]: use Oyranos to move profiles around
* [core]: switch to oyMessageFunc_p with oy_debug>0
* [core]: add more debug output
* [core]: reset Oyranos DB cache to see new DB values
* [core]: add more debug output to observe caching
* [core]: update context key name
* [core]: add atom name to messages
* [core]: reduce profile fetching
* [docu]: describe compiz --debug switch
* [core]: add getScreenProfile()
* [core]: pass through icc_profile_flags variable
* [core]: include Oyranos error in error message
* [core]: better check for profile equality in setupColourTable()
* [core]: update to Oyranos key name macro changes
* [core]: use better qualified key name
* [conf]: bump to 0.8.10
* [core]: support 30-bit visual without region profiles
* [build]: update spec requirements
* [conf]: bump version

# Version 0.8.8

### Kai-Uwe Behrmann (2):
* [conf]: remove references to unused fltk tests
* [core]: substitute last Net occurence

### Petr Gajdos (4):
* [core]: move up _BSD_SOURCE
* [conf]: xcm is present fix
* [conf]: remove STRIPOPT variable
* [build]: fix build in oS-factory

# Version 0.8.7

### Kai-Uwe Behrmann (5):
* [core]: add ICM attribute to _ICC_COLOR_DESKTOP
* [core]: remove obsolete client message
* [core]: describe our _ICC_COLOR_DESKTOP attributes
* [core]: observe more XRandR events
* [conf]: bump version

# Version 0.8.6

### Kai-Uwe Behrmann (9):
* [docu]: update requirements to Oyranos >= 0.9.0
* [core]: compile with oyranos:gsoc2011 branch
* [docu]: add wiki page
* [build]: use spdx.org format for spec file
* [core]: render outputs as well without profile
* [core]: initialise string once
* [build]: require ccsm in spec file
* [build]: require newer Xcm versions in spec file
* [conf]: bump version

# Version 0.8.5

### Kai-Uwe Behrmann (34):
* [build]: minor spec fixes
* [core]: fix unused comment
* [core]: fix wrong variable access from #90d2df89
* [build]: adapt to openSUSE spec file
* [build]: remove non existent file
* [core]: update to Xcm changes
* [core]: use module provided hash
* [core]: support colour correction to multi monitor
* [core]: count window region
* [core]: use GL_EQUAL in pluginDrawWindow
* [core]: update to x_color_region_target
* [core]: store stencil start per window
* [core]: compute stencil ID during drawing
* [core]: clean up to 200 monitors
* [core]: do not use context description hook
* [core]: tell Oyranos we are a display
* [core]: fix string length array
* [core]: move ICC setup inside
* [core]: omit EDID removal
* [docu]: update NET to ICC atoms prefix
* [conf]: prepare C++ builds
* [conf]: bump libXcm requirement to 0.5
* [conf]: require libXcm during configure
* [core]: rename net-color spec
* [core]: support per region profiles
* [core]: make allocations fit for C++
* [core]: modularise CLUT creation
* [core]: add PrivColorContext
* [core]: cache profiles in Oyranos
* [core]: fix debug messages
* [core]: clean unused cruft
* [core]: improve debug clut images
* [conf]: bump version
* [docu]: update ChangeLog

### Tomas Carnecky (1):
* [core]: remerge with old profile code

# Version 0.8.4

### Kai-Uwe Behrmann (36):
* [conf]: update
* [build]: explicite require compiz for packaging
* [build]: link against basic Compiz libs
* [docu]: fix typo
* [docu]: some more introduction
* [docu]: add more details to the introduction
* [docu]: tell about compiz + nouveau
* [core]: fix double correction for first opt-out
* [core]: report only actual capabilities
* [core]: better check before claim colour managed
* [docu]: resize icon
* [core]: adapt to new public oyHash_s APIs
* [core]: fix compiler warnings
* [build]: compress package with bzip2
* [docu]: add installation instructions
* [conf]: sync test script with Oyranos
* [conf]: use -fPIC only on 64-bit builds
* [docu]: nouveau + compiz package on openSUSE
* [core]: add compatibility macro for oy < 201
* [core]: cache the transformed pixels in memory
* [docu]: add user installation hint
* [core]: fix new rendering bug from #cfbb3ab3
* [docu]: label the colour transform in ARB code
* [core]: simplify previous commit
* [core]: de-and multiply alpha
* [core]: reduce shader code
* [core]: remove unused variable
* [conf]: bump version
* [docu]: fix typo
* [core]: reorder setupColourTables()
* [core]: add more error messages
* [docu]: _NET_COLOR_DISPLAY_ADVANCED usage
* [core]: support _NET_COLOR_DISPLAY_ADVANCED
* [core]: use Oyranos CMM settings
* [core]: first steps towards compiz 0.9.x
* [docu]: update ChangeLog

### Nicolas Chauvet (1):
* [conf]: apply Fedora patch for pkg-config

# Version 0.8.3

### Kai-Uwe Behrmann (11):
* [docu]: update ChangeLog
* [conf]: bump version
* conf]: add --regdir and --plugindir to configure
* [conf]: sync test script with Oyranos
* [conf]: fail for compiz
* [docu]: hint about Fedora package for noveau
* [core]: sync X11 and Oyranos contexts
* [core]: fix drawing of window borders
* [conf]: update date
* [core]: ignore ICC_PROFILE_IN_X
* [core]: check before calling XDestroyRegion()

# Version 0.8.2

### Kai-Uwe Behrmann (15):
* [docu]: update ChangeLog and README
* [conf]: bump version
* [build]: omit make uninstall during install
* [core]: update to libXcm-0.3.0
* [build]: update to RPM spec
* [core]: rename ICC profile setup function
* [core]: ignore removed _ICC_PROFILE(_xxx) atoms
* [core]: reduce net-color-desktop messages
* [core]: release oy_profile during init
* [core]: debug message from cleanScreenProfile()
* [core]: fix moving of atoms without size
* [core]: support dynamic monitor hotpluging
* [core]: add more verbosity to debug messages
* [core]: init ignore profiles
* [core]: skip sRGB in _ICC_PROFILE(_xxx)

# Version 0.8.1

### Kai-Uwe Behrmann (11):
* [build]: clean better
* [conf]: bump version
* [build]: switch test variable
* [build]: rename registration to compicc
* [build]: link with Oyranos libs
* [core]: add debug markers
* [build]: explicite compicc.xml in spec file
* [core]: rename internally to compicc
* [core]: hand over through _NET_COLOR_DESKTOP
* [build]: rename colour_desktop.c to compicc.c
* [core]: set _ICC_PROFILE after _NET_COLOR_DESKTOP

# Version 0.8.0

### Kai-Uwe Behrmann (2):
* [core]: initial commit
* [core]: support live monitor connect

The previous ChangeLog can be found in Oyranos git. Search for the
colour_desktop.c plugin and dont forget the original authors work.

