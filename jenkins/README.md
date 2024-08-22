1. Install Jenkins:
- On Ubuntu, use:
sudo apt update
sudo apt install jenkins
2. Start Jenkins:
sudo systemctl start jenkins
3. Access Jenkins:
- Open your browser and navigate to `http://your-server-ip:8080`.
- Unlock Jenkins using the password from `/var/lib/jenkins/secrets/initialAdminPassword`.
4. Install Plugins:
- Install recommended plugins during the initial setup.
5. Create a New Pipeline:
- Go to Jenkins Dashboard ➡ New Item ➡ Pipeline.

Now, let's create a `Jenkinsfile` to define the pipeline. This file will automate the steps to
clone the code, build the Docker image, and run the container.