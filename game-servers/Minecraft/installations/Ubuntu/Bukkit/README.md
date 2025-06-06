# Bukkit Installation Procedures for Ubuntu/Debian
---

> Attention: You must be connected to your server with the “ ROOT ” user.

### Available Versions:

| Bukkit | Bukkit | 
| -------- | -------- |
| 1.21.5  | 1.16.5  |
| 1.21.4  |
| 1.21.3  |
| 1.21.1  |

---

### Step 1:

**Select the version you want to install, modify the command we use to call the script according to your choice.** <br>
**We call the script that will install the necessary files for us by running the following command.** <br>

```
sudo wget https://get.elewon.net/mc/ubuntu/bukkit/[Version]/setup.sh
```

#### Example;

```
sudo wget https://get.elewon.net/mc/ubuntu/bukkit/1.21.1/setup.sh
```

---

### Step 2:

**We install the incoming setup.sh script using the following command.**

```
sudo chmod +x setup.sh
```

```
sudo ./setup.sh
```

---

### Step 3:

**After installation, open the file with the <blockquote>cd (file name)</blockquote> command and enter the following command.**

<blockquote>Enter the version you have chosen in the required place on the command.</blockquote>

```
sudo ./start-X.XX.X.sh
```

### Step 4:

---

<blockquote>Finally, it will ask you to accept an eula, open the txt file using the command below and change false to true, then do CTRL+S and CTRL+X in sequence. restart the start.sh file and that's it.</blockquote>
