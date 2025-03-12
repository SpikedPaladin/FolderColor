project(
    'folder-color',
    
    version: '1.0',
    meson_version: '>= 1.0',
)

i18n = import('i18n')

config = configuration_data()
config.set('GETTEXT_PACKAGE', meson.project_name())
config.set('LOCALEDIR', join_paths(get_option('prefix'), get_option('localedir')))

subdir('src')
subdir('po')