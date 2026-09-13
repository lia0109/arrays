# arrays
/* int[] reihung = new int[5];
    Scanner sc = new Scanner(System.in);
    for(int i = 0; i< reihung.length; i++) {
    reihung[i] = sc.nextInt();
    }

    for(int i = 0; i<reihung.length; i++) {
    IO.println(reihung[i]);
      }

    int[] a = new int[5];
    int[] b = {1, 2, 3, 4, 5, 6};
    for(int i= 0; i< a.length; i++) {
     a[i] = i;

}

    IO.println(Arrays.toString(a));
    IO.println(Arrays.toString(b));

    a = b;
    IO.println(Arrays.toString(a));
    IO.println(Arrays.toString(b));



    int[] c = {1, -2, -3, 4, 6, 8, -7};
    IO.print(negative(c));
*/

    float[] d = {1, 4, 7, 8};
    float erg = 0;
    for (int z = 0; z < d.length; z++){
        erg = erg + d[z];
    }
    erg = erg / d.length;
    IO.println(erg);
}

public int negative (int[] c){

    int anzahl = 0;
    for (int i = 0; i < c.length; i++){
    if (c[i] < 0) {
        anzahl++;
    }
    }
    return anzahl;
