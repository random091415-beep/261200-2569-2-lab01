# AI Log

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
Explain Java sorting assignment and help create project implementation.

### Actions
- Explained assignment requirements:
  - Read integer N.
  - Read N integers.
  - Sort integers in ascending order.
  - Print sorted result.

- Provided Java solution using:
  - Scanner
  - Arrays.sort()

- Explained code functionality:
  - main method
  - Scanner usage
  - array creation
  - loops
  - sorting process
  - output generation

### Files Modified
- Main.java

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
How to create a Java project in IntelliJ IDEA.

### Actions
- Explained project structure.
- Explained creation of src directory.
- Explained creation of Main.java.
- Explained JDK configuration.
- Explained running a Java application.

### Files Modified
- None

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
Use java.io instead of Scanner/System.in.

### Actions
- Explained BufferedReader.
- Explained BufferedWriter.
- Explained InputStreamReader.
- Provided sample implementation using java.io package.
- Explained differences between Scanner and BufferedReader.

### Files Modified
- Main.java

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
What does IntelliJ Java run command mean.

### Actions
- Explained:
  - java.exe path
  - classpath
  - JVM startup options
  - UTF-8 encoding options
  - Main entry point
- Explained Process finished with exit code 0.

### Files Modified
- None

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
Why does main use String[] args.

### Actions
- Explained Java entry point requirements.
- Explained command-line arguments.
- Explained String array usage.
- Provided argument examples.
- Explained why main() must follow the JVM signature.

### Files Modified
- None

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
Review Bubble Sort implementation.

### Actions
- Reviewed Bubble Sort code.
- Found ArrayIndexOutOfBounds risk caused by:
  - nums[j + 1]
  - loop condition j < n
- Suggested:
  - j < n - 1
- Provided optimized Bubble Sort implementation using:
  - for (int j = 0; j < n - 1 - i; j++)

### Files Modified
- Main.java

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
How to push project to GitHub.

### Actions
- Explained Git workflow:
  - git init
  - git add .
  - git commit
  - git remote add origin
  - git push -u origin main
- Explained branch checking.
- Explained remote configuration.

### Files Modified
- Git repository metadata

---

## Date
2026-11-18

### Model
M365 Copilot (GPT-5 based)

### Prompt
Create AI_LOG.md and explain project root.

### Actions
- Defined project root directory.
- Provided AI_LOG.md template.
- Explained purpose of AI activity logging.
- Verified GitHub push success.
- Recommended .gitignore.

### Files Modified
- AI_LOG.md

### Notes
Suggested .gitignore contents:

.idea/
out/
*.iml