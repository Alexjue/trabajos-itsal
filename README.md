#codigos itsal,calcu.
Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package com.mycompany.calculadora2;

/**
 *
 * @author aleja
 */
public class Calculadora2 {

    public static void main(String[] args) {
      Operaciones op=new Operaciones();
      op.leerNumeros();
      op.sumar();
      op.restar();
      op.multiplicar(20, 19);
      op.dividir();
      op.mostrarresultado();
    }
}.
