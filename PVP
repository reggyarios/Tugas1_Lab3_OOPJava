class hero {
    String nama;
    int hp;
    int mana;
    int att;
    int def;
    String weapon;
        hero (String nama, int hp, int mana, int att, int def,String weapon){
             this.nama= nama;
            this.hp = hp;
            this.mana = mana;
            this.att = att;
            this.def= def;
            this.weapon = weapon;
    }

    void print(){
        System.out.println("Nickname : "+nama);
        System.out.println("HP       : "+hp);
        System.out.println("Mana     : "+mana);
        System.out.println("Attack   : "+att);
        System.out.println("Defense  : "+def);
        System.out.println("Weapon   : "+weapon);
    }
}

public class PVP {
     public static void main (String[]orgs){
         int a; int b;
         
     hero hero1 = new hero ("Lenn", 100, 98, 20, 20, "Excalibur");
     hero hero2 = new hero ("Tayo", 90, 98, 10, 30, "LightSaber");
     
     hero1.print();
     System.out.println();
     hero2.print();
     System.out.println();
     System.out.println();
     
     a = (hero1.hp*hero1.def)/hero2.att;
     b = (hero2.hp*hero2.def)/hero1.att;
        
        if(b>a){
            System.out.print(hero2.nama+ "'s WIN");       
        }
        else if (a>b){
            System.out.print(hero1.nama+ "'s WIN");
        } 
     
     }
 }
