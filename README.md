Type_casting


public class Type_casting {
    public static void main(String[] args) {
       //Type casting
       int myInt =5;
       double myDouble = myInt;
        System.out.println("myInt = "+ myInt);

        System.out.println("myDouble = " + myDouble);

        float myFloat = myInt;
        //floattan sonra normalde "f" eklenir ancak castingde ihtiyac yok
        System.out.println("myFloat = " + myFloat);

        byte myByte= 10;
        myInt = myByte;
        System.out.println("myInt = " + myInt);

short myShort = 100;
double yourDouble = myShort;
        System.out.println("yourDouble = "+ myShort);

//task Mary'nin ortalamasi
        int mat = 80;
        int fiz = 7;
        double kim = 65.0;
        double mat_double = mat;
        System.out.println(mat_double);
        double fiz_double = fiz;
        System.out.println(fiz_double);
        double ortalama = (mat_double + fiz_double + kim) / 3;
        System.out.println("ortalama = " + ortalama);

//narrowing casting
        double double_number = 10.5;
        int int_number = (int) double_number;
        System.out.println("int_number = "+ int_number);
        //10.5 àlan deger outputs ta 10 olarak cikti;
        //tekrar double cevirsek bile kaybolan deger geri gelmez.


float float_number = 126.67788f;
short short_number = (short) float_number;
        System.out.println("short_number = "+ short_number);
        // ciktisinda =126 virgulden sonrasi komple siliniyor.

        //shopping 1 kg Elma 2.75, 2kg muz 10.9, 1 Kg havuc 0.05
        double elma = 2.75;
        double muz = 10.9;
        double havuc = 0.05;

        int elma_int = (int) elma;
        int muz_int =  (int) muz;
        int havuc_int = (int) havuc;

        int ort = (elma_int + muz_int + havuc_int)/3;

        System.out.println("ort = " + ort);
//ortalama 4 cikti 1.70 eoru deger kaybi var

        //Addition
        int sum1 =100+50;
        System.out.println("sum1 = "+sum1);
        int sum2 = sum1 + 250;
        System.out.println("sum2 = "+ sum2);
int sum3 = sum1+sum2;
        System.out.println("sum3 ="+ sum3);

//Subtraction
        int sub1 = 400-100;
        System.out.println("sub1 ="+ sub1);
        int sub2 = sub1-50;
        System.out.println("sub2 = "+ sub2);
int sub3 = sub1-sub2;
        System.out.println("sub3 = " + sub3);


        //multiplication carpma

int sun1 =10*5;
        System.out.println("sun1 = "+ sun1);
int sun2 = sun1 * 10;
        System.out.println("sun2 ="+ sun2);
        int sun3 = sun1 * sun2;
        System.out.println("sun3 = "+ sun3);

        //division bolme islemi
        int div1 = 400/20;
        System.out.println("div1 = "+ div1);
        int div2 = div1/5;
        System.out.println("div2 = "+div2);
        int div3 = div1/div2;
        System.out.println("div3 =" + div3);

        //practice
        int x = 5;
                int y = 7;
                        int ortlm =(x+y)/2;
        System.out.println ("ortalama =" +ortlm);


//Task alan hesapla dikdortgen 6,4
        int length = 6;
                int width = 4;
                        int alan = length*width;
        System.out.println("Alan = "+alan);

//Task ucgen 2,3,5 cevresi ne kadar
        int a = 2;
        int b = 3;
        int c = 5;
        int perimeter = (a+b+c);
        System.out.println("Perimeter = " + perimeter);


        //task yamuk alan hesaplama 5.5 cm, 7.2 cm ve yukseklik 10 cm
        double w = 5.5;
                double h = 7.2;
                        double j = 10;
                        double alan_tr =0.5*(w+h)*j;
        System.out.println("Alan = " + alan_tr);



    }
}
