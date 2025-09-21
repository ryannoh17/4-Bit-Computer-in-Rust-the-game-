# 4-Bit-Computer-in-Rust-the-game

This is a 4 bit "computer" I made in a video game called Rust. Rust is originally an open world multiplayer survival game but separate servers exist for people to play in a "creative mode".
The computer includes a 4 bit ALU, a clock speed of 0.2 hertz (runs 1 line every 5 seconds), 4 lines of programmable read-only memory, and an instruction set of add, subtract, read, and write.
I first started creating this by using a website which allowed me to design and quickly edit the computer.
<img width="962" height="673" alt="image" src="https://github.com/user-attachments/assets/91e26ce4-f840-445f-85a3-6c8a9f2c3ae0" />

After a decent design was made I started creating it in game. Because of how many components there were and all the wiring I had to do I only initially added 1 byte of RAM as that was enough to test along with the a/b registers.
The image below shows the version with only 1 byte of RAM. The computer has the ability to have up to 4 bytes of ram. 
With only 1 byte of RAM the most interesting thing I could make it do was increment by an set number. 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/be49f71b-dc49-4af5-88ad-8e15d9fddc16" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/22feb120-f712-4684-8719-c18f832e05a7" />

An upgrade was made to give it 2 bytes of RAM. 4 lines of Programmable ROM along with 2 bytes of RAM was enough to run the Fibonacci sequence. 
I sadly made no recordings of this when I got it to work and now the world file has been corrupted causing some of the components to shift around and sink into the ground, becoming unreachable.
<img width="1919" height="1079" alt="image" src="https://github.com/user-attachments/assets/db6a2b43-0425-4b03-8a89-89c73f7a3783" />

Maybe this will be fixed one day, a new save was made to organize the computer and upgrade it to 6 bits to show more digits of the Fibonacci sequence, but that file has also been corrupted.
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/a4a3f4f3-00d4-4850-90c7-084144be4799" />
