# Final_project

string[] array1 = new string[5] {"123", "23", "hello", "world", "res"};

string []array2 = new string [array1.Length];

    int count = 0;
    for (int i = 0; i < array1.Length; i++)
    {

    if(array1[i].Length <= 3)
        { 
            array2[count] = array1[i];
            count++;
        }
        else 
        {

         Console.WriteLine($"{array1[i]}");
         
        }