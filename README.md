package com.personal;

public class TareaFunciones {

    public static void main(String[] args) {
        double PrecioConIva=iva(54);

        System.out.println("El Precio  final ya con Iva es de: " + "$"+PrecioConIva);
    }




    static double iva(double numero1){
        return numero1 * 1.21;

    }
}
