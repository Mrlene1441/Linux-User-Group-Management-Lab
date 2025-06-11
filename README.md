# Linux User & Group Management Lab

This project simulates a real-world system administration task using Linux. It focuses on creating users, assigning them to groups, managing file permissions, and restricting access to sensitive directories — all within a virtualized Linux environment.

---

## Objective

To practice and demonstrate Linux system administration skills, specifically user and group management, directory permission control, and security best practices.

---

## Tools Used

- Ubuntu 22.04 LTS (VirtualBox)
- Bash Shell / Terminal
- User management (`useradd`, `usermod`)
- Permission tools (`chmod`, `chown`, `groups`)

---

## Tasks Performed

| Step | Description |
|------|-------------|
| 1    | Created a group named `project_team` |
| 2    | Added three users: `alice`, `bob`, and `charlie` |
| 3    | Assigned passwords to all users |
| 4    | Added `alice` and `bob` to the `project_team` group |
| 5    | Created a shared directory `/project` accessible only to the group |
| 6    | Verified access: `alice` and `bob` could access; `charlie` was denied |
| 7    | Bonus: Created a read-only directory `/project/public_docs` for the group |

---

## Key Screenshots

- Group creation and user setup
- Group permission testing with `alice` and `charlie`
- Directory structure and permission outputs
- Bonus test: Read-only access confirmed

---

## Bonus Tests

### Bonus Directory Access Test – Group Member

Validated that a group member (e.g., `alice`) could read files from `/project/public_docs` but could not create or modify files.

### Bonus Directory Access Test – Non-Group User

Confirmed that a non-member (e.g., `charlie`) could not access the `/project/public_docs` directory at all due to restricted permissions (`750`).

---

## Outcome

- Demonstrated proper use of Linux file and directory permissions.
- Practiced secure group-based access control.
- Simulated real-world IT support tasks in a Linux environment.

---
