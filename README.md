# Introduction to Jenkins

## What is Jenkins?
* A tool which simplifies the establishment of a continuous integration and continuous delivery, core aspects of DevOps.
* An open-source automation server
#### Continuous Integration
*  You want all parts of your application to go to the same place and run through the same processes with results published to an easy access place.
* Committing all your application code in a single repository.
* `CI is a development practice that requires developers to integrate code into a shared repository several times a day. Each check in is then verified by an automated build, allowing teams to detect problems early.` [source](https://stackify.com/what-is-cicd-whats-important-and-how-to-get-it-right/)
* 3 main stages: push --> test --> fix

#### Continuous Delivery
* Developers changes are automatically tested for bugs and uploaded to a repository.
* Ensure minimal effort required to deploy new code.
* Code is delivered to a production like environment

#### Continuous Deployment
* Automate deployment
* \'Automatically releasing a developers changes from repository to production \`
* `Ability to get changes of all types (features, configuration changes, bug fixes etc.) into production, or to users in a safe, quick and reliable manner. This is achieved by ensuring code is always in a deployable state.` [source](https://stackify.com/what-is-cicd-whats-important-and-how-to-get-it-right/)
* Principles of CD include frequent small deployments, automation, continuous improvement, and a shared responsibility model.

## Steps
1. Set up a repository
2. Run unit tests locally
3. Trigger --> Jenkinsjob + WebHook
4. Actions --> Setup, Unit tests
