include_defs('//BUCKAROO_DEPS')

prebuilt_cxx_library(
  name = 'boost-type-traits',
  header_only = True,
  header_namespace = 'boost',
  exported_headers = subdir_glob([
    ('include/boost', '**/*.hpp'),
  ]),
  visibility = [
    'PUBLIC',
  ],
  deps = BUCKAROO_DEPS,
)
