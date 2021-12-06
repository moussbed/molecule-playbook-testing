# molecule-playbook-testing

- molecule can works without role 

- Init scenario to work with molecule and playbook

  $ molecule init scenario

- To build image 
  $ molecule converge   

- You can ovveride MOLECULE_DISTRO
 
  $ export MOLECULE_DISTRO=debian10

  and run

  $ molecule destroy
  $ molecule converge 



