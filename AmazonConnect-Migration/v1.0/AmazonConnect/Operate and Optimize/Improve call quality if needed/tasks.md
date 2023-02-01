
# Module: Improve call quality if needed
## Task 1: Improve call quality if needed
#### Description
Description: Call quality issues are some of the most difficult problems to troubleshoot in contact centers. To avoid voice quality issues and complex troubleshooting procedures, you must optimize your agents’ work environment and workstation settings. This pattern describes voice quality optimization techniques for agent workstations in Amazon Connect contact centers. It provides recommendations in the following areas:

•	Work environment adjustments. Agents’ surroundings don’t affect how voice is transmitted over the network, but they do have an effect on call quality.  
•	Agent workstation settings. Hardware and network configurations for contact center workstations have significant effects on call quality.  
•	Browser settings. Agents use a web browser to access the Amazon Connect Contact Control Panel (CPP) website and communicate with customers, so browser settings can affect call quality.

[Reference](https://docs.aws.amazon.com/prescriptive-guidance/latest/patterns/improve-call-quality-on-agent-workstations-in-amazon-connect-contact-centers.html?did=pg_card&trk=pg_card) 


#### Tools
Tools: 

•  Connect Endpoint Test Utility
#### Tools

•  This utility checks network connectivity and browser settings.
#### Tools

•  Browser configuration editors for WebRTC settings.
#### Tools

•  For Firefox: about:config  
•  For Chrome: chrome://flags
#### Tools

•  For Firefox: about:config
#### Tools

•  For Chrome: chrome://flags
#### Tools

•  CCP Log Parser - This tool helps you analyze CCP logs for troubleshooting purposes.
## Task 2: Adjust the work environment and reduce background noise
#### Description
Avoid noisy environments. If this is not possible, optimize the environment with these soundproofing tips:

•	Absorb noise by using sound-dissipating surfaces such as curtains, carpets, and soft furnishings.  
•	Block noise by putting barriers between desks.  
•	Consider an active noise cancellation (ANC) solution such as a white noise generator to help concentration and ensure privacy, or use noise-canceling headsets.  
•	Prevent echo on your calls. Big, empty spaces might create echo effects or amplify noises. Covering surfaces that can bounce sounds will help reduce echo.
## Task 2: Subtask 1: Choose the right headset
#### Description
•	If the environment is noisy, choose a stereo headset. Directing sound to both ears helps agents focus and hear the customer better, and reduces the overall noise by making it less likely for agents to raise their voices.  
•	Avoid using loud speakers or built-in computer audio. For best quality, use a wired headset that’s dedicated to contact center use. Wireless headsets are convenient, but they might be a source of additional audio delay and reduced audio quality because of radio interference and transcoding.
## Task 2: Subtask 2: Use the headset as intended
#### Description
•	Enable the active noise canceling and speech enhancement features of your headset if they are available. Look for settings such as ANC or ANR. For instructions on activating these settings, see the user manual for your headset.  
•	Adjust your microphone so you can speak directly into it. The best position for your microphone is just below your chin. Correct placement can make a difference of 10 decibels (dB) in the sound level. Most headsets allow you to rotate or bend the microphone arm (boom), so it is important to keep it in the right place when you are talking.   
•	Some headsets are equipped with multiple microphones and advanced features such as voice beamforming, which helps capture speech without a boom. To make sure that you’re using the main microphone as intended by the manufacturer, see the user manual for your device.
## Task 2: Subtask 3: Check workstation resources
#### Description
Make sure that your agents’ computers are performant. If they use third-party applications that consume resources, their computers might not meet the minimum hardware requirements to run CCP. If agents experience call quality issues, make sure that they have enough processing power (CPU), disk space, network bandwidth, and memory available for CCP. Agents must close any unnecessary applications and tabs to improve CPP performance and call quality.
## Task 2: Subtask 4: Configure operating system’s sound settings
#### Description
The default settings for microphone level and boost usually work fine. If you find that outbound voice is quiet or the microphone is picking up too much, it might help to adjust these settings. Microphone settings can be found in your computer’s system sound configuration (Sound, Input on MacOS, Microphone Properties in Windows). You can access advanced settings that might affect voice quality through system tools or third-party applications. Here are some of the settings you can check:


•	Sample rate – This value determines how many times the sound is probed per second. The default setting is usually 44 or 48 kilohertz (kHz). The optimal value for Amazon Connect is 48 kHz. You can use your browser settings to override the default value. For more information, see the troubleshooting section of the Amazon Connect Administrator Guide.  
•	Gain – This value determines how much the microphone amplifies the sound. If you turn the gain up, your microphone might pick up more background noise.  
•	Bit depth – This digital resolution value describes how many levels of sound amplitude are being recognized. The higher the bit depth, the smoother the voice sounds. However, many traditional telephony networks use the pulse-code modulation (PCM) standard, which supports only 8-bit resolution.  
•	Open threshold – This is the minimal sound amplitude that a microphone picks up. 

If you’re experiencing voice quality issues, try restoring these values to their default settings before investigating further.

For more information about these and other adjustable settings, see your device manual. 
## Task 2: Subtask 5: Use a wired network
#### Description
Typically, wired ethernet has lower latency, so it is easier to provide the consistent transmission quality required for voice data transmission. We recommend 100 kB bandwidth per call at the minimum.

•	If agents are working from home, we recommend wired connections. It must not take more than 150 milliseconds to hear the customer. You can access Amazon Connect’s latency test from the Connect Endpoint Test Utility. However, this utility measures the delay from the browser to Amazon Connect Regions, not to customers

• The 150-millisecond one-way delay recommendation prevents the agent and customer from talking over each other. The value is measured from end to end, and each element adds a delay, including the part of the call between the Amazon Connect Region and the customer.  

•	If agents are working from the office, corporate Wi-Fi is acceptable as long as parameters are in the recommended range, and Real-time Transport Protocol (RTP) traffic is prioritized. 
## Task 2: Subtask 6: Update hardware drivers
#### Description
When you use a USB or other type of headset that has its own firmware, we recommend that you keep it updated with the latest version. Simple headsets that use an auxiliary port use the computer’s built-in audio device, so make sure that the operating system hardware driver is up to date. In rare cases, an audio driver update can cause audio issues, and you might need to roll it back. For more information about changing firmware and driver versions, see your device manual.
## Task 2: Subtask 7: Avoid USB hubs and dongles
#### Description
When you connect your headset, avoid additional devices such as dongles, port type converters, hubs, and extension cables.

These devices might affect call quality. Connect your device directly to the port in your computer instead.
## Task 2: Subtask 8: Check CCP logs
#### Description
The CCP log parser provides an easy way to check application logs.

1.	Download the CCP logs after a call.
2.	Open the CCP Log Parser.
3.	Drag and drop the log file to upload the log for analysis.
4.	When the log has been analyzed, the Snapshots & Logs tab will be selected by default. Choose the Metrics tab next to it to check insights.
5.	In the WebRTC Metrics - audio_input section, check the following:  
•	The Audio Level graph, to see if your received audio level is above 0. This indicates that audio was received from your caller.  
•	The Packets graph for any lost packets. If this chart shows significant increases, contact your IT support team.
6.	In the WebRTC Metrics - audio_output section, check the following:  
•	The Audio Level graph, to confirm that audio was sent out from your device.  
•	The Packets graph. If you see a packet-loss spike, report it to your IT support team.  
•	The Jitter Buffer & RTT graph. Round trip time (RTT) values above 300 will affect the call experience.

Report these to your IT support team.
## Task 3: Optimize browser settings
#### Description
Optimize browser settings
## Task 3: Subtask 1: Restore default WebRTC settings
#### Description
WebRTC has to be enabled to make soft phone calls with CCP. We recommend that you keep the default settings for WebRTC-related features. 

•	In Chrome, you can set flags by navigating to the URL chrome://flags. Type WebRTC in the search box to find settings that can interfere with CCP, and set these to Default.   
•	In Firefox, type about:config in the address bar, and then type WebRTC in the search box on the configuration page. Non-default settings appear in bold text and can be changed to Default. 
## Task 3: Subtask 2: Disable browser extensions when troubleshooting
#### Description
Some browser extensions might affect call quality or even prevent calls from connecting properly. Use the incognito window or private mode in your browser, and disable all extensions. If that solves the problem, review your browser extensions and look for suspicious add-ons, or disable them individually.
## Task 3: Subtask 3: Check the browser sample rate 
#### Description
Confirm that your microphone input is set to the optimal 48 kHz sample rate. For instructions, see the Amazon Connect Administrator Guide.