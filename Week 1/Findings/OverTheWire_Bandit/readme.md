# OverTheWire Bandit Wargame
## Practical Write-Up: Levels 0–10

- **Platform:** OverTheWire
- **Wargame:** Bandit
- **Category:** Linux Fundamentals and Beginner Cybersecurity
- **Target Host:** `bandit.labs.overthewire.org`
- **SSH Port:** `2220`
- **Levels Completed:** 0–10
- **Tools Used:** Windows Command Prompt, SSH, Linux command-line utilities

---

## 1. Introduction

OverTheWire Bandit is a beginner-friendly cybersecurity wargame designed to introduce users to Linux, command-line operations, and fundamental security concepts. The game consists of multiple levels, with each challenge requiring the player to discover a password that grants access to the next level.

In this practical exercise, I completed Bandit Levels 0 through 10. I used SSH to connect to the remote server and applied Linux commands to navigate directories, inspect files, identify hidden information, search for specific content, analyze file types, and decode data.

The primary objective was to develop practical Linux skills and improve problem-solving abilities through hands-on cybersecurity challenges.

## 2. Objectives

The objectives of this practical exercise were:

- To understand how SSH is used to access a remote Linux system.
- To learn basic Linux commands for navigating the file system.
- To identify and access hidden files.
- To search for information within files and directories.
- To understand file permissions, ownership, and file properties.
- To work with text-processing commands and encoded data.
- To identify and extract information from files with different formats.
- To develop a systematic approach to solving cybersecurity challenges.

## 3. Environment and Tools

### System Requirements

- A Windows computer with an SSH client.
- An active internet connection.
- Access to the OverTheWire Bandit server.

### Tools and Commands

| Tool or Command | Purpose |
|---|---|
| `ssh` | Connect to the remote Linux server |
| `ls` | List files and directories |
| `cd` | Change directories |
| `pwd` | Display the current directory |
| `cat` | Display file contents |
| `find` | Search for files based on specified conditions |
| `file` | Identify file types |
| `du` | Examine disk usage |
| `grep` | Search text for matching patterns |
| `sort` | Sort lines of text |
| `uniq` | Identify or count repeated adjacent lines |
| `strings` | Extract readable strings from binary data |
| `base64` | Encode or decode Base64 data |
| `xxd` | Display hexadecimal representations of data |
| `tr` | Translate or transform characters |

**Note:** The commands listed above are relevant to the skills covered by these levels. Not every command was necessarily required in every challenge.

## 4. Connecting to the Bandit Server

The Bandit server can be accessed through SSH using the following command in Windows Command Prompt or PowerShell:

```bash
ssh bandit0@bandit.labs.overthewire.org -p 2220
```

After executing the command, the server prompts for the password associated with the specified account.

For Level 0, the initial password is:

```text
bandit0
```

After successfully logging in, I used the Linux shell to investigate the environment and locate the information required to progress through the game.

For subsequent levels, I connected using the username associated with the next level and the password obtained from the previous challenge.

This write-up documents my practical experience with OverTheWire Bandit Levels 0–10, focusing on Linux fundamentals, command-line operations, and beginner cybersecurity skills.

## 5. Final Result

I successfully completed the challenges from Bandit Level 0 through Level 10 and obtained the credentials required to progress through the corresponding accounts.

The final password obtained for Bandit Level 11 was recorded as part of the practical exercise. For security and documentation purposes, the actual credential should be stored separately rather than included in a publicly accessible report.

The challenges demonstrated how basic Linux commands can be combined to inspect files, filter information, identify file properties, and decode data.

## 6. Skills Acquired

Through this practical exercise, I developed and strengthened the following skills:

- **Linux command-line proficiency:** Learned to navigate directories, inspect files, and execute commands in a Linux shell.
- **Remote system access:** Gained practical experience connecting to a remote server using SSH and a non-default port.
- **File system investigation:** Learned to identify hidden files and locate files based on size, ownership, group, and execution status.
- **Text processing:** Practiced searching, sorting, filtering, and extracting relevant information from text files.
- **File analysis:** Used file identification and string-extraction techniques to inspect files that were not immediately readable as plain text.
- **Data decoding:** Understood how to decode Base64-encoded content and distinguish encoding from encryption.
- **Problem-solving:** Improved the ability to interpret challenge requirements, select appropriate commands, and combine utilities using pipelines and redirection.

## 7. Security Observations

The Bandit challenges also highlighted several important security concepts:

- SSH provides encrypted communication between a client and a remote server.
- File permissions and ownership determine which users can access or modify files.
- Hidden filenames do not provide meaningful security by themselves.
- Sensitive credentials should not be exposed in public reports, screenshots, source repositories, or shared documents.
- Encoded data can often be decoded without a secret key; encoding should not be mistaken for encryption.
- Linux command-line tools can help security practitioners investigate systems and locate relevant information efficiently.

All activities in this exercise were performed within the intended OverTheWire Bandit learning environment.

## 8. Reflection

I completed OverTheWire Bandit Levels 0–10 and gained practical experience with the Linux command line and basic system operations. I learned how to navigate directories, identify and search files, work with file permissions, process text, handle encoded and non-text data, and connect to remote systems using SSH.

The challenges improved my problem-solving skills by requiring me to analyze each objective, understand the available information, and select appropriate Linux commands to retrieve the required results. I also developed a better understanding of file ownership, hidden files, command pipelines, input and error redirection, and the difference between data encoding and encryption.

Overall, this exercise strengthened my Linux fundamentals and provided a useful foundation for further study in cybersecurity, ethical hacking, system administration, and penetration testing.

## 9. Conclusion

The OverTheWire Bandit Levels 0–10 exercise was a valuable hands-on introduction to Linux and cybersecurity fundamentals. By completing the challenges, I learned to use common command-line utilities to investigate files, search for specific data, examine file metadata, and decode encoded content.

This practical experience demonstrated that effective cybersecurity work requires more than memorizing commands. It also requires logical reasoning, careful observation, an understanding of system behavior, and the ability to combine simple tools to solve a problem.

The knowledge gained from these levels will support my continued learning in Linux administration, ethical hacking, and security analysis.

## 10. Reference

**OverTheWire — Bandit Wargame**

Official website: https://overthewire.org/wargames/bandit/

The official Bandit page provides the challenge descriptions, access information, and level-specific instructions.
