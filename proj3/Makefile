opt: opt.c
	gcc -g -o opt -DPRINT_MATRIX -O3 -floop-block -floop-interchange -funroll-loops -fmove-loop-invariants opt.c
opt0: opt.c
	gcc -g -o opt0 -DPRINT_MATRIX -O0 opt.c
naive: naive.c
	gcc -g -o naive -DPRINT_MATRIX -O0 naive.c
clean:
	rm naive opt opt0
