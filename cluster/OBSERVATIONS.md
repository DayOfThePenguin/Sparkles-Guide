# Stuff I had to figure out

- How vagrant works
  - How to create a vagrantfile that matches the config in the Deploy k3d node
- What the actual goal was

## Deploy K3d

What the overall goal is:

- Appears to be to get a vagrant VM running that will give you an isolated environment to play with the tooling.
- Once you get `vagrant up` to work, you want to enter the vm `vagrant ssh` and install `docker`, `kubectl`, and `k3d`.
- Once you have those running, spin up a test cluster.
