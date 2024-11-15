# classes
hi
using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace @class
{
    internal class Program
    {
        class employee
            {
            public int Id;
            public string Name;
            public int age;
            public string job;
           
            public void SetData(int id, string name, int age, string job)
            {
                Id = id;
                Name = name;
                this.age = age;
                this.job = job;
                Console.WriteLine("**Detail Of Employee**");

                Console.WriteLine($"Employee Id:{id} \nEployee name:{name} \nEmployee Age:{age} \nEmployee job:{job}  ");
            }
        } 
        static void Main(string[] args)
        {
            employee e1 = new employee();
            //e1.Id = 987;
            //e1.Name = "laraib";
            //e1.age = 25;
            //e1.job = "developer";

            ////Console.WriteLine( "ID: {0}  Name: {1}  Age: {2}  Job: {3}", e1.Id,e1.Name, e1.age, e1.job);
            //Console.WriteLine( $"Employee Id:  {e1.Id} \n Eployee name:{e1.Name} \n Employee Age: {e1.age} \n  Employee job: {e1.job}  ");
            e1.SetData(765, "laraib", 25, "developer");
            e1.SetData(262, "danish", 26, "marketing executive");

            Console.ReadLine();
           
        }
    }
}
