# Git Branch Testing

# Project Setup Guide တတ်သလောက် မှတ်သလောက်ပါပဲ ညီတို့

## Steps to Integrate Folders from Different Branches

### 1. Adding the Dashboard Folder
To Create the `dashboard` folder in src folder:
1. Switch to the `dashboard` branch:
    ```bash
    git checkout -b dashboard
    ```
2. Create the `dashboard` folder into your project directory.
3. Commit and push the changes:
    ```bash
    git add .
    git commit -m "Add dashboard folder from dashboard branch"
    git push origin dashboard
    ```

### 2. Adding the Feature Folder
To Create the `feature` folder in src folder:
1. Switch to the `feature` branch:
    ```bash
    git checkout -b feature
    ```
2. Commit and push the changes:
    ```bash
    git add .
    git commit -m "Add feature folder from feature branch"
    git push origin feature
    ```

### 3. Adding the Service Folder
To Create the `service` folder in src folder:
1. Switch to the `service` branch:
    ```bash
    git checkout -b service
    ```
2. Commit and push the changes:
    ```bash
    git add .
    git commit -m "Add service folder from service branch"
    git push origin service
    ```

### 4. Adding the Public Folder
To Create the `public` folder in src folder:
1. Switch to the `public` branch:
    ```bash
    git checkout -b public
    ```
2. Commit and push the changes:
    ```bash
    git add .
    git commit -m "Add public folder from public branch"
    git push origin public
    ```

## Notes
## ရမ်းရေးထားတာပါ
- Ensure you have the proper permissions to access and merge branches.
- Verify each folder's contents after merging to avoid conflicts or missing files.

## Conclusion
Following the above steps will integrate the `dashboard`, `feature`, `service`, and `public` folders into your project from their respective branches.


- [@vitejs/plugin-react](https://github.com/vitejs/vite-plugin-react/blob/main/packages/plugin-react/README.md) uses [Babel](https://babeljs.io/) for Fast Refresh
- [@vitejs/plugin-react-swc](https://github.com/vitejs/vite-plugin-react-swc) uses [SWC](https://swc.rs/) for Fast Refresh
