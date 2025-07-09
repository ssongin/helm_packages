# Default target
all:

# Install
apply:
	ansible-playbook apply.yaml #--ask-become-pass --ask-pass

prereqs:
	ansible-galaxy install -r roles/helm_apps/meta/requirements.yaml

# Help message
help:
	@echo "Usage:"
	@echo "  make prereqs				# Installs required collections"
	@echo "  make apply				# Create namespaces and install helm applications"
