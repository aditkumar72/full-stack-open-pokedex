# Some Info About CI

This markdown file contains information about CI tools in Java and some general information about CI.

## CI tools in Java

- **Linting**: Checkstyle and SonarQube
- **Testing**: JUnit and Mockito
- **Building**: Maven

## What alternatives are there to set up the CI besides Jenkins and GitHub Actions?

- **Travis CI**: A cloud-based CI service that integrates with GitHub repositories. (Paid)
- **CircleCI**: A cloud-based CI service that integrates with GitHub repositories. (Paid)
- **GitLab CI**: A CI service that is part of GitLab. (Free)

## Would this setup be better in a self-hosted or a cloud-based environment? Why? What information would you need to make that decision?

In general, cloud-based CI services are easier to set up and maintain. They also provide more flexibility in terms of scaling
and integrations with other services. However, self-hosted CI services provide more control over the environment and data.
The decision between self-hosted and cloud-based CI services depends on factors such as cost, security requirements,
and the need for customization.
