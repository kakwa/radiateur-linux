radiateur-linux
===============

A simple linux iso builder transforming a computer into a radiator (boot -> launch stress, that's all)

How to use
----------

Build the iso:

* `./radiateur-linux.sh -a amd64 -o radiator.iso`

Burn the iso:

* `cdrecord ...`
* `dd if=radiator.iso of=/dev/sd<your key>`

Boot the iso.
