# Task Quest: Pixel Adventure 🎯

## Basic Details
**Team Name:** Binary Brains 🧠  
**Team Members:**  
- Raza Fathima V - Government Engineering College, Kozhikode  
- Vasundhara VS - Government Engineering College, Kozhikode  

**Hosted Project Link:**
https://vasxox.github.io/gamifiedproductivity/

---

## Project Description
Task Quest is a retro, pixel-themed web app that gamifies daily tasks. Users add "quests," complete them to earn XP, and track progress with survey analytics and mini focus videos. The app combines productivity, gamification, and a fun pixel aesthetic to help users stay focused and organized.  

---

## The Problem Statement
Many students and professionals struggle with **time management** and maintaining focus while handling multiple tasks. Traditional task managers are often boring and fail to motivate consistent engagement, leading to missed deadlines and reduced productivity.  

---

## The Solution
Task Quest solves time management and focus issues by:  
- **Gamifying tasks:** Users earn XP for completing quests  
- **Pixel-themed UI:** Engaging retro interface makes task tracking fun  
- **Focus videos:** Pomodoro-style embedded videos to enhance concentration  
- **Survey & Analytics:** Track task completion and focus levels with real-time pie charts  

---

## Technical Details

### Technologies/Components Used

**Software:**  
- **Languages:** HTML, CSS, JavaScript  
- **Libraries/Frameworks:** Chart.js (for survey pie chart)  
- **Tools:** VS Code, Git, Canva (for pixel assets)

**Hardware:** *(if applicable)*  
- None required  

---

## Features
1. **Task Management:** Add, view, and complete quests to earn XP  
2. **Profile & XP Tracking:** Personalized avatar with experience points  
3. **Focus Videos:** Pomodoro-style embedded videos for better focus  
4. **Survey & Analytics:** Pixel-style survey panel and pie charts to monitor user progress  

---

## Implementation

### For Software:

#### Installation
```bash
[Installation commands - e.g., npm install, pip install -r requirements.txt]
```

#### Run
```bash
[Run commands - e.g., npm start, python app.py]

---

## Project Documentation

### For Software:

#### Screenshots (Add at least 3)
<img width="953" height="503" alt="Screenshot 2026-02-14 063949" src="https://github.com/user-attachments/assets/0d709e95-d5b2-4f57-a921-5d3cd6d15cf0" />
Late-night building mode: turning tasks into XP in my own pixel-powered productivity world

<img width="960" height="500" alt="Screenshot 2026-02-14 064424" src="https://github.com/user-attachments/assets/6595539f-b0e5-4d88-8c7b-ef9ac29e21e4" />
When your AI study buddy understands the assignment better than you do

<img width="960" height="500" alt="Screenshot 2026-02-14 063838" src="https://github.com/user-attachments/assets/f933d584-541a-4ef5-9727-8ef9285794bf" />
Welcome back, player! Your pixel adventure begins here. The login page.

<img width="949" height="506" alt="image" src="https://github.com/user-attachments/assets/8c71ef1c-98e2-4b9a-99ef-b402fa9b9eea" />
Level up, achievements leads to more fun games!

#### Diagrams

**System Architecture:**
![WhatsApp Image 2026-02-14 at 7 26 00 AM](https://github.com/user-attachments/assets/754ebbf2-ff20-4568-a825-4a2b0b2edc2a)

*Explain your system architecture - components, data flow, tech stack interaction*
App follows a Client-Side Web Architecture. It is a Single Page Application(SPA) using browser storage.

**Application Workflow:**

User
   ↓
Browser (UI)
   ↓
JavaScript Logic
   ↓
LocalStorage (Data Persistence)
---

![Team](Add photo of your team here)
![8adbf2c3-2625-4bb6-84f7-9fa5be446532](https://github.com/user-attachments/assets/0d06c1f7-35c4-4e02-a161-f1383367dded)


---

## Additional Documentation

### For Web Projects with Backend:

#### API Documentation

**Base URL:** `https://api.yourproject.com`

##### Endpoints

**GET /api/endpoint**
- **Description:** [What it does]
- **Parameters:**
  - `param1` (string): [Description]
  - `param2` (integer): [Description]
- **Response:**
```json
{
  "status": "success",
  "data": {}
}
```

