# Project Title

The Todo App UI is a modern and intuitive interface for task management. It features a list of tasks color-coded by priority and a pie chart for quick insights. This sleek design ensures efficient navigation and a user-friendly experience. Perfect for those seeking a streamlined task overview.

### Prerequisites

*Node.js: Ensure you have Node.js installed. If not, download and install it from Node.js official website.
*Yarn Package Manager: This project uses Yarn for dependency management. If you don't have Yarn installed, you can get it by following the instructions here.
*Git (Optional): If you're planning to clone the project repository, it's a good idea to have Git installed on your machine. Download and install it from Git's official site.

### Installation

A step by step guide that will tell you how to get the development environment up and running.

```
$ Cloning the repository
$ git clone https://github.com/samirugamage/todo-app-samirugamge.git

$ Navigating to the diretory
$ cd path_to_downloaded_directory

$ Install Dependancies
$ yarn install
$ yarn start

$ This will open a tab in your default browser URL: "LOCALHOST:3000"

$  Now you can explore the UI components.
```


## Additional Documentation and Acknowledgments

src/
│
├── components/
│   ├── img/               (F - Folder containing all the assets/icons)
│   └── shared/           (F - Folder for Static Components)
│       ├── header.jsx    (h - File)
│       ├── layout.jsx    (h - File)
│       └── sidebar.jsx   (h - File)
│
├── activityFeed.jsx      (h - File)
├── pieChart.jsx          (h - File)
├── tasks.jsx             (h - File)
├── welcomeMessage.jsx    (h - File)
│
├── lib/                  (F - Folder)
│
├── pages/
│   └── Dashboard.jsx     (h - File)
│       ├── activityFeed.jsx (h - File)
│       ├── pieChart.jsx     (h - File)
│       ├── tasks.jsx        (h - File)
│       └── welcomeMessage.jsx (h - File)
│
├── styles/               (F - Folder for all external styling sheets)
│
└── app.jsx               (h - File)

