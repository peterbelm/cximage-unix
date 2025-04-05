env = Environment()

lib = env.SharedLibrary('cximage', Glob('./*.cpp'), SHLIBVERSION="7.0.1")
env.InstallVersionedLib(target='/usr/local/lib', source=lib)
install_lib = env.Alias('install-lib', '/usr/local/lib')

env.Install(target='/usr/local/include/cximage', source=Glob('./*.h'))
install_inc = env.Alias('install-inc', '/usr/local/include/cximage')

env.Alias('install', [install_lib, install_inc])