
### Remote Birding with TinyML and Raspberry Pi
* References
 * (hackster.io/rob-lauer)[hackster.io/rob-lauer]
* Machine learning to solve false positives
* First question to answer
 * What is machine learning?
  * Incredibly inconsistent depending on data models
  * Lets computers learn from data, compared to explicit instructions
  * "Tell me what you think it is"
  * ML Model == Brain
  * ML Runtime == Body
* What is Tiny ML?
 * Small but highly optimized data models for microcontroller
* Edge computing
 * Brings computation closer to source of data
  * Rain gauges in a field
  * Temperature in a DC
  * More secure, private, and reliable
  * Reduced bandwidth requirements
* Tools & Services for Models
 * TensorFlow Lite
  * Enables on-device machine learning
  * Low-power devices (phones, IoT, etc)
  * Smaller models but worse performance than TensorFlow
  * Python, Swift, Java, Objective C
 * Edge Impulse
  * Web based UI for building and training models
 * Lobe.AI
* Image processing
 * Image classification
 * Object detection
 * Image segmentation
  * What pixels belong to which object?
* TensorFlow Hub
  * Free and OSS machine learning models
  * Unlikely to find out-of-the-box solution
* Hardware
  * Raspberry Pi 4 model B
  * Raspberry Pi OS
  * Powerful SBC (Single-board computer)
  * Off-grid power
    * 30,000 mAh USB-C Power Bank
    * 42w Solar Array
    * PIR Motion Sensor
  * Remote Data
   * Blues Wireless Notecard for Cellular
   * Notecarrier-Pi Host HAT
   * Notehub.io to Securely Route Data
   * Twilio to Send SMS
* Future improvements
