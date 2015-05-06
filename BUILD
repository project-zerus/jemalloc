licenses(['notice'])

cc_library(
  name = 'jemalloc',
  visibility = ['//visibility:public'],
  hdrs = [],
  srcs = [
    'src/arena.c',
    'src/atomic.c',
    'src/base.c',
    'src/bitmap.c',
    'src/chunk.c',
    'src/chunk_dss.c',
    'src/chunk_mmap.c',
    'src/ckh.c',
    'src/ctl.c',
    'src/extent.c',
    'src/hash.c',
    'src/huge.c',
    'src/jemalloc.c',
    'src/mb.c',
    'src/mutex.c',
    'src/prof.c',
    'src/quarantine.c',
    'src/rtree.c',
    'src/stats.c',
    'src/tcache.c',
    'src/tsd.c',
    'src/util.c',
  ],
  includes = [
    'include',
    '__build__/linux/include',
  ],
  copts = [
    '-std=gnu99',
  ],
  alwayslink = 1
)
