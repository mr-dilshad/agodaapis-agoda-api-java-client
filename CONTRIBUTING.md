# Contributing to Agoda Spring Boot API Client

Thank you for considering contributing to the Agoda Spring Boot API Client! Your contributions are critical to making this library robust, efficient, and helpful for the developer community. Whether it's fixing a bug, adding a feature, or improving documentation, we appreciate your efforts.

---

## How You Can Contribute

Here are some ways you can get involved:

1. **Report Bugs**
   - Found a bug? Open an issue with a detailed description and steps to reproduce it.

2. **Suggest Features**
   - Have an idea to improve the library? Share it by opening a feature request issue.

3. **Fix Issues**
   - Browse the [Issues](https://github.com/mr-dilshad/agodaapis-agoda-api-java-client/issues) section for tasks tagged as `good first issue` or `help wanted`.

4. **Improve Documentation**
   - Contribute by adding or refining documentation, including usage examples.

5. **Write Tests**
   - Enhance the test coverage by writing unit and integration tests.

---

## Workflow for Contributing

Follow these steps to contribute:

1. **Fork the Repository**  
   Click the "Fork" button on the repository page.

2. **Clone Your Fork**  
   Clone your fork to your local machine:
   ```bash
   git clone https://github.com/mr-dilshad/agodaapis-agoda-api-java-client.git
   cd agodaapis-agoda-api-java-client
   ```

3. **Create a New Branch**  
   Use a descriptive branch name:
   ```bash
   git checkout -b feature/your-feature-name
   ```

4. **Make Changes**  
   Implement your changes while adhering to the coding standards.

5. **Run Tests Locally**  
   Ensure all tests pass before pushing your changes:
   ```bash
   mvn test
   ```

6. **Commit and Push Changes**  
   Commit your changes with a clear message:
   ```bash
   git add .
   git commit -m "Describe your changes"
   git push origin feature/your-feature-name
   ```

7. **Create a Pull Request**  
   Go to your forked repository on GitHub and click the "New Pull Request" button.

---

## Coding Standards

To maintain consistency and quality, please follow these guidelines:

- **Code Style**  
  - Follow standard Java conventions (e.g., 4 spaces for indentation).
  - Ensure your code is clean, modular, and well-documented.

- **Naming Conventions**  
  - Use descriptive and meaningful variable, method, and class names.
  - Follow camelCase for variables and methods, and PascalCase for class names.

- **Dependency Management**  
  - Add Maven dependencies judiciously and avoid unnecessary ones.
  - Ensure dependencies are compatible with Spring Boot.

- **Configuration**  
  - Use properties in `application.properties` or `application.yml` for external configurations.

---

## Testing

Before submitting changes, ensure that:

1. **Unit Tests**  
   - Write unit tests for any new feature or bug fix.
   - Tests should cover edge cases and core functionality.

2. **Run All Tests**  
   Execute all tests to confirm nothing is broken:
   ```bash
   mvn test
   ```

3. **Integration Tests**  
   - If your contribution involves API calls, ensure integration tests are isolated and mock external dependencies where possible.

4. **Code Coverage**  
   - Aim for high code coverage. Tools like JaCoCo can help.

---

## Code of Conduct

Please note that this project follows a [Code of Conduct](CODE_OF_CONDUCT.md). By contributing, you agree to uphold these standards.

---

We’re excited to collaborate with you and make this library an indispensable tool for developers! 
