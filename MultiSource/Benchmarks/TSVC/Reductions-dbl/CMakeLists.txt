list(APPEND LDFLAGS -lm)
list(APPEND CFLAGS -std=gnu99)
set(RUN_OPTIONS 1670 14)
llvm_multisource(Reductions-dbl)
