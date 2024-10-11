# Step 1
### You need to download this folder into my-app because it contains:
**Link Download** [GoogleDrive-Project ISD](https://drive.google.com/drive/folders/1SQTcaPiX_aEfhbkQ0k5m7tF5X3UvxSNj?usp=sharing)

![image](https://github.com/user-attachments/assets/ce84f121-43fc-476e-9ae1-f614095d2bf9)

Download the Folder: Download the folder that contains all the necessary files.

1. Virtual Environment:

Inside the downloaded folder, locate the requirements.txt file.
Set up your virtual environment named hdrenv and install the required packages by running:

### ` python -m venv hdrenv `
source hdrenv/bin/activate  # For macOS/Linux
hdrenv\Scripts\activate  # For Windows
pip install -r requirements.txt `

2. API File: The downloaded folder contains a file named main.py. This file serves as the API for loading the model, processing it, and sending requests to various web pages.

3. Database File: There’s a database file named User_input.db included in the folder.

4. Model File: Also included is a model file named best.onnx, which you will use for your application.


# Step 2
## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

# Step 3
### Run Your FastAPI Application
You can run your FastAPI app using uvicorn. In your terminal, navigate to the directory where your main.py file is located and execute the following command:

 ### `uvicorn main:app --reload`

**main**: This refers to the name of the Python file without the .py extension.
**app**: This is the instance of the FastAPI application you created.
**--reload**: This option enables auto-reload, so the server restarts whenever you make changes to the code.

### Access Your Application
Once the server is running, you should see output indicating that your application is running on ` http://127.0.0.1:8000 `. You can access it in your web browser or use tools like curl or Postman.

To see the API documentation (Swagger UI), go to ` http://127.0.0.1:8000/docs `.


# I hope it works too! If you run into any issues or need help, just let me know! <3 <3 <3
