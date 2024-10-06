check:
	@find -name '*.txt*' | xargs isutf8
	@ath12k-fw-repo --check

notices:
	@find -name '*.txt' | xargs file

install:
	ath12k-fw-repo --install /lib/firmware
