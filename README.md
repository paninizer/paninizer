About Me
--------

→ Beginner at java! Yes, I'm a beginner, despite what it looks like.

⤷ Try out StackOverflow!!!

⤷ Ask me about anything related to java8 and DMOJ. I'll be glad to help out!

⤷ How to reach me: panzer chan#8578 on Discord. I turned off DM from anyone because of some recent events, but you can comment your tag so I don't ignore it!


Tip for New Java People in DMOJ:
--------------------------------

Always use **BufferedReader**

It's fast, versatile, and doesn't result in Eclipse giving you nightmares over memory leaks.

Example:

    import java.io.BufferedReader;
    import java.io.IOException;
    import java.io.InputStreamReader;

    /*Don't import stuff that you won't need. It takes up space.
    New programmers like to include every single thing to show complexity.
    Also, don't import the whole library if you only need some things from it.*/
    
    public class Russian_Bias {
         public void main(String[] args) throws IOException 
         //note you need to yeet IOException, or IOException will yeet you
         {
             BufferedReader br = new BufferedReader(new InputStreamReader(System.in));
             //must include

             String test1 = br.readLine(); //br reads in string
             
             byte test2 = Byte.parseByte(br.readLine()); //so you need to parse
             int test3 = Integer.parseInt(br.readLine()); 
             //note that you need it to be a class, not a primitive object, but br.read() reads in int so...
             //shown in Integer.parseInt(...)

             System.out.println(test1+test2+test3);
             //confirm if the code works. you can copy-paste this code to see if it works
         }
    }

Also, **ABSOLUTELY** don't forget that **JAVA INDEXES STARTS AT 0**!!! Essential for many problems you will see around here.

Lastly, watch your spellings. Don't want to get a WA just for misspellings or punctuations, right?
