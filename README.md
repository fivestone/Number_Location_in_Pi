# Number Position in Pi

Just a record of positions that each number appears in Pi, up to 9,999,999.

The data is stored in a sqlite3 file.

Table: pi_location

| number_str | position  | digits |
|------------|-----------|--------|
| 14         | 1         | 2      |
| 1415926    | 1         | 7      |
| 5926       | 4         | 4      |
| 535897     | 8         | 6      |
| 314        | 2120      | 3      |
| 0000314    | 2366817   | 7      |


As the examples shows, 
- the position means where each number starts with in Pi
- it does not count the "3."
- numbers filled with 0 are stored separately in each digit group.

Here are the positions where the last number appears in each digit group.

| number_str | position  | digits |
|------------|-----------|--------|
| 0          | 32        | 1      |
| 68         | 605       | 2      |
| 483        | 8553      | 3      |
| 6716       | 99846     | 4      |
| 33394      | 1369560   | 5      |
| 569540     | 14118307  | 6      |
| 1075656    | 166100500 | 7      |
|            |           | 8      |

The source data of Pi are gained from https://pi2e.ch/blog/2017/03/10/pi-digits-download/
