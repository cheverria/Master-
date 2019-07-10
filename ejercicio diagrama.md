# Master-
ejercicios
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paolaejer;

/**
 *
 * @author Cheverria Paz
 */
public abstract class Formas {
private String color;

public String getColor() {
return color;
}
/**
*
* @param color
*/
public void setColor(String color) {
this.color = color;
}

protected abstract void dibujar();
   
}
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paolaejer;

import java.util.logging.Logger;




/**
 *
 * @author Cheverria Paz
 */
public class circulo extends formas {
    
   

private double radio;
private static final double PI = Math.PI;
private double area;
private double contorno;

protected void dibujar() {
throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
}

public double getRadio() {
return radio;
}

public void setRadio(double radio) {
this.radio = radio;
}

public double getArea() {
return area;
}

public void setArea(double area) {
this.area = area;
}

public double getContorno() {
return contorno;
}

public void setContorno(double contorno) {
this.contorno = contorno;
}

public double calcularArea(double radio) {
this.area = 0;
this.radio = radio;
if (this.radio > 0) {
area = PI * this.radio * this.radio;
}
return this.area;
}
    private static final Logger LOG = Logger.getLogger(circulo.class.getName());
   
}
/*
* To change this license header, choose License Headers in Project Properties.
* To change this template file, choose Tools | Templates
* and open the template in the editor.
*/
package paolaejer;

import java.util.logging.Logger;

/**
*
* @author cheverria paz
*/
public class linea extends Formas {

private double largo;

public double getLargo() {
return largo;
}

public void setLargo(double largo) {
this.largo = largo;
}

@Override
protected void dibujar() {
throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
}
    private static final Logger LOG = Logger.getLogger(linea.class.getName());

}

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paolaejer;

import java.util.logging.Logger;

/**
 *
 * @author Cheverria Paz
 */

public class triangulo extends Formas {

private double base;
private double altura;
private double angulo;

public double getBase() {
return base;
}

public void setBase(double base) {
this.base = base;
}

public double getAltura() {
return altura;
}

public void setAltura(double altura) {
this.altura = altura;
}

public double getAngulo() {
return angulo;
}

public void setAngulo(double angulo) {
this.angulo = angulo;
}

public double calcularArea(double base, double altura) {
double area = 0;
this.base = base;
this.altura = altura;

if (this.base > 0 && this.altura > 0) {
area = (this.base * this.altura) / 2;
}
return area;
}

@Override
protected void dibujar() {
throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
}
    private static final Logger LOG = Logger.getLogger(triangulo.class.getName());

}

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package paolaejer;

import java.util.logging.Logger;

/**
 *
 * @author Cheverria Paz
 */
    public class Cuadrado extends Formas {

private double lado;

public double getLado() {
return lado;
}

public void setLado(double lado) {
this.lado = lado;
}

@Override
protected void dibujar() {
throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
}

public double area(double lado) {
double area = 0;
this.lado = lado;
if (this.lado > 0) {
area = Math.pow(lado, 2);
}
return area;
}
    private static final Logger LOG = Logger.getLogger(Cuadrado.class.getName());
}

