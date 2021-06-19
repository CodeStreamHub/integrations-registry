# Code Stream Integrations Registry

#### How to register your custom integration here?

- Create a pull request with the following details about your custom integration in registry.yaml file
- We will verify the request and approve it if the custom integration meets all standards
- Once approved, it is live for all users of Code Stream to install in their environments/orgs

### Required details for a new custom integration registration

Sample registration entry in registry.yaml
```
  name: Jira Actions
  description: Contains popular Jira actions
  publisher: VMware
  email: demo@demo.com
  verified: true
  latestVersion: 0.1.0
  repo: https://github.com/CodeStreamHub/jira-actions
  versions:
    - version: 0.1.0
      image: cmbucicd/jira-actions:0.1.0
      yaml: https://raw.githubusercontent.com/CodeStreamHub/jira-actions/main/definitions/0.1.0/definition.yaml 
