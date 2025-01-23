package javaapplication1;

/**
 *
 * @author 2BCAB17
 */
public class JavaApplication1 {

    public static void main(String[] args) {
        Main number = new Main();

        int res1 = number.addition(444, 555);
        System.out.println("Addition of two integers: " + res1);

        int res2 = number.addition(333, 444, 555);
        System.out.println("Addition of three integers: " + res2);

        double res3 = number.addition(10.15, 20.22);
        System.out.println("Addition of two doubles: " + res3);
    }
}

class Main {
    
    public int addition(int x, int y) {
        return x + y;
    }

    public int addition(int x, int y, int z) {
        return x + y + z;
    }

    public double addition(double x, double y) {
        return x + y;
    }
}

out put
run:
Addition of two integers: 999
Addition of three integers: 1332
Addition of two doubles: 30.369999999999997
BUILD SUCCESSFUL (total time: 0 seconds)
# compile-time-polymorphism
