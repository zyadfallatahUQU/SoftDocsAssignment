# Robusty - Testing Apps Made Easier⏰

![Robusty Landscape Image](robusty.jpg)

Testing Tool To Make Your App More Reliable

## Key Features 📈

- **Easy To Setup**

- **Manual & Automated Tests**

- **Integration & End-End Test**

- **Comprehensive Bug Reports**

- **AI Testing Supported**

---

## Installation Guide ⬇️

1. Choose The **_Appropriate_**Operating System

2. Press The **_Download_** Button

3. After installing:

- **_Windows_**: `Follow The Wizard`

- **_MacOS & Linux_**: Open the command line. Then Write: `sudo apt install Robusty Robusty-core Robusty-platform`

---

## User Guide 📖

### Create a new Test Project 📅

- [ ] Create new project

- [ ] Give a name to the project

- [ ] Import the desired File Or Folder

- [ ] Choose The Desired Features

- [ ] Press **_Create_** to initalize the Testing Project

---

### Features Limitations

| Feature            | Description                                     | Maximum Test Use |
| ------------------ | ----------------------------------------------- | ---------------- |
| Integration Tests  | Testing Related Functions                       | 2000             |
| End To End Tests   | Testing The Application Features                | 150              |
| AI Generated Tests | AI Predict and Gives Test Cases                 | 500              |
| Manual Tests       | Create Manual Testing With Manual Specification | unlimited        |

---

### Reporting 🚩

```

{

    reportMessage: 'Report Message',

    occurPlace: 'Report place',

    time: '01-01-2024 21:00',

    additionalInfo: 'More Information'

}

```

## Troubleshooting ⚡

_Testing Cannot Begin:_

: It's Either The Folder is not linked properly OR There's No Features assigned to that project

_Testing Resources is High:_

: If you manual changes the Resources Management you need to check the allocation you assigned

_Testing is not Supported:_

: If Folder doesn't have an entry of the supported exstinsion[^2], Robusty won't start

## Advanced Usage 👨‍💻

### Scripting ⌨️

_Create new test project_

```
robusty create project as Project_Name

robusty use Project_Name

// Should look like this
> Project_Name

robusty add feature1 feature2

robusty import [File_path OR Folder_path]

// Ensure Everything Is Working
robusty test .
```

_Automate Tests_

```
robusty use Project_Name

// Should look like this
> Project_Name

robusty automate [test_type] #[min|hour]
// example
robusty automate integration 10min
```

---

### Integrations 🤝⌨️

| Application Name | Type    | Link                                                                                   |
| ---------------- | ------- | -------------------------------------------------------------------------------------- |
| VScode           | IDE[^1] | [VScode Link](https://code.visualstudio.com/) |

[^1]: **_IDE_**: Integrated Development Environments
[^2]: **_Extension_**: The End part of any file, ex: file.extension

<!--stackedit_data:
eyJoaXN0b3J5IjpbMTk3MDYwMjU2OCw4ODY3MTA5MCw3NzYyMj
M4MTgsLTcwOTU2NzExNywyMTMxMjM5ODA4XX0=
-->