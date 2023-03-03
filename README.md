# Simple nix VM for just anything

As described in this [post](https://jeancharles.quillet.org/posts/2023-01-16-Basic-nix-vm-for-just-anything.html)

Build with:

```bash
$ nix build  ./#nixosConfigurations.vm.config.system.build.vm
```

Then run with:

```bash
$ ./result/bin/run-nixos-vm
```

