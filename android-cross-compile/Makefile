run: clean
	make -C ../puppet
	docker build -t=android-cross-compile .

clean:
	./clean android-cross-compile

.PHONY: run clean
