project(
  'dynamic-wallpaper-editor',
  version: '1.9.0',
  meson_version: '>= 0.40.0',
)

i18n = import('i18n')

subdir('data')
subdir('help')
subdir('src')
subdir('po')

meson.add_install_script('build-aux/meson/postinstall.py')
