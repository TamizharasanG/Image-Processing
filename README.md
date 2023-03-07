## Business Card Reader Streamlit Web App

This is a web application that allows users to extract information from a business card image, including name, designation, company name, address, email,contact number
and website.
Users can also upload the extracted information to a database, view the records, and delete them.

## Installation
Clone the repository to your local machine.

-->> git clone https://github.com/<username>/<repository>.git

Install the required Python packages using pip.

-->> pip install -r requirements.txt

Run the Streamlit app.

-->> streamlit run app.py

## Usage

-->> Upload a picture of a business card.

-->> Wait for the app to extract the information.

-->> Verify and correct any incorrect or missing information.

-->> Click "Upload to database" to add the extracted information to the database.

-->> Click "View Records" to view all records in the database.

-->> Click "Delete Record" to delete a specific record.

## Technologies Used

-->> Python

-->> Streamlit

-->> OpenCV

-->> EasyOCR

## Contributing
Contributions are always welcome! If you would like to contribute to this project, please create a new branch and submit a pull request.

For your reference i have attached some photos of the web app

-->> Upload a image and wait for few seconds. After the Fetch Text button appears click that
![image](https://user-images.githubusercontent.com/119114780/223506095-607a9858-4ba5-40a8-92c8-714e88f9768c.png)

-->> The fetched informations will appear along with the uploaded image in the text editor. Edit the informations if any deviations
![image](https://user-images.githubusercontent.com/119114780/223506307-6200d28c-ae17-4083-8573-7f7d4b360183.png)
![image](https://user-images.githubusercontent.com/119114780/223506503-cad532e5-93b3-4062-b762-caca1a4d5882.png)

-->> If you want to store the information click the upload button. The fetched informations will be uploaded in the SQL database (Used - SQLite3)
![image](https://user-images.githubusercontent.com/119114780/223506767-75bc64d3-84ad-40e1-afca-90a946cb8866.png)
![image](https://user-images.githubusercontent.com/119114780/223507865-7f4d7edb-effb-4043-8adf-c560ccea2f20.png)


-->> If you want to see a particular record or delete a particular record click the respective buttons after entering their name.
![image](https://user-images.githubusercontent.com/119114780/223507852-4f5d9217-ae94-41ed-ae46-94f1f9f5a3df.png)


-->> If you want to see all the records in the database, click View all records.




