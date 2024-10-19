# Chronos - Time Management Redefined ⏰

![chronos Interface Image](chronos_screenshot.png)

Time management tool to Increase your productivity

## Key Features 📈

- **Easy To Use**

- **Creating Multiple Projects**

- **Setting Deadlines**

- **Communication Tools**

- **Task Assignment**

---

## Installation Guide ⬇️

1. Choose The **_Appropriate_**Operating System

2. Press The **_Download_** Button

3. After installing:

- **_Windows_**: `Follow The Wizard`

- **_MacOS & Linux_**: Open the command line. Then Write: `sudo apt install chronos chronos-core`

---

## User Guide 📖

### Creating a Project 📅

- [ ] Create new project

- [ ] Give a name to the project

- [ ] Create a new deadline

- [ ] Set the deadline date and hour in that date

- [ ] Press the deadline that you created

- [ ] Create a Task to associate to that deadline

- [ ] Provide Title & Description (required fields)

- [ ] You can have multiple Tasks to one deadline

---

### Collaboration 🤝

| Collaboration Feature | Maximum Use | Description                                          |
| --------------------- | ----------- | ---------------------------------------------------- |
| Shared Projects       | 10          | How many project you can be shared with others       |
| Task Assignments      | 20          | How Many Tasks can be assigned to a deadline         |
| Communication Tools   | 8           | How many users you can communicate with concurrently |

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

_Deadline Already Exists:_

: Each Deadline that didn't reach it time is consider unique

_Cannot Join a Project:_

: If you reach the maximum amount of projects you can Join

_User Not Found:_

: When trying to communicate with user that doesn't enable communication (Become Anonymous [^1])

## Advanced Usage 👨‍💻

### Scripting ⌨️

Set a deadline automatically each period of time

```

chronos set deadline each (#number) (day | week | month | year)

// example

chronos set deadline each 2 week



// To Push notification

chronos use last deadline to notify



// create boilerplate task

chronos create task as task-name task-description

chronos attach last task to last deadline



// ending an old tasks

chronos delete before last task in deadline-name

```

---

### Integrations 🤝⌨️

| Application Name | Description       | Link                                                                                   |
| ---------------- | ----------------- | -------------------------------------------------------------------------------------- |
| Notion           | Organize tasks    | [Notion Link](https://www.notion.so/?_x_tr_sl=en&_x_tr_tl=ar&_x_tr_hl=ar&_x_tr_pto=sc) |
| Word             | Writing documents | [Word Link](https://www.microsoft.com/ar/microsoft-365/word?market=er)                 |
| Google Keep      | Notes writing     | [Google Keep Link](https://keep.google.com)                                            |

[^1]: **_Anonymous_**: usually used in programming when something become untraceable
<!--stackedit_data:
eyJoaXN0b3J5IjpbMjEzMTIzOTgwOF19
-->