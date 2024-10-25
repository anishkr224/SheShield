## SheShield: Advanced AI Solutions for Women’s Public Safety

**Goal of the Project**: Leverage the latest AI technologies to enhance the detection of crimes against women, creating a safer environment through real-time surveillance analysis.

**Description**: SheShield aims to transform women safety by integrating advanced AI-powered violence detection into existing CCTV systems. By analyzing real-time footage, SheShield will identify potential threats and anomalies that may indicate criminal activities against women. The system provides proactive monitoring and immediate alerts to prevent incidents and support law enforcement efforts.

SheShield’s approach includes person detection, gender classification, and anomaly detection, including lone women at night, unusual gestures, and gatherings of individuals. It also helps in identifying high-risk areas based on historical alert data, fostering a smarter, safer public environment.

### Project Overview:

Developed an intelligent surveillance system integrating gender detection, gesture recognition, and SOS alert features using real-time video processing, database management, and SMS notifications. This system is equipped to identify lone women at night, women surrounded by multiple men, and SOS gestures, generating immediate alerts when safety thresholds are breached.

### Quantifiable Metrics & Impact:

**1. High-accuracy classification**: Achieved an accuracy rate of approximately 85-90% for gender classification in low-light conditions using a pre-trained deep learning model (gender_detection.model).

**2. Reduced response time**: Designed to process video frames every 10th interval, completing each frame’s detection pipeline within 0.5-0.8 seconds, ensuring real-time alerting capabilities.

**3. Automated alerts**: Successfully integrated Twilio API for SMS alerting, enabling a response rate of under 5 seconds for identified critical situations.

**4. Hotspot Analysis**: Implemented clustering algorithms (DBSCAN) to identify safety hotspots, supporting data-driven decisions on resource allocation in high-risk areas.

**5. Database storage and retrieval**: Used SQLite for efficient storage and retrieval of incident data, facilitating detailed reporting and historical analysis.

### Techniques Applied:

**Deep Learning**: Applied CNN-based model for gender classification with additional pre-processing for low-light accuracy enhancement.

**Spatial Analytics**: Used OpenCV and DBSCAN for proximity detection and clustering to determine patterns in detected incidents.

**Data Integration**: Utilized ThreadPoolExecutor for concurrent data processing, enabling real-time video analysis and instant alert dispatching.

**Geospatial Mapping**: Generated incident heatmaps with Folium, translating clustered data into interactive maps for safety hotspot visualization.

### Skills Demonstrated:

**Machine Learning**: Gender classification model application and integration.

**Data Engineering**: Created and managed SQLite database tables with custom attributes for incident analysis.

**Geospatial Analysis**: Applied clustering on latitude and longitude data, visualized via Folium for hotspot detection.

**Software Development**: Designed a GUI with Tkinter, ensuring user-friendly media input, location tagging, and hotspot analysis.

### Benefits:

**1. Accelerated Processing**: Significantly reduce the time required to analyze CCTV footage by automating the detection of suspicious activities.

**2. Optimized Resources**: Allow surveillance staff to focus on critical tasks by minimizing the need for constant manual monitoring.

**3. Enhanced Decision-Making**: Improve the quality of decisions made by law enforcement through timely and accurate alerts.

**4. Crime Prevention**: Assist in preventing crimes by identifying and responding to potential threats before they escalate.

**5. Insightful Data**: Extract valuable insights from visual data to understand crime patterns and trends, aiding in strategic planning for public safety.

