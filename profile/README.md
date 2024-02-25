# Visual alarm for the deaf and HoH, Glow alarm 💡
A visual alarm application using a smart light bulb.

<p align="center">
  <img src="https://github.com/sound-light/Glow-Alarm/assets/131771046/4e50fc5b-7b55-4e1a-9c71-31fbaedeb1bd">
</p>


## 💡 Project Overview
In the event of a fire, evacuation alerts are issued but rely solely on sound, becoming ineffectual for those with deaf and hard of hearing, highlighting a critical social inequality. Neuroplasticity suggests that individuals with hearing loss often have enhanced visual capabilities, making visual alarms a preferred method for alerts, as indicated by research in the *Fire Technology journal's* "Alarm Technologies to Wake Sleeping People Who are Deaf or Hard of Hearing (2022)." This underscores the necessity for a visual warning system.

Addressing this need, we developed Glow Alarm, a system providing visual alerts through lights and flashes, aiding those with hearing impairments in recognizing emergency situations promptly. This system utilizes red lights and flashing effects for alerts, seamlessly integrating with current auditory alert systems to ensure quick responses during emergencies, playing a vital role in life-saving situations.


## 🖱️ Project Links

[Flutter App](https://github.com/sound-light/sound_light_app)

[Fast API Backend](https://github.com/sound-light/sound-light-backend)


## 🔑 Key Features

- Google Login: Users can access Glow Alarm via Google login.
- Real-time Disaster Information: Use the Disaster API to receive disaster information in real time.
- Risk Analysis: Use Gemini to analyze the risk of disaster information received.
- Smart bulb settings: Show various bulb color, brightness, and speed of different bulbs depending on their risk to visually alert them to danger.


## 💻 Technical stack

Glow Alarm uses the following technology stack:

- Gemini: Used to analyze the risk of disaster information.
- Flutter: Used for the development of the front end of Glow Alarm.
- Firebase: Used for user authentication and database management.
- FastAPI: Used for backend development.
- Google Cloud Platform: Used for deployment and hosting of Glow Alarm.


## 📱 How To Use

1. Install the Glow Alarm.
2. Prepare the Yeelight smart bulb.
3. Press the icon located in the top right corner of the home screen to check if it is connected to the Yeelight smart bulb.
4. Personalized Alarm:
- Press the + icon on the home screen to set the time you want to wake up.
- You can set the desired color of the bulb.
  
5. Disaster Alarm:
- There are no separate settings! Glow Alarm analyzes disaster messages with AI to determine their importance.
- For disasters requiring immediate evacuation, the red light will wake you up.
- For less urgent disasters that still require your attention, the blue light will wake you up.



## ✨ Expectation Effects

1. Deaf and hard of hearing will become safer in disaster situations since they can swiftly respond to emergencies through visual alerts, facilitating smoother prevention and response during accidents.
2. Improve the quality of daily life for deaf and HoH as they can receive various alerts more effectively, not only in disaster situations but also in everyday life, helping boost their confidence and independence.
3.  Enhance social inclusivity by ensuring that all individuals have equal access to information and opportunities to respond in disaster situations, thereby contributing to reducing social inequality among community members.


## 🧑🏻‍💻 Team Sound Light 

| 윤병욱 [@speculatingwook](https://github.com/speculatingwook)| 이지민 [@clicelee](https://github.com/clicelee)       | 윤수혁 [@ShuYuns](https://github.com/ShuYuns)        | 강성우 [@KSW-KSM](https://github.com/KSW-KSM)         |
|:---------------------------:|:-----------------------------:|:-----------------------------:|:-----------------------------:|
| Backend/PM                | Backend/Designer            | Frontend                    | AI                          |

