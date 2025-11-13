# Procedural Faces Lab

Original Face:
![image](https://github.com/user-attachments/assets/4707eb0a-b25e-4eda-84e3-3bb336981781)

## Surprise Paramete
In the faceSDF function, added a new float parameter called SURPRISE, a value between 0 and 1. Copying the way EYE_SEPARATION is used, modified the face such that the gingerbread face looks more or less surprised based on the value of SURPRISE. SURPRISE = 0 is not very surprised, and SUPRISE = 1.0 is very surprised.
Changing this parameter changes eye size (radius is inversely proportional to SURPRISE), eyebrow angle, and mouth size (both proportional to SURPRISE).

<img width="1815" height="671" alt="image" src="https://github.com/user-attachments/assets/88e7f5c2-76b2-4d7c-876d-58c418c08812" />
SURPRISE = 0.2

<img width="1819" height="665" alt="image" src="https://github.com/user-attachments/assets/715137a4-04b2-45b7-b9bc-3522a6d18e5a" />
SURPRISE = 0.5

<img width="1820" height="673" alt="image" src="https://github.com/user-attachments/assets/af834353-09f7-405d-9473-59078f8f5f84" />
SURPRISE = 1.0

## Task 2
Your own parameter! Create a new attribute of your choice that maps to a procedural face characteristic in the domain of [0,1]. It SHOULD NOT be a literal attribute, eg. eye-separation or mouth size, but instead a more qualitative, subjective quality that you tie to specific geometic parameters using your design sense. Have fun!

## Extra Credit
In the faceSDF function, create a new float parameter called SADNESS. Follow the same guidelines as outlined in Task 1.
 
## Submission
- Create a pull request to this repository
- In the README, include the names of both your team members
- In the README, create a link to your shader toy solutions
- Make sure your shadertoy is set to UNLISTED or PUBLIC (so we can see them!)

