include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'sfml',
  header_namespace = 'SFML',
  header_only = True,
  exported_headers = subdir_glob([
    ('include/SFML', '**/*.hpp'),
    ('include/SFML', '**/*.inl')
  ]),
  deps = BUCKAROO_DEPS,
  visibility = ['PUBLIC']
)
