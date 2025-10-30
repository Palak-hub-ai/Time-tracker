# Productivity Tracker Pro 🚀

A comprehensive time tracking and productivity management application built with **React**.  
Track your work sessions, use the **Pomodoro technique**, analyze productivity patterns, and build consistent habits.

---

## ✨ Features

### 📊 Time Tracking
- **Manual Session Tracking:** Start, pause, resume, and stop sessions  
- **Activity Categorization:** Organize by Study, Exercise, Reading, Work, etc.  
- **Notes & Context:** Add notes for better session details  
- **Real-time Duration:** Live tracking of active session time  

### 🍅 Pomodoro Timer
- **Customizable Durations:** Choose work and break intervals  
- **Automatic Session Logging:** Save Pomodoro sessions automatically  
- **Visual Timer:** Large, clear countdown display  
- **Focus/Break Modes:** Clear mode indication  
- **Desktop Notifications:** Get notified when sessions end  

### 📈 Analytics Dashboard
- **Daily Stats:** Total time, sessions, category breakdown  
- **Weekly Overview:** 7-day productivity trends  
- **Progress Bars:** Goal completion visuals  
- **Category Analysis:** Time spent per activity  
- **Achievement Badges:** Unlock milestones as you progress  

### 🎯 Goal Setting
- **Daily Time Goals:** Set target minutes/day  
- **Pomodoro Goals:** Define daily Pomodoro sessions  
- **Progress Tracking:** Real-time indicators  
- **Streak Counter:** Maintain daily streaks  

### 🌓 Customization
- **Dark Mode:** Switch between light/dark themes  
- **Flexible Settings:** Adjust durations and goals  
- **Import/Export:** Backup and restore data  
- **Persistent Storage:** Automatic data saving  

---

## 🚀 Getting Started

### Prerequisites
- Modern web browser with JavaScript enabled  
- No installation required – runs entirely in-browser  

### Usage

1. **Start Tracking**
   - Enter activity name  
   - Select category  
   - Add optional notes  
   - Click “Start Session”  

2. **Use Pomodoro Timer**
   - Go to Pomodoro tab  
   - Click “Start Pomodoro”  
   - Focus during work  
   - Take breaks as prompted  

3. **View History**
   - Check completed sessions in History tab  
   - Review durations, delete if needed  

4. **Analyze Progress**
   - Visit Analytics tab  
   - Track daily & weekly progress  
   - Check badges  

---

## 🎨 Categories

| Icon | Category | Description |
|------|-----------|-------------|
| 📘 | Study | Learning & academic work |
| 💪 | Exercise | Physical activity |
| 📚 | Reading | Books & documents |
| 💼 | Work | Professional tasks |
| 🔨 | Project | Personal projects |
| 👥 | Meeting | Collaboration |
| ☕ | Break | Rest & relaxation |
| 📋 | Other | Miscellaneous |

---

## ⚙ Settings

- **Daily Goal:** Default 240 mins (4 hours)  
- **Pomodoro Goal:** Default 8 sessions  
- **Work Duration:** Default 25 mins  
- **Break Duration:** Default 5 mins  

---

## 💾 Data Management

### Export Data
Download all session history as JSON.

### Import Data
Restore data to continue tracking across devices.

### Data Persistence
Automatically saved to browser storage.

---

## 🏆 Achievements

- 🔥 **Week Streak:** 7-day streak  
- 🍅 **Pomodoro Master:** Complete daily Pomodoro goal  
- 💯 **Century Club:** 100 total sessions  
- 🎯 **Goal Crusher:** Achieve daily time goal  

---

## 🎯 Use Cases

- **Students:** Track study sessions  
- **Freelancers:** Log billable hours  
- **Remote Workers:** Balance productivity  
- **Developers:** Time-box coding sessions  
- **Writers:** Track writing consistency  
- **Anyone:** Build strong habits  

---

## 🔒 Privacy

- 100% local browser storage  
- No servers or data collection  
- You control all data  
- Export anytime  

---

## 🛠 Technical Details

**Built With**
- React 18  
- Lucide React (icons)  
- Tailwind CSS (styling)  
- Browser Storage API (persistence)

**Browser Compatibility**
- Chrome / Edge (recommended)  
- Firefox  
- Safari  
- Any ES6+ compatible browser  

---

## 📱 Responsive Design

Works seamlessly on:  
- 💻 Desktop  
- 📱 Mobile  
- 🧭 Tablets  

---

## ⌨ Keyboard Shortcuts

- **Enter:** Start a new session (activity input)  
- **Enter:** Add a session (notes input)  

---

## 🎨 Themes

**Light Mode:** Clean and colorful interface  
**Dark Mode:** Eye-friendly for long use  

---

## 📊 Data Format

```json
{
  "sessions": [...],
  "activeSessions": [...],
  "settings": {
    "dailyGoal": 240,
    "pomodoroGoal": 8,
    "workDuration": 25,
    "breakDuration": 5
  }
}
