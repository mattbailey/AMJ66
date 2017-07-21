# AMJ66
AMJ66 Keyboard tmk firmware

## dependencies

* `brew tap osx-cross/avr && brew install avr-libc dfu-programmer`
* `git submodule init && git submodule update`

## build & flash

* Hit reset switch to enter kb into programming mode
* `cd src && make clean && KEYMAP=mattbailey make all dfu`
