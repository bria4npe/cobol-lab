# cobol-lab

COBOL practice project: batch programs compiled with GnuCOBOL on WSL (Ubuntu).

## Programs

- `src/hello.cob`: hello world
- `src/interest.cob`: reads `customers.dat`, calculates 3.5% interest per customer and writes `report.txt`

## Build and run

    cobc -x src/interest.cob -o build/interest && ./build/interest
    cat report.txt
