# Mencari-FPB-dan-KPK
package fpb.kpk;

/**
 * @author Azaria Dhea Rismaya
 */
import java.util.Scanner;

public class FPB_KPK {

    public static void main(String[] args) {
        int m,n,a,b,c,FPB = 0,KPK;
        Scanner input = new Scanner (System.in);
        System.out.print("Bilangan1 : ");
        m = input.nextInt();
        System.out.print("Bilangan2 : ");
        n = input.nextInt();
        for (a=1; a <= m ; a++){
            b=m % a;
            c=n % a;
            if (b==c && b==0 && c==0){
                FPB=a;
            }
        }
        KPK = (m*n)/FPB;
        System.out.println("FPB : " +FPB);
        System.out.println("KPK : " +KPK);
    }
}
