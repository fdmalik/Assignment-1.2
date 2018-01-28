# Assignment-1.2

        Dim mName As String = ""
        Dim mId As Integer = 0

        FileOpen(1, "c:\Assignment 1\mRec.txt", OpenMode.Input)


        While Not EOF(1)

            Input(1, mName)
            Input(1, mId)

            Console.WriteLine("Member`s name : " & mName)
            Console.WriteLine("Members`s ID number : " & mId)




        End While
        FileClose(1)
        Console.ReadKey()

