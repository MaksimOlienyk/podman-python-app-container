# podman-python-app-container
## - Створити простий Python-файл app.py:
print("Hello, Docker!")
<img width="940" height="170" alt="image" src="https://github.com/user-attachments/assets/48c12635-0403-4064-8163-91d566d972dd" />

## - Написати Dockerfile
<img width="935" height="208" alt="image" src="https://github.com/user-attachments/assets/ee6e5e35-aae3-424c-9b30-e23cdbee4c2e" />


## - Побудувати образ:
docker build -t my-python-app .
<img width="940" height="522" alt="image" src="https://github.com/user-attachments/assets/9e56d8c7-b8d3-471d-ac1d-7f0c54b96d8b" />


## - Запустити контейнер:
docker run my-python-app
<img width="930" height="86" alt="image" src="https://github.com/user-attachments/assets/56f34061-b685-4cb1-bcf1-f0166d3d0068" />
