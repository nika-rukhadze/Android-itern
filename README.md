# Android-itern




class Playground {
    public static void main(String[ ] args) {
        //Ex: nika, giorgi, ani, mari

        String original = "abcd";

        for(int i = original.length() - 1; i >= 0; i--){
            reverse += original.chaRat(i);
            system.out.println(reverse);
        }

        boolean palidrome = true;
        for(int i = 0; i < original.lenth(); i++) {
           if(orignal.charAt(i) != reverse.charAt(i)) {
               palidrome = false;
           }
        }
        if(palidrome) {
            System.out.println("PALINDROME!");
            } else {
                System.out.println("Not a palidrome");
            }
    }
}


