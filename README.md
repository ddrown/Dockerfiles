android-cross-compile is an environment to build binaries for the android platform

to start a shell (changes not saved): docker run -t -i --rm ddrown/android-cross-compile /home/admin/shell

To compile an x86 binary:
    ARCH_NAME=x86 agcc -o test-x86 test.c
    ARCH_NAME=x86 agcc -pie -fPIE -o test-x86-pie test.c

To compile an arm binary:
    ARCH_NAME=arm agcc -o test-arm test.c
    ARCH_NAME=arm agcc -pie -fPIE -o test-arm-pie test.c

PIE (Position Independent Executables) are needed for Android L
