list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 3450 5)
llvm_multisource(GlobalDataFlow-flt)
