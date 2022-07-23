
# Install the prerequisite program Löve

https://github.com/computate-org/computate_love

# Install the mari0 ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_mari0

# Clone the mari0 ansible role. 
git clone git@github.com:computate-org/computate_mari0.git ~/.ansible/roles/computate.computate_mari0

# Change into the mari0 ansible role directory. 
cd ~/.ansible/roles/computate.computate_mari0
```

# Run the mari0 ansible playbook to install mari0 locally. 

```bash
ansible-playbook install.yml
```

