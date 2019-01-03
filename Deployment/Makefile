target_dir := Examples/simple_test_k64f_gcc/

.PHONY: force

all: libkws.a

libkws.a: force
	@make -C $(target_dir)
	@cp -vf $(target_dir)/BUILD/$@ .

clean:
	rm -f libkws.a
	make -C $(target_dir) clean
