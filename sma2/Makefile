###
### Depending on the compiling and linking environment used, some of these
### tests compile, link and run successfully only when certain
### macros are defined or certain compile or link options are specified.
### See the top level README file for a description of these macros.
###

CC=CC

CCFLAGS=

TESTS= \
	all_and_alltypes \
	all_max_alltypes \
	all_min_alltypes \
	all_or_alltypes \
	all_prod_alltypes \
	all_sum_alltypes \
	all_xor_alltypes 

all:	$(TESTS)

$(TESTS): %:	%.cpp
	-$(CC) $(CCFLAGS) -o $@ $<

clean:
	rm -f $(TESTS)

