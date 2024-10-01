public class Palindrome {
    public static void main(String[] args) {
        String str = "madam"; // input string
        String rev = ""; // reversed string
        int len = str.length(); // length of input string

        // reverse the string using a loop
        for (int i = len - 1; i >= 0; i--) {
            rev = rev + str.charAt(i);
        }

        // check if original string is equal to reversed string
        if (str.equals(rev)) {
            System.out.println(str + " is a palindrome");
        } else {
            System.out.println(str + " is not a palindrome");
        }
    }
}
