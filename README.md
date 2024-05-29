# Creative coding major project

![Pacita Abad Wheels of fortune.jpg](assets/Pacita_Abad_Wheels_of_fortune.jpg)

Based on: Wheels of Fortune, Pacita Abad, 2000

### **User Input:** Incorporate keyboard inputs for animation.

I chose to change the artwork based on keyboard input to make it animated. When the user presses the left or right arrow keys on the keyboard, the inside of wealth wheels changes. 

### **←**

If you press the left arrow key, the star-like shape in wealth wheels is reduced, indicating a decrease in wealth. 

![Screenshot 2024-05-30 at 2.37.43 AM.png](assets/Screenshot_2024-05-30_at_2.37.43_AM.png)

### **→**

Vice versa, when you press the right arrow key, the star-like shape of the wealth wheel increases, symbolising that the wealth wheels have accumulated more wealth. 

![Screenshot 2024-05-30 at 2.34.53 AM.png](assets/5763b369-aa38-45d4-a766-97f46d20ac25.png)

### **%**

When the wealth is reduced to the minimum, the screen will randomly appear empty area, symbolising that the wealth is completely consumed by other wealth wheels.

![Untitled](assets/5a0c7bf3-f543-4d10-b572-329b33be6175.png)

### Inspiration - Kaleidoscope

Our artwork and animations are influenced by the concept of a kaleidoscope. Based on the original artwork created by Pacita, we restored the polka dots and star-shaped textures. Based on the Angle of rotation of the kaleidoscope, the user can see different polygons.

![istockphoto-1254967103-1024x1024.jpg](assets/istockphoto-1254967103-1024x1024.jpg)

Picture source: Vector floral pattern, naqiewei, iStock

### Conclusion

I created a keyPressed( ) function to change the vertexOffset variable, which will affect on the number of vertices of star-like shape. Through press left and right arrow key, the vertexOffset variable will change, to increase or decrease the vertices amount.