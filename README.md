

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.

# OUTPUT

## Scenario 1: Creative Story  

- **Naïve Prompt Response:**  
“Once upon a time, there was a worker in a factory. He worked every day and wanted things to be easier. One day technology helped him, and the factory improved.”  
*Analysis:* The response is very short, generic, and lacks meaningful context. No details about IoT, emotions, or challenges are provided.  

- **Basic Prompt Response:**  
“A factory worker named Ravi often struggled with frequent machine breakdowns in his plant. The stress of unscheduled downtime meant he had to constantly adjust production schedules and deal with frustrated team members. One day, IoT sensors were introduced into his factory. At first, he felt skeptical, wondering if another 'new technology' would only cause more confusion. However, soon he received his first alert on his dashboard — it warned that a motor was overheating. Instead of waiting for the machine to fail, the maintenance team was notified immediately and resolved the issue within minutes. This proactive approach saved hours of production time. Over the weeks, Ravi noticed that automation eased his pressure and gave him more confidence in decision-making. He was no longer worried about surprise failures, and his own outlook toward technology improved. The transformation wasn’t just about machines; it was about Ravi finding trust in innovation.”  
*Analysis:* The refined prompt produced a well-structured short story with specific IoT application, emotions, and transformation. Clear improvement over naïve output.  

**Rubric Scoring:**  
- Naïve: Quality 2, Accuracy 2, Depth 2  
- Basic: Quality 5, Accuracy 5, Depth 5  

---

## Scenario 2: Factual Question  

- **Naïve Prompt Response:**  
“IoT stands for Internet of Things. It is used to connect devices so that they can exchange information and monitor performance. Many industries use IoT to improve their work.”  
*Analysis:* The answer is very broad, incomplete, and lacks real-life examples.  

- **Basic Prompt Response:**  
“IoT in manufacturing improves efficiency in multiple ways. First, IoT sensors continuously monitor machines, checking for overheating, imbalance, or vibration. By predicting a fault before it occurs, workers can replace or repair machines early — this is called predictive maintenance. Second, IoT reduces downtime since managers no longer wait for full breakdowns before acting. Two examples:  
1. **Automotive Industry:** IoT sensors track robotic arms and alert engineers before wear and tear reduces accuracy, ensuring precision in assembly lines.  
2. **Food Processing:** Smart IoT meters adjust temperature and humidity automatically, preventing spoilage and reducing energy waste.  

Thus, IoT helps factories save cost, minimize downtime, and improve quality.”  
*Analysis:* This version provides clarity, examples, and industry relevance, fulfilling the factual requirement.  

**Rubric Scoring:**  
- Naïve: Quality 3, Accuracy 2, Depth 2  
- Basic: Quality 5, Accuracy 5, Depth 4  

---

## Scenario 3: Summarizing Concept  

- **Naïve Prompt Response:**  
“IoT is used in manufacturing to connect machines, automate processes, and increase productivity. It has many benefits like efficiency, saving costs, and real-time monitoring.”  
*Analysis:* Broad summary, but too high-level and repetitive, no details on predictive maintenance or real-time monitoring as specified.  

- **Basic Prompt Response:**  
“IoT connects machines, sensors, and controllers in manufacturing to create smart factories. Its key role lies in predictive maintenance, where sensors detect unusual patterns like vibration or heat and prevent failures before they occur. IoT also enables real-time monitoring through centralized dashboards, allowing managers to track performance anytime. Together, these functions reduce downtime, optimize energy use, and boost output — all within a more reliable, data-driven ecosystem.”  
*Analysis:* Meets the requested summary length, includes specific focus areas (predictive maintenance and real-time monitoring), and avoids unnecessary generalization.  

**Rubric Scoring:**  
- Naïve: Quality 2, Accuracy 2, Depth 2  
- Basic: Quality 5, Accuracy 5, Depth 4  

---

## Scenario 4: Advice / Recommendation  

- **Naïve Prompt Response:**  
“To save energy in a factory, you can switch off machines after working hours, reduce the use of lights, and encourage workers to conserve power.”  
*Analysis:* The answer is simple but too generic. It lacks industrial context and IoT applications.  

- **Basic Prompt Response:**  
“As an energy consultant, I would advise three IoT-based energy-saving strategies for an electronics manufacturing factory:  
1. **Smart Energy Meters:** Install IoT-based smart meters that monitor energy consumption patterns in real-time and switch off idle machines automatically, reducing waste.  
2. **IoT-driven HVAC Systems:** Integrate IoT sensors into heating, ventilation, and cooling systems to adjust air handling units based on occupancy and machine heat output, reducing unnecessary load.  
3. **Predictive Energy Analytics:** Use IoT platforms to analyze peak energy data and reschedule heavy operations to off-peak times when electricity costs are lower. This leads to significant long-term savings.”  
*Analysis:* Provides detailed, practical, and IoT-specific recommendations relevant to the scenario.  

**Rubric Scoring:**  
- Naïve: Quality 3, Accuracy 2, Depth 2  
- Basic: Quality 5, Accuracy 5, Depth 5  

---

# Overall Observations  

1. **Quality:** Naïve prompts lead to shallow, vague, and generic responses, while basic prompts result in structured, creative, and context-rich answers.  
2. **Accuracy:** Refined prompts provide factual correctness with relevant examples, which naïve prompts fail to achieve consistently.  
3. **Depth:** More detailed analysis, industry-specific applications, and storytelling were present only when prompts were clearly framed.  

**Final Remark:** Clear, structured (basic) prompts consistently enhanced the quality, accuracy, and depth of ChatGPT’s responses across all test scenarios. Naïve prompts worked decently only for very simple creative outputs but failed to provide depth and real-world applicability in technical or recommendation tasks.  

# RESULT: The prompt for the above said problem executed successfully
