Java:

"CI ensures that code changes are continually integrated and tested, while CD takes this a step further by automating the deployment process, allowing for rapid and reliable delivery of software."

CI setup tools (build & test)			Jenkins, Travis CI, CircleCI, GitLab CI/CD
CD setup tools							Kubernetes, Docker, Jenkins, Spinnacker
-(automated deployment & orchestration)
Infrastructure as Code					Terraform, CloudFormation, Ansible

lint:
build: 									maven(Java) / Gradle(*) / Make(C/C++) / Jenkins / TravisCI
test:									Jenkins / TravisCI
VCS: 									git(speed & robust branching) / svn(strong binary files support) / Mercurial /Perforce
versioning strategy:					semantic(Major.Minor.Patch) / custom
workflow:								gitflow (feature/release/fixes branches)/ github_flow (cont. delivery specific) / custom
build automation						Jenkins / TravisCI
deployment								Jenkins
artifact repository						Docker / Amazon ECR store / AWS S3 / private Nexus repository
deployment strategies					blue-green (identical environments one for production, other for updation/testing), 
											canary deployments, rolling updates
monitoring & feedback loop				Prometheus / Grafana (dashboarding capabilities)
 (health & perf of applicationsNinfra)
Security and Compliance Checks			OWASP ZAP / Nessus
Compliance as Code						Chef InSpec and Terraform
Git repository							GitHub, GitLab, Bitbucket
static code analysis tools				SonarQube
deployment automation					Ansible, Kubernetes, Terraform
pipeline orchestration tools			jenkins pipeline, GitLab Ci/CD, YAML, AWS CodePieline
centralized loggin solutions			ELK (Elasticsearch, Logstash, Kibana) / cloud-native logging services
automate db migrations					Flyway / Liquidbase



automated-testing						unit-tests + integration-tests + end-to-end tests
___________________
Jenkins: highly customizable
Travis CI: popular among open-source projects