publicIcons = [
  'hicolor/apps/16x16/nemo.png',
  'hicolor/apps/22x22/nemo.png',
  'hicolor/apps/24x24/nemo.png',
  'hicolor/apps/32x32/nemo.png',
  'hicolor/apps/scalable/nemo.svg',
  'hicolor/actions/16x16/nemo-eject.png',
  'hicolor/actions/16x16/menu-bullet.png',
  'hicolor/actions/16x16/menu-sort-up.png',
  'hicolor/actions/16x16/menu-sort-up-free.png',
  'hicolor/actions/16x16/menu-sort-down.png',
  'hicolor/actions/16x16/menu-sort-down-free.png',
  'hicolor/actions/16x16/menu-sort-right.png',
  'hicolor/actions/16x16/menu-sort-right-free.png',
  'hicolor/actions/16x16/menu-sort-left.png',
  'hicolor/actions/16x16/menu-sort-left-free.png',
  'hicolor/actions/16x16/menu-none.png',
  'hicolor/actions/32x32/nemo-eject.png',
  'hicolor/actions/scalable/view-compact-symbolic.svg',
  'hicolor/actions/scalable/location-symbolic.svg',
  'hicolor/actions/scalable/location-symbolic-rtl.svg',
  'hicolor/actions/scalable/mount-archive-symbolic.svg',
  'hicolor/actions/scalable/sidebar-hide-symbolic.svg',
  'hicolor/actions/scalable/sidebar-hide-symbolic-rtl.svg',
  'hicolor/actions/scalable/sidebar-show-symbolic.svg',
  'hicolor/actions/scalable/sidebar-show-symbolic-rtl.svg',
  'hicolor/actions/scalable/sidebar-tree-symbolic.svg',
  'hicolor/actions/scalable/sidebar-tree-symbolic-rtl.svg',
  'hicolor/actions/scalable/sidebar-places-symbolic.svg',
  'hicolor/actions/scalable/nemo-auto-arrange-symbolic.svg',
  'hicolor/actions/scalable/nemo-desktop-scale-symbolic.svg',
  'hicolor/actions/scalable/nemo-horizontal-layout-symbolic.svg',
  'hicolor/actions/scalable/nemo-horizontal-layout-wide-symbolic.svg',
  'hicolor/actions/scalable/nemo-vertical-layout-symbolic.svg',
  'hicolor/actions/scalable/nemo-vertical-layout-wide-symbolic.svg',
  'hicolor/actions/scalable/nemo-recursive-search-symbolic.svg',
  'hicolor/actions/scalable/nemo-recursive-search-symbolic-rtl.svg',
  'hicolor/devices/scalable/drive-removable-media-usb-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-0-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-10-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-20-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-30-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-40-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-50-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-60-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-70-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-80-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-90-symbolic.svg',
  'hicolor/status/scalable/nemo-progress-100-symbolic.svg',
  'hicolor/status/scalable/nemo-bookmark-not-found-symbolic.svg',
]
privateIcons = [
  'hicolor/emblems/16x16/emblem-note.png',
  'hicolor/emblems/24x24/emblem-note.png',
  'hicolor/emblems/48x48/emblem-note.png',
]
noInstallIcons = [
  'hicolor/apps/16x16/nemo.svg',
  'hicolor/apps/22x22/nemo.svg',
  'hicolor/apps/32x32/nemo.svg',
]

foreach icon : publicIcons
  nameParts = icon.split('/')
  theme   = nameParts[0]
  context = nameParts[1]
  size    = nameParts[2]
  file    = nameParts[3]
  install_data(icon,
    install_dir: join_paths(get_option('datadir'), 'icons', theme, size, context)
  )
endforeach


foreach icon : privateIcons
  nameParts = icon.split('/')
  theme   = nameParts[0]
  context = nameParts[1]
  size    = nameParts[2]
  file    = nameParts[3]
  install_data(icon,
    install_dir: join_paths(get_option('datadir'), 'nemo', 'icons', theme, size, context)
  )
endforeach

