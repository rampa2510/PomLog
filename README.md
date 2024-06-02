# PomLog
PomTracker is a powerful command-line interface (CLI) tool built with Go that combines the Pomodoro technique with task tracking, GitHub branch tracking, and meeting logging to enhance your productivity and streamline your workflow.

# PomTracker Roadmap

## Phase 1: Core Functionality

- [ ] Implement Pomodoro timer functionality
  - [ ] Start, stop, and reset timer
  - [ ] Customizable work and break durations
  - [ ] Timer persistence across tmux sessions
- [ ] Integrate task logging
  - [ ] Automatically log tasks when a new layout opens
  - [ ] Persist logged tasks across sessions
- [ ] Implement GitHub branch tracking
  - [ ] Log GitHub branch changes when using `git switch`
  - [ ] Associate logged tasks with the corresponding GitHub branch
- [ ] Add meeting tracking
  - [ ] Manually log meetings with start and end times
  - [ ] Categorize meetings as scheduled or impromptu


## Phase 2: User Experience and Customization

- [ ] Enhance command-line interface
  - [ ] Implement intuitive commands and flags for easy interaction
  - [ ] Provide help documentation and examples
- [ ] Allow customization of timer settings
  - [ ] Enable users to set preferred work and break durations
  - [ ] Support multiple timer profiles for different work scenarios
- [ ] Improve visual feedback
  - [ ] Display timer progress and remaining time
  - [ ] Provide visual cues for task and meeting notifications

## Phase 3: Reporting and Analytics

- [ ] Generate end-of-day reports
  - [ ] Summarize tasks completed, time spent on each task, and meetings attended
  - [ ] Provide insights and visualizations based on tracked data
- [ ] Implement GitHub commit analysis
  - [ ] Integrate with GitHub API to fetch commit data
  - [ ] Generate reports on coding productivity and project progress
- [ ] Enhance meeting tracking
  - [ ] Integrate with calendar APIs to automatically sync meeting timings
  - [ ] Generate meeting reports with attendees, agenda, and action items


## Future Enhancements

- [ ] Mobile app integration for on-the-go tracking
- [ ] Team collaboration features for shared tasks and meetings
- [ ] Gamification elements to motivate and engage users
- [ ] Voice-based interaction for hands-free tracking
