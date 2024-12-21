# File Metadata Microservice

This is a solution to the [File Metadata Microservice](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/file-metadata-microservice) challenge from freeCodeCamp's Back End Development and APIs certification.

## Features

- Provides an endpoint to upload a file and retrieve metadata about the file.
- Returns the following details about the uploaded file:
  - **File name**
  - **File size** (in bytes)
  - **MIME type**

## API Endpoint

1. **Upload File**  
   **POST** `/api/fileanalyse`  
   - Form-data:
     - Key: `upfile`
     - Value: The file to be uploaded  
   
   Response:
   ```json
   {
     "name": "example.txt",
     "type": "text/plain",
     "size": 1024
   }
   ```

## How to Run Locally

1. Clone the repository:

```bash
git clone https://github.com/ashangunatilake/File-Metadata-Microservice.git
```

2. Navigate to the project directory:
```bash
cd File-Metadata-Microservice
```

3. Install dependencies:
```bash
npm install
```

4. Start the server:
```bash
npm start
```

