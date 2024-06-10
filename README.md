# Ansible Semaphore

Ansible Semaphore is a modern UI for Ansible. It lets you easily run Ansible playbooks, get notifications about fails, and control access to deployment systems.

## Demo Video

Check out this demo video to see how this web UI for Ansible is so useful!

[Demo Video](link_to_demo_video)

## Installation and Setup

Follow these steps to set up Ansible Semaphore:

1. After making appropriate changes in the `docker-compose.yml` file, execute the following command in your terminal:
   ```bash
   docker-compose up
2. Ansible Semaphore will be available via the following URL: http://localhost:3000

3. Click on "Repositories" on the right-hand side and add a new repository. Provide the link for the repository that has the Ansible playbook you want to run.

4. Click on "Key Store" and add the SSH key or login details for your VM.

5. Click on "Environment" and configure it according to your needs.

6. Click on "Inventory" and provide your VM details here.

7. Then add a task that you would like to run by selecting the valid configuration.

8. Finally, run the task.
