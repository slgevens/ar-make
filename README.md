# Very simple ansible role to invoke make

[1]: https://docs.ansible.com/ansible/make_module.html "docs.ansible.com"

There is an ansible [module][1] to to that, but it don't take an
argument to name the Makefile.

The role is made idempotent via a first invocation of `make -q`.
