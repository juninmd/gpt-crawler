```markdown
# AGENTS.md - Coding Agent Guidelines

These guidelines are designed to ensure high-quality, maintainable, and robust code for our AI coding agents. Adherence to these principles is crucial for long-term success.

## 1. DRY (Don't Repeat Yourself)

*   **Single Responsibility Principle:** Each agent should have a single, well-defined purpose. Avoid creating multiple agents with overlapping functionality.
*   **Module Design:**  Break down complex logic into reusable modules with clear responsibilities.
*   **Code Patterns:** Favor established coding patterns (e.g., dependency injection, strategy patterns) to reduce repetition.
*   **Templates:** Utilize templates where applicable to define reusable components.

## 2. KISS (Keep It Simple, Stupid)

*   **Minimal Code:** Strive for the shortest possible solution that achieves the desired result.
*   **Readability:** Prioritize clear and understandable code. Use meaningful variable and function names.
*   **Avoid Complexity:** Don’t over-engineer. Simplify logic whenever possible.
*   **Comments:** Provide concise comments only when absolutely necessary to explain complex logic or assumptions.

## 3. SOLID Principles

*   **Single Responsibility:**  Each class should have a single, well-defined purpose.
*   **Open/Closed Principle:**  The agent should be open for extension but closed for modification. This is achieved through modular design.
*   **Liskov Substitution Principle:**  Subclasses should be able to replace their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Each interface should have only the methods it needs.
*   **Dependency Inversion Principle:**  High-level modules should not depend on low-level modules.

## 4. YAGNI (You Aren’t Gonna Need It)

*   **Avoid Unnecessary Code:**  Don’t write code that isn’t currently required. Focus on implementing the essential functionality.
*   **Refactor Only When Needed:**  Refactoring is a last resort. Only refactor when performance or design issues are clearly identified.
*   **Prioritize Core Logic:**  Ensure that the core functionality of the agent is implemented before adding features that aren't essential.

## 5. Development Practices

*   **Testability:** All agent code must be designed to be easily testable.  Consider edge cases and boundary conditions.
*   **Modularity:**  All agent components should be modular and easily reusable.
*   **Error Handling:**  Implement robust error handling to prevent unexpected crashes or incorrect behavior.  Use appropriate error types and logging.
*   **Logging:**  Provide informative logging to aid in debugging and monitoring.

## 6. Code Length Constraint

*   **Maximum Code Length:** Each file must be 180 lines of code or less.
*   **Unit Tests:** All code must be accompanied by comprehensive unit tests covering all core functionalities.

## 7. Test Coverage

*   **Target Coverage:** Aim for 80% test coverage. This is a minimum requirement.
*   **Test Suite:**  A well-defined test suite is essential for maintaining code quality.

## 8. File Structure & Organization

*   **Naming Conventions:** Follow consistent naming conventions (e.g., camelCase for variables and functions).
*   **Docstrings:**  Include clear and concise docstrings for all functions, classes, and modules. Explain the purpose, inputs, and outputs.
*   **Comments:**  Provide brief, informative comments to explain complex logic or assumptions.
*   **Clear Separation of Concerns:** Each agent should have a distinct responsibility and well-defined boundaries.

## 9.  Specific Considerations for AGENTS.md

*   **Configuration:**  Any configuration data should be clearly separated and managed.
*   **Data Structures:**  Well-defined data structures should be used to represent agent data and state.
*   **Error Handling Strategies:**  Document the error handling strategy for each agent.

## 10.  Further Guidelines

*   **Code Reviews:**  All code should undergo peer code reviews.
*   **Static Analysis:** Utilize static analysis tools to identify potential issues.
*   **Refactoring:**  Regularly refactor code to improve its quality and maintainability.
*   **Documentation Updates:**  Keep documentation updated to reflect changes in the agent's code.

These guidelines are intended as a starting point.  Continuous improvement and adaptation are crucial for the long-term success of this project.  Any deviation from these guidelines should be documented and justified.
```