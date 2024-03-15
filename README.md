## About TP01 IPE
`Introduction to Programming Environment` is a subject that helps students to build a professional environment for coding and understanding some technical words used in everyday project development. We believe development must be an enjoyable and creative experience to be truly fulfilling. IPE takes the pain out of development by easing common tasks used in many projects, such as:
- Code sharing for group project development.
- Code versioning for keeping changes under control.
- Code ownership by identifying who make any part of the code.
- Task management for dividing tasks for each team member.
## Code of Conduct
In order to ensure that everyone understand the subject, make sure everyone
complete every `Task Practice`.
## License
The IPE TP01 is open-sourced software licensed under the [MIT
license](https://opensource.org/licenses/MIT).
## Example code
Java code example:
```Java
public class App {
    public static void main(String[] args) {
        System.out.println("Welcome to IPE TP01.");
    }
}
```
View it in GitHub you will see it looks good.

## Commands to run
The following commands to initial git:
```sh
git config --global user.name taltongsreng
git config --global user.email ttongsreng@gmail.com
```
Create new folder TP01-IPE.
Open Git Bash 
(right click on fold TP01-IPE and choose Git Bash):
```sh
cd /d/I3/VCS/TP01-IPE
git init
git remote add origin/main https://github.com/taltongsreng/tp01-ipe.git
git branch -M main
```
Create README.md file
(right click in folder TP01-IPE choose new text document and then rename it to README.md)
```sh
git commit -m "Add README.md file"
git config --global --add --bool push.autoSetupRemote true
```
Using vscode:
Go to Source control in left sidebar.
Save stage changes the files.
