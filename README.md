using System;
					
public class Program
{
	public static void Main()
	{

            bool valid = false;

            for (int i = 0; i <= cards.Length - 5; i++)
            {

                if (cards[i + 1] == cards[i] + 1 &&

                    cards[i + 2] == cards[i] + 2 &&

                    cards[i + 3] == cards[i] + 3 &&

                    cards[i + 4] == cards[i] + 4)

                {

                    valid = true;

                    gameWon = true; 
                    break;

                }

            }

   
 
	}
}
