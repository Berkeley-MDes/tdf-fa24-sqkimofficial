# Hello!
I'm Sun-Q Kim, a designer expanding across emerging technology fields.
Branching from my background in Architecture, I plan on exploring other mediums of design that impact our future lives.

--------------------------------------------------------------------------------------------------------------------------------------------------------

# TDF Weekly Progress
## Week 7 : Starting to work on Assignment2

Our team will be developing a safety device based on Berkeley WarnMe Messages.
As Berkeley students, we constantly receive messages from the Berkeley Warn Me system of potential hazards and crimes that occur around the campus area. Most people shrug off the information believing it is irrelevant to them or disregarding its seriousness. The exact location of the event is often forgotten or ignored, which could render the WarnMe system useless. Our objective is to design a physical comprehensive system that alerts the user when they are near or in contact with a ‘Warn Me’ Zone. Zones are detected using a loudness sensor, gas sensor, and button which give coordinates of a potential zone. LEDs and Vibrating Motors let the user know of if they are close proximity to the location.
[Team Proposal_ Safe-2 (1).pdf](https://github.com/user-attachments/files/17424753/Team.Proposal_.Safe-2.1.pdf)


We met up and tried out connecting the vibrating motor, button, gas sensor, and loudness sensor.
https://github.com/user-attachments/assets/45d08094-800d-4d1d-8cf1-f884cc514f46
https://github.com/user-attachments/assets/12cccbc3-46ea-430d-ac4f-c5540c733f19
https://github.com/user-attachments/assets/23d7b32b-2710-4131-a90b-4139a491d795
(credit : Mia Wu)

However we weren't able to get the loudnesss sensor to differentiate gun shot sounds from just loud noises.
Also connecting the web api for location tracking and cross-referencing was also rather difficult.
Lastly because we did not have any gas to test with, we couldn't test if the gas sensor was working or not.
We told Jeff about these difficulties during class last monday and are waiting for solutions that he will be providing soon to develop our proejct further.





## Week 6 : Soldering the Stemma QT & flashing on Visual Studio
<img width="300" alt="04" src="https://github.com/user-attachments/assets/42ae7ea2-5bd1-44b1-bd9e-e344631f7ee3">
<img width="300" alt="04" src="https://github.com/user-attachments/assets/3a6491f8-cc42-4cc9-aebf-50e055f09ff3">

I've successfully soldered the Stemma QT board to my photon 2.

![03](https://github.com/user-attachments/assets/c28ec182-b52e-4832-8ee7-2c852b49910a)
Also my second photon has arrived! Can't wait to use this with the soldered photon.

I'm still trying to understand what we exactly have to do on visual studio this week, but I'm glad it's finally working(too soon to say?) again.
<img width="300" alt="04" src="https://github.com/user-attachments/assets/19eb6f13-46e7-4a05-827e-2505c7b66994">
![Screenshot 2024-10-06 164336](https://github.com/user-attachments/assets/0359ad77-eca0-492b-af35-d61ad43859ed)
![Screenshot 2024-10-06 164351](https://github.com/user-attachments/assets/89342f77-8d43-41bf-b3cf-b11ee66a3b42)

For some reason I get a bunch of errors when I try flashing the accel_gyro code.
BUT
Thanks to TJ I managed to get it to work and now it's flashing like crazy
https://github.com/user-attachments/assets/3c9903cc-2d37-4240-a0b8-a68c754eae36


Reflections)
I'm glad that Visual Studio finally works (with a few errors) to flash my device.
However I'm not totally sure if it's okay to just copy and paste the code and flash it to my device without understanding the basics of C++.
I'm also not sure if I know what Stemma QT exactly does and what it can do  if applied to other things.
It feels like I'm cheating my way through to forcibly make something without learning anything.

Speculations)
My team for the final assignment for Microcontrollers is with Mia and Shryas.
We plan on developing a device that tracks the users location and warn them if they enter zones alerted by BerkeleyWarnMe.
We hope to apply Stemma QT with other GPS tracking devices from Adafruit.
It feels very risky to plan something with such minimal understanding of the technicals but I really hope it turns out well and functions its purpose.
![image](https://github.com/user-attachments/assets/56faac41-7c93-4bbf-8bf7-0a7af804da14)






## Week 6 : 241003 Particle Web IDE part 2

This week I tried following the tutorial files given to us.
I tried the button_led_pulse / fsr_to_ledcolor / acccel_to_servo files.


[Button LED Press]
![01](https://github.com/user-attachments/assets/f63a78ba-89e1-4b5f-a252-a2f166c2da7c)
https://github.com/user-attachments/assets/0c55520f-a7d5-4a77-91e7-c080f6f4ad65

[FSR to LED Color]
![02](https://github.com/user-attachments/assets/fbffb859-f0c6-45b4-b908-9bf9b788a105)
https://github.com/user-attachments/assets/53440f7d-8198-4634-abeb-c3717275e37a

[Basic Button]
![basic button](https://github.com/user-attachments/assets/4b1bd166-1d81-4aeb-856d-3800648b5088)
for some reason when I tried to view the logs in the web ide serial monitor, everytime I flashed the code it would show that my device was disconnected and connected again, now allowing the monitor to display the code status.

Reflections)
Understanding how the breadboard connections work and how to follow the diagrams to make sure the wires are correctly connected was one of the main takeaways.
Also looking through the code to see which wire is connected to which part of the photon made it more easier to understand the system.
I ran into a lot of hiccups including the photon not being able to connect to the wifi again which required Fareha's help to sort out.
I still can't run Visual studio code for Particle which is also very frustrating

Speculations)
I'm hoping to be able to connect other sensors like leapfrog (I saw there was an ultrasonic sensor that I don't know the name of in the toolkit) to detect proximity interactions soon to try out more interesting projects. This could allow physical interactions with the digital system much like the FSR to LED color code componenet.
Also the second photon2 that I ordered using the business particle account arrived so I'm hoping to connect multiple photons to try out more advanced systems.




## Week 5 : 240929 Particle Web IDE

During last class I had a difficult time following the instructions because for some reason everytime I tried to create a new project in VisualStudio,
it would appear with 2 problems automatically. Nobody could seem to come up with a solution so I could barely concentrate the class contents.
![image (3)](https://github.com/user-attachments/assets/926e11bd-a3e9-4c43-a4c2-5c9650baf4cf)

Luckily, Baurzhan and Fareha was able to find an alternative web platform to use instead of VisualStudio.
I was able to initiate the given example scripts on web IDE and verify/flash them onto my photon.
Below were some of the scripts I was able to successfully flash.
![altering periodicity1](https://github.com/user-attachments/assets/116acb51-6f73-4694-a89a-5d483db45a2e)
![publish](https://github.com/user-attachments/assets/08f1a374-42f7-4843-ad3d-e9ef313ead3d)
![result publish](https://github.com/user-attachments/assets/94e8745f-8e2b-42ef-a083-6a4f9531c313)
![3](https://github.com/user-attachments/assets/b43b5ea8-2fcc-4ed2-9b3e-71a90595a14e)
![Results](https://github.com/user-attachments/assets/8a3d8c5b-cbdd-4d73-83fb-649f511e37cb)

Connecting my photon to my laptop wasn't too much of an issue either.
![microcontroller](https://github.com/user-attachments/assets/8ba99322-fba9-4037-864d-add3673a84e7)
https://github.com/user-attachments/assets/99a1f0bf-5764-4a86-a453-0d3ae0eb44ee

I hope I'll be able to find ways to connect web IDE to other software programs maybe using OSC signals.




## Week 5 : 240926 Project2 Begins

We'll be using microcontrollers for this project.
I haven't exactly used photon hardware before but I have used arduino or raspberrypi briefly in the past on my own.

We've been asked to outline a diagram that shows how things around us are connected to each other.
The info below must be included in the diagram.
- Connections: How different elements are connected.
- Information Flow: What kinds of information or data are shared.
- Feedback Loops: Where feedback happens, showing how actions or data influence future behaviors.

![Key DailyLife Eco-Systems](https://github.com/user-attachments/assets/4ffe7367-0c1f-4aae-b584-e766fa507199)

Reflections
I had a hard time drawing more of an intuitive diagram which shows how all the devices are connected to each other.
I tried drawing several nodes of devices and connect them in a web but it turned out too messy and repetitive.
All devices are connected to each other and it is very likely that they will share the same info to each other both ways rather than different things.
Also I wasn't entirely sure what type of things would be deemed as feedback in these settings.
Would it be any sort of signal or communication that is given to the subject?
Would it have to be a signal or communication that is relevant to a signal or communication sent out?

https://youtu.be/l3iCWKXP0Cg
The thoughts of an interconnected system took me back to the AI+Healthcare Hackathon Shryas, Josh, and I (thanks Baurzhan for the footage!)

We developed and designed a system where an AI agent could reply to emergency callers in distress who are looking for ambulances.
AI based agents can keep the necessary questions concise and brief to understand if the situation requires urgent attention or can be less prioritized preventing ambulance dispatch delays.
Introducing AI into the whole connected systems where information flows in so many ways can automate certain processes preventing signal congestions.

Speculations
Not exactly sure where we're going with this but I hope the photon work won't be too advanced since it's completely new to me.
I have hopes to apply my knowledge in motion sensors like Mediapipe or KINECT devices as well as interactive software such as Touchdesigner.
I had ideas of connecting realtime data apis to touchdesigner and mico controllers but I'll have to understand how to use photon controllers first.






## Week 4 : 240919 First Assignment Submitted! [Creating a 3D Printed Wrist Cast]

1st Assignment Video Link : https://www.youtube.com/watch?v=p_8ykj9fLzU
I chose to fabricate a Wrist Cast that can be used for Chronic Wrist Pain Patients.
The concept seemed interesting as it could open possiblities to use 3D scanning and 3D Printing in the process.

![System](https://github.com/user-attachments/assets/acd09a52-703c-43da-9877-fd7987dcd7de)
This was the process flow system I came up with.

https://github.com/user-attachments/assets/d20f3b1d-0b3b-4044-9f1e-7869e0e74d21
https://github.com/user-attachments/assets/0a593241-d12b-4fe4-970b-ce680d6ec6d7
https://github.com/user-attachments/assets/461142b3-9a4f-4e75-ab92-c257b7865d02
https://github.com/user-attachments/assets/adb15605-0563-4886-87cd-c1317cdbac30
These were attempts of scanning my own Arm to import the 3D Model into grasshopper.

https://github.com/user-attachments/assets/c625cadc-20c7-46ae-b48e-f2eed33acb03
The preparation prior to 3D Printing.

https://github.com/user-attachments/assets/b8225eb4-e0f4-42b2-a2c0-f56dfc3d0001
https://github.com/user-attachments/assets/516c2dd4-8aa7-4c99-b4bf-88ddd798aefe
Some footage of the 3D Printing Process

https://github.com/user-attachments/assets/07fd3fd4-a308-45b2-9715-45258a62691c
https://github.com/user-attachments/assets/18c57869-52ac-41ad-8048-fbd9349f98f0
Some footage of detaching the supports from the 3D Printed Model.

![14](https://github.com/user-attachments/assets/052c30a5-7166-436f-94db-354fea363cca)
![15](https://github.com/user-attachments/assets/d3c7f685-2217-4a90-9425-bcdfd2c36d22)
Before / After the detachment process.


![nibbs_nibbsss_a_group_of_people_using_individually_customized_3_e16993e6-766d-40f8-85ed-a829d52ea58f](https://github.com/user-attachments/assets/0bdad564-4ab4-4576-8720-d670cd3ca1f5)
![nibbs_nibbsss_a_long_shot_of_a_fully_automated_manufacturing_sy_d3efaca2-e191-4766-ab1c-59e6a45cb71b](https://github.com/user-attachments/assets/495d6f11-0232-4461-9f43-f96cf9bd5e30)
Reference images I generated through midjourney to illustrate my speculations of systemic & computational design.

I didn't take into consideration the part where the hand wouldn't be able to fit the wrist opening which leaves room for improvement.
I believe it would be better to 3D cut the part into 2 pieces so that it can be combined after being 3d printed.

More in-depth speculations, reflections, and details of the process are included in the youtube video above.




## Week 3 part2 : 240912 Trying out my own Grasshopper forms

I was tasked to experiment and come up with my own grasshopper algorithm to make forms.
I felt building my own algorithm from scratch was a bit overwhelming from now so I just brought up an old algorithm I came up with a few years ago.
It's basically a set of cubes that were interconnected to each other.
![01](https://github.com/user-attachments/assets/11db06e3-e414-483c-a846-068f5b498acf)

It's done using List, Closest Point, and Extend Curve components 
![03](https://github.com/user-attachments/assets/61a467f5-3015-4682-b5c2-1f9660bd3b73)
![02](https://github.com/user-attachments/assets/28b52812-eb0c-443d-8508-d1b2aeee0ba9)

Baking the form and using as a module to combine with each other can look a little like this :
![04](https://github.com/user-attachments/assets/2f0e8972-bc5d-411a-8c99-f0056df07e4e)


Next week I'm hoping to 3D print out what I've come up with.




## Week 3 part1 : 240908 Breaking down the Grasshopper Algorithm

Well, this class we were ambushed by a Grasshopper Algorithm used to create a Cellphone Stand.

The algorithm could be broken down into 4 main parts.
I borrowed professor Dubberly's method of concept mapping here. (Thank you!)
1) Preparing the Foundations of the Cellphone Stand
2) Designing the Aesthetics of the Cellphone Stand (Through subtracting shapes)
3) Importing & Adjusting the Cellphone Model
4) Evaluating the Product's Feasibility
  
![240909 TDF Cellphone Stand_page-0001](https://github.com/user-attachments/assets/b4ede3fe-9831-4bdf-9503-56c8693f5211)


I played around with the parameters of the sphere to change the aesthetics of the Cellphone Stand.
It didn't seem to change the feasibility of the product.

<img width="1000" alt="01" src="https://github.com/user-attachments/assets/54f1eea1-1b55-4d29-bf17-476b674ccd4f">
<img width="1000" alt="02" src="https://github.com/user-attachments/assets/4ac20fa5-2898-4196-9071-86e94cf91401">


However, playing with the parameters of the subtracted cylinder seemed to cause problems with the feasibility evaluations.
It was interesting to see how it evaluator component produced texts that described the reason of the faulty feasibility as well as changing the simulated color.

<img width="1000" alt="04" src="https://github.com/user-attachments/assets/c7895778-e852-4626-b323-a8539c7d6d60">
<img width="1000" alt="05" src="https://github.com/user-attachments/assets/1d8dd9fa-2f33-4aaa-88c6-7bbb8b8352fc">


I made a set of my own components to replace the original Sphere form to come up with different aesthetics for the Cellphone stand.
I made sure to adjust the number slider parameters to make the product pass the feasibility evaluation test.

<img width="1000" alt="06" src="https://github.com/user-attachments/assets/4c36e2d5-1cf9-418d-a18f-ef597769fcd6">
<img width="1131" alt="07" src="https://github.com/user-attachments/assets/3fe74164-d13b-4665-95ec-7481246f1cd8">










## Week 2 : 240905 First Fabrication

We were tasked to fabricate any object whether by 3D printing or laser cutting.
Being an Architecture major student, I'm familiar with either method, though I've never actually done the actual hands-on work myself.
I thought I'd choose laser cutting for now since I expected that I'll be using it more than the 3d Printer for upcoming projects.

Upon wondering what to make as well as trying not to over-engineer something as my first project, I realized I haven't got myself a Berkeley MDes souvenir yet!
I decided to create a Key-chain / Desk Toy that reminds me that I've finally enrolled in Berkeley MDes.

![Outcome](https://github.com/user-attachments/assets/075b4721-c860-4dd7-bb53-baf5218539b5)

https://github.com/user-attachments/assets/1e1bf2cc-3e7c-4f93-9aaf-eb2ec046bf14

The thickness of the plywood was 0.25 inches but when I set the lasercutter settings to 0.25, the laser didn't manage to completely cut through the wood at certain spots of the wood. After adjusting the thickness to 0.275 inches it managed to cut the whole thing seamlessly.

This was the first time I've prepared the material, set it in the laser cutter, sent the work to the laser cutting software, make sure the settings were correct etc. It did take some Trial & Error and did take time to get my way around the Laser Cutter but I thought this opportunity was a good chance to get familiar with the machine for future purposes.
I'll be trying out the 3D Printer next!



---

## Quick Links, compiled here for your convenience: ##

- [TDF Wiki](https://github.com/Berkeley-MDes/24f-desinv-202/wiki) - the ultimate source for truth and information about the course and assignments
- [Google Drive Folder](https://drive.google.com/drive/u/0/folders/1DJ1b6sSDwHXX6NRcQYt10ivyQSgU0ND6) - slides and other resources
- [bCourses](https://bcourses.berkeley.edu/courses/1537533) - where the grading happens
