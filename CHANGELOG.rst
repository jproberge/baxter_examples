0.7.0 (2013-11-21)
---------------------------------
- Creation of baxter_examples repository from sdk-examples/examples.
- Adds joint torque springs examples.
- Adds gripper cuff control example.
- Adds gripper action client example.
- Package restructure in support of Catkin expected standards.
- Adds launch files for examples using action servers or the joystick.
- Adds gripper position playback to joint trajectory file playback example.
- Removes camera_control example, now located in baxter_tools repository.
- Removes getch usage as means of exiting example programs (latency).
- Fixes joint position file playback looping. Loops now start at correct playback start.
- Fixes head movement during exit of wobbler example.
- Adds timeouts to action client's wait_for calls making sure the action servers are running.
- Fixes D-Pad mapping for ps3 joysticks.
- Adds success verification for result of joint trajectory file playback.
