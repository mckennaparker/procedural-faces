# Procedural Faces Lab

Shadertoy Link: https://www.shadertoy.com/view/wXSfD3

Original Face:
![image](https://github.com/user-attachments/assets/4707eb0a-b25e-4eda-84e3-3bb336981781)

## Surprise Parameter
In the faceSDF function, added a new float parameter called SURPRISE, a value between 0 and 1. Copying the way EYE_SEPARATION is used, modified the face such that the gingerbread face looks more or less surprised based on the value of SURPRISE. SURPRISE = 0 is not very surprised, and SUPRISE = 1.0 is very surprised.
Changing this parameter changes eye size (radius is inversely proportional to SURPRISE), eyebrow angle, and mouth size (both proportional to SURPRISE).

<img width="795" height="448" alt="image" src="https://github.com/user-attachments/assets/b3ca6863-b718-4b8f-a20c-b525ecf2776e" />
<br />
SURPRISE = 0.2
<br />

<img width="796" height="450" alt="image" src="https://github.com/user-attachments/assets/8c4d0e07-6234-445a-850e-8af5c6ee7ad1" />
<br />
SURPRISE = 0.5
<br />

<img width="796" height="449" alt="image" src="https://github.com/user-attachments/assets/3b011ad8-b5d5-4731-80f8-6a2975e4d708" />
<br />
SURPRISE = 1.0
<br />

## Anger Parameter
In the faceSDF function, added a new float parameter called ANGER, a value between 0 and 1. Copying the way EYE_SEPERATION and SURPRISE are used, modified the face such that the gingerbread face looks more or less angry based on the value of ANGER. ANGER = 0 is not very angry, and ANGRY = 1.0 is very angry.
Changing this parameter changes eyebrow overlap with eye, eyebrow angle, and mouth size.

<img width="798" height="451" alt="image" src="https://github.com/user-attachments/assets/db33baf6-3dd1-4086-9a41-30143dbd6f6b" />
<br />
ANGRY = 0.3
<br />

<img width="793" height="447" alt="image" src="https://github.com/user-attachments/assets/58af3d82-9286-40ae-b011-d243bb8b6794" />
<br />
ANGRY = 0.6
<br />

<img width="797" height="446" alt="image" src="https://github.com/user-attachments/assets/82cc9c4e-700c-4f8e-bb5f-f63429c52fa4" />
<br />
ANGRY = 0.9
<br />

## Extra Credit
In the faceSDF function, create a new float parameter called SADNESS. Follow the same guidelines as outlined in Task 1.
