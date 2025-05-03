Find the trajectory of a point M belonging to a circle of radius r, which rolls without sliding along a fixed circle of radius R, and the point M is located at a distance h = 2R from the center of the movable circle. Use the coordinate method to determine the trajectory. The crank OO1 rotates uniformly with a constant angular velocity w_0.Prepare a graphical program representing the movement of point M over time along the trajectory, as well as the dynamics of the entire mechanism

<img width="282" alt="image" src="https://github.com/user-attachments/assets/cf2c52a8-0e11-4d61-a3aa-8a792cc493d8" />

The points M, O1 and the rest are considered as spheres of radius 0.04;
The elements of the crank mechanism will be created as cylinders with a radius of 0.05;

Let's clarify the attributes of the cylinder() instance. pos() is the position of the lower base of the cylinder, axis() is the height of the cylinder, which has a direction.

<img width="161" alt="image" src="https://github.com/user-attachments/assets/5d59a5ff-8681-46de-b4a6-b7c1917c0832" />
Let's write down expressions for the velocity of motion of point O1 relative to the coordinate system with the origin at point O, as well as with the origin at the instantaneous center of velocities P, which is the point of contact of the movable and fixed circles.:
<img width="167" alt="image" src="https://github.com/user-attachments/assets/99fdeb34-f74a-40d1-bfe0-e33c7536c177" />
w_1 is the rotation speed of the movable circle, and w_0 is the angular velocity of the crank.Let's express w_1 in terms of w_0:Let's express w_1 in terms of w_0:
