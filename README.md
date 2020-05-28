# Test
            Console.WriteLine("Type a number!");
            double a =0, b=0;
            a = double.Parse(Console.ReadLine());           
            
            Console.WriteLine("Try to mach the first number");
            b = double.Parse(Console.ReadLine());
            if (a==b)
            {
                Console.WriteLine("The two numbers are equal!");
            }
            else if(a!=b)
            {
                Console.WriteLine("The two numbers are not equal!");
            }
            
