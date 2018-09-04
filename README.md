# mit-elections-data

### Files

- `1976-2016-president.csv` - source: [U.S. President 1976-2016](https://electionlab.mit.edu/data)
- `1976-2016-senate.csv` - source: [U.S. Senate 1976-2016](https://electionlab.mit.edu/data)
- `1976-2016-house.csv` - source: [U.S. House 1976-2016](https://electionlab.mit.edu/data)



### Correction Process

1. Work from a branch for each ... _branch_ of government:

  - `president-corrections`
  - `senate-corrections`
  - `house-corrections`

2. If not done already, reorder the original CSV and commit that change on the branch. Order with respect to:
  - `state` (ascending)
  - `year` (descending)
  - `district` (ascending, if applicable)
  - `candidatevotes` (descending)

3. Make each correction and commit individually with a message referencing the state or district and year of the election result you are correcting.
  - E.g., `CA-17 2016`

4. Commit your changes on the branch and then file a PR.
