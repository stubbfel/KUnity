# Kunity 
KUnity configure the c unit test framework Unity (http://www.throwtheswitch.org/unity) so that it can use in kernel space and provide a test runner (module), which can invoke from user space.

The submodule KUnity-Core contains the "test framework code", which should be insert to your kernel module (for more information please see [KUnity-Core](https://github.com/stubbfel/KUnity-Core)).

The submodule KUnity-Test-Runner-Module contains the "test runner", which should be insert (`insmod`) to your test system (for more information please see [KUnity-Core](https://github.com/stubbfel/KUnity-Test-Runner-Module)).