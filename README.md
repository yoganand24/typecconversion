# typecconversion
class type
{
    public static void main(String args[])
    {
        int num1=127;
        byte b = (byte)num1;
        float f = (float)num1;

        byte x = 125;
        int y = x;

        float k = 5.7f;
        int g = (int) k;
        // type promotion
        byte o = 10;
        byte p = 30;
        int result = o * p;
        System.out.println(b);
         System.out.println(f);
         System.out.println(y);
         System.out.println(g);
         System.out.println(result);
    }
}
