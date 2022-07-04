from building import *

cwd     = GetCurrentDir()
src     = Glob('parson.c')
CPPPATH = [cwd]

group = DefineGroup('Parson', src, depend = ['PKG_USING_PARSON'], CPPPATH = CPPPATH)

Return('group')
