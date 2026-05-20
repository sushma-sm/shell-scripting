# 🐚 Shell Scripting for DevOps (Quick Notes)

## 📌 What is Shell Scripting?

Shell scripting is writing Linux commands in a file to **automate tasks**.

---

## 📁 File Type

```bash
script.sh
```

---

## 🚀 Basic Script

```bash
#!/bin/bash
echo "Hello DevOps"
```

Run:

```bash
chmod +x script.sh
./script.sh
```

---

## 🔤 Variables

```bash
name="DevOps"
echo $name
```

---

## 📥 Input

```bash
read name
echo "Hello $name"
```

---

## 🔁 If Condition

```bash
if [ $a -gt 10 ]
then
  echo "Big number"
else
  echo "Small number"
fi
```

---

## 🔄 Loop

```bash
for i in 1 2 3
do
  echo $i
done
```

---

## 📁 File Check

```bash
if [ -f file.txt ]
then
  echo "Exists"
fi
```

---

## ⚙️ Function

```bash
func() {
  echo "Hello"
}
func
```

---

## 🧪 DevOps Uses

* Automation scripts
* Server setup
* CI/CD pipelines
* Log cleanup
* Service checks

---

## ⚡ Example Script

```bash
#!/bin/bash
systemctl status docker

if [ $? -eq 0 ]
then
  echo "Running"
else
  echo "Not Running"
fi
```

---

## 📌 Key Points

* Always start with `#!/bin/bash`
* Use `chmod +x` to run script
* Automates DevOps tasks

