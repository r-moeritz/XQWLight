import platform
import os

ccflags = '-O3 -msse2'
ldflags = '--static'
source  = ['XQWLight.cpp']
target  = 'XQWLight'

if platform.system() == 'Windows':
    env = Environment(tools = ['mingw'],
                      CCFLAGS = ccflags,
                      ENV = os.environ)
else:
    env = Environment(CCFLAGS = ccflags,
                      ENV = os.environ)

env.Program(target = target,
            source = source,
            LINKFLAGS = ldflags)
