# Flutter Particle Clock

For my entry in the Flutter Clock Challenge I wanted to build something colorful, animated and playful that changes appearance with time. Ideally, I wanted it to look different every time I looked at it. I also wanted to explore the custom painting features of Flutter.

I ended up with an analog watch face featuring a simple particle system. It randomizes the color palettes while also maintaining legibility by calculating the luminance in real-time.

Building this was a bit of a struggle as I'm not very good with math, but the framework and the developer experience (live reload, in particular) helped me out a lot. Being able to iterate quickly is a great way to learn new things. I guess there are several ways the code could be improved both in terms of elegance and performance. However, I've managed to easily stay far below the 16ms/frame limit (average 5ms/frame on my iPad while debugging). Flutter's rendering engine really performs fantastically, even with my horrible math! 😅