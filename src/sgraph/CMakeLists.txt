project(sgraph)

make_library(sgraph
  SOURCES
    sgraph.cpp
    sgraph_triple_apply.cpp
    sgraph_io.cpp
    sgraph_constants.cpp
  REQUIRES
    flexible_type sframe pylambda
)
