# ZenFLOW Desk 2.0 README



## About

ZenFLOW Desk 2.0 is designed to transform traditional desks into dynamic and smart workspaces, providing real-time feedback to enhance efficiency, productivity, and collaboration. The beta build represents a significant advancement from the alpha version, integrating all main features and refining the user experience based on feedback.

## Usability
---
**Interface**

The desk's interface prioritizes intuitiveness and user-friendliness, centered around real-time feedback features for seamless navigation and operation.

**Navigation**

Users can control the desk's audio capture with a mute/unmute button, and the desk provides personalized insights, catering to individual speech patterns.

**Perception**

Key functionalities include Volume Monitoring, Appropriateness Rating, Speech Speed tracking, and real-time transcript generation for comprehensive summaries.

---

## Build Quality
---

**Singular User Experience**

The initial plans to accommodate multiple users have been revised to prioritize a singular user experience. This strategic shift magnifies the emphasis on real-time feedback, showcasing a unique function not commonly implemented in similar systems. By channeling resources towards optimizing feedback precision for a single user, the overall quality and effectiveness of the real-time feedback mechanisms are elevated.

**Standalone Device**

The ZenFLOW Desk 2.0 has transitioned from being part of a larger system to a standalone device. This strategic pivot allows the desk to function as a portable, versatile, and adaptable workspace companion. It can now be integrated into various work environments without dependency on external systems or peripherals. This change simplifies deployment and improves reliability, enhancing the overall usability of the desk.

**Bug Minimization**

Significant progress has been made in minimizing bugs related to audio functionality. While most issues have been successfully addressed, a minor challenge persists with certain audio clips not consistently captured. This occasional occurrence is attributed to the sensitivity of the current microphone device, which captures excess ambient noise. Efforts are underway to mitigate this issue by exploring alternative microphone options and modifying the code to capture less noise.

**Future Enhancements**

- Continued efforts to optimize feedback precision and enhance real-time feedback mechanisms.
- Exploration of alternative microphone options to improve audio capture reliability.
- Ongoing bug fixes and refinements to further improve the overall build quality and user experience.

---

## Vertical Features

### External Interface

- **LCD Touchscreen Interface**: Provides an intuitive interaction experience, though currently requires connection to a computer for application usage.
  
- **Real-Time Feedback Mechanism**: Offers personalized insights and gentle reminders, with satisfactory visibility and simplicity in feedback.

- **LED Striplight**: Enhances workspace ambiance and offers interactive relaxation methods, though dependent on user engagement.

### Internal Systems

- **Whisper and ChatGPT Integration**: Integrates real-time audio transcription and analysis, with potential long-term cost implications and performance issues.

- **Audio Capture and Processing**: Enables accurate audio transcription, though security measures and hardware limitations need consideration.

### Persistent State

- **Transcript and Summary Generation**: Provides prompt transcriptions, albeit with limitations in accuracy and formatting due to AI processing.

---

## Current Limitations and Considerations

- **Hardware and Software**: Issues with microphone sensitivity and audio clip cutoffs.
- **API Calls**: Performance impacts and response delays.
- **Cost**: Potential long-term expenses, especially with Whisper integration.
- **AI Processing**: Accuracy and formatting limitations in transcriptions and summaries.

---

## Outline of Work Done

- Communication with OpenAI's API to enable Whisper and ChatGPT analysis
- Real-time transcription
- Live chatbox functionality
- LEDs with serial communication enable user peripheral interactions
- Improved UI for user-friendliness
- Improved functionality for volume detection, transcription, and analysis
- Improved model of the tabletop design

---

## Currently Known Bugs

- Microphone still picks up excess background noise
- Audio is sometimes misinterpreted
- Wrong appropriateness ratings being given, ocassionally
- Arduino occasionally is unable to find the port for serial communication
- Discussion Summaries and Filler Word Analysis don't provide consistent formatting in responses
  
---

## Instructions for Use

  1. Once a group member has given you access to the UnityTeams Repository, find the scene titled: “UIScene” which one can easily search for in the search bar. 
  2. Click on “File” on the top and find “Build Settings”. Make sure that the “Scenes In Build” contains the scene you want.
  3. Click on “Build” and specify the location of where you want the build to be placed.
  4. Once the build has compiled, it should open the file location that you specified.
  5. Run the executable file titled: “ZENdesk”.
     
---


*Note: This README file provides an overview of the ZenFLOW Desk 2.0 beta build, including its features, usability, build quality, vertical features, current limitations, and considerations for future development.*