**POST /api/endpoint**
- **Description:** [What it does]
- **Request Body:**
```json
{
  "field1": "value1",
  "field2": "value2"
}
```
- **Response:**
```json
{
  "status": "success",
  "message": "Operation completed"
}
```

[Add more endpoints as needed...]

---

### For Mobile Apps:

#### App Flow Diagram

![App Flow](docs/app-flow.png)
*Explain the user flow through your application*

#### Installation Guide

**For Android (APK):**
1. Download the APK from [Release Link]
2. Enable "Install from Unknown Sources" in your device settings:
   - Go to Settings > Security
   - Enable "Unknown Sources"
3. Open the downloaded APK file
4. Follow the installation prompts
5. Open the app and enjoy!

**For iOS (IPA) - TestFlight:**
1. Download TestFlight from the App Store
2. Open this TestFlight link: [Your TestFlight Link]
3. Click "Install" or "Accept"
4. Wait for the app to install
5. Open the app from your home screen

**Building from Source:**
```bash
# For Android
flutter build apk
# or
./gradlew assembleDebug

# For iOS
flutter build ios
# or
xcodebuild -workspace App.xcworkspace -scheme App -configuration Debug
```

---

### For Scripts/CLI Tools:

#### Command Reference

**Basic Usage:**
```bash
python script.py [options] [arguments]
```

**Available Commands:**
- `command1 [args]` - Description of what command1 does
- `command2 [args]` - Description of what command2 does
- `command3 [args]` - Description of what command3 does

**Options:**
- `-h, --help` - Show help message and exit
- `-v, --verbose` - Enable verbose output
- `-o, --output FILE` - Specify output file path
- `-c, --config FILE` - Specify configuration file
- `--version` - Show version information

**Examples:**

```bash
# Example 1: Basic usage
python script.py input.txt

# Example 2: With verbose output
python script.py -v input.txt

# Example 3: Specify output file
python script.py -o output.txt input.txt

# Example 4: Using configuration
python script.py -c config.json --verbose input.txt
```

#### Demo Output

**Example 1: Basic Processing**

**Input:**
```
This is a sample input file
with multiple lines of text
for demonstration purposes
```

**Command:**
```bash
python script.py sample.txt
```

**Output:**
```
Processing: sample.txt
Lines processed: 3
Characters counted: 86
Status: Success
Output saved to: output.txt
```

**Example 2: Advanced Usage**

**Input:**
```json
{
  "name": "test",
  "value": 123
}
```

**Command:**
```bash
python script.py -v --format json data.json
```

**Output:**
```
[VERBOSE] Loading configuration...
[VERBOSE] Parsing JSON input...
[VERBOSE] Processing data...
{
  "status": "success",
  "processed": true,
  "result": {
    "name": "test",
    "value": 123,
    "timestamp": "2024-02-07T10:30:00"
  }
}
[VERBOSE] Operation completed in 0.23s
```

---

## AI Tools Used (Optional - For Transparency Bonus)

If you used AI tools during development, document them here for transparency:

**Tool Used:** e.g., GitHub, ChatGPT

**Purpose:** [What you used it for]
- Example: "Generated boilerplate React components"
- Example: "Debugging assistance for async functions"
- Example: "Code review and optimization suggestions"

**Key Prompts Used:**
- "Create a REST API endpoint for user authentication"
- "Debug this async function that's causing race conditions"
- "Optimize this database query for better performance"

**Percentage of AI-generated code:** [Approximately X%]

**Human Contributions:**
- Architecture design and planning
- Custom business logic implementation
- Integration and testing
- UI/UX design decisions

*Note: Proper documentation of AI usage demonstrates transparency and earns bonus points in evaluation!*

---

## Team Contributions

- Raza Fathima: Specific contributions -  Frontend development, API integration
- [Name 3]: Specific contributions -  UI/UX design, Testing, Documentation

---

## License

This project is licensed under the [LICENSE_NAME] License - see the [LICENSE](LICENSE) file for details.

**Common License Options:**
- MIT License (Permissive, widely used)
- Apache 2.0 (Permissive with patent grant)
- GPL v3 (Copyleft, requires derivative works to be open source)

---

Made with ❤️ at TinkerHub
