# Visit Logger - Simple Web Server

## What This Project Does

- Runs a web server using **Express.js**.
- Logs visitor time and IP address in a file (`visits.log`).
- Serves static files from the `public/` folder.
- Provides a `/logs` page to view visit history.

## How to Use

1. **Install Node.js** if you don’t have it.
2. Open the project folder in a terminal.
3. Install Express:
   ```sh
   npm install express
   ```
4. Start the server:
   ```sh
   node server.js
   ```
5. Open `http://localhost:1409/` in your browser.
6. Click **View Logs** to see visit records.

## How It Works

| Action        | What Happens           |
| ------------- | ---------------------- |
| Open website  | Logs visit (time + IP) |
| Visit `/logs` | Shows all saved visits |

## Example Log Data

```json
[
  {
    "time": "2025-02-15T15:55:03.354Z",
    "ip": "::1"
  },
  {
    "time": "2025-02-15T15:55:12.980Z",
    "ip": "::1"
  }
]
```

## Project Files

```
/project-folder
│-- public/        # Website files
│-- server.js      # Runs the server
│-- visits.log     # Stores visit logs
│-- package.json   # Dependencies
│-- README.mdn     # This file
```

## Screenshot



## Notes

- The server runs on **PORT 1409**.
- If `visits.log` does not exist, it will be created automatically.



