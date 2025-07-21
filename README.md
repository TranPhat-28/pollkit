# PollKit - A real time voting app
This repository is a detailed documentation of the development of the PollKit project

For details about the project progress and implementation, please visit:

| Repository     | Link |
|----------------|------|
| PollKit Client | https://github.com/TranPhat-28/pollkit-client |
| PollKit Server | https://github.com/TranPhat-28/pollkit-server |


## 1. Table of Contents

| Section                                      | Description |
|----------------------------------------------|-------------|
| [1. Table of Contents](#1-table-of-contents) | Overview of contents |
| [2. Project general information](#2-project-general-information) | General infomation about the project |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.1. Section A](#21-section-a) | Description |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2. Developer Tools & Helpers](#22-developer-tools--helpers) | Setting up some tools and helpers for workflow |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2.1. Husky](#221-husky) | Help with commits naming rule |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[2.2.2. Prettier](#222-prettier) | Help with code formatting |
| [3. Detailed technical information](#3-detailed-technical-information) | In-depth information about the technical development process |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.1. Section C](#31-section-c) | Description |
| &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;[3.2. Section D](#32-section-d) | Description |

## 2. Project general information

### 2.1. Section A

### 2.2. Developer Tools & Helpers

#### 2.2.1. Husky

Developers must name commit message with a prefix: feat, fix, refactor or chore.

1. Run `npm install husky --save-dev`.
2. Run `npx husky` to create folder `.husky/_`.
3. Inside the above folder, create a file named `commit-msg` to add your rules.

#### 2.2.2. Prettier

Apply the same code format rules for all members.

- [x] Make sure Prettier is installed.
- [x] Add file `.prettierrc` to define rules.
- [x] Add file `.prettierignore` to exclude any folders / files from being formatted.
- [ ] In case some code were pushed before Prettier setting up, run `npx prettier --write src` to reformat all files in `src` directory.

## 3. Detailed technical information 

### 3.1. Section C

### 3.2. Section D
