
package salarios;

import java.util.Scanner;

public class Salarios {

    public static void main(String[] args) {
        Scanner entrada = new Scanner(System.in);
        
        System.out.println("Digite su nombre: ");
        String nombre = entrada.nextLine();
            
        System.out.println("Digite el numero de horas trabajadas: ");
        int horas;
        horas = entrada.nextInt();
        
        System.out.println("Digite el sueldo establecido por hora: ");
        double sueldoh;
        sueldoh = entrada.nextDouble();
        
        double sueldo;
        
        sueldo = sueldoh * horas;
        
        System.out.println("El sueldo de "+nombre+ " por esta semana fue de: $"+sueldo);
        
	System.out.println( +nombre+ "Hizo un excelente trabajo");
        
    }
    
}
