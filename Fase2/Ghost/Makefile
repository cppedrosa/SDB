all:
	clear
	@echo "Welcome to Ghost Deployment Script!"
	warn=False ANSIBLE_HOST_KEY_CHECKING=False ANSIBLE_LOCALHOST_WARNING=False ansible-playbook GhostPlaybook.gcp.yml

clean:
	rm -f *.retry
