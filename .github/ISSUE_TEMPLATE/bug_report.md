---
name: Bug report
about: Create a report to help us improve
title: ''
labels: bug
assignees: ''

---

**CommandAPI version**
The version of the CommandAPI that has caused this bug

**Minecraft version**
What version of Minecraft you're using (e.g. 1.14.4)

**Describe the bug**
A clear and concise description of what the bug is.

**My code**
This code reproduces the behavior:
```java
LinkedHashMap<String, Argument> args = new LinkedHashMap<>();
CommandAPI.getInstance().register("mycmd", args, (sender, args) -> {
    //blah
});
```

**Expected behavior**
A clear and concise description of what you expected to happen.

**Screenshots**
If applicable, add screenshots to help explain your problem.

**Additional context**
Add any other context about the problem here.
