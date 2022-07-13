# News Code Blog 📝
> This blog was made thanks to the help of django girls ❤.
> ![Captura de pantalla 2022-07-13 125740](https://user-images.githubusercontent.com/90936639/178789485-4344bd1b-542a-4f9c-84e2-9a2de4c9b305.png)

## Functionality: 
- You can write, update and delete posts in your own blog. <br>
- This application is deployed on pythonanywhere. To checkout this application visit this [link](https://newscode.pythonanywhere.com/).
# 👨‍💻Installation
## 📄Pre-Requirements
- Python Installed (Recommended version 3.8 or above)
- Pip Package Manager (pip)
- Django Installed (This proyect use the version 2.2)
## ⚙️How to use it?
1. Download this repository with git clone or by clicking the download as archive on this page

    ```
    git clone https://github.com/Fer-Bar/News-Code-Blog.git
    ```
    Go to the project directory.
    ```
    cd News-Code-Blog
    ```
    
2. Create a virtual environment:
    ### 🪟Windows:
   
    ```
    py -m venv venv
    ```
    Once created you can activate it.
    ```
    venv\Scripts\activate.bat
    ```
    ### 🐧Unix or MacOS:
    
    ```
    pip install virtualenv
    virtualenv venv
    ```
    Once created you can activate it.
    ```
    source venv/bin/activate
    ``` 
3. Install dependencies with `pip install -r requirements.txt`. Make sure everything is installed properly with `pip freeze`.
4. Apply the migrations.
    ```
    python manage.py migrate
    ```
5. To run the proyect locally, run the following command (If you want change the port):
    ```
    python manage.py runserver 8000
    ```
## 😎 Author

👤 **Fernando Barrientos**

<!---* Website: xadec
-->
* Website: [fer-bar.github.io](https://fer-bar.github.io/Portfolio/)
* Github: [Fer-Bar](https://github.com/Fer-Bar)
* LinkedIn: [Fernando Barrientos](#)
