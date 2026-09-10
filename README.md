# Ex.No.10
Content Creation (Reports, Articles, Case Studies, etc.) Using Prompt Patterns

## Date:10/09/2026
## Reg. No.212223050062

## Aim:
To demonstrate how various prompting techniques (query decomposition, decision-making, semantic filtering, etc.) can be employed to create content such as reports, articles, case studies, or creative works like comic books, using ChatGPT or similar models. The objective is to highlight how different prompt structures affect the content's quality, coherence, and structure.

Yes. I’ll use the attached **Ex.No.10 reference** as the format and methodology, but instead of copying the Agriculture/AgriTwin example, I’ll adapt the experiment to **your final-year EEE project: Cloud-Based Speed Control and Monitoring of an Induction Motor using PLC, VFD, HMI, Arduino and AWS**.

The reference experiment demonstrates seven prompt patterns—query decomposition, decision making, answer engineering, fact-check listing, tail generation, menu actions, and semantic filtering—and compares basic vs refined outputs. 

# Ex.No.10 – Content Creation Using Prompt Patterns

## Date:

10-09-2026

## Reg. No.:

212223240135

## Aim

To demonstrate how various prompting techniques such as **query decomposition, decision-making, answer engineering, fact-check listing, tail generation, menu actions, and semantic filtering** can be employed to create technical content such as reports, articles, and case studies using ChatGPT or similar AI models.

The objective is to study how different prompt structures improve the **quality, coherence, accuracy, organization, and readability** of AI-generated technical content.

---

# Engineering Domain Selected

**Electrical and Electronics Engineering – Industrial Automation**

# Selected Project

## Cloud-Based Speed Control and Monitoring of Induction Motor

The proposed system is designed to overcome the limitations of conventional manual and localized induction-motor speed control. The system integrates a **PLC, Variable Frequency Drive (VFD), HMI, Arduino, sensors, cloud platform (AWS), and an induction motor**.

The HMI/cloud interface provides control commands to the PLC. The PLC communicates with the VFD to control the motor speed, while sensors connected through Arduino collect parameters such as **speed, voltage, current, and power** and transmit the information for cloud-based monitoring.

### Basic System Flow

**HMI / AWS Cloud → PLC → VFD → Induction Motor**

**Motor Sensors → Arduino → AWS Cloud Dashboard**

---

# Problem Statement

Traditional induction-motor speed control is often performed locally using manual controls or conventional control panels. Such systems provide limited remote accessibility and do not offer centralized monitoring of important motor parameters.

The absence of cloud-based monitoring makes it difficult for operators to continuously observe parameters such as **motor speed, voltage, current, and power** from a remote location.

There is therefore a need for an integrated system that combines **industrial automation and cloud technology** to enable remote speed control, real-time parameter monitoring, and improved accessibility.

The experiment uses structured prompting techniques to create technical content related to this project in the form of a **case study and an educational article**.

---

# Selected Content Generation Scenarios

Two content types are selected:

1. **Case Study** – *Cloud-Based Speed Control and Monitoring of an Induction Motor: A Case Study*
2. **Article** – *How Cloud Technology is Transforming Induction Motor Monitoring and Control*

---

# Prompt Patterns Used and Their Application

| Prompt Pattern          | Application in This Experiment                                                                                                                         |
| ----------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Query Decomposition** | The project was divided into smaller topics such as problem, architecture, components, operation, monitoring, advantages, challenges and future scope. |
| **Decision Making**     | The AI was asked to choose between a technology-focused and application-focused approach for the case study.                                           |
| **Answer Engineering**  | Specific instructions were given regarding headings, technical depth, word count, tables and audience.                                                 |
| **Fact Check List**     | Technical claims about PLC, VFD, HMI, Arduino, AWS and motor parameters were listed before generating the content.                                     |
| **Tail Generation**     | Additional sections such as lessons learned, limitations and future scope were generated after the main content.                                       |
| **Menu Actions**        | The AI was given different possible article styles and asked to select the most appropriate one.                                                       |
| **Semantic Filter**     | The final article was rewritten using simple, technically accurate language suitable for undergraduate students.                                       |

This follows the same pattern used in the reference experiment, where the prompts were progressively refined rather than relying on one generic prompt. 

---

# Content 1: Case Study

## Title

**Cloud-Based Speed Control and Monitoring of an Induction Motor: A Case Study**

### Basic Prompt – First Draft

```text
Write a short case study about a system used for
controlling and monitoring the speed of an induction motor
using cloud technology.
```

### Sample Output – First Draft

