# CareCall AI Assistant

A comprehensive desktop application designed to help elderly users manage their daily tasks, health reminders, and provide AI-powered assistance for better care and wellbeing.

## 🌟 Features

### Core Functionality
- **Smart Reminders**: Add and manage daily medication and health reminders
- **Emergency Contacts**: Store and manage important contact information
- **Personal Notes**: Write and save personal notes with timestamps
- **AI Chat Assistant**: Interactive AI chatbot for health and wellness support
- **Health Tips**: Random health tips with text-to-speech functionality
- **Modern UI**: Adaptive light/dark theme based on time of day

### AI Assistant Capabilities
- Health and wellness guidance
- Medication reminders
- Emotional support responses
- Interactive conversation
- Voice feedback for health tips

## 🛠️ Installation

### Prerequisites
- Python 3.8 or higher
- pip package manager
- Jupyter Notebook

### Required Dependencies

Install these packages by running the first two cells in the notebook:

**Cell 1:**
```bash
pip install PyQt5
```

**Cell 2:**
```bash
pip install pyttsx3
```

**Cell 3:** Contains the main application code

### Installation Steps

1. **Clone or Download** the project files
2. **Install Jupyter Notebook** (if not already installed):
   ```bash
   pip install jupyter
   ```
3. **Install dependencies**:
   ```bash
   pip install PyQt5 pyttsx3
   ```
4. **Run the application**:
   ```bash
   jupyter notebook Project.ipynb
   ```
   Then execute the cells in order

## 💻 Usage

### Getting Started
1. Open the `Project.ipynb` file in Jupyter Notebook
2. Execute the first cell to install PyQt5
3. Execute the second cell to install pyttsx3 (if needed)
4. Run the third cell containing the main application code
5. The CareCall AI Assistant window will open
6. The interface will automatically adapt to light/dark theme based on current time
7. Use the sidebar navigation to access different features

### Main Features

#### 📅 Add Reminder
- Click "Add Reminder" in the sidebar
- Enter task description
- Select date using the calendar widget
- Click "Add" to save

#### 🔍 Today's Reminders
- View all reminders scheduled for today
- Automatically filters current date reminders

#### 📞 Emergency Contacts
- View saved emergency contacts
- Add new contacts with name and phone number
- Quick access to important numbers

#### 📝 Personal Notes
- Write and save personal notes
- View recent notes with timestamps
- Persistent storage across sessions

#### 🤖 AI Chat Assistant
- Interactive chat with CareCall AI
- Ask about health, medications, or general questions
- Emotional support and guidance

#### 💡 Health Tips
- Get random health and wellness tips
- Text-to-speech functionality for accessibility
- Motivational daily advice

## 🎨 User Interface

### Adaptive Theming
- **Light Theme**: Active during daytime hours (before 6 PM)
- **Dark Theme**: Active during evening hours (after 6 PM)
- **Background Images**: Supports custom background images for enhanced experience

### Sidebar Navigation
- Profile section with optional profile image
- Time-based greeting system
- Easy-to-use button navigation
- Modern, accessible design

## 💾 Data Storage

The application uses JSON files for data persistence:

- **`reminders.json`**: Stores all user reminders
- **`contacts.json`**: Stores emergency contacts
- **`notes.json`**: Stores personal notes

### File Structure
```
project-directory/
├── Project.ipynb (main notebook file)
├── reminders.json
├── contacts.json
├── notes.json
├── profile.png (optional)
├── background_light.jpg (optional)
├── background_dark.jpg (optional)
└── icons/ (optional)
    ├── calendar-plus.png
    ├── calendar.png
    ├── phone.png
    ├── user-plus.png
    ├── edit.png
    ├── book.png
    ├── chat.png
    ├── heart.png
    ├── web.png
    └── exit.png
```

## 🔧 Configuration

### Optional Assets
- **Profile Image**: Place `profile.png` in the project directory
- **Background Images**: 
  - `background_light.jpg` for light theme
  - `background_dark.jpg` for dark theme
- **Icons**: Create an `icons/` folder with corresponding icon files

### Demo Data
The application automatically creates demo data on first run:
- Sample emergency contacts (Son, Neighbor)
- Sample reminders (Take medicine, Walk for 15 min)

## 🤖 AI Chat Features

The AI assistant can respond to:
- Health and medication queries
- Emotional support requests
- General greetings and conversations
- Reminder management guidance
- Wellness advice

### Sample Interactions
- "Hello" → Friendly greeting
- "How are you?" → Supportive response
- "I'm sad" → Emotional support
- "Remind me" → Guidance to reminder feature
- "Medicine" → Medication reminders

## 🔊 Accessibility Features

- **Text-to-Speech**: Health tips are read aloud
- **Large Font Sizes**: Easy-to-read interface
- **High Contrast**: Clear color schemes
- **Keyboard Navigation**: Full keyboard support
- **Simple Interface**: Intuitive design for elderly users

## 🛡️ Privacy & Security

- All data is stored locally
- No external data transmission
- User privacy is fully protected
- Offline functionality

## 🔍 Troubleshooting

### Common Issues

1. **PyQt5 Installation Error**:
   ```bash
   pip install --upgrade pip
   pip install PyQt5
   ```

2. **Text-to-Speech Not Working**:
   ```bash
   pip install pyttsx3
   ```

3. **Jupyter Notebook Not Found**:
   ```bash
   pip install jupyter
   jupyter notebook
   ```

4. **Icons Not Displaying**:
   - Ensure icon files are in the `icons/` directory
   - Check file permissions

5. **Notebook Won't Run**:
   - Restart the Jupyter kernel
   - Run cells in sequential order
   - Check for any missing dependencies

### System Requirements
- **OS**: Windows 10/11, macOS 10.14+, Linux
- **Python**: 3.8+
- **Jupyter Notebook**: Latest version recommended
- **RAM**: 2GB minimum
- **Storage**: 100MB for application and data

## 📱 Future Enhancements

- Voice command integration
- Medication image recognition
- Calendar synchronization
- Health data tracking
- Family member notifications
- Multi-language support

## 🤝 Contributing

This is an open-source project. Contributions are welcome:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 📞 Support

For support or questions:
- Create an issue in the project repository
- Contact the development team
- Check the troubleshooting section

## 🙏 Acknowledgments

- Built with PyQt5 for cross-platform compatibility
- Uses pyttsx3 for text-to-speech functionality
- Designed with elderly users in mind
- Focused on accessibility and ease of use

---

**CareCall AI Assistant** - Making healthcare management easier for everyone! 🏥❤️
