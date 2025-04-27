# Mini Voting System for College Elections

This project is a simple *C language-based Voting System* designed to conduct *college-level elections*.  
It handles voter authentication, voting, and election result management.

## Features
- Admin Panel for election setup and result management.
- Voter Panel for casting votes securely.
- Voter ID validation based on date, location, and ID number.
- Protection against double voting.
- Live vote count update and result display.
- Ability to delete illegal votes.
- Election data saved in external text files.

## Tools & Technologies Used
- C Programming Language
- File Handling in C
- Structures (struct) for organized data management

## Project Structure
- main function — Main application code (admin panel, voter panel, result declaration).
- ElectionInfo.txt — Stores current election details.
- candidateX.txt — Stores vote count and voters for each candidate (where X = candidate number).

## How to Use
1. *Admin Panel*:  
   - Login using Username: Admin and Password: admiN.
   - Create a new election or continue a previous one.
   - Manage candidates and voting.
   - View and declare election results.

2. *Voter Panel*:  
   - Voters input their voter ID.
   - System validates the ID.
   - If valid and not voted yet, voter can cast vote.

## Example Voter ID Format
- 14 characters long.
- First 2 digits → Election Date.
- Next 9 characters → Location Name.
- Last 3 digits → Unique Voter Number.

Example: 12Mumbai001

## Future Improvements
- Add encryption for voter ID for higher security.
- Web or GUI-based front-end for better usability.
- SMS/Email notification to voters after voting.

## Author
Gollapalli Greeshma

## Project Link
- [GitHub Repository Link](https://github.com/Greeshma23-cmk/Mini-voting-System)
