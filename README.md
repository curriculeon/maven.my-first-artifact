# My First Artifact Deployment
* **Objective** - to deploy this project as a maven dependency to [packagecloud.io](https://packagecloud.io/)
* **Project Description** - this repository is used to generate random objects; Floats, Doubles, Longs, Integers, Strings, Dates

* Use the documentation [here](https://curriculeon.github.io/Curriculeon/lectures/java/build-automation/maven/packagecloud-maven-hosting/content.html) as your guide

### Creating a packagecloud account
* Navigate to [packagecloud.io](packagecloud.io) to create a new account.
* **DO NOT** click, _Sign Up With Github_
* **DO NOT** click, _Sign Up With Google_
* Ensure that you create a new account using email and password.

### Deploying an artifact

1. Edit permissions
   * `chmod u+x ./install-rbenv.sh` 
   * `chmod u+x ./install-package_cloud.sh`
   * `chmod u+x ./deploy.sh`
   * `chmod u+x ./mvnw`
2. Install `rbenv`
   * `./install-rbenv.sh`
3. From a <u>**new**</u> terminal, execute the command below
   * `./install-package_cloud.sh`
3. From a <u>**new**</u> terminal, execute the command below
   * `./deploy.sh`
4. Navigate to the newly deployed artifact in `packagecloud.io`
