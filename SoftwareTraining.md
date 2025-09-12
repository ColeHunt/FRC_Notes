# Software Training
The students will work through a step by step process progressively getting more involved in the robot program. Lessons should start with minimum code writing and end with a student making a new subsystem from scratch and implementing autos.

## Learning Structure

## Lesson Overviews

### Making a Motor Move
In this lesson the student should be able to make a motor spins with based off the value of a joystick. Most of the code will be provided and setup in a sample project.

#### Learning Objectives
- Basic code syntax
- Introduction to IO container

#### Template
- Drivetrain subsystem structure
- IO Container for real robot control

### Driving the Robot
In this lesson the students should be able to drive the robot (ideally in arcade) based off the value from joysticks. Most of the code will be provided and setup in a sample project.

#### Learning Objectives
- Basic code syntax
- Continued interaction with the IO container
- Multi motor control
- Introduction to math operations

#### Template
- Drivetrain subsystem structure
- IO Container for real robot control
- IO Container for simulated robot control

### Determining the Position of the Robot
In this lesson the students should be get their first interaction with the internals of the IO container. They will need to read the values of the motor encoders and implement a pose estimator for robot position.

#### Learning Objectives
- Working with the internals of the IO container
- Integrating with sensor (IMU and Encoders)

#### Template
- Drivetrain subsystem structure
- IO Container for real robot control
- IO Container for simulated robot control

### Adding a State Machine to the Subsystem
In this lesson the students should add a basic state machine to the Drivetrain subsystem. It should allow for external