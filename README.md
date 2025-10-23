# **Signal Equalizer**

Signal Equalizer is a versatile tool for audio and signal processing, with applications in music, speech, and biomedical fields such as hearing aid analysis and abnormalities detection. This desktop application allows users to modify the magnitudes of specific frequency components using sliders and reconstruct the adjusted signal. It offers multiple modes and intuitive visualization tools for different use cases.

![App Design Overview](https://github.com/user-attachments/assets/9d02efe0-0fa9-4b17-9eca-d4f69d7c0b2c)


---

## **Video Demo**

https://github.com/user-attachments/assets/d9f477f2-027d-402d-b953-52c1aa925c3b

---

## **Features**

### **Core Functionality**
- **Multiple Equalizer Modes**:
  1. **Uniform Range Mode**: Divide the frequency range into 10 equal segments, each controlled by a slider.  
  2. **Musical Instruments Mode**: Control specific instruments or animal sounds in a mixed audio file using dedicated sliders.  
  3. **Eliminates Vowels Mode**: Adjust or mute vowel components in songs using sliders.  
  4. **Wiener Filter Mode**: Remove noise from an audio file and reconstruct the clean signal.  

- **Interactive UI**:
  - Switch seamlessly between modes with a click.  
  - Adjustable sliders dynamically update captions and counts per mode.  
  - Toggle frequency view between linear and audiogram scales.  

- **Visualization Tools**:
  - Linked cine signal viewers for synchronous playback of input and output signals.  
  - Interactive playback features: play, pause, stop, speed control, zoom, pan, reset.  
  - Spectrograms for input and output signals, updated dynamically with slider changes.  

---

## **Application Interface**

### **Uniform Range Mode**
- **Hidden Spectrograms**  
![Uniform Mode](https://github.com/user-attachments/assets/e843b1ce-948b-46ad-8fcd-2b6c7a5efd25)

- **Slider 2 and 3 affect frequency ranges and reflect in output spectrogram**  
- **Audiogram Scale displayed for visualization**  
![Audiogram Scale](https://github.com/user-attachments/assets/ef53bfa8-48b5-4c85-a8cd-8d4ac55529f0)

---

### **Hybrid Sounds Mode**
- **Only the bird sound is audible; sliders for other frequencies are at minimum, muting other sounds**  
![Hybrid Mode](https://github.com/user-attachments/assets/6b1dc2cf-82fd-4c4b-9a6c-86da3f0f8498)

---

### **Eliminates Vowels Mode**  
![Vowel Mode](https://github.com/user-attachments/assets/ed7776e4-d70c-4848-b3d9-83d33db03882)

---

### **Wiener Filter Mode**
- **After clicking on Adjust Band to eliminate noise**  
![Wiener Filter](https://github.com/user-attachments/assets/685132b5-29a3-478b-9fd0-efbef90e2e67)

---

## **How to Run the Project**

1. Clone the repository:
 ```
 git clone https://github.com/your-repository/signal-equalizer.git
 ```

2.	Navigate to the project directory:
   ```
   cd signal-equalizer
   ```



3.	Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```


4.	Run the application:
   ```
   python Main.py
   ```
   
⸻

Contributors

<div>
<table align="center">
  <tr>
        <td align="center">
      <a href="https://github.com/YassienTawfikk" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/126521373?v=4" width="150px;" alt="Yassien Tawfik"/>
        <br />
        <sub><b>Yassien Tawfik</b></sub>
      </a>
    </td>
    <td align="center">
      <a href="https://github.com/madonna-mosaad" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/127048836?v=4" width="150px;" alt="Madonna Mosaad"/>
        <br />
        <sub><b>Madonna Mosaad</b></sub>
      </a>
    </td>
        <td align="center">
      <a href="https://github.com/nancymahmoud1" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/125357872?v=4" width="150px;" alt="Nancy Mahmoud"/>
        <br />
        <sub><b>Nancy Mahmoud</b></sub>
      </a>
    </td>
        <td align="center">
      <a href="https://github.com/yousseftaha167" target="_blank">
        <img src="https://avatars.githubusercontent.com/u/128304243?v=4" width="150px;" alt="Youssef Taha"/>
        <br />
        <sub><b>Youssef Taha</b></sub>
      </a>
    </td>    
  </tr>
</table>
</div>
