from building import * 

# get current dir path
cwd = GetCurrentDir()

# init src and inc vars
src = []
inc = []

# add Signal Led common include
inc = inc + [cwd]

# add Signal Led source code
src = src + ['./signal_led.c']
src = src + ['./led_sample.c']

# add group to IDE project
group = DefineGroup('SignalLed', src, depend = ['PKG_USING_SIGNAL_LED'], CPPPATH = inc)

Return('group')
