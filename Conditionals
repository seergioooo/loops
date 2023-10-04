public class Conditionals {

    public static void main(String[] args) {
//        workingIfs();
//        exercise1();
//        disco();
//        switchSentence();
        ejercicioSwitch1();
//        ejercicioSwitch2();
    }

    public static void workingIfs() {
        boolean isSunny = false;
        boolean isWindy = true;
        if (isSunny == true) {
            if (isWindy == true) {
                System.out.println("Voy de navegación");
            }
            System.out.println("Salgo de paseo");
        } else {
            System.out.println("Voy al cine");
        }
    }

    public static void exercise1() {
        //Si está soleado y hace viento salgo a navegar, si no, salgo a pasear.
        //Si está nublado y llueve canto bajo la lluvia, si no, me quedo en casa.
        boolean isSunny = false;
        boolean isWindy = true;
        boolean isRainny = true;
        if (isSunny == true) {
            if (isWindy == true) {
                System.out.println("Voy de navegación");
            } else {
                System.out.println("Voy a pasear");
            }

        } else {
            if (isRainny) {
                System.out.println("Canto bajo la lluvia");
            } else {
                System.out.println("Me quedo en casa");
            }
        }
    }

    public static void disco() {
        /* voy a la discoteca, si soy mayor de 18 años entro, si no me voy a la bolera. si he entrado en la
    discoteca me tomo una cocacola, suena dj tiesto y me pongo a bailar, en el caso de irme a la bolera
    me tomo un helado y si estan poniendo avatar 2 me voy al cine. al final siempre vuelvo a casa a acostarme
         */

 /* modificar el programa anterior para que todas las variables que necesite se las
    pida al usuario mediante JOption page*/
 /* modificar el programa anterior para pedir la cantidad de dinero de la que dispone el usuario teniendo en cuenta que los precios son
    : entrada disco 15€, coca cola 3€, avatar 8€, helado 2€, bolera 20€
         */
    }

    public static void switchSentence() {
        //Ejemplo: Introducir un número entero entre 1 y 7 y poner su traducción 
        //días de la semana (lunaes, martes, miércoles...)
        int day = 5;
        switch (day) {
            case 1:
                System.out.println("Es lunes");
                break;
            case 2:
                System.out.println("Es martes");
                break;
            case 3:
                System.out.println("Es miércoles");
                break;
            case 4:
                System.out.println("Es jueves");
                break;
            case 5:
                System.out.println("Es viernes");
                break;
            case 6:
                System.out.println("Es sábado");
                break;
            case 7:
                System.out.println("Es domingo");
                break;
            default: System.out.println("No es un día");
                break;
        }

    }
    
    public static void ejercicioSwitch1 () {
        //Hacer una función en la que generemos un número aleatorio y mostremos
        //por pantalla el mes con letras.
    
        int month = (int)(Math.random()*11+1);
        System.out.println("Month: " + month);
        switch(month){
            case 1:
                System.out.println("Es enero");
                break;
            case 2:
                System.out.println("Es febrero");
                break;
            case 3:
                System.out.println("Es marzo");
                break;
            case 4:
                System.out.println("Es abril");
                break;
            case 5:
                System.out.println("Es mayo");
                break;
            case 6:
                System.out.println("Es junio");
                break;
            case 7:
                System.out.println("Es julio");
                break;
            case 8:
                System.out.println("Es agosto");
                break;
            case 9:
                System.out.println("Es septiembre");
                break;
            case 10:
                System.out.println("Es octubre");
                break;
            case 11:
                System.out.println("Es noviembre");
                break;
            case 12:
                System.out.println("Es diciembre");
                break;
            default: System.out.println("No es un mes");
                break;
         }

    }
    
    public static  void ejercicioSwitch2() {
        //Pedimos al usuario que introduzca el día de la semana con letras y 
        //mostramos por pantlla lo siguiente:
        
        //Lunes y Miércoles --> Llevo al niño al pádel
        //Martes y Jueves --> El niño tiene natación
        //Viernes --> El niño queda para ir al cine
        //Fines de semana --> El niño se va a la playa
        
        Scanner keyboard =new Scanner (System.in);
        System.out.println("Introduce un día de la semana: ");
        String day = keyboard.nextLine();
        switch (day) {
            case "lunes":
                System.out.println("Llevo al niño al pádel");
                break;
            case "martes":
                System.out.println("El niño tiene natación");
                break;
            case "miércoles":
                System.out.println("Llevo al niño al pádel");
                break;
            case "jueves":
                System.out.println("El niño tiene natación");
                break;
            case "viernes":
                System.out.println("El niño queda para ir al cine");
                break;
            case "sábado":
                System.out.println("El niño se va a la playa");
                break;
            case "domingo":
                System.out.println("El niño se va a la playa");
                break;
        }
    }
    
}
