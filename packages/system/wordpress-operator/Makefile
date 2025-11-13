export NAME=wordpress-operator
export NAMESPACE=external-$(NAME)

include ../../../scripts/package.mk

update:
	rm -rf charts
	helm pull oci://registry-1.docker.io/bitnamicharts/wordpress --untar --untardir wordpress-operator
