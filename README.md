# hackerrank2
 public static void solve(double meal_cost, int tip_percent, int tax_percent)
        {

        }

    
    internal class Solution
    {

        public static void Main(string[] args)
        {
            double meal_cost = Convert.ToDouble(Console.ReadLine().Trim());

            int tip_percent = Convert.ToInt32(Console.ReadLine().Trim());

            int tax_percent = Convert.ToInt32(Console.ReadLine().Trim());

            Result.solve(meal_cost, tip_percent, tax_percent); /* */

            double tip = meal_cost * tip_percent / 100; 

            double tax = meal_cost * tax_percent / 100; 

            meal_cost = Math.Round(meal_cost + tip + tax); /*math.round sayıları yuvarlama ile ilgili kütüphane */

            Console.WriteLine(meal_cost);

            Console.ReadKey();
        }    
    }
}    
