project('example', 'c')

sources = []
inc     = []

subdir( 'boards' )

message(b_sanitize)

#add_project_arguments('-march=rv32imc', language: 'c')
#linker_script = join_paths(meson.current_source_dir(), 'ld/esp32c3.ld')

#add_project_link_arguments('-T', linker_script1 ,'-T', linker_script2 ,'-T', linker_script3 ,'-march=rv32imc', '--specs=nano.specs', '--specs=nosys.specs', '-nostartfiles', language: 'c')

exe = executable('example', sources, include_directories:[inc])


