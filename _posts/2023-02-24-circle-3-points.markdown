---
layout: post
title:  "3 Points and the Circle"
date:   2023-02-24 09:07:51 -0300
categories: matematica geogebra 
author: paulo
---

To find the radius of a circle given 3 points, we can use the formula:

r = (abc)/(4A)

where a, b, and c are the lengths of the sides of the triangle formed by the three points, and A is the area of the triangle.

The area of a triangle can be found using the determinant of a 3x3 matrix, which is given by:
>
> A = 0.5 * |x1 y1 1|
>           |x2 y2 1|
>           |x3 y3 1|

where (x1, y1), (x2, y2), and (x3, y3) are the coordinates of the three points.

To use this formula, we need to express the three points in matrix form and take the determinant of the resulting matrix. The matrix we use for this purpose is:

> | x1^2 + y1^2 x1 y1 1 |
> | x2^2 + y2^2 x2 y2 1 |
> | x3^2 + y3^2 x3 y3 1 |

The first two columns of this matrix represent the coefficients of x^2, y^2, and xy in the equation of the circle centered at (h, k), where h and k are the coordinates of the center of the circle. The third column contains a constant term of 1.

The 1 in the third column is necessary to represent the constant term in the equation of the circle. Without it, we would not be able to find the center of the circle. The determinant of this matrix is proportional to the negative of the square of the radius of the circle, so we can use the determinant to find the radius of the circle.

Therefore, the 1 in the third column of the matrix is included to allow us to find the center of the circle and hence the radius.

The constant term in the equation of a circle is there to account for the fact that the center of the circle may not necessarily lie on the x or y axis. Without a constant term, the equation of a circle centered at the origin would be x^2 + y^2 = r^2, where r is the radius of the circle. This equation assumes that the center of the circle is at (0, 0).

However, in general, the center of a circle can have any coordinates (h, k), where h is the x-coordinate of the center and k is the y-coordinate of the center. The equation of a circle centered at (h, k) can be expressed as:

> (x - h)^2 + (y - k)^2 = r^2

Expanding the equation and simplifying, we get:

> x^2 - 2hx + h^2 + y^2 - 2ky + k^2 = r^2

This is the general equation of a circle centered at (h, k), and it includes a constant term h^2 + k^2. This constant term ensures that the equation of the circle is satisfied for all points (x, y) that lie on the circle, regardless of the location of the center.

In the context of finding the equation of a circle given three points, we use a matrix to represent the equation of the circle. The third column of the matrix represents the constant term in the equation of the circle, which is h^2 + k^2. We can set this constant term to 1, or any other value, without affecting the equation of the circle, as long as we adjust the other elements of the matrix accordingly. However, setting the constant term to 1 makes it easier to work with the matrix, and it does not affect the accuracy of the result.

In the equation of a circle centered at (h, k), the constant term is the sum of the squares of the x-coordinate and y-coordinate of the center, which is h^2 + k^2. This constant term ensures that the equation of the circle is satisfied for all points (x, y) that lie on the circle, regardless of the location of the center.

In the matrix used to find the equation of the circle given three points, the third column represents the constant term in the equation of the circle, which is h^2 + k^2. By convention, we can set this constant term to 1, which means that the matrix looks like:

> | x1^2 + y1^2 x1 y1 1 |
> | x2^2 + y2^2 x2 y2 1 |
> | x3^2 + y3^2 x3 y3 1 |

This convention does not affect the accuracy of the result, and it makes it easier to work with the matrix.