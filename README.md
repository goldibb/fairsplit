# FairSplit

FairSplit is a project designed to help manage and settle expenses for group trips and other shared costs.

## Features

- Track expenses for group trips
- Split costs fairly among participants
- Generate detailed reports of expenses

## Getting Started

### Prerequisites

- Go 1.18 or higher

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/fairsplit.git
    ```
2. Navigate to the project directory:
    ```sh
    cd fairsplit
    ```
3. Install dependencies:
    ```sh
    go mod tidy
    ```

### Running the Server

To start the server, run:
```sh
go run api/cmd/server/main.go