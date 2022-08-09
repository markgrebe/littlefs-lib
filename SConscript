from building import *
import os

cwd = GetCurrentDir()
src = ['lfs.c','pico_hal.c']
CPPPATH = [cwd]
group = DefineGroup('FileSystem', src, depend = [''], CPPPATH = CPPPATH)

Return('group')
