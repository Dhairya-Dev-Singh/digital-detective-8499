# Mission 3 — Understand the operating system

Study draft: verify the observations on your own computer and rewrite the explanations in your own words before submission.

## 1. Task / objective

Explore the operating system, account identity, storage, running processes, paths, permissions, and operating-system responsibilities.

## 2. Work completed

- Checked macOS and storage information and reviewed a running-process snapshot in Activity Monitor.
- Identified processes and their PIDs.
- Compared absolute and relative paths and checked a practice file's permissions.
- Drafted explanations of six operating-system responsibilities.

## 3. Commands / tools used

- `sw_vers` — checked macOS version and build.
- `id -un` — checked account identity; its value is redacted.
- `df -h .` — checked used and available storage.
- Activity Monitor — viewed running processes, CPU activity, and PIDs.
- `ls -l` — viewed the practice file's permission string.
- `ps` and `top` were blocked by the session's permission limits; Activity Monitor was used for the process snapshot.

## 4. My understanding

The operating system manages processes, memory, devices, files, the user interface, and permissions. A process is a running program, and its PID identifies it in the process list. Absolute paths start at the file-system root; relative paths start from the current folder. The study draft in [Mission-03.txt](Mission-03.txt) includes examples to verify and explain in my own words.

## 5. Difficulties faced

The session returned “operation not permitted” for command-line process listings.

## 6. How I resolved them

I used Activity Monitor to review processes and PIDs. I will verify the behavior in my own Terminal before submission.

## 7. Evidence / files

- [Mission-03.txt](Mission-03.txt) — study notes and draft tables.

## 8. Commit details

- Suggested commit message: `Document operating system and file management`
- Commit status: Not committed.
- Push status: Not pushed.