> A cloud-based system can be used to control and monitor an induction motor. The system uses a controller and sensors to collect motor information. The data is sent to the cloud where it can be monitored remotely. The system helps improve motor control and makes monitoring easier.

### Observation

The output is **very generic**. It does not clearly explain the architecture, components, communication flow, measured parameters or role of each component.

---

# Refined Prompt

### Query Decomposition + Fact Check List

```text
Before writing, list the key factual claims that can be made
about the following project based only on the details provided.

Project:
Cloud-Based Speed Control and Monitoring of an Induction Motor.

System details:
- PLC is used as the main industrial controller.
- VFD is used to control the induction motor speed.
- HMI is used for local monitoring and control.
- Arduino collects motor parameters through sensors.
- AWS is used for cloud-based monitoring.
- Parameters include motor speed, voltage, current and power.
- HMI/Cloud sends control commands to the PLC.
- PLC communicates with the VFD.
- VFD controls the induction motor.

Then write a 300-word case study covering:
1. Background
2. System architecture
3. Working
4. Monitoring
5. Advantages
6. Challenges
```

### Sample Output – Refined Draft

**Fact Check List:**

1. PLC acts as the industrial controller.
2. VFD controls induction-motor speed.
3. HMI provides a local interface.
4. Arduino collects sensor information.
5. AWS provides cloud-based monitoring.
6. Speed, voltage, current and power are monitored.
7. The PLC controls the VFD.
8. The VFD controls the induction motor.

### Case Study

The proposed cloud-based induction-motor control system integrates industrial automation with cloud monitoring. The objective is to overcome the limitations of conventional local speed control by providing both controlled motor operation and remote monitoring.

The system consists of an **HMI, PLC, VFD, induction motor, Arduino, sensors and AWS cloud platform**. The HMI provides an operator interface through which speed commands can be given. These commands are processed by the PLC, which communicates with the VFD. The VFD controls the motor speed by controlling the frequency supplied to the induction motor.

At the same time, sensors collect important motor parameters. Arduino processes the sensor information and transfers the required data to the cloud platform. Parameters such as motor speed, voltage, current and power can therefore be monitored through a cloud dashboard.

The system provides a combination of **industrial control and remote monitoring**. It can improve accessibility because the operator does not need to depend entirely on a local control panel for observing motor conditions.

### Observation

The refined prompt produces a more **structured and project-specific answer**. The fact-check stage also reduces the possibility of the AI introducing components or specifications that are not part of the proposed system.

---

# Advanced / Final Prompt

### Decision Making + Answer Engineering + Tail Generation

```text
Two possible narrative approaches are available for this case study:

(a) Technology-first – explain PLC, VFD, HMI, Arduino and AWS
before discussing the application.

(b) Application-first – begin with the problem of local motor
control and monitoring, then explain how the proposed system
solves the problem.

Choose the approach that is most suitable for an undergraduate
EEE technical audience and briefly justify your choice.

Then write a 450-word case study using the following structure:

1. Background
2. Problem
3. Proposed System
4. System Architecture
5. Working Principle
6. Monitoring and Control
7. Advantages
8. Challenges
9. Lessons Learned
10. Future Scope

Use a professional but simple technical tone.
Include a table summarizing the role of each major component.
Do not invent numerical performance results.
```

---

# Sample Output – Final Version

### Chosen Approach

**Application-first approach** is selected because it introduces the practical problem before explaining the technical solution. This makes the case study easier to understand for an undergraduate EEE audience.

### 1. Background

Induction motors are widely used in industrial applications because of their simple construction, reliability and suitability for continuous operation. However, conventional motor-control systems may depend heavily on local control panels and manual monitoring.

### 2. Problem

The major limitation addressed by the proposed system is the lack of integrated remote monitoring and control. Operators may not have convenient access to motor parameters such as speed, voltage, current and power from a remote location.

### 3. Proposed System

The proposed system integrates **PLC, VFD, HMI, Arduino, sensors and AWS cloud services**. The PLC performs the industrial control operation, while the VFD controls the speed of the induction motor.

### 4. System Architecture

The primary control flow is:

**HMI / AWS → PLC → VFD → Induction Motor**

The monitoring flow is:

**Sensors → Arduino → AWS Cloud Dashboard**

### 5. Working Principle

The required speed command is provided through the HMI or cloud interface. The PLC processes the command and sends the corresponding control signal to the VFD. The VFD controls the operating speed of the induction motor.

Meanwhile, sensors measure the required motor parameters. Arduino collects and processes this information before transferring it to the cloud platform for monitoring.

### Component Roles

