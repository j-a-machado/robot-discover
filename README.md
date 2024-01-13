# Robot Discover

![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![NPM](https://img.shields.io/badge/NPM-%23CB3837.svg?style=for-the-badge&logo=npm&logoColor=white)
![Robot Framework](https://img.shields.io/badge/Robot%20Framework-000000?style=for-the-badge&logo=robot-framework&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![Git](https://img.shields.io/badge/GIT-E44C30?style=for-the-badge&logo=git&logoColor=white)
![Yarn](https://img.shields.io/badge/Yarn-2C8EBB?style=for-the-badge&logo=yarn&logoColor=white)
![Mac OS](https://img.shields.io/badge/mac%20os-000000?style=for-the-badge&logo=apple&logoColor=white)

![QAExperience](https://cdn.eveclass.com/p/64da9e3dedc4a33519851fbe/files/logo/image/63420660-3fa1-11ee-a8cb-45f80ceed9bf/thumbnail.png)

____

Materials developed during the Robot Discover course on the QAXperience platform, about Robot Framework

For this project was used:
- Visual Studio Code
- Homebrew
- Node JS
- Yarn
- Git + Bash
- Robot Framework
- Python
- PIP

____

![](https://cdn.eveclass.com/p/64da9e3dedc4a33519851fbe/files/gallery/image/8d2700e0-55b1-11ee-9f29-9ddf2dd4e39d/original.png)

____

## Installation

### OS X
1. Download [Visual Studio Code](https://code.visualstudio.com/download)

2. Install Homebrew
```sh
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

3. Install Node:
```sh
brew install node 
node --version
npm --version
```

4. Install Yarn:
```sh
brew install yarn
yarn --version
```

5. Install Python:
```sh
$ brew install python
python --version
pip --version
```

6. Install Robot Framework:
```sh
brew install robot-framework
robot --version
Or
python -m robot --version
```

____

## Project Structure

```sh
|__ apps: folders and files of the app that will be tested
|__ projects: folders and files for tests built with Robot Framework
   |__ logs:
   |__ starbugs:
   |__ walkdogs:
```