# Checkstyle Configuration README

This is the Checkstyle configuration file (`checkstyle.xml`) for the project. It defines various rules and checks to ensure code quality and consistency.

## Checker Configuration

- **Severity**: `error`
- **Supported File Extensions**: `.java`, `.properties`, `.xml`, `.json`

## Modules

### Translation Check

- **Purpose**: Checks that property files contain the same keys.
- **Check Documentation**: [Translation Check](https://checkstyle.org/checks/misc/translation.html)

### Size Violations Checks

#### FileLength

- **Purpose**: Checks for size violations in files.
- **Check Documentation**: [FileLength Check](https://checkstyle.org/checks/sizes/FileLength.html)

#### LineLength

- **Purpose**: Checks for line length violations in Java files.
- **Maximum Line Length**: 150 characters
- **Check Documentation**: [LineLength Check](https://checkstyle.org/checks/sizes/LineLength.html)

### Whitespace Checks

#### FileTabCharacter

- **Purpose**: Checks for tabs in files.
- **Check Documentation**: [FileTabCharacter Check](https://checkstyle.org/checks/whitespace/FileTabCharacter.html)

### Miscellaneous Checks

#### RegexpSingleline

- **Purpose**: Checks for trailing whitespaces.
- **Check Documentation**: [RegexpSingleline Check](https://checkstyle.org/checks/misc/RegexpSingleline.html)
- **Regex Format**: `\s+$`
- **Minimum Occurrences**: 0
- **Maximum Occurrences**: 0
- **Message for Violation**: Line has trailing spaces.

### TreeWalker Module

The `TreeWalker` module encompasses various checks for code structure, Javadoc comments, naming conventions, size violations, modifier checks, block checks, common coding problems, and class design.

#### Javadoc Checks

- **InvalidJavadocPosition**: Checks for invalid positions of Javadoc comments.
- **JavadocMethod**: Checks for Javadoc comments on methods.
- **JavadocType**: Checks for Javadoc comments on types.
- **JavadocStyle**: Checks for Javadoc style violations.
- **MissingJavadocMethod**: Checks for missing Javadoc comments on methods.

