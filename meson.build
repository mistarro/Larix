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

# take next/prev icons for the cinnamon clandar from the icon theme
install_data(
    [
        'icon-theme/papirus-icon-theme/Papirus-Dark/16x16/actions/pan-end.svg',
        'icon-theme/papirus-icon-theme/Papirus-Dark/16x16/actions/pan-start.svg'
    ],
    install_dir : join_paths(themedir, 'cinnamon/assets')
)
