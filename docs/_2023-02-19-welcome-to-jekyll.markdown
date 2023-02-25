---
layout: post
title:  "Seja Bem Vindo!"
date:   2023-02-19 17:07:51 -0300
categories: jekyll update
---
Apenas um teste. Mas promete!

You’ll find this post in your `_posts` directory. Go ahead and edit it and re-build the site to see your changes. You can rebuild the site in many different ways, but the most common way is to run `jekyll serve`, which launches a web server and auto-regenerates your site when a file is updated.

Jekyll requires blog post files to be named according to the following format:

`YEAR-MONTH-DAY-title.MARKUP`

Where `YEAR` is a four-digit number, `MONTH` and `DAY` are both two-digit numbers, and `MARKUP` is the file extension representing the format used in the file. After that, include the necessary front matter. Take a look at the source for this post to get an idea about how it works.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

    using MathNet.Numerics.LinearAlgebra.Double.Solvers;
    using MathNet.Numerics.LinearAlgebra.Double;
    using System;

    namespace ConsoleAppTestBed
    {
    class Program
    {
      static void Main(string[] args)
      {
          var dataPoints = new double[,]
          {

              { 5, 80 },
              { 20, 100 },
              { 40, 140 }
          };


          var fitter = new CircleFitter();
          var result = fitter.Fit(dataPoints);

          var x = -result[0];
          var y = -result[1];
          var c = result[2];

          Console.WriteLine("Center Point:");
          Console.WriteLine(x);
          Console.WriteLine(y);
          Console.WriteLine(c);

          //// (x^2 + y^2 - c^2)
          var radius = Math.Pow(x, 2) + Math.Pow(y, 2) - Math.Pow(c, 2);
          //// sqrt((x^2 + y^2 - c^2))
          radius =  Math.Sqrt(radius);
          Console.WriteLine("Radius:");
          Console.WriteLine(radius);
          Console.ReadLine();
      }

      public class CircleFitter
      {
          public double[] Fit(double[,] v)
          {
              var xy1 = new double[] { v[0,0], v[0,1] };
              var xy2= new double[] { v[1, 0], v[1, 1] };
              var xy3 = new double[] { v[2, 0], v[2, 1] };

              // Create Left Side Matrix of Equation
              var a = CreateLeftSide_(xy1);
              var b = CreateLeftSide_(xy2);
              var c = CreateLeftSide_(xy3);
              var matrixA = DenseMatrix.OfArray(new[,] 
              {
                  { a[0], a[1], a[2] },
                  { b[0], b[1], b[2] },
                  { c[0], c[1], c[2] }
              });

              // Create Right Side Vector of Equation
              var d = CreateRightSide_(xy1);
              var e = CreateRightSide_(xy2);
              var f = CreateRightSide_(xy3);
              double[] vector = { d, e, f };
              var vectorB =  Vector<double>.Build.Dense(vector);

              // Solve Equation
              var r = matrixA.Solve(vectorB);
              var result = r.ToArray();

              return result;
          }

          //2x, 2y, 1
          public double[] CreateLeftSide_(double[] d) 
          {
              return new double[] { (2 * d[0]), (2 * d[1]) , 1};
          
          }

          // -(x^2 + y^2)
          public double CreateRightSide_(double[] d) 
          { 
              return -(Math.Pow(d[0], 2) + Math.Pow(d[1], 2));

          }
      }
    }

    }

Java - obtenção de raio do circulo com tres pontos:
https://www.xarg.org/2018/02/create-a-circle-out-of-three-points/
function circleFromThreePoints(p1, p2, p3) {

  var x1 = p1.x;
  var y1 = p1.y;
  var x2 = p2.x;
  var y2 = p2.y;
  var x3 = p3.x;
  var y3 = p3.y;

  var a = x1 * (y2 - y3) - y1 * (x2 - x3) + x2 * y3 - x3 * y2;

  var b = (x1 * x1 + y1 * y1) * (y3 - y2) 
        + (x2 * x2 + y2 * y2) * (y1 - y3)
        + (x3 * x3 + y3 * y3) * (y2 - y1);
 
  var c = (x1 * x1 + y1 * y1) * (x2 - x3) 
        + (x2 * x2 + y2 * y2) * (x3 - x1) 
        + (x3 * x3 + y3 * y3) * (x1 - x2);
 
  var x = -b / (2 * a);
  var y = -c / (2 * a);

  return {
    x: x,
    y: y,
    r: Math.hypot(x - x1, y - y1)
  };
}