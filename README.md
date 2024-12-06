# pi-simulation-calculation
A simple method for simulation the calculation of the irrational number pi (π)


Consider a circle with a radius of 1 unit, perfectly fitting inside a square with 2-unit sides. If we randomly scatter 300 balls across the square, ensuring they're uniformly distributed, we can use the number of balls that land inside the circle to estimate the value of 
π
π.

Here's how it works:

The area of the circle is 
π
r
2
πr 
2
 , and the area of the square is 
(
2
r
)
2
(2r) 
2
 . Since the radius 
r
r is 1 unit, the area of the circle is 
π
(
1
)
2
=
π
π(1) 
2
 =π, and the area of the square is 
(
2
)
2
(2) 
2
  = 4.

By calculating the ratio of the circle's area to the square's area and multiplying by 4, we get:

Area of circle
×
4
Area of square
=
π
×
1
2
×
4
2
2
=
π
Area of square
Area of circle×4
​
 = 
2 
2
 
π×1 
2
 ×4
​
 =π
In our experiment, this ratio is represented by the number of balls that fall inside the circle relative to the total number of balls, multiplied by 4:

Area of circle
×
4
Area of square
=
Number of balls in circle
×
4
Total number of balls
Area of square
Area of circle×4
​
 = 
Total number of balls
Number of balls in circle×4
​
 
Running this simulation 300 times (refer to the code below) and cumulatively calculating the ratio leverages the law of large numbers, leading to a more accurate estimation of 
π
π as the number of trials increases. Each repetition refines our estimate, demonstrating how a simple physical model can mirror a complex mathematical principle.
