# npm-start

Execute "npm start" inside a target_path folder.

## Requirements

This is assuming NPM is exist, without explicit dependencies.

## Role Variables

   - name: target_path
     desc: The location of the folder "npm start" to execute.

## Dependencies

No explicit dependencies.

## Example Playbook

   - hosts: servers
     roles:
       - role: npm-start
         target_path: "/home/ubuntu/{{ service_name }}"
