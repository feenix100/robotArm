# Trim Bot Project

<details>

<summary> ***30,000 foot goal.*** Create a pair of electric robot arms that can trim 1 pound of dried cannabis buds in 8 hours.  </summary>

- Create a pair of electric robotic arms that can **automatically** trim dried cannabis flowers using a standard pair of trimming scissors. **The target goal is to trim 1 pound of cannabis in 8 hours time.** The arm uses servo motors to rotate the joints. For vision- open cv or other methods of object detection using one or more cameras. The arm will be able to grasp (using a two fingered-claw) a branch or bud from a bin full of branches, then hold the branch while a second arm with standard trimming scissors attached (to the claw) will trim the buds. The finished buds will be dropped into a bucket when complete. The average human trimmer would trim for about 7.2 hours in a standard work day, 1 pound of trimmed cannabis would be the expected minimum after 8 hours. 2 pounds would be a high amount for a human trimmer in a standard 8 hour work day.
- I have a real world application for this robot. I can put it to work immediately after it is finished. I work in the cannabis industry, so I hope to have this finished before I lose my position here and have to move to a different industry. I have advanced as far as I can in the company I work for, so this is a way to advance my career without having to completely switch industries and have to start from the bottom.

<summary> ****The pair of robot arms should do the following:**** </summary>

- trim = remove all fan leaves using standard trimming [scissors](http://www.chikamasa.com/products/index.cgi?key=27) (see workspaceExamples directory) I will be using CHIKAMASA B-500SF shears(I refer to them as scissors)

- Able to grasp a branch or bud with pincer-type end effector(2 finger claw)

- Able to open and close a pair of standard trimming scissors, which will be securely attached to end effector(claw). Scissors will be detachable from claw for cleaning.

- Able to identify a single branch or bud in a bin full of similar items.

- Will need camera for object detection. 
    - using open-cv or other methods. python or c++ maybe used.
    - Yolo v5 is compatible with jetson nano.
- Able to work together as a pair of arms, one will hold the scissors(scissor arm), the other will hold a branch/bud(branch arm).

- Branch arm able to identify fan leaves on bud and coordinate with scissor arm to remove all fan leaves.

- Branch arm able to rotate the bud/branch while scissor arm opens and closes scissors to complete trim.

</details>


- I am using a RaspberryPi 4 attached to a robot arm purchased from [amazon.com](https://www.amazon.com/Yahboom-Controlled-Programmable-Robotics-Identity/dp/B09T96PS3S/ref=asc_df_B09T96PS3S/?tag=hyprod-20&linkCode=df0&hvadid=647177154660&hvpos=&hvnetw=g&hvrand=9522090457653424090&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9029977&hvtargid=pla-1948863623457&psc=1&gclid=CjwKCAjw-vmkBhBMEiwAlrMeF-Z9-dOB8Xg7fpWzmVdcTm2_Ga3R2E9iPS-FwKbWelSRKJymOayAkxoCRlYQAvD_BwE)
- For a complete 3d printable robot arm, [Moveo BCN3D](https://github.com/BCN3D/BCN3D-Moveo) I may adapt the design for my uses
- Also check out this repository [Robot Arm 3d printable](https://github.com/AngelLM/Thor/tree/developer)
- I would use a 3d printing service such as www.xometry.com to print parts.
<details>

</details>

  
- Here is a link  to a [YouTube playlist- Build a Robot Arm](https://www.youtube.com/playlist?list=PLcbaYozXcpF65uUvdCmepFYYjx4FZ4Iwq), these videos have info that may assist in completing the goal.
I will store the info I find useful in this repository. Some code maybe generated by chat-gpt or similar methods.

### See [workspaceExamples](https://github.com/potSm0ker/robotArm/tree/main/workspaceExamples) folder for visual definition of bud, branch, fan leaf and other items.




