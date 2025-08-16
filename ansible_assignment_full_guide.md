# 🧪 Ansible Assignment: Basic Setup and Configuration

## 🎯 Objective
Practice Ansible fundamentals including:
- SSH setup
- User creation
- Package installation
- File management
- Variables
- Facts gathering

---

## ✅ Task Requirements

### 1. 🔐 Configure SSH Between Two Machines

- Set up **one control machine** (with Ansible) and **one target machine**.
- On the **control machine**, create a user called: `ansible_control`
- On the **target machine**, create a user called: `deploy`
- Ensure the control machine can SSH into the target machine using the user `deploy` **without typing a password** or typing **'yes' for confirmation**.

---

### 2. 📦 Install Apache (Latest Version) on the Target Machine

- Install `apache2` on Debian or `httpd` on RedHat.
- Use `when` condition based on `ansible_os_family`.
- Skip the install if total memory < 512MB using .

---

### 3. 📁 Create a Directory and Config File

- Create a directory: `/etc/demo_config`
- Inside it, create a file: `config`
- Add the line: `"Hello from control machine"`

🔧 Use variables for:
- The directory path
- The file name
- The message

---

### 4. 🧠 Print System Facts

Use the `debug` module to print:

- 🧮 Number of CPU cores
- 🧠 Total memory in MB 

---

### 5. 🔁 Install Multiple Packages Using Loop

Define Var:
```yaml
packages:
  - curl
  - htop
  - git
```

Use `loop` to install each of them.

---

### 6. ⏱️ Show Uptime

- Use the `command` module to run `uptime`.
- Print the output in terminal

---

## 📸 Deliverables

After completing the tasks, send:


- 📷 Screenshot showing:
  - Terminal output of playbook run (all tasks succeeded)
  - Your `inventory` file
  - Your `playbook.yml` file
  - Upload all of them in your drive 
  - send mail to moatazfci997@gmail.com
  - put your drive link + your name + your group ID
  - upload your task in the DEPI Drive

Good luck and happy automating! 🚀