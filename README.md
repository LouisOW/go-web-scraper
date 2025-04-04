# Download and Run the Go Application

Follow the steps below to download and run the Go application from GitHub.

## Prerequisites

Ensure you have the following installed on your system:

- [Go](https://golang.org/dl/) (version 1.16 or later)
- Git

## Step 1: Clone the Repository

Clone the Go project repository to your local machine by running the following command:

```bash
git clone https://github.com/username/repository.git
```

## Step 2: Navigate to the Project Directory

```bash
cd repository
```

Replace `repository` with the name of the cloned directory.

## Step 3: Install Dependencies

If the project has any dependencies, run the following command to fetch them:

```bash
go mod tidy
```

## Step 4: Run the Application

Finally, to run the appllication use:

```bash
#you can run the file directly by using
go run scraper.go

#to build for your current system, use:
go build -o scraper

#then run using:
./scraper
```

## Step 5 (optional): Build the Application for Heroku

To build the application, run the following command to build for linux(for Heroku to run:

To build for Heroku
```bash
GOOS=linux GOARCH=amd64 go build -o scraper
```

*instructions to be added for hosting on Heroku*
