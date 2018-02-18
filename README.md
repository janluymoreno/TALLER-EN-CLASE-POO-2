# TALLER-EN-CLASE-POO-2
TALLER REALIZADO EN CLASE DONDE LAS CLASES HEREDAN ATRINUTOS DE DIFERENTES CLASES

package ejemplo_clase1;


public class Ejemplo_clase1 {

    
    public static void main(String[] args) {
       int A,B;
       A = 7;
       B = 8;
       A += B;
       System.out.println(A);
       
       persona uno = new persona();
       uno.setNombre("Janluy ");
       uno.setApellido(" Moreno ");
       System.out.println(uno.getNombre());
       System.out.println(uno.Nombre_completo());
       
       persona dos = new persona();
       dos.setNombre("Luis ");
       dos.setApellido(" Castañeda ");
       System.out.println(dos.Nombre_completo());
       
       persona tres = new persona();
       tres.setNombre("Leonel ");
       tres.setApellido(" Mahecha");
       System.out.println(tres.Nombre_completo());
       
       persona cuatro = new persona();
       cuatro.setNombre("Alex ");
       cuatro.setApellido(" Guio");
       System.out.println(cuatro.Nombre_completo());
       
       Estudiante estudianteuno = new Estudiante();
       estudianteuno.setNombre(uno.Nombre_completo());
       estudianteuno.setCodigo(" f-1023");
       System.out.println(estudianteuno.Nombre_completo()+estudianteuno.getCodigo());
       System.out.println(estudianteuno.codigo);
       
       Docente Docenteuno = new Docente();
       Docenteuno.setNombre(dos.Nombre_completo());
       Docenteuno.setMateria("Programacion orientada a objetos 2.");
       System.out.println(Docenteuno.Nombre_completo()+Docenteuno.getMateria()+Docenteuno.getCodigo());//preguntar al profesor por que arroja el (null)
    }
    
}
