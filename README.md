# World Cup Games Data Import Script - Bash

## Introduction

The World Cup Games Data Import Script is a bash script designed to import game data from a CSV file into a PostgreSQL database. It allows for the insertion of game records, teams, and related information, facilitating the management of World Cup tournament data.

## Usage

1. **Database Setup**: Before using the script, ensure you have a PostgreSQL database set up with the required tables (`games` and `teams`). The script uses a specific database schema, so make sure your database matches the expected structure.

2. **Clone the Repository**: Start by cloning this repository to your local machine.

   ```bash
   git clone https://github.com/bistaalish/Wordcup-Database-FreeCodeCamp.git
    ```

3. **CSV Data**: Prepare a CSV file named games.csv containing the World Cup game data. The CSV format should include columns for YEAR, ROUND, WINNER, OPPONENT, WINNER_GOALS, and OPPONENT_GOALS.

4. **Configure Script**: Open the script (world_cup_data_import.sh) in a text editor. If you want to test the script with a different database, change the PSQL variable values accordingly.

5. **Run the Script**: In the terminal, navigate to the project directory and execute the script.
```bash
    cd world-cup-data-import
    ./world_cup_data_import.sh
```
6.**Follow the Process**: The script will read data from the games.csv file, insert teams if needed, and populate the games table with the game records.

## Important Notes
- This script assumes a specific CSV data structure and expects a certain database schema. Make sure your CSV file and database match the required format.
- The script does not include extensive error handling. Modify and enhance the script according to your specific needs and error-handling requirements.
- This script is intended as a basic example and may need customization for production use.

## Author
- Alish Bista
