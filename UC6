public class OopsBanner {

    // Method to return pattern of O
    public static String getOPattern(int line) {
        String[] O = {
                " ***** ",
                "*     *",
                "*     *",
                "*     *",
                "*     *",
                "*     *",
                " ***** "
        };
        return O[line];
    }

    // Method to return pattern of P
    public static String getPPattern(int line) {
        String[] P = {
                " ***** ",
                "*     *",
                "*     *",
                " ***** ",
                "*      ",
                "*      ",
                "*      "
        };
        return P[line];
    }

    // Method to return pattern of S
    public static String getSPattern(int line) {
        String[] S = {
                " ***** ",
                "*      ",
                "*      ",
                " ***** ",
                "      *",
                "*     *",
                " ***** "
        };
        return S[line];
    }

    public static void main(String[] args) {

        System.out.println("OOPS Banner App - UC6\n");

        // Banner array populated using methods
        String[] banner = new String[7];

        for (int i = 0; i < 7; i++) {
            banner[i] = String.join("   ",
                    getOPattern(i),
                    getOPattern(i),
                    getPPattern(i),
                    getSPattern(i)
            );
        }

        // Enhanced for loop to print
        for (String line : banner) {
            System.out.println(line);
        }
    }
}