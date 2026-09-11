---
name: java-code-reviewer
description: Review Java code and identify bugs, performance issues, security risks, and maintainability problems.
version: 1.0.0
author: test
tags:
  - java
  - code-review
  - development
---

# Java Code Reviewer

## Overview

This skill performs code reviews for Java applications.

The review focuses on:

- Correctness
- Code quality
- Performance
- Concurrency
- Security
- Exception handling
- Maintainability
- Spring Boot best practices

## Instructions

When Java code is provided:

1. Understand the purpose of the code.
2. Check for logical errors.
3. Check for possible NullPointerException issues.
4. Check resource management.
5. Check concurrency and thread-safety issues.
6. Check database and transaction usage.
7. Check performance problems.
8. Check security risks.
9. Suggest improvements when necessary.

For Spring Boot applications, additionally check:

- Dependency injection
- Transaction boundaries
- Controller design
- Service responsibilities
- Repository usage
- Configuration management

## Input

The input may contain:

- A Java class
- Multiple Java classes
- A Git diff
- A code snippet
- Spring Boot configuration

Example:

```java
@Service
public class UserService {

    @Autowired
    private UserRepository userRepository;

    public User findUser(Long id) {
        return userRepository.findById(id).get();
    }
}