project('Larix', version : '0.0.0', meson_version : '>=1.0.0')

prefix = get_option('prefix')
themedir = join_paths(prefix, 'Larix')

subdir('cinnamon')

install_subdir(
    'cinnamon',
    exclude_files: ['meson.build'],
    exclude_directories: ['sass'],
    install_dir: themedir,
)

install_subdir(
    'shared',
    install_dir: themedir,
)
