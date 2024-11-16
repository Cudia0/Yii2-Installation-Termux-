# How to Set Up Yii2 in Termux 📱

## Follow the steps below to install Yii2:

---

### **1. Setup Termux Storage Permission**
Run the following command and allow storage access when prompted:
```bash
termux-setup-storage
```
![Screenshot image](img/01.png)

> **Tip:** Tap **Allow** when prompted.

![Screenshot image](img/02.png)


---

### **2. Update and Upgrade Termux Packages**
```bash
pkg update && pkg upgrade
```
> Using this to ensures all packages are up-to-date.

![Screenshot image](img/03.png) 

![Screenshot image](img/04.png)
> Input: Capital **Y**
![Screenshot image](img/05.png)
> Input: Capital **Y**

---

### **3. Install Required Packages**
Install PHP, Curl, Git, and Unzip:
```bash
pkg install php curl git unzip
```

![Screenshot image](img/06.png)
![Screenshot image](img/07.png)
> Input: Capital **Y**


---

### **4. Install Composer**
Install the Composer package to download Yii2:
```bash
pkg install composer
```

![Screenshot image](img/08.png)

---

### **5. Verify Composer Installation**
Check if Composer is installed correctly:
```bash
composer --version
```

![Screenshot image](img/09.png)
> It suppose to look like this 
![Screenshot image](img/10.png)


---

### **6. Create a Directory for Yii2**
Create a new directory named `yii2`:
```bash
mkdir yii2
```

![Screenshot image](img/11.png)

---

### **7. List Files and Folders**
Use the `ls` command to list files:
```bash
ls
```

![Screenshot image](img/12.png)


---

### **8. Navigate to the Directory**
Change to the `yii2` directory:
```bash
cd yii2
```

![Screenshot image](img/13.png)


---

### **9. Install Yii2 Basic Template**
Run the following Composer command to install Yii2 Basic:
```bash
composer create-project --prefer-dist yiisoft/yii2-app-basic yii2-basic
```

![Screenshot image](img/14.png)
![Screenshot image](img/15.png)
![Screenshot image](img/16.png)
![Screenshot image](img/17.png)


---

### **10. Verify Files in the Directory**
List the files in the `yii2-basic` folder:
```bash
ls
```

![Screenshot image](img/18.png)


---

### **11. Change to `yii2-basic` Directory**
Navigate into the Yii2 Basic folder:
```bash
cd yii2-basic
```

![Screenshot image](img/19.png)


---

### **12. List Files Again**
List all files in this folder:
```bash
ls
```

---

### **13. Navigate to the `web` Folder**
Change to the `web` folder where the app runs:
```bash
cd web
```

![Screenshot image](img/20.png)


---

### **14. Start a Local PHP Server**
Run PHP's built-in server on port 8080:
```bash
php -S localhost:8080
```

![Screenshot image](img/21.png)
![Screenshot image](img/22.png)


---

### **15. Access the App in Browser**
Open your browser and visit:
```
http://localhost:8080
```

![Screenshot image](img/23.png)
![Screenshot image](img/24.png)
![Screenshot image](img/25.png)
> Login using **admin** user and password
![Screenshot image](img/26.png)

### **🎉 TADAA!! Your Yii2 application should now be running locally in port 8080 like this**

![Screenshot image](img/27.png) 
---
