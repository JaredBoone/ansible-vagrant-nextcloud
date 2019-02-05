# vagrant-ansible-nextcloud

## Provision a Nextcloud VM using Vagrant and Ansible

* Step 1: Install the following roles using ansible-galaxy:
```ansible-galaxy install geerlingguy.repo-remi geerlingguy.apache geerlingguy.php geerlingguy.postgresql geerlingguy.php-versions geerlingguy.redis geerlingguy.apache-php-fpm```

* Step 2: Provision the VM:
```vagrant up --provision```