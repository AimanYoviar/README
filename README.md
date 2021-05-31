# Hasil Modul bab enkasulapsi


Latihan 1
![Screenshot (194)](https://user-images.githubusercontent.com/68726545/111719482-856a4580-888e-11eb-9d46-46daebd0cfdf.png)


Latihan 2
![Screenshot (195)](https://user-images.githubusercontent.com/68726545/111719501-931fcb00-888e-11eb-8ed0-e105097e53c4.png)


Latihan 3
![Screenshot (196)](https://user-images.githubusercontent.com/68726545/111719510-97e47f00-888e-11eb-8c70-f383d6eefead.png)

Latihan 4
public class Bus3 {
    public int penumpang;
    public int maxpenumpang;
    
    public Bus3(int maxpenumpang){
        
        this.maxpenumpang = maxpenumpang;
        penumpang = 0;
        
    }
    //method Mutator
    public void addpenumpang(int penumpang){
        int temp;
        temp = this.penumpang+penumpang;
        if(temp>maxpenumpang)
        {
          System.out.println("penumpang melebihi kuota");
    }
        else
        {
            this.penumpang=temp;
        }
    }
       public void getpenumpang(int password){
        if (password==24){
            System.out.println("Password Benar ");
        }
    
        else{
    System.out.println("Password Salah");
    }
    }
    public void cetakpenumpang(){
        System.out.println("penumpang Bus sekarang = "+penumpang);
        System.out.println("Maksimum penumpang yang seharusnya adalah = "+maxpenumpang);
    }
}

Latihan 4.2
public class UjiBus3 {

    
    public static void main(String[] abc){
        //membuat objek busBesar dari class Bus3
    UjiBus3 Bus = new UjiBus3(5);
        Bus.getpenumpang(17);
        Bus.getPenumpang(24);
        Bus.cetakpenumpang();
        // penambahan penumpang
        Bus.addpenumpang (2);//tambah 2 penumpang
        Bus.cetakpenumpang();
        // penambahan penumpang
        Bus.addpenumpang (1);//tambah 2 penumpang
        Bus.cetakpenumpang();
        // penambahan penumpang
        Bus.addpenumpang (2);//tambah 2 penumpang
        Bus.cetakpenumpang();
        // penambahan penumpang
        Bus.addpenumpang (2);//tambah 2 penumpang
        Bus.cetakpenumpang();
        
    }
}

    
