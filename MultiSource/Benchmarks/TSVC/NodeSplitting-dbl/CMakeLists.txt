list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 10000 14)
llvm_multisource(NodeSplitting-dbl)
