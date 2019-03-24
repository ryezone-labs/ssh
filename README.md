ryezonen_labs.ssh
=========

This role configures the SSH daemon and provisioning keys.

Role Variables
--------------

### Global Variables

- `ryezone_labs_provision_user` (string)

   Sets the provisioning username.

- `ryezone_labs_public_key_path` (string)

   Sets the path to the authorized public key for the provisioning user.

### Role Variables

- `sshd_provision_user` (string)

  Sets the provisioning username.  Defaults to `{{ ryezone_labs_provision_user }}`

- `sshd_provision_user_authorized_key` (string)

   Sets the path to the authorized public key for the provisioning user.  Defaults to `{{ sshd_provision_user_authorized_key }}`

License
-------

BSD
