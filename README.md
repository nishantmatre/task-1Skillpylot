# SkillPilots Day 22 — Maven Project with Git

Based on the uploaded screenshot.

## Task shown
**Initialize a Maven project with Git tracking for the upcoming full-stack application.**
1. Run `mvn archetype:generate` to create a basic project structure.
2. Initialize a Git repository and make the initial commit.
3. Add a `.gitignore` file for Maven and IDE files.

## Included files
- `pom.xml` — Maven project configuration (Java 17)
- `.gitignore` — ignores Maven build output and IDE files
- `src/main/java/com/skillpilots/app/App.java` — starter Java application
- `src/test/java/com/skillpilots/app/AppTest.java` — placeholder test class

## Requirements
Install Java JDK 17+, Apache Maven, and Git.

## Open and run in VS Code
1. Extract this ZIP.
2. Open the extracted folder using **File → Open Folder** in VS Code.
3. Open Terminal → New Terminal.
4. Check tools with `java -version`, `mvn -version`, and `git --version`.
5. Build using:
   ```bash
   mvn clean package
   ```
6. Run using:
   ```bash
   java -cp target/classes com.skillpilots.app.App
   ```

Expected output: `Full Stack Application - Maven project is ready!`

## Initialize Git tracking
Run these commands in the project folder:
```bash
git init
git add .
git commit -m "Initial Maven project setup"
```
If Git asks for your identity, configure your own details:
```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```
Then repeat the commit command.

## Note
This is a starter Maven project recreated from the screenshot, not the original SkillPilots website source code. Git history is created locally when you run the Git commands; the ZIP does not contain your personal repository history.
