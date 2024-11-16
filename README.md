<!DOCTYPE html>
<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f9f9f9;
            color: #333;
        }
        h1 {
            color: #0056b3;
            text-align: center;
            border-bottom: 2px solid #0056b3;
            padding-bottom: 10px;
        }
        h2 {
            color: #333;
            background: #f1f1f1;
            padding: 10px;
            border-radius: 5px;
        }
        .highlight {
            background: #e3f2fd;
            padding: 10px;
            border-left: 5px solid #42a5f5;
            margin: 10px 0;
            border-radius: 5px;
        }
        img {
            display: block;
            margin: 10px auto;
            max-width: 100%;
            height: auto;
        }
    </style>
</head>
<body>

# How to Set Up Yii2 in Termux 📱

## Follow the steps below to install Yii2:

---

### **1. Setup Termux Storage Permission**
Run the following command and allow storage access when prompted:
```bash
termux-setup-storage
```
> **Tip:** Tap **Allow** when prompted.

**Insert Image Here:**
```html
<img src="path/to/image1.png" alt="Step 1 Image">
```

---

### **2. Update and Upgrade Termux Packages**
```bash
pkg update && pkg upgrade
```
> Using this to ensures all packages are up-to-date.

**Insert Image Here:**
```html
<img src="path/to/image2.png" alt="Step 2 Image">
```

---

### **3. Install Required Packages**
Install PHP, Curl, Git, and Unzip:
```bash
pkg install php curl git unzip
```

**Insert Image Here:**
```html
<img src="path/to/image3.png" alt="Step 3 Image">
```

---

### **4. Install Composer**
Install the Composer package to download Yii2:
```bash
pkg install composer
```

**Insert Image Here:**
```html
<img src="path/to/image4.png" alt="Step 4 Image">
```

---

### **5. Verify Composer Installation**
Check if Composer is installed correctly:
```bash
composer --version
```

**Insert Image Here:**
```html
<img src="path/to/image5.png" alt="Step 5 Image">
```

---

### **6. Create a Directory for Yii2**
Create a new directory named `yii2`:
```bash
mkdir yii2
```

**Insert Image Here:**
```html
<img src="path/to/image6.png" alt="Step 6 Image">
```

---

### **7. List Files and Folders**
Use the `ls` command to list files:
```bash
ls
```

**Insert Image Here:**
```html
<img src="path/to/image7.png" alt="Step 7 Image">
```

---

### **8. Navigate to the Directory**
Change to the `yii2` directory:
```bash
cd yii2
```

**Insert Image Here:**
```html
<img src="path/to/image8.png" alt="Step 8 Image">
```

---

### **9. Install Yii2 Basic Template**
Run the following Composer command to install Yii2 Basic:
```bash
composer create-project --prefer-dist yiisoft/yii2-app-basic yii2-basic
```

**Insert Image Here:**
```html
<img src="path/to/image9.png" alt="Step 9 Image">
```

---

### **10. Verify Files in the Directory**
List the files in the `yii2-basic` folder:
```bash
ls
```

**Insert Image Here:**
```html
<img src="path/to/image10.png" alt="Step 10 Image">
```

---

### **11. Change to `yii2-basic` Directory**
Navigate into the Yii2 Basic folder:
```bash
cd yii2-basic
```

**Insert Image Here:**
```html
<img src="path/to/image11.png" alt="Step 11 Image">
```

---

### **12. List Files Again**
List all files in this folder:
```bash
ls
```

**Insert Image Here:**
```html
<img src="path/to/image12.png" alt="Step 12 Image">
```

---

### **13. Navigate to the `web` Folder**
Change to the `web` folder where the app runs:
```bash
cd web
```

**Insert Image Here:**
```html
<img src="path/to/image13.png" alt="Step 13 Image">
```

---

### **14. Start a Local PHP Server**
Run PHP's built-in server on port 8080:
```bash
php -S localhost:8080
```

**Insert Image Here:**
```html
<img src="path/to/image14.png" alt="Step 14 Image">
```

---

### **15. Access the App in Browser**
Open your browser and visit:
```
http://localhost:8080
```

**Insert Image Here:**
```html
<img src="path/to/image15.png" alt="Step 15 Image">
```

<div class="highlight">
    🎉 TADAA!! Your Yii2 application should now be running locally in port 8080
</div>

---

</body>
</html>
