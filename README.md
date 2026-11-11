# EX. No.3.1. CREATE 3D MODEL FROM ORTHOGRAPHIC PROJECTION
## DATE:

## AIM:
To create a 3D model from given orthographic projection.

## REQUIREMENTS:
1. Autodesk fusion 360
2. Windows 10
3. 16 GB of RAM (integrated graphics recommend 1 GB or more)
4. 2.5 Mbps or faster download; 500 Kbps or faster upload 

## PROCEDURE:
1. Click Create Sketch and select the XY Plane (Front Plane).

<img width="446" height="583" alt="image" src="https://github.com/user-attachments/assets/f06d12f8-62fd-4fb8-90f5-1aa105ccf452" />

2. Draw a 2-Point Rectangle starting from the origin with a width of 36 mm and a height of 32 mm.

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/410af238-d5c5-4807-b89e-5e890df401e1" />

3. Draw a Center Diameter Circle centered exactly on the midpoint of the left vertical edge of the rectangle with a diameter of 32 mm (this creates the R16 curve).

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/effc13a9-5a3f-4b5f-9d4f-1784ed79ee66" />

4. Draw a concentric Center Diameter Circle at that same center point with a diameter of 16 mm (Ø16).

5. Use the Trim tool (T) to delete the vertical line segment separating the rectangle and the outer circle to combine them into one profile.

6. Click Finish Sketch in the top right.

<img width="201" height="170" alt="Screenshot 2026-10-11 174217" src="https://github.com/user-attachments/assets/7e61a87f-126e-4c7e-b67a-262833c087d5" />

7. Select Extrude (E), click your combined profile, extrude it to a width of 40 mm, and set the operation to New Body.

<img width="503" height="605" alt="Screenshot 2026-11-03 211338" src="https://github.com/user-attachments/assets/b5f4a456-b330-4a66-81b3-bbad7bf37430" />

8. Select Create Sketch and click directly on the top flat surface of your new body.

<img width="507" height="568" alt="Screenshot 2026-11-08 233147" src="https://github.com/user-attachments/assets/0545abe1-1ece-4b82-90f3-e50d8a250c78" />

9. Draw a 2-Point Rectangle starting from the left rounded end and stretching toward the back face.

10. Use the Sketch Dimension tool (D) to set the distance from both side edges of the part to the rectangle lines to 11 mm (leaving a central slot width of 18 mm).

11. Dimension the back line of this rectangle so it is exactly 11 mm away from the back face of the block (making the total slot length 52 mm - 11 mm = 41 mm).

12. Click Finish Sketch.

<img width="126" height="192" alt="Screenshot 2026-11-03 211255" src="https://github.com/user-attachments/assets/26eb2b78-a890-4bbc-909d-606bbb12800f" />

13. Select Extrude (E), click the slot profile you just drew, drag it all the way down through the part, set the operation to Cut, and click OK.

<img width="503" height="605" alt="Screenshot 2026-11-03 211338" src="https://github.com/user-attachments/assets/640d7187-c3f9-4e92-a977-4c76fbfaf5bd" />

14. Select Create Sketch and click on the flat, solid back face of the block.

15. Draw a Center Diameter Circle with a diameter of 18 mm (Ø18).Center the circle on the back face by dimensioning it 20 mm from either side edge and 16 mm from the top edge.

<img width="363" height="461" alt="image" src="https://github.com/user-attachments/assets/29969657-32bc-494e-82aa-7b799d89aeea" />

16. Click Finish Sketch.

17. Select Extrude (E), click the circle profile, extrude it outwards by 32 mm, set the operation to Join, and click OK.

<img width="503" height="605" alt="Screenshot 2026-11-03 211338" src="https://github.com/user-attachments/assets/ba2a2282-cda2-46d4-a113-217c505322fe" />

18.Finally, use Create Drawing to convert the completed 3D model into a 2D engineering drawing with the required front, top and isometric views.

<img width="284" height="453" alt="Screenshot 2026-10-11 172436" src="https://github.com/user-attachments/assets/bf9232aa-deaf-4857-8019-25eff9989835" />
<img width="415" height="462" alt="Screenshot 2026-10-11 172509" src="https://github.com/user-attachments/assets/d429747e-d9b2-4d81-a43c-bb31b6dbc333" />


## INPUT:

<img width="773" height="546" alt="Screenshot 2026-11-03 084130" src="https://github.com/user-attachments/assets/5b26ee60-ded0-467e-b7a0-ebabbceaab27" />

## OUTPUT:

<img width="1535" height="818" alt="Screenshot 2026-11-03 084108" src="https://github.com/user-attachments/assets/b211aa81-83e6-4de1-a495-7250924dde7c" />
<img width="773" height="546" alt="Screenshot 2026-11-03 084130" src="https://github.com/user-attachments/assets/5b26ee60-ded0-467e-b7a0-ebabbceaab27" />

## RESULT:
Thus, 3D model is created from orthographic projection.
