- 👋 Hi, I’m @9585706540
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
9585706540/9585706540 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import java.util.Scanner;

public class Main {

    public static void main(String[] args)
    {
    	Scanner in = new Scanner(System.in);

        System.out.println("Enter the days::\n");

        int d = in.nextInt();
        int y;
        int w;

        // d = days
        // y = years
        // w = weeks

        /* Conversion of days in to years, weeks and days */
        y = (d / 365);
        w = (d % 365) / 7;
        d = d - ((y * 365) + (w));

        // Output
        System.out.println("\n" + y + " Year, " + w + " Weeks, and " + d + " Days\n");
    }
}import java.util.Scanner;

public class Main {

    public static void main(String[] args)
    {
    	Scanner in = new Scanner(System.in);

        System.out.println("Enter the days::\n");

        int d = in.nextInt();
        int y;
        int w;

        // d = days
        // y = years
        // w = weeks

        /* Conversion of days in to years, weeks and days */
        y = (d / 365);
        w = (d % 365) / 7;
        d = d - ((y * 365) + (w));

        // Output
        System.out.println("\n" + y + " Year, " + w + " Weeks, and " + d + " Days\n");
    }
}
