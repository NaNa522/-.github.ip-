# h1 消費カロリー計算

### h3 痩せ創価と一緒に消費カロリー計算せよう～＞＜


###### h6 ではでは：

 h8 次の中から出発点選んでみましょう
public class Circle {

    public static void main(String[] args) {
        int n = Integer.parseInt(args[0]);

        for (int i = -n; i <= n; i++) {
            for (int j = -n; j <= n; j++) {
                if (i*i + j*j <= n*n) System.out.print("* ");
                else                  System.out.print(". ");
            }
            System.out.println();
        }
    }
}
