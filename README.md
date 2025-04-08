double theta = 2 * Math.PI * u;
double phi = Math.Acos(2 * v - 1);
double r = Math.Pow(w, 1.0 / 3); // radiusni kub ildiz bo'yicha qisqartirish

double x = r * Math.Sin(phi) * Math.Cos(theta);
double y = r * Math.Sin(phi) * Math.Sin(theta);
double z = r * Math.Cos(phi);

Console.WriteLine($"({x:F3}, {y:F3}, {z:F3})");
        }

        Console.ReadKey();
    }
}
  zxxx
