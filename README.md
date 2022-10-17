# Niles Ingalls 2022
# LLDC phone system including mantrap
# rewriting old phone system for current asterisk, and moving from phpagi to starpy




ansible-galaxy role install -p ./roles/ -r roles/requirements.yml
ansible-playbook --vault-password-file=.vault_pass site.yml
