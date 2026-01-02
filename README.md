# Postman for Testers 🚀

This repository represents my learning from Postman’s
**15 Days of Postman for Testers** program.

Since Postman workspaces cannot be exported directly,
each collection from the workspace is exported and
organized here for easy learning and reuse.

## Who is this for?
- Manual testers starting with API testing
- QA engineers learning Postman step by step
- Beginners who prefer structured examples

## Repository structure
postman/

├collections/ 

├environments/


## How to use
 1. Clone the repository
 2. Open Postman
 3. Import required collections from:
   `postman/collections`

## Credits
Based on Postman’s official **15 Days of Postman** learning series.

## Reference

https://github.com/user-attachments/assets/a70119f1-f4a7-445d-86df-3463dd367585


## Link 

https://quickstarts.postman.com/guide/15-days-of-postman

## Running collections using Newman (CLI)

Newman is Postman’s command-line runner.

### Prerequisites
- Node.js installed
- Newman installed globally

```bash
npm install -g newman
newman run postman/collections/day01_*.json -e postman/environments/postman_test_env.json