| Component           | Function                               |
| ------------------- | -------------------------------------- |
| **PLC**             | Main industrial controller             |
| **VFD**             | Controls induction-motor speed         |
| **HMI**             | Local monitoring and control interface |
| **Arduino**         | Collects and processes sensor data     |
| **Sensors**         | Measure motor parameters               |
| **AWS Cloud**       | Remote data monitoring and dashboard   |
| **Induction Motor** | Industrial load being controlled       |

### 6. Monitoring and Control

The system combines local industrial control with cloud-based monitoring. This provides a centralized method of observing motor operating parameters while maintaining PLC-based control.

### 7. Advantages

* Remote monitoring capability
* Controlled induction-motor speed
* Centralized data visualization
* Reduced dependence on local monitoring
* Integration of industrial automation with cloud technology
* Improved accessibility of motor operating information

### 8. Challenges

Possible challenges include reliable communication between different devices, sensor accuracy, network connectivity, PLC-VFD communication and secure cloud data transmission.

### 9. Lessons Learned

The case study demonstrates that combining industrial automation components with cloud technology can provide a more connected approach to motor control and monitoring. Proper division of responsibilities between the PLC, VFD, Arduino and cloud platform is important for reliable operation.

### 10. Future Scope

The system can be extended with historical data analysis, automated alerts, predictive maintenance, energy-consumption analysis and advanced dashboards.

### Observation

The advanced prompt produces a more **complete, logically organized and technically relevant case study**. Tail generation adds the **Lessons Learned** and **Future Scope** sections, providing greater depth than the basic prompt.

---

# Content 2: Educational Article

## Title

**How Cloud Technology is Transforming Induction Motor Monitoring and Control**

### Basic Prompt

```text
Write an article about cloud-based monitoring of induction motors.
```

### Sample Output

> Cloud technology allows motor parameters to be monitored remotely. Sensors collect motor information and send it to the cloud. Engineers can use this information to observe motor performance and identify problems.

### Observation

The article is understandable but **short, generic and technically shallow**.

---

## Refined Prompt

### Menu Actions + Semantic Filter

```text
Choose the most suitable approach for an undergraduate EEE audience
from the following:

1. Highly technical explanation
2. Simple educational article with technical examples
3. Industrial case-study style
4. Policy-oriented article

Explain your choice.

Then write a 400-word article about cloud-based induction motor
monitoring using PLC, VFD, HMI, Arduino and AWS.

Explain technical terms when they are first introduced.
Maintain technical accuracy.
Use simple language.
Discuss both benefits and limitations.
```

## Selected Approach

**Simple educational article with technical examples** is selected because it provides sufficient technical information without making the content difficult for undergraduate students to understand.

---

## Sample Output – Refined Article

## How Cloud Technology is Transforming Induction Motor Monitoring and Control

Induction motors are among the most widely used machines in industrial environments. They are used in pumps, conveyors, fans, compressors and many other applications. Traditionally, their speed and operating parameters are monitored using local control panels.

Cloud technology provides an opportunity to improve this method by allowing motor information to be monitored remotely.

In a cloud-based induction-motor system, sensors collect information about the motor. Important parameters may include **speed, voltage, current and power**. This information can be processed and transferred to a cloud platform where it can be displayed through a dashboard.

A **Programmable Logic Controller (PLC)** can act as the main industrial controller. A **Variable Frequency Drive (VFD)** can be connected between the PLC and induction motor to control motor speed. An **HMI (Human-Machine Interface)** provides a convenient local interface for the operator.

An Arduino-based sensing unit can be used to collect motor parameters from sensors. The collected information can then be transferred to an **AWS cloud platform** for remote monitoring.

The overall system can therefore be divided into two major paths:

**Control path:**
HMI / Cloud → PLC → VFD → Motor

**Monitoring path:**
Sensors → Arduino → Cloud Dashboard

One major advantage of this approach is accessibility. An operator can observe motor information without depending entirely on the physical location of the motor. Cloud-based historical data can also support analysis of motor operation.

However, cloud-based systems also have limitations. Network availability, communication reliability, sensor accuracy and cybersecurity must be considered while designing such systems.

Therefore, cloud technology does not replace industrial controllers such as PLCs and VFDs. Instead, it can complement them by adding remote monitoring and data-access capabilities.

---

## Final Version – Semantic Filter

### Semantic Filter Prompt

```text
Rewrite the article above using the following semantic filter:

- Make the explanation easier for undergraduate EEE students.
- Use a clear and engaging introduction.
- Avoid unnecessary technical jargon.
- Keep all technical information accurate.
- Explain PLC, VFD, HMI, Arduino and AWS in simple terms.
- Use a practical industrial example.
- Maintain a professional academic tone.
- End with a short conclusion about the future of cloud-based
  motor monitoring.
```

