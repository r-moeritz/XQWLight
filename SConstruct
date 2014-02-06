import platform
import os

ldflags = ''
source  = ['XQWLight.cpp']
target  = 'XQWLight'

if platform.system() == 'Windows':
    ccflags  = '/DWIN32 /EHsc /O2 /Gy'
    env      = Environment(CCFLAGS = ccflags,
                           ENV     = os.environ)
else:
    ccflags = '-O3 -msse2'
    env     = Environment(CCFLAGS = ccflags,
                          ENV     = os.environ)

env.Program(target    = target,
            source    = source,
            LINKFLAGS = ldflags)
