# Lawnmower Simulation Web App

## Problem
Given a lawn with some lownmowers on it, each lawnmower has a full battery. There are also some craters and charging pads on the lawn. The problem is how to make all the lawnmowers cut the lawn efficiently without crashing or running out of battery.

## Solution
Built a web app with Java for users to run lawnmower simulation and monitor its progress. Designed and implemented RESTful APIs with Java Spring Boot framework. Developed a search algorithm to improve lawn cutting efficiency by 80%. Designed an interactive and responsive UIs with React.js framework.

## Get Started
1. Type into the terminal: ./mvnw spring boot:r un
2. Open a browser and input the address: http://127.0.0.1:8080/
3. Input the file path of a test case and click submit
![Image of Main](./images/input_file.png)
4. A sample of the initial scenario according to the test case file:
![Image of Main](./images/lawnmower_map.png)
5. Click on the buttons to test the application
* Next button: it can trigger the mower's action. The mower can select their action smartly in order to cut the lawn efficiently without crashing or running out of battery.
* Stop button: it can be used to terminates the current simulation run.
* Fastforward button: it will allow the user to execute the current simulation run to completion.
![Image of Main](./images/fastforward.png)
![Image of Main](./images/terminal.png)

6. After finishing a test case, refresh the page to load other test cases

## Class Diagram
![Image of Main](./images/class_diagram.png)

## Deployment Diagram
![Image of Main](./images/deploy_diagram.png)

## Sequence Diagram
![Image of Main](./images/sequence_diagram.png)

## Use Case Diagram
![Image of Main](./images/use_case_diagram.png)
