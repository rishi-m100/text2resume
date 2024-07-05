# text2resume Module

A Python module to generate PDFs from YAML data.

## Installation

First, ensure you have `pdflatex` installed on your system. You can install it via a LaTeX distribution such as TeX Live or MiKTeX.

Then, install the module using pip:

```bash
pip install text2resume
```

```bash
generate-resume path/to/yaml/file output_file_name.tex
```

# YAML File Format

Your YAML File should be in this format:

```yaml
information:
  name: "Emma Johnson"
  location: "Seattle, WA"
  phone: "(206)-555-1234"
  email: "emma.johnson@example.com"
  linkedin: "linkedin.com/in/emmajohnson"
  github: "github.com/emmajohnson"

education:
  school: "University of Washington"
  gpa: 3.8
  graduation: "June 2025"
  degree: "Bachelor of Science"
  major: "Electrical Engineering"
  location: "Seattle, WA"
  relevant-coursework: "Digital Signal Processing, Embedded Systems, Control Systems, Machine Learning"
  involvement: "IEEE President, Robotics Club Member, Women in Engineering"

technical-skills:
  languages: "C++, Python, MATLAB, Verilog, Assembly"
  developer-tools: "Git, Visual Studio, Quartus, Xilinx Vivado, MATLAB Simulink"
  technologies: "TensorFlow, Arduino, Raspberry Pi, FPGA Design, PCB Design"
  additional-skills: "Agile Methodologies, Linux, SolidWorks, AutoCAD, Microsoft Office"

experience:
  - company: "TechCorp"
    title: "Software Engineering Intern"
    location: "San Francisco, CA"
    dates: "May 2024 -- August 2024"
    description:
      - "Developed new features for a cloud-based CRM system using Python and Django framework."
      - "Implemented RESTful APIs for data retrieval and integration with third-party services."
  - company: "InnovateTech"
    title: "Embedded Systems Engineer Intern"
    location: "Austin, TX"
    dates: "June 2023 -- August 2023"
    description:
      - "Designed and tested firmware for IoT devices using C and embedded Linux."
      - "Collaborated with hardware engineers to optimize performance and power consumption."
  - company: "Research Institute of Technology"
    title: "Research Assistant"
    location: "Seattle, WA"
    dates: "September 2022 -- May 2023"
    description:
      - "Conducted experiments to analyze power distribution networks for next-gen processors."
      - "Used MATLAB to simulate and optimize circuits for efficiency and reliability."

research:
  - group: "UW Robotics Lab"
    dates: "January 2024 -- Present"
    description:
      - "Developing algorithms for autonomous navigation of UAVs using computer vision and machine learning."
      - "Testing and refining models for obstacle detection and path planning in dynamic environments."

projects:
  - title: "Smart Home Automation System"
    link: "https://github.com/emmajohnson/smart-home-automation"
    date: "December 2024"
    tech: "Python, Raspberry Pi, MQTT, Home Assistant, OpenCV"
    description:
      - "Designed a scalable IoT system to control home appliances based on user preferences and environmental conditions."
      - "Implemented computer vision for facial recognition to adjust settings personalized for each household member."
  - title: "Real-time ECG Monitoring System"
    link: "https://github.com/emmajohnson/ecg-monitor"
    date: "May 2023"
    tech: "Verilog, FPGA, MATLAB, Bluetooth Low Energy (BLE)"
    description:
      - "Developed a low-power ECG monitoring device for continuous real-time monitoring and analysis."
      - "Integrated with a smartphone app to alert users and healthcare providers of abnormal heart rhythms."
```