### Sample Output – Final Article

## Cloud-Based Monitoring: A Smarter Way to Manage Induction Motors

Imagine an industrial motor running continuously in a factory. Traditionally, an operator may need to be near the control panel to check its speed or electrical parameters. What if this information could instead be viewed from a cloud dashboard?

This is the idea behind **cloud-based induction-motor monitoring and control**.

The proposed system combines industrial automation with cloud technology. A **PLC (Programmable Logic Controller)** acts as the main controller. A **VFD (Variable Frequency Drive)** controls the speed of the induction motor. An **HMI** provides a local screen through which an operator can monitor and control the system.

At the same time, sensors collect information such as motor speed, voltage, current and power. An **Arduino** can collect the sensor data and transfer the information towards the cloud platform.

The cloud platform, such as **AWS**, provides a way to visualize the collected information remotely. Thus, the system has two important functions: **motor control and motor monitoring**.

The control process can be represented as:

**HMI / AWS → PLC → VFD → Induction Motor**

The monitoring process can be represented as:

**Sensors → Arduino → AWS Cloud Dashboard**

This approach can make motor monitoring more accessible and organized. Instead of depending completely on local observation, operators can access important information through a centralized cloud interface.

However, cloud integration also introduces challenges. Reliable communication, accurate sensing, network availability and cybersecurity must be considered during implementation.

Overall, cloud-based motor monitoring represents an important step towards connected industrial automation. By combining **PLC-based control, VFD-based speed regulation and cloud-based monitoring**, induction-motor systems can become more accessible, observable and suitable for modern industrial applications.

---

## AI Output Evaluation

| Content    | Version | Coherence | Creativity | Accuracy  | Tone & Style     | Overall    |
| ---------- | ------- | --------- | ---------- | --------- | ---------------- | ---------- |
| Case Study | Basic   | Fair      | Low        | Fair      | Generic          | **5.5/10** |
| Case Study | Refined | Good      | Moderate   | Good      | Neutral          | **7.5/10** |
| Case Study | Final   | Excellent | Good       | Excellent | Professional     | **9.2/10** |
| Article    | Basic   | Fair      | Low        | Good      | Generic          | **5.0/10** |
| Article    | Refined | Good      | Good       | Good      | Appropriate      | **7.8/10** |
| Article    | Final   | Excellent | High       | Good      | Clear & engaging | **9.0/10** |

---

## Summary

The experiment demonstrates that the quality of AI-generated technical content depends strongly on the structure of the prompt.

**Query Decomposition** helped divide the induction-motor project into smaller and manageable topics. **Fact Check Listing** helped keep the generated content aligned with the actual system components. **Decision Making** provided a clear narrative direction for the case study.

**Answer Engineering** improved the organization of the output by specifying headings, tables, audience and word limits. **Tail Generation** added useful sections such as lessons learned and future scope.

**Menu Actions** helped select the most suitable writing approach for the educational article, while **Semantic Filtering** improved readability and made the technical explanation more suitable for undergraduate students.

The reference experiment similarly concludes that structured prompting improves coherence, accuracy and engagement compared with basic prompts. 

---

## Ethical Considerations

1. **Technical accuracy:** AI-generated information about PLCs, VFDs, sensors and cloud communication must be verified before use.

2. **Avoiding fabricated results:** Numerical performance values, efficiency improvements or experimental results should not be invented if actual measurements are unavailable.

3. **AI-assisted authorship:** Content generated with AI assistance should be reviewed and appropriately disclosed when required.

4. **Industrial safety:** AI-generated instructions should not be treated as a substitute for proper electrical safety procedures or qualified engineering judgment.

5. **Cybersecurity:** Cloud-connected industrial systems should consider authentication, access control and secure communication.

6. **Balanced presentation:** The advantages of cloud-based monitoring should be presented along with limitations such as network dependency and communication reliability.

---

## Conclusion

The experiment successfully demonstrates the use of **query decomposition, decision making, answer engineering, fact-check listing, tail generation, menu actions and semantic filtering** for technical content creation.

By applying these prompt patterns to the **cloud-based speed control and monitoring of an induction motor**, the generated case study and article became more structured, technically relevant and easier to understand than the basic prompts.

The experiment shows that effective prompt engineering can help generate useful engineering reports, articles and case studies while **human verification remains essential for technical accuracy and safety**.

This follows the same overall structure and evaluation approach as your attached reference experiment. 
