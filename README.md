# Project 7 - *TaskKeeper*

Submitted by: **Gerald Shimo**

**TaskKeeper** is an iOS app that helps users manage their daily tasks and deadlines. It allows users to create, edit, and delete tasks while persisting all data locally using **UserDefaults**. The app includes a tab bar navigation system so users can easily switch between the task list and a calendar view that displays upcoming tasks.

Time spent: **8 hours** spent in total

## Required Features

The following **required** functionality is completed:

- [x] App displays a list of tasks
- [x] Users can add tasks to the list
- [x] Session persists when application is closed and relaunched (tasks don’t get deleted when closing app)  
- [x] Note: You have to quit the app, not minimize it, in order to see the persistence.
- [x] Tasks can be deleted
- [x] Users have a calendar view via navigation controller that displays tasks	

The following **additional** features are implemented:

- [ ] Tasks can be toggled completed
- [ ] User can edit tasks by tapping on the task in the feed view
- [ ] List anything else that you can get done to improve the app functionality!

## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/8d8eaecb257c4a1ab42320b3fe08c196">
      <p>Videos | Library | Loom - 11 November 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/8d8eaecb257c4a1ab42320b3fe08c196">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/8d8eaecb257c4a1ab42320b3fe08c196-db3721d4a23e3e9e-full-play.gif#t=0.1">
    </a>
  </div>


## Notes

One of the main challenges was setting up proper data persistence using `UserDefaults` for custom `Task` structs. Debugging JSON encoding and decoding was necessary to ensure tasks saved and loaded correctly across sessions. Integrating the `UITabBarController` and linking both the Task and Calendar views also required careful configuration.

## License

    Copyright 2025 Gerald Shimo

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
