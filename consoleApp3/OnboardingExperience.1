using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;

namespace OnboardingExperience
{
    class Program
    {
        static void Main(string[] args)
        {
            var user = new User();
            
            Console.WriteLine("Welcome to your banking experience!");

            var question = "What is your first name?";
            var answer = AskQuestion(question);
            user.FirstName = answer;

            
            Console.WriteLine("Great, Your name is" + user.FirstName);

            user.LastName = AskQuestion("What is your last name?");
            Console.WriteLine("Awesome! Your full name is " + user.FirstName + " " + user.LastName);

            user.IsAccountOwner = AskBoolQuestion("Are you the account owner?");
            Console.WriteLine("Awesome! You are the account owner: " + user.IsAccountOwner);

            user.PinNumber = AskPinNumber("Please set a 4-digit pin.", 4);
            Console.WriteLine("Awesome! You entered: " + user.PinNumber);

            Console.ReadLine();

        }
        public static string AskQuestion(string question)
        {
            Console.WriteLine(question);
            var answer = Console.ReadLine();
            return answer;

        }
        static bool AskBoolQuestion(string question)
        {
            var hasAnswered = false;
            var responseBool = false;

            while (!hasAnswered)
            {
                var response = AskQuestion(question + " (y/n)");

                if (response =="y")
                {
                    responseBool = true;
                    hasAnswered = true;
                }
                else if (response == "n")
                {
                    responseBool = false;
                    hasAnswered = true;
                }
            }

            return responseBool;
        }

        static string AskPinNumber(string question, int length)
        {
            string numberString = null;

            while (numberString == null)
            {
                var response = AskQuestion(question);

                if (response.Length == length && Int32.TryParse(response, out int _))
                {
                    numberString = response;
                }
            }
            return numberString;
        }
                
       
    }
}

