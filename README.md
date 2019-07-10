# Master-
ejercicios
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package estudiante;

import java.util.logging.Logger;

/**
 *
 * @author Cheverria Paz
 */
public class estudiante {

    static void setNombre(String juan_Carlos) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }
    
private final char nombre;
private final  String edad;
    private final string anosdeexperiencia;
    private char Nombre;
    private String Edad;

public estudiante (char nombre, String edad, string anosdeexperiencia, char Nombre ) {
        this.nombre = nombre;
        this.edad = edad;
        this.anosdeexperiencia = anosdeexperiencia;
        this.Nombre = Nombre;
    }

    estudiante(String charli_Mendoza, String universidad_) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

public char getnombre() {
 return nombre;
}
public void setnombre(char nombre) {
 this.Nombre = nombre;
}
public String getedad() {
 return edad;
}
public void setedad(String edad) {
 this.Edad = edad;
}
   
    private static final Logger LOG = Logger.getLogger(estudiante.class.getName());

    void setunah(String uth) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

    void setanosdeexperiencia(String _anos) {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }

    String getuth() {
        throw new UnsupportedOperationException("Not supported yet."); //To change body of generated methods, choose Tools | Templates.
    }
        
    }
 
/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package estudiante;

import java.util.logging.Logger;

/**
 *
 * @author Cheverria Paz
 */
public class unah extends Universidad{
    
    private static final Logger LOG = Logger.getLogger(unah.class.getName());
    private final  char unah;
    private final  char unitec;
    private final char universidadcristiana;
    private final char uth;
    private char Unah;
    

public unah (char unah, char unitec, char universidadcristiana, char uth ) {
        this.unah = unah;
        this.unitec = unitec;
        this.universidadcristiana = universidadcristiana;
        this.uth = uth;
    }

 public char getunah() {
 return unah;
}

public char getunitec() {
 return unitec;
}
public char getuniversidadcristiana() {
 return universidadcristiana;
}
public char uth() {
 return uth;
}
}

/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package estudiante;

import java.util.logging.Logger;



/**
 *
 * @author Cheverria Paz
 */
public class main {

    public static void main(String[] args) {
        // TODO code application logic here
        estudiante estudiante = new estudiante("Charli Mendoza", "universidad ");
        
       System.out.println ("Charli Mendoza");
              
                System.out.println ("Charli Mendoza");

  System.out.println ("uht: "+ estudiante.getuth());
        estudiante.setNombre("charli mendoza");
        estudiante.setedad("25");
        estudiante.setanosdeexperiencia("3 anos");
        estudiante.setunah("uth");
    }
    private static final Logger LOG = Logger.getLogger(main.class.getName());
  

}

 
  
