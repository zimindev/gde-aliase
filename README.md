### 🐚 Step 1: Check which shell you are using

Run:

```bash
echo $SHELL
```

You'll get something like:

* `/bin/bash` → you're using **Bash**
* `/bin/zsh` → you're using **Zsh**

---

### 🛠 Step 2: Edit the config file for your shell

#### For **Bash**:

```bash
nano ~/.bashrc
```

#### For **Zsh**:

```bash
nano ~/.zshrc
```

---

### 📋 Step 3: Paste the aliases

Scroll to the bottom of the file and **paste** all the aliases you copied (from the Markdown block I gave you).

---

### 💾 Step 4: Save and close the file

* In `nano`:
  Press `CTRL+O` → `Enter` to save
  Then `CTRL+X` to exit

---

### 🔄 Step 5: Apply the changes

Run:

```bash
source ~/.bashrc   # if you edited .bashrc
```

or

```bash
source ~/.zshrc    # if you edited .zshrc
```
