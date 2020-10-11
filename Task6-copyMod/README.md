The copy module copies a file from the local or remote machine to a location on the remote machine.

Use the ansible.builtin.fetch module to copy files from remote locations to the local box.

If you need variable interpolation in copied files, use the ansible.builtin.template module. Using a variable in the content field will result in unpredictable output.

For Windows targets, use the ansible.windows.win_copy module instead
